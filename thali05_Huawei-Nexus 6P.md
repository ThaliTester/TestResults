#### Test 88838102571b7ae_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-12 09:31:37.033   537   537 I ServiceManager: Waiting for service AtCmdFwd...
10-12 09:31:38.034   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 09:31:39.144  5630  5630 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-12 09:31:39.149  5630  5630 D AndroidRuntime: CheckJNI is OFF
10-12 09:31:39.176  5630  5630 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-12 09:31:39.208  5630  5630 I Radio-JNI: register_android_hardware_Radio DONE
10-12 09:31:39.223  5630  5630 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-12 09:31:39.239   928  3748 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-12 09:31:39.280   928  3748 I ActivityManager: Start proc 5639:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-12 09:31:39.298  5630  5630 D AndroidRuntime: Shutting down VM
,10-12 09:31:39.635   928   939 I WindowManager: Screenshot max retries 4 of Token{b5efefa ActivityRecord{babbd25 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{bf56bdd u0 Starting com.test.thalitest} drawState=4
,10-12 09:31:39.712  5639  5639 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 09:31:39.747  5639  5639 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 09:31:39.773  5639  5639 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 4928-4950)
,10-12 09:31:39.773  5639  5639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 09:31:39.795  5639  5639 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a2dcca3}
,10-12 09:31:39.796  5639  5639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 09:31:39.796  5639  5639 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 09:31:39.802  5639  5639 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-12 09:31:39.804  5639  5639 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 09:31:39.840  5639  5639 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 09:31:39.855  5639  5639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-12 09:31:39.855  5639  5639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 09:31:39.856  5639  5639 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 09:31:39.856  5639  5639 I Adreno  : Build Date                       : 12/06/15
10-12 09:31:39.856  5639  5639 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 09:31:39.856  5639  5639 I Adreno  : Local Branch                     : mybranch17112971
10-12 09:31:39.856  5639  5639 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 09:31:39.856  5639  5639 I Adreno  : Remote Branch                    : NONE
10-12 09:31:39.856  5639  5639 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 09:31:39.921   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17f3995:true
,10-12 09:31:39.960   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34136]" dev="sockfs" ino=34136 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-12 09:31:39.960   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34136]" dev="sockfs" ino=34136 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:31:39.975  5639  5639 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 09:31:39.984  5639  5639 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 09:31:40.019  5639  5676 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-12 09:31:40.017  3912  3912 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32648]" dev="sockfs" ino=32648 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-12 09:31:40.017  3912  3912 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32648]" dev="sockfs" ino=32648 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:31:40.020  3738  3738 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28774]" dev="sockfs" ino=28774 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 09:31:40.020  3738  3738 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28774]" dev="sockfs" ino=28774 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 09:31:40.028  5639  5663 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-12 09:31:40.060  5639  5676 I OpenGLRenderer: Initialized EGL, version 1.4
,10-12 09:31:40.072   928  5378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-12 09:31:40.137   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +501ms (total +882ms)
,10-12 09:31:40.164  5639  5639 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5639
,10-12 09:31:40.263  5639  5639 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-12 09:31:40.439  5639  5679 D jxcore_app_log: JniHelper::setJavaVM(0xf4e7c000), pthread_self() = -591652560
10-12 09:31:40.443  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-12 09:31:40.443  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-12 09:31:40.443  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-12 09:31:40.443  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-12 09:31:40.443  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-12 09:31:40.443  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@228c378 added. We now have 1 listener(s)
10-12 09:31:40.447  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-12 09:31:40.447  5639  5679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 09:31:40.448  5639  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:31:40.449  5639  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-12 09:31:40.453  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa7bb7 added. We now have 1 listener(s)
10-12 09:31:40.453  5639  5679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:31:40.459   928  2998 D WifiService: New client listening to asynchronous messages
,10-12 09:31:40.460  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:31:40.460  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-12 09:31:40.460  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-12 09:31:40.460  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-12 09:31:40.461  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-12 09:31:40.464  5639  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:31:40.464  5639  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-12 09:31:40.470  5639  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:31:40.470  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:31:40.470  5639  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-12 09:31:40.470  5639  5679 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:31:40.471  5639  5679 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 09:31:40.473  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:31:40.475  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:31:40.487  5639  5639 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-12 09:31:40.765  5639  5685 W jxcore-log: Initializing JXcore engine
10-12 09:31:40.765  5639  5685 W jxcore-log: JXcore engine is ready
,10-12 09:31:40.787  5685  5685 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11699 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-12 09:31:40.787  5685  5685 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15433]" dev="sockfs" ino=15433 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-12 09:31:40.787  5685  5685 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-12 09:31:40.787  5685  5685 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32620]" dev="sockfs" ino=32620 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-12 09:31:40.796  5639  5685 W jxcore-log: Starting JXcore engine
,10-12 09:31:40.805  5639  5648 I art     : Background sticky concurrent mark sweep GC freed 86414(8MB) AllocSpace objects, 19(2MB) LOS objects, 24% free, 24MB/32MB, paused 1.321ms total 104.985ms
,10-12 09:31:40.850  5639  5685 W jxcore-log: Platform android
10-12 09:31:40.850  5639  5685 W jxcore-log: 
,10-12 09:31:40.850  5639  5685 W jxcore-log: Process ARCH arm
10-12 09:31:40.850  5639  5685 W jxcore-log: 
,10-12 09:31:40.958  5639  5685 I jxcore-log: JXcore Cordova bridge is ready!
10-12 09:31:40.958  5639  5685 I jxcore-log: 
10-12 09:31:40.958  5639  5685 W jxcore-log: JXcore engine is started
,10-12 09:31:40.970  5639  5679 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-12 09:31:40.977  5639  5639 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-12 09:31:42.357   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:31:44.846   928  2986 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:31:45.380   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:31:50.822  5639  5685 I jxcore-log: 2016-10-12 13:31:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-12 09:31:50.822  5639  5685 I jxcore-log: 
,10-12 09:31:50.824  5639  5685 I jxcore-log: 2016-10-12 13:31:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-12 09:31:50.824  5639  5685 I jxcore-log: 
,10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:31:50.828  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:31:50.830  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:31:50.831  5639  5685 I jxcore-log: 2016-10-12 13:31:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-12 09:31:50.831  5639  5685 I jxcore-log: 
,10-12 09:31:50.833  5639  5685 I jxcore-log: 2016-10-12 13:31:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-12 09:31:50.833  5639  5685 I jxcore-log: 
,10-12 09:31:51.093  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 09:31:51.093  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b43601 added. We now have 2 listener(s)
10-12 09:31:51.094  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:31:51.094  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:31:51.094  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:31:51.094  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:31:51.094  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf57ca6 added. We now have 2 listener(s)
10-12 09:31:51.094  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:31:51.095  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 09:31:51.097  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:31:51.101  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:31:51.102  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:31:51.102  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 09:31:51.102  5639  5685 D ExecuteNativeTests: Running unit tests
10-12 09:31:51.103  5639  5685 D BluetoothAdapter: enable(): BT is already enabled..!
10-12 09:31:51.103   928  3155 D WifiService: setWifiEnabled: true pid=5639, uid=10077
10-12 09:31:51.103   928  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:31:51.109  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:31:51.115  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:31:54.469   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:32:00.530   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:32:01.109  5639  5685 I com.test.thalitest.ThaliTestRunner: Running UT
,10-12 09:32:01.180  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 09:32:01.180  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a67248 added. We now have 3 listener(s)
,10-12 09:32:01.181  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 09:32:01.181  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:32:01.181  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:32:01.181  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:32:01.181  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@760c8e1 added. We now have 3 listener(s)
10-12 09:32:01.181  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:32:01.183  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:32:01.185  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:01.190  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:32:01.191  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:01.191  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:32:01.196  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,10-12 09:32:01.196  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 09:32:01.196  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:32:01.196  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:32:01.197  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 09:32:01.197  5639  5685 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,10-12 09:32:01.197  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 09:32:01.197  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 09:32:01.197  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:32:01.197  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:32:01.197  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:32:01.198  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-12 09:32:01.199  5639  5685 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-12 09:32:01.199  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:01.200  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
10-12 09:32:01.201  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-12 09:32:01.202  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-12 09:32:01.205  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:01.205  5639  5685 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-12 09:32:01.205  5639  5685 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-12 09:32:01.206  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-12 09:32:01.206  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:01.206  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 09:32:01.206  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:32:01.206  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:01.206  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-12 09:32:01.207  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 09:32:01.207  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-12 09:32:01.207  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 09:32:01.207  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 09:32:01.207  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 09:32:01.207  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:01.208  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 09:32:01.208  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-12 09:32:01.208  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:32:01.210  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:32:01.210  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 09:32:01.210  4570  4570 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33104]" dev="sockfs" ino=33104 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:32:01.210  4570  4570 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33104]" dev="sockfs" ino=33104 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:01.211  5639  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:01.215  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-12 09:32:01.218  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 09:32:01.220  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 09:32:01.221  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:32:01.224  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 09:32:01.224  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 09:32:01.224  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
10-12 09:32:01.225  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:01.225  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-12 09:32:01.225  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-12 09:32:01.226  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:01.226  5639  5685 D BluetoothAdapter: STATE_ON
,10-12 09:32:01.228  4556  4570 D BtGatt.GattService: registerClient() - UUID=5922101c-8b1e-425a-a59e-3677f10fb056
,10-12 09:32:01.230  4556  4617 D BtGatt.GattService: onClientRegistered() - UUID=5922101c-8b1e-425a-a59e-3677f10fb056, clientIf=5
,10-12 09:32:01.231  5639  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 09:32:01.233  4556  4619 D BtGatt.AdvertiseManager: message : 0
10-12 09:32:01.236  4556  4619 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 09:32:01.250  4556  4617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 09:32:01.258  4556  4617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 09:32:01.259  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-12 09:32:01.260  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-12 09:32:01.260  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-12 09:32:01.260  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
,10-12 09:32:01.260  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:32:01.260  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:32:01.261  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 09:32:01.261  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-12 09:32:01.263  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-12 09:32:01.263  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-12 09:32:01.263  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 09:32:01.263  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-12 09:32:01.263  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:01.263  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 09:32:01.263  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-12 09:32:01.263  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-12 09:32:01.263  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-12 09:32:01.267  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 09:32:01.267  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 09:32:01.765  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:32:01.765  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-12 09:32:01.766  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-12 09:32:01.767  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 09:32:01.768  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-12 09:32:01.769  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-12 09:32:01.769  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 09:32:01.769  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-12 09:32:01.769  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,10-12 09:32:01.769  5639  5685 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 09:32:01.769  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-12 09:32:01.769  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 09:32:01.770  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 09:32:01.770  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 09:32:01.770  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 09:32:01.770  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:32:01.770  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:32:01.770  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 09:32:01.770  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:32:01.771  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:32:01.771  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:32:01.771  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:32:01.772  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-12 09:32:01.773  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 09:32:01.773  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:01.773  5639  5685 D BluetoothLeScanner: could not find callback wrapper
10-12 09:32:01.774  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 09:32:01.774  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 09:32:01.774  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:32:01.774  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 09:32:01.775  4556  4619 D BtGatt.AdvertiseManager: message : 1
10-12 09:32:01.776  4556  4619 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-12 09:32:01.789  4556  4617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 09:32:01.789  4556  4617 D BtGatt.GattService: Client app is not null!
10-12 09:32:01.791  4556  4755 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 09:32:01.792  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:32:01.792  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-12 09:32:01.792  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:01.792  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-12 09:32:01.792  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:01.792  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-12 09:32:01.793  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 09:32:01.793  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-12 09:32:01.793  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-12 09:32:01.795  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:01.795  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-12 09:32:01.796  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:32:01.797  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 09:32:01.800  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:32:01.800  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 09:32:01.802  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-12 09:32:01.802  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-12 09:32:01.802  5639  5685 V io.jxcore.node.ConnectivityMonitor: start: Already started
,10-12 09:32:01.802  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:01.802  5639  5685 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,10-12 09:32:01.802  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 09:32:01.802  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-12 09:32:01.802  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-12 09:32:01.802  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:32:01.802  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:01.802  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:32:01.802  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 09:32:01.803  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:32:01.803  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:01.806  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-12 09:32:01.806  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 09:32:01.807  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-12 09:32:01.807  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 09:32:01.807  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 09:32:01.807  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 09:32:01.807  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:01.807  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:32:01.807  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-12 09:32:01.807  5639  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:32:01.808  5639  5690 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:01.807  4570  4570 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33106]" dev="sockfs" ino=33106 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:01.810  4570  4570 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33106]" dev="sockfs" ino=33106 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:01.811  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:32:01.811  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 09:32:01.813  5639  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-12 09:32:01.816  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 09:32:01.817  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 09:32:01.817  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 09:32:01.820  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 09:32:01.820  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:32:01.820  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
10-12 09:32:01.821  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:01.821  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-12 09:32:01.821  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-12 09:32:01.821  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:01.822  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:01.824  4556  4774 D BtGatt.GattService: registerClient() - UUID=60014af7-13e9-46b4-b9a0-e2d1982a9157
10-12 09:32:01.825  4556  4617 D BtGatt.GattService: onClientRegistered() - UUID=60014af7-13e9-46b4-b9a0-e2d1982a9157, clientIf=5
,10-12 09:32:01.825  5639  5650 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-12 09:32:01.827  4556  4619 D BtGatt.AdvertiseManager: message : 0
,10-12 09:32:01.829  4556  4619 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 09:32:01.840  4556  4617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 09:32:01.846  4556  4617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 09:32:01.847  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-12 09:32:01.847  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-12 09:32:01.847  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-12 09:32:01.847  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-12 09:32:01.847  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 09:32:01.849  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 09:32:01.850  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
10-12 09:32:01.850  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:01.850  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-12 09:32:01.850  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-12 09:32:01.850  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-12 09:32:01.850  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-12 09:32:01.850  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:01.850  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 09:32:01.850  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:32:01.851  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,10-12 09:32:01.851  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-12 09:32:01.853  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 09:32:01.853  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 09:32:02.354  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
10-12 09:32:02.354  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-12 09:32:02.354  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-12 09:32:02.355  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 09:32:02.355  5639  5685 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-12 09:32:02.355  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 09:32:02.355  5639  5685 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-12 09:32:02.356  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,10-12 09:32:02.358  4556  4619 D BtGatt.AdvertiseManager: message : 1
,10-12 09:32:02.360  4556  4619 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-12 09:32:02.375  4556  4617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-12 09:32:02.375  4556  4617 D BtGatt.GattService: Client app is not null!
,10-12 09:32:02.377  4556  4774 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 09:32:02.378  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 09:32:02.378  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-12 09:32:02.378  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:02.378  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 09:32:02.378  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 09:32:02.378  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:32:02.379  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
10-12 09:32:02.379  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:02.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-12 09:32:02.379  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-12 09:32:02.379  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:02.381  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:02.385  4556  4774 D BtGatt.GattService: registerClient() - UUID=107fb433-d668-4191-ab12-386e01d941de
,10-12 09:32:02.386  4556  4617 D BtGatt.GattService: onClientRegistered() - UUID=107fb433-d668-4191-ab12-386e01d941de, clientIf=5
10-12 09:32:02.386  5639  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-12 09:32:02.388  4556  4619 D BtGatt.AdvertiseManager: message : 0
,10-12 09:32:02.393  4556  4619 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 09:32:02.408  4556  4617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 09:32:02.417  4556  4617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 09:32:02.418  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-12 09:32:02.418  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-12 09:32:02.418  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-12 09:32:02.418  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-12 09:32:02.418  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-12 09:32:02.418  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-12 09:32:02.418  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-12 09:32:02.418  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-12 09:32:02.418  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:32:02.418  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 09:32:02.419  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 09:32:02.419  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:32:02.419  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
10-12 09:32:02.419  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:02.420  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 09:32:02.420  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-12 09:32:02.420  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:32:02.420  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-12 09:32:02.420  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 09:32:02.420  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 09:32:02.421  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 09:32:02.421  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 09:32:02.421  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-12 09:32:02.421  5639  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 09:32:02.421  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:32:02.421  5639  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:32:02.421  5639  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 09:32:02.421  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 09:32:02.421  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:32:02.421  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:32:02.421  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-12 09:32:02.421  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:32:02.421  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:32:02.421  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:32:02.422  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:32:02.422  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 09:32:02.422  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:02.423  5639  5685 D BluetoothLeScanner: could not find callback wrapper
10-12 09:32:02.423  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 09:32:02.423  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 09:32:02.424  4556  4619 D BtGatt.AdvertiseManager: message : 1
10-12 09:32:02.424  4556  4619 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-12 09:32:02.432  4556  4617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 09:32:02.432  4556  4617 D BtGatt.GattService: Client app is not null!
,10-12 09:32:02.433  4556  4568 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:02.434  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 09:32:02.434  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-12 09:32:02.434  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-12 09:32:02.436  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:32:02.436  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:32:02.436  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:32:02.437  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 09:32:02.438  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:32:02.439  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 09:32:02.439  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:02.439  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 09:32:02.439  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:32:02.441  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-12 09:32:02.441  5639  5685 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-12 09:32:02.443  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,10-12 09:32:02.444  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-12 09:32:02.445  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,10-12 09:32:02.445  5639  5685 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-12 09:32:02.447  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-12 09:32:02.447  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-12 09:32:02.448  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-12 09:32:02.448  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 09:32:02.448  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 09:32:02.448  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:32:02.448  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 09:32:02.448  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-12 09:32:02.448  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 09:32:02.449  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 09:32:02.449  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:32:02.449  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 09:32:02.449  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:32:02.449  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:32:02.449  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:32:02.450  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,10-12 09:32:02.450  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 09:32:02.451  5639  5685 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-12 09:32:02.455  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-12 09:32:02.455  5639  5685 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-12 09:32:02.457  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
10-12 09:32:02.457  5639  5685 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-12 09:32:02.458  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
10-12 09:32:02.458  5639  5685 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
10-12 09:32:02.458  5639  5685 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-12 09:32:02.458  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-12 09:32:02.458  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 09:32:02.458  5639  5685 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-12 09:32:02.458  5639  5685 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 09:32:02.458  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-12 09:32:02.459  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 09:32:02.459  5639  5685 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-12 09:32:02.459  5639  5685 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 09:32:02.459  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,10-12 09:32:02.459  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 09:32:02.459  5639  5685 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-12 09:32:02.460  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-12 09:32:02.460  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-12 09:32:02.460  5639  5685 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-12 09:32:02.460  5639  5685 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-12 09:32:02.460  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,10-12 09:32:02.460  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:02.461  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 09:32:02.461  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:32:02.461  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:32:02.462  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 09:32:02.463  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 09:32:02.463  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-12 09:32:02.463  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 09:32:02.463  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-12 09:32:02.463  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 09:32:02.463  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 09:32:02.463  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:02.463  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:32:02.463  5639  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:32:02.464  5639  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:02.464  4570  4570 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[34866]" dev="sockfs" ino=34866 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:32:02.464  4570  4570 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[34866]" dev="sockfs" ino=34866 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:32:02.468  5639  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-12 09:32:02.468  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 09:32:02.468  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 09:32:02.475  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:32:02.477  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 09:32:02.477  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 09:32:02.478  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 09:32:02.479  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:32:02.479  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
10-12 09:32:02.479  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:02.479  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-12 09:32:02.479  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-12 09:32:02.479  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:02.480  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:02.481  4556  4774 D BtGatt.GattService: registerClient() - UUID=4fc3213d-662f-4894-99ec-a2bf62a78955
10-12 09:32:02.482  4556  4617 D BtGatt.GattService: onClientRegistered() - UUID=4fc3213d-662f-4894-99ec-a2bf62a78955, clientIf=5
10-12 09:32:02.482  5639  5650 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 09:32:02.483  4556  4619 D BtGatt.AdvertiseManager: message : 0
,10-12 09:32:02.485  4556  4619 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 09:32:02.494  4556  4617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 09:32:02.499  4556  4617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 09:32:02.500  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-12 09:32:02.500  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-12 09:32:02.500  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 09:32:02.500  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-12 09:32:02.500  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 09:32:02.502  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:32:02.503  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
10-12 09:32:02.503  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:02.503  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-12 09:32:02.503  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-12 09:32:02.503  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-12 09:32:02.503  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-12 09:32:02.503  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-12 09:32:02.503  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 09:32:02.503  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:32:02.503  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-12 09:32:02.503  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-12 09:32:02.506  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 09:32:02.506  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 09:32:03.004  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:32:03.004  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-12 09:32:03.005  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 09:32:03.005  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-12 09:32:03.005  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:32:03.006  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:32:03.006  5639  5694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 09:32:03.006  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-12 09:32:03.006  5639  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:32:03.006  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-12 09:32:03.006  5639  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 09:32:03.006  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a67248 removed from the list
10-12 09:32:03.006  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:32:03.007  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-12 09:32:03.007  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:32:03.007  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-12 09:32:03.007  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:32:03.007  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:32:03.007  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 09:32:03.007  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 09:32:03.008  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:32:03.009  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:03.009  5639  5685 D BluetoothLeScanner: could not find callback wrapper
10-12 09:32:03.010  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:32:03.010  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 09:32:03.011  4556  4619 D BtGatt.AdvertiseManager: message : 1
,10-12 09:32:03.013  4556  4619 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-12 09:32:03.027  4556  4617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 09:32:03.028  4556  4617 D BtGatt.GattService: Client app is not null!
,10-12 09:32:03.029  4556  4755 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 09:32:03.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 09:32:03.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-12 09:32:03.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:03.031  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-12 09:32:03.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:03.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:32:03.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 09:32:03.032  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-12 09:32:03.032  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-12 09:32:03.034  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:03.035  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:32:03.035  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:32:03.035   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-12 09:32:03.035   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-12 09:32:03.036  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:32:03.038  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@760c8e1 removed from the list
10-12 09:32:03.038  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:03.038  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:32:03.038  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:03.038  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:32:03.038  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:32:03.540  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:32:04.848   928  2986 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:32:08.043  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-12 09:32:08.045  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:32:08.045  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:32:08.049  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 09:32:08.050  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-12 09:32:08.050  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 09:32:08.050  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-12 09:32:08.050  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 09:32:08.051  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:32:08.051  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 09:32:08.051  5639  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:32:08.052  5639  5695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:08.053  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
10-12 09:32:08.055  5639  5685 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-12 09:32:08.055  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 09:32:08.054  4755  4755 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34873]" dev="sockfs" ino=34873 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:32:08.054  4755  4755 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34873]" dev="sockfs" ino=34873 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:32:08.055  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 09:32:08.057  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 09:32:08.057  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:32:08.059  5639  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-12 09:32:08.061  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,10-12 09:32:08.072  5639  5685 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-12 09:32:08.073  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:32:08.073  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 09:32:08.073  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 09:32:08.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 09:32:08.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:32:08.073  5639  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 09:32:08.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:32:08.073  5639  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:32:08.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 09:32:08.073  5639  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 09:32:08.074  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a67248 not in the list
10-12 09:32:08.074  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 09:32:08.074  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:32:08.074  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:32:08.074  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 09:32:08.074  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:32:08.074  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:32:08.074  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:32:08.074  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:32:08.074  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:32:08.076  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:08.076  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:08.076  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@760c8e1 not in the list
10-12 09:32:08.076  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:32:08.076  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 09:32:08.076  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:32:08.077  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:32:08.077  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:08.078  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-12 09:32:08.080  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-12 09:32:08.080  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 09:32:08.080  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,10-12 09:32:08.080  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 09:32:08.080  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-12 09:32:08.080  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 09:32:08.081  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
10-12 09:32:08.081  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,10-12 09:32:08.083  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,10-12 09:32:08.083  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-12 09:32:08.083  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-12 09:32:08.084  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
10-12 09:32:08.084  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-12 09:32:08.084  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 09:32:08.084  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,10-12 09:32:08.084  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 09:32:08.084  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-12 09:32:08.084  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-12 09:32:08.085  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
10-12 09:32:08.085  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-12 09:32:08.085  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-12 09:32:08.085  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
10-12 09:32:08.085  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,10-12 09:32:08.086  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-12 09:32:08.086  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-12 09:32:08.086  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-12 09:32:08.086  5639  5685 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
10-12 09:32:08.087  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:32:08.087  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9cac51 added. We now have 3 listener(s)
,10-12 09:32:08.088  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:32:08.088  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:32:08.089  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:32:08.089  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:32:08.089  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc3cb6 added. We now have 3 listener(s)
10-12 09:32:08.089  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:32:08.089  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 09:32:08.092  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:08.096  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:08.097  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:08.098  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 09:32:08.099  5639  5685 D BluetoothAdapter: enable(): BT is already enabled..!
10-12 09:32:08.099   928  3156 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-12 09:32:08.100   928  3156 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-12 09:32:08.100  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:08.101  5639  5685 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
10-12 09:32:08.104  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:08.104  5639  5685 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-12 09:32:08.105  5639  5685 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-12 09:32:08.109   928  3155 D WifiService: setWifiEnabled: false pid=5639, uid=10077
10-12 09:32:08.109   928  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:32:08.111   928  2986 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-12 09:32:08.111   928  2986 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-12 09:32:08.111   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:32:08.111   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:08.120   928  5379 D DhcpClient: Clearing IP address
10-12 09:32:08.120   506   922 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:32:08.127   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:08.129   928  5380 D DhcpClient: Receive thread stopped
,10-12 09:32:08.135  3578  5432 V NativeCrypto: Read error: ssl=0x7f8d453880: I/O error during system call, Connection timed out
,10-12 09:32:08.137  3578  5432 V NativeCrypto: SSL shutdown failed: ssl=0x7f8d453880: I/O error during system call, Broken pipe
,10-12 09:32:08.138   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 09:32:08.139   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-12 09:32:08.142   535   535 E Parcel  : Reading a NULL string not supported here.
10-12 09:32:08.145   928   928 D RttService: SCAN_AVAILABLE : 1
10-12 09:32:08.146   928  3084 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 09:32:08.150   928  3006 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-12 09:32:08.152  3731  3909 W QCNEJ   : |CORE| network lost: 100
,10-12 09:32:08.152  3731  3909 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-12 09:32:08.162   928  2986 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-12 09:32:08.175   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:08.176   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 09:32:08.197   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:08.197   506   922 D CommandListener: Clearing all IP addresses on wlan0
10-12 09:32:08.198   506   922 D TetherController: Setting IP forward enable = 0
,10-12 09:32:08.199   928  3006 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,10-12 09:32:08.199   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 09:32:08.201   928  2986 D DhcpClient: doQuit
10-12 09:32:08.201   928  2986 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 09:32:08.202   928  5379 D DhcpClient: onQuitting
10-12 09:32:08.202  3453  3453 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 09:32:08.202   928   945 D Tethering: MasterInitialState.processMessage what=3
10-12 09:32:08.205  5274  5274 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@60bd3bf and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:08.210  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:08.212  4980  4999 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:32:08.212  4980  4999 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:32:08.212  4980  4999 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 09:32:08.212  4980  4999 E SarControlService: no key has been found,reset the power
,10-12 09:32:08.213  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:32:08.213  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:32:08.213  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:08.214  3890  3890 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 09:32:08.214  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-12 09:32:08.215  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:08.215  5005  5005 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 09:32:08.217  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 09:32:08.218  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:32:08.218  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:32:08.218  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000ea03000000000000ffffffff]
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:08.219  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:08.219  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:08.219  5005  5019 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-12 09:32:08.220  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:08.220  5005  5005 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:32:08.222  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:08.223  3890  3890 D SystemUpdateService: onCreate
10-12 09:32:08.226  3453  3453 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:08.226  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:08.229  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:08.231  3453  3453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:08.233  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:08.234  3890  3890 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-12 09:32:08.236  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:08.236  4980  4991 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 09:32:08.239  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000eb03000000000000ffffffff]
10-12 09:32:08.239  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:08.239  5005  5019 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-12 09:32:08.239  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:08.240  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:08.240  4980  4990 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:32:08.241  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:08.242  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:08.244  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-12 09:32:08.249  3890  5404 I iu.UploadsManager: num queued entries: 0
10-12 09:32:08.249  3890  5404 I iu.UploadsManager: num updated entries: 0
10-12 09:32:08.250  3890  5404 I iu.SyncManager: NEXT; no task
10-12 09:32:08.251  3890  5713 I SystemUpdateService: active receiver: enabled
10-12 09:32:08.253  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-12 09:32:08.255  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-12 09:32:08.258  3890  5713 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-12 09:32:08.259  3890  5713 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-12 09:32:08.259  3890  5713 I SystemUpdateService: now status is 0 (complete)
10-12 09:32:08.259  3890  5713 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:32:08.259  3890  5713 I SystemUpdateService: file has been verified
10-12 09:32:08.260  3890  5713 I SystemUpdateService: OTA package size = 21989297
10-12 09:32:08.266   506   922 E Netd    : netlink response contains error (No such file or directory)
10-12 09:32:08.265  3890  5713 I SystemUpdateService: showing system update notification
,10-12 09:32:08.266   928  3748 I ActivityManager: Start proc 5717:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
10-12 09:32:08.266   506   922 D TetherController: Setting IP forward enable = 0
10-12 09:32:08.267   928  3006 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-12 09:32:08.274  3453  3453 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-12 09:32:08.281  3890  3890 D SystemUpdateService: onDestroy
10-12 09:32:08.289  3453  3453 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-12 09:32:08.306  5717  5717 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
10-12 09:32:08.308  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:32:08.316  5717  5717 D SprintDMHelper: simOperator: 
,10-12 09:32:08.316  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:32:08.329   928  3156 I ActivityManager: Start proc 5731:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-12 09:32:08.330   928  3156 I ActivityManager: Killing 4894:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-12 09:32:08.395   928  2986 D wifi    : In wifi stop Hal
10-12 09:32:08.395  4929  4929 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 09:32:08.395   928  2986 D wifi    : halHandle = 0x7f8bd08400, mVM = 0x7fa838d140, mCls = 0x100a06
,10-12 09:32:08.395   928  3452 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 09:32:08.395   928  3452 D WifiHAL : Got a signal to exit!!!
10-12 09:32:08.395   928  3452 I WifiHAL : Exit wifi_event_loop
10-12 09:32:08.395   928  2986 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 09:32:08.395   928  2986 E WifiHAL : Event processing terminated
10-12 09:32:08.396   928  2986 D wifi    : In wifi cleaned up handler
10-12 09:32:08.396   928  2986 I WifiHAL : Internal cleanup completed
10-12 09:32:08.398  4053  4221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:32:08.398  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:08.401  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:08.403  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:08.418   928  3452 D wifi    : set interface wlan0 flags (DOWN)
,10-12 09:32:08.419   928  2986 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 09:32:08.420  4929  5745 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 09:32:08.423   928  3801 I ActivityManager: Killing 5454:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-12 09:32:08.446   928  3801 I ActivityManager: Start proc 5746:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-12 09:32:08.476  5746  5746 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-12 09:32:08.484   928  3805 I ActivityManager: Killing 5274:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-12 09:32:08.576  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:32:08.613  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:08.617   928   939 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-12 09:32:08.617   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:32:08.623   506   922 D SoftapController: Softap fwReload - Ok
,10-12 09:32:08.627   928   945 D Tethering: InitialState.processMessage what=4
,10-12 09:32:08.629   506   922 D CommandListener: Setting iface cfg
10-12 09:32:08.630   506   922 D CommandListener: Trying to bring down wlan0
,10-12 09:32:08.631   506   922 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:32:08.632   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 09:32:08.636   928  2986 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 09:32:09.125   928  3738 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-12 09:32:09.129   928  3738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:32:09.246   928  2986 D wifi    : set interface wlan0 flags (UP)
,10-12 09:32:09.246   928  2986 I WifiHAL : Initializing wifi
10-12 09:32:09.246   928  2986 I WifiHAL : Creating socket
,10-12 09:32:09.253   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 09:32:09.257   928  2986 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-12 09:32:09.258   928  2986 D wifi    : Did set static halHandle = 0x7f8bd08400
10-12 09:32:09.258   928  2986 D wifi    : halHandle = 0x7f8bd08400, mVM = 0x7fa838d140, mCls = 0x20192e
10-12 09:32:09.258   928  2986 D wifi    : array field set
10-12 09:32:09.259   928  2986 I WifiNative-HAL: interface[0] = wlan0
10-12 09:32:09.262   928  5761 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547806544896
,10-12 09:32:09.262   928  5761 D wifi    : waitForHalEvents called, vm = 0x7fa838d140, obj = 0x20192e, env = 0x7f8cb18fc0
,10-12 09:32:09.340  5762  5762 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 09:32:09.361  5762  5762 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:32:09.367   928  2986 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 09:32:09.375  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.377  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.378  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.386  5762  5762 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:32:09.386  5762  5762 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 09:32:09.401   928  2986 D WifiConfigStore: Loading config and enabling all networks 
,10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:09.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:09.411  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:09.411   928  2986 D WifiConfigStore: loaded 0 passpoint configs
10-12 09:32:09.411   928  2986 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 09:32:09.412   928  2986 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 09:32:09.413   928  2986 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:09.413  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:09.414   928  2986 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-12 09:32:09.414   928  2986 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 09:32:09.414   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 09:32:09.414   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-12 09:32:09.415  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:09.418  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:09.419   928  2986 D WifiNative-HAL: Setting external_sim to 1
10-12 09:32:09.419  4929  4929 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:32:09.419   928  2986 D wifi    : setting dfs flag to true, 0x7f8ccbac80
10-12 09:32:09.420   928  2986 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 09:32:09.420   928  2986 D wifi    : setting scan oui 0x7f8ccbac80
10-12 09:32:09.420   928  2986 D WifiHAL : Sending mac address OUI
,10-12 09:32:09.421  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:09.424   928  2986 E native  : do suspend false
,10-12 09:32:09.431   928  2986 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-12 09:32:09.431   928   928 D RttService: SCAN_AVAILABLE : 3
10-12 09:32:09.431   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 09:32:09.431   928  3084 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-12 09:32:09.432   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:09.436   928  2977 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-12 09:32:09.436   928  2977 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 09:32:09.444   928  2977 D WifiNative-HAL: p2pGetDeviceAddress
,10-12 09:32:09.449   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=224626 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-12 09:32:09.449   928  2977 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 09:32:09.635  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.647  4556  4613 D BluetoothAdapterState: Current state: ON, message: 23
,10-12 09:32:09.648  4556  4613 D BluetoothAdapterProperties: Setting state to 13
10-12 09:32:09.648  4556  4613 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-12 09:32:09.649  4556  4613 D BluetoothAdapterProperties: onBluetoothDisable()
,10-12 09:32:09.653  4556  4613 I BluetoothAdapterState: Entering PendingCommandState
10-12 09:32:09.653  4556  4556 D BluetoothMapService: onReceive
,10-12 09:32:09.653  4556  4556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:32:09.654  4556  4556 D BluetoothMapService: STATE_TURNING_OFF
10-12 09:32:09.654  4556  4556 D BluetoothMapService: MAP Service closeService in
,10-12 09:32:09.654  4556  4556 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 09:32:09.654  4556  4556 D ObexServerSockets0: shutdown(block = true)
10-12 09:32:09.656  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:32:09.657  4556  4777 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-12 09:32:09.657  4556  4752 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 09:32:09.657  4556  4778 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-12 09:32:09.658  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:32:09.659  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:09.659  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:09.662  4556  4556 I BtOppRfcommListener: stopping Accept Thread
10-12 09:32:09.664  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:09.664  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:09.665  4556  5304 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-12 09:32:09.668  4556  5304 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-12 09:32:09.669  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:09.669  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:09.671  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:09.671  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:09.674  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:09.674  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:09.675  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:09.675  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:09.684   928   941 I ActivityManager: Start proc 5766:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-12 09:32:09.686  4556  4617 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:32:09.686  4556  4613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-12 09:32:09.690  4556  4556 D HeadsetService: Received stop request...Stopping profile...
,10-12 09:32:09.694  3780  4017 D BluetoothHeadset: Proxy object disconnected
,10-12 09:32:09.694   928   928 D BluetoothHeadset: Proxy object disconnected
,10-12 09:32:09.694   928   928 D BluetoothHeadset: Proxy object disconnected
,10-12 09:32:09.694   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 09:32:09.695  3118  3131 D BluetoothHeadset: Proxy object disconnected
10-12 09:32:09.695  4556  4556 D A2dpService: Received stop request...Stopping profile...
10-12 09:32:09.695  3118  3118 D HeadsetProfile: Bluetooth service disconnected
10-12 09:32:09.696  4556  4769 D A2dpStateMachine: Exit Disconnected: -1
10-12 09:32:09.696  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.698   928   928 D BluetoothA2dp: Proxy object disconnected
10-12 09:32:09.698  3118  3118 D BluetoothA2dp: Proxy object disconnected
10-12 09:32:09.701  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.701  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:09.701  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.701  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 09:32:09.701  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:09.703  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.704  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-12 09:32:09.704  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-12 09:32:09.704  4556  4617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 09:32:09.704  4556  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:09.704  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.704  4556  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:09.704  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.704  4556  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 09:32:09.704  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:09.704  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:09.706  4556  4617 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-12 09:32:09.706  4556  4556 D HidService: Received stop request...Stopping profile...
10-12 09:32:09.706  4556  4556 D HidService: Stopping Bluetooth HidService
10-12 09:32:09.707  3118  3118 D BluetoothInputDevice: Proxy object disconnected
10-12 09:32:09.709  3118  3118 D HidProfile: Bluetooth service disconnected
,10-12 09:32:09.714  4556  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:09.714  4556  4617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 09:32:09.714  4556  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:09.715  4556  4748 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-12 09:32:09.715  4556  4748 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:32:09.715  4556  4748 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 09:32:09.715  4556  4748 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:32:09.715  4556  4556 D HealthService: Received stop request...Stopping profile...
,10-12 09:32:09.716  4556  4556 D PanService: Received stop request...Stopping profile...
,10-12 09:32:09.718  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-12 09:32:09.718  3118  3118 D PanProfile: Bluetooth service disconnected
10-12 09:32:09.719  4556  4556 D BluetoothMapService: Received stop request...Stopping profile...
10-12 09:32:09.719  4556  4556 D BluetoothMapService: stop()
10-12 09:32:09.719  4556  4556 D BluetoothMapAppObserver: deinitObservers()
,10-12 09:32:09.719  4556  4556 D BluetoothMapAppObserver: removeReceiver()
10-12 09:32:09.720  3118  3118 D BluetoothMap: Proxy object disconnected
10-12 09:32:09.720  3118  3118 D MapProfile: Bluetooth service disconnected
,10-12 09:32:09.721  4556  4556 D SapService: Received stop request...Stopping profile...
,10-12 09:32:09.721  4556  4556 V SapService: stop()
,10-12 09:32:09.723  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.723  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.723  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:09.723  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:09.723  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 09:32:09.724  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 09:32:09.724  4556  4617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 09:32:09.724  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.724  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.724  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:09.724  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:32:09.724  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 09:32:09.724  4556  4617 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 09:32:09.725  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 09:32:09.725  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.725  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.725  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 09:32:09.725  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:09.726  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 09:32:09.727  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 09:32:09.727  4556  4556 D BluetoothMapService: MAP Service closeService in
10-12 09:32:09.727  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.727  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.727  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:09.728  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:32:09.728  4556  4556 D BluetoothMapService: cleanup()
10-12 09:32:09.728  4556  4556 D BluetoothMapService: MAP Service closeService in
10-12 09:32:09.728  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:09.728  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:09.728  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:09.728  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:09.728  4556  4613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-12 09:32:09.728  4556  4613 D BluetoothAdapterProperties: Setting state to 15
10-12 09:32:09.728  4556  4613 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 09:32:09.729  4556  4613 I BluetoothAdapterState: Entering BleOnState
10-12 09:32:09.729  3118  3131 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:32:09.730  3118  3133 D BluetoothMap: onBluetoothStateChange: up=false
10-12 09:32:09.731   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:09.731  3780  3807 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:09.731   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:09.732   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:09.732   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-12 09:32:09.734  3118  3924 D BluetoothPbap: onBluetoothStateChange: up=false
,10-12 09:32:09.737  3118  3131 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:09.737  3118  3133 D BluetoothPan: onBluetoothStateChange on: false
10-12 09:32:09.737  3118  3924 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 09:32:09.738  4556  4613 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 09:32:09.738  4556  4613 D BluetoothAdapterProperties: Setting state to 16
10-12 09:32:09.738  4556  4613 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 09:32:09.739  4556  4613 D BluetoothAdapterProperties: onBleDisable
10-12 09:32:09.739  4556  4613 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:32:09.739  4556  4614 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 09:32:09.742  4556  4748 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 09:32:09.742  4556  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:09.743  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.744  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:09.741  4556  4617 D BluetoothAdapterProperties: Scan Mode:20
,10-12 09:32:09.746  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:09.747  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:09.748  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:09.749  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:09.758  5766  5766 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-12 09:32:09.769  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 09:32:09.774   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b3fe0c:true
,10-12 09:32:09.776  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:09.788   928   938 I ActivityManager: Start proc 5778:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-12 09:32:09.800  5766  5766 D LocalBluetoothProfileManager: Adding local MAP profile
,10-12 09:32:09.804  5766  5766 D BluetoothMap: Create BluetoothMap proxy object
,10-12 09:32:09.815  5766  5766 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-12 09:32:09.823  5778  5778 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-12 09:32:09.828  5766  5766 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:32:09.833   928   938 I ActivityManager: Killing 4627:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-12 09:32:09.947  4556  4617 I bt_hci  : shut_down
,10-12 09:32:09.951  4556  4622 D bt_hwcfg: hw_epilog_process
,10-12 09:32:09.951  4556  4622 I bt_vendor: low_power_mode_cb
,10-12 09:32:09.953  4556  4622 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-12 09:32:09.953  4556  4622 I bt_vendor: epilog_cb
10-12 09:32:09.953  4556  4622 I bt_hci  : epilog_finished_callback
,10-12 09:32:09.956  4556  4617 I bt_hci_h4: hal_close
,10-12 09:32:09.957  4556  4617 I bt_userial_vendor: device fd = 54 close
,10-12 09:32:10.025  5778  5778 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-12 09:32:10.025  5778  5778 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.025  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.026  5778  5778 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.026  5778  5778 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.026  5778  5778 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.k.d(PG:583)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.026  5778  5778 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.026  5778  5778 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.026  5778  5778 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:32:10.026  5778  5778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:32:10.030  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:32:10.036  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:10.054  5766  5766 D DockEventReceiver: finishStartingService: stopping service
10-12 09:32:10.055   928  3868 I ActivityManager: Killing 5093:com.google.android.deskclock/u0a66 (adj 15): empty #17
10-12 09:32:10.086  4556  4614 D bt_stack_manager: event_shut_down_stack finished.
10-12 09:32:10.086  4556  4613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-12 09:32:10.088  4556  4556 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 09:32:10.088  4556  4613 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-12 09:32:10.089  4556  4556 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 09:32:10.089  4556  4556 D BtGatt.GattService: stop()
10-12 09:32:10.089  4556  4556 D BtGatt.AdvertiseManager: advertise clients cleared
10-12 09:32:10.090  4556  4556 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:10.091  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:10.091  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:10.091  4556  4556 V BluetoothAdapterState: isBleTurningOff()=true
10-12 09:32:10.091  4556  4613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-12 09:32:10.091  4556  4613 D BluetoothAdapterProperties: Setting state to 10
10-12 09:32:10.091  4556  4613 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 09:32:10.092  4556  4613 I BluetoothAdapterState: Entering OffState
10-12 09:32:10.093   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-12 09:32:10.103  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-12 09:32:10.104  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 09:32:10.104  4556  4556 I BluetoothServiceJni: cleanupNative: return from cleanup
10-12 09:32:10.105  4556  4614 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-12 09:32:10.115  4556  4556 I art     : System.exit called, status: 0
,10-12 09:32:10.115  4556  4556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 09:32:10.147  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:10.149   380   380 E lowmemorykiller: Error writing /proc/4556/oom_score_adj; errno=22
10-12 09:32:10.149   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,10-12 09:32:10.150   928   945 W ActivityManager: Application dead when creating service ServiceRecord{6efe227 u0 com.android.bluetooth/.btservice.AdapterService}
10-12 09:32:10.151   928   945 I ActivityManager: Process com.android.bluetooth (pid 4556) has died
,10-12 09:32:10.151   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,10-12 09:32:10.152   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
10-12 09:32:10.153   928   945 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
10-12 09:32:10.153   928   945 W ActivityManager: android.os.DeadObjectException
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:10.153   928   945 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 09:32:10.153   928   945 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-12 09:32:10.153   928  3801 W ActivityManager: Spurious death for ProcessRecord{70ac4f5 0:com.android.bluetooth/1002}, curProc for 4556: null
,10-12 09:32:10.264  5778  5798 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-12 09:32:10.274   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f94e7d:true
,10-12 09:32:12.600  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:12.605  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:12.611  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:12.615  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:12.686   928  2986 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-12 09:32:12.688   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-12 09:32:12.688   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:12.702   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 09:32:12.747   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 09:32:12.749  5762  5762 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 09:32:13.036   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:13.149   928   945 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,10-12 09:32:13.195  5762  5762 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 09:32:13.197   928   945 I ActivityManager: Start proc 5812:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 09:32:13.226  5762  5762 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 09:32:13.229  5762  5762 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 09:32:13.236   928  2986 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:32:13.236   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:13.237   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 09:32:13.247   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:13.259   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:13.263   928  2986 D WifiStateMachine: Start Dhcp Watchdog 2
,10-12 09:32:13.268   928  5827 D DhcpClient: Receive thread started
,10-12 09:32:13.271   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-12 09:32:13.271   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-12 09:32:13.271   928  3006 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-12 09:32:13.280  5812  5812 D AdapterServiceConfig: Adding HeadsetService
10-12 09:32:13.280  5812  5812 D AdapterServiceConfig: Adding A2dpService
10-12 09:32:13.280  5812  5812 D AdapterServiceConfig: Adding HidService
10-12 09:32:13.280  5812  5812 D AdapterServiceConfig: Adding HealthService
10-12 09:32:13.280  5812  5812 D AdapterServiceConfig: Adding PanService
10-12 09:32:13.280  5812  5812 D AdapterServiceConfig: Adding GattService
10-12 09:32:13.281  5812  5812 D AdapterServiceConfig: Adding BluetoothMapService
10-12 09:32:13.281  5812  5812 D AdapterServiceConfig: Adding SapService
,10-12 09:32:13.290   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d61282:true
,10-12 09:32:13.290  5812  5812 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 09:32:13.293  5812  5812 I bt_bluedroid: init
,10-12 09:32:13.293  5812  5828 I BluetoothAdapterState: Entering OffState
,10-12 09:32:13.295  5812  5829 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-12 09:32:13.295  5812  5829 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 09:32:13.295  5812  5829 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-12 09:32:13.296  5812  5829 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-12 09:32:13.296  5812  5812 I bt_bluedroid: get_profile_interface socket
,10-12 09:32:13.298  5812  5812 I bt_bluedroid: get_profile_interface sdp
,10-12 09:32:13.298  5812  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:32:13.300  5812  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 09:32:13.303  5812  5823 I bt_bluedroid: config_hci_snoop_log
,10-12 09:32:13.304   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 09:32:13.308  5812  5828 D BluetoothAdapterState: Current state: OFF, message: 0
,10-12 09:32:13.308  5812  5828 D BluetoothAdapterProperties: Setting state to 14
10-12 09:32:13.308  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-12 09:32:13.309  5812  5828 D BluetoothBondStateMachine: make
,10-12 09:32:13.311  5812  5833 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 09:32:13.313  5812  5828 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:32:13.314  5812  5812 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 09:32:13.317  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:13.317  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 09:32:13.318  5812  5812 D BtGatt.GattService: Received start request. Starting profile...
10-12 09:32:13.318  5812  5812 D BtGatt.GattService: start()
,10-12 09:32:13.318  5812  5812 I bt_bluedroid: get_profile_interface gatt
,10-12 09:32:13.320  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:13.320  5812  5812 D BtGatt.AdvertiseManager: advertise manager created
,10-12 09:32:13.325  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:32:13.325  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:13.325  5812  5812 V BluetoothAdapterState: isBleTurningOn()=true
10-12 09:32:13.325  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:13.325  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 09:32:13.326  5812  5828 I bt_bluedroid: bt_bluedroid
10-12 09:32:13.327  5812  5829 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-12 09:32:13.327  5812  5829 I bt_hci  : start_up
,10-12 09:32:13.331  5812  5829 I bt_vendor: alloc value 0xf3b3d871
10-12 09:32:13.332  5812  5829 I bt_vendor: init
,10-12 09:32:13.332  5812  5829 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 09:32:13.332  5812  5829 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 09:32:13.351   928  2986 E native  : do suspend false
,10-12 09:32:13.358   928  5826 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 09:32:13.371   928  5827 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172611, domain null
,10-12 09:32:13.371   928  5826 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172611 seconds
,10-12 09:32:13.372   928  5826 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 09:32:13.383   928  5827 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-12 09:32:13.384   928  5826 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-12 09:32:13.385   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:13.387   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 09:32:13.389   928  5826 D DhcpClient: Scheduling renewal in 86399s
,10-12 09:32:13.393   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 09:32:13.394   928  2986 D WifiConfigStore: No blacklist allowed without epno enabled
10-12 09:32:13.394   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-12 09:32:13.396   928  2986 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-12 09:32:13.398   928  3006 D ConnectivityService: Adding iface wlan0 to network 101
,10-12 09:32:13.422   928  3006 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-12 09:32:13.422   928  3006 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-12 09:32:13.424   928  3006 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-12 09:32:13.426   928  3006 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-12 09:32:13.428   928  3006 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-12 09:32:13.433   928  3006 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 09:32:13.437   928  3006 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-12 09:32:13.437   928  3006 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-12 09:32:13.437   928  3006 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,10-12 09:32:13.437   928  3006 D ConnectivityService:    accepting network in place of null
,10-12 09:32:13.437   928  2986 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-12 09:32:13.437   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:32:13.438   928  3006 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-12 09:32:13.439  5812  5829 D bt_hci  : start_up starting async portion
10-12 09:32:13.440  5812  5836 I bt_hci  : event_finish_startup
10-12 09:32:13.440  5812  5836 I bt_hci_h4: hal_open
10-12 09:32:13.440  5812  5836 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-12 09:32:13.437  5841  5841 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-12 09:32:13.441  5812  5836 I bt_userial_vendor: device fd = 54 open
,10-12 09:32:13.449   928  5825 D NetlinkSocketObserver: NeighborEvent{elapsedMs=228626, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 09:32:13.453  5812  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:32:13.455  5812  5836 D bt_hwcfg: Chipset BCM4358A3
,10-12 09:32:13.455  5812  5836 D bt_hwcfg: Target name = [BCM4358A3]
10-12 09:32:13.455  5812  5836 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 09:32:13.460   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:13.481   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:13.485   928  3006 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-12 09:32:13.485   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:32:13.485  3731  3909 W QCNEJ   : |CORE| network available: 101
,10-12 09:32:13.486   928  3006 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-12 09:32:13.487  3731  3909 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-12 09:32:13.489   928   945 D Tethering: MasterInitialState.processMessage what=3
10-12 09:32:13.489  3731  3909 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 09:32:13.489  3731  3909 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-12 09:32:13.493  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:13.493  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:13.494  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:13.494  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:13.495  4980  4999 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:32:13.495  4980  4999 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:32:13.495  4980  4999 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,10-12 09:32:13.497  4980  4999 E SarControlService: no key has been found,reset the power
,10-12 09:32:13.497  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:32:13.497  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:32:13.498  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:13.498  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:13.498  3890  3890 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 09:32:13.499  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:13.499  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:13.500  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 09:32:13.501  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:13.501  5005  5005 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 09:32:13.502  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:13.502  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:13.502  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:32:13.502  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:13.504  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 09:32:13.504  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:32:13.504  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:32:13.504  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:13.505  5005  5005 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:32:13.505  3890  3890 D SystemUpdateService: onCreate
,10-12 09:32:13.507  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000ec03000000000000ffffffff]
10-12 09:32:13.507  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:13.507  5005  5019 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-12 09:32:13.507  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-12 09:32:13.508  4980  4991 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 09:32:13.508  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000ed03000000000000ffffffff]
10-12 09:32:13.508  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:13.508  5005  5019 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-12 09:32:13.509  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:13.509  4980  4990 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:32:13.512  3890  3890 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 09:32:13.522  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 09:32:13.528   928  5824 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-12 09:32:13.533  3890  5404 I iu.UploadsManager: num queued entries: 0
,10-12 09:32:13.533  3890  5404 I iu.UploadsManager: num updated entries: 0
,10-12 09:32:13.534  3890  5404 I iu.SyncManager: NEXT; no task
,10-12 09:32:13.536  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 09:32:13.537  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 09:32:13.539  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-12 09:32:13.543  5717  5717 D SprintDMHelper: simOperator: 
10-12 09:32:13.543  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:32:13.555  3890  5849 I SystemUpdateService: active receiver: enabled
,10-12 09:32:13.575  3890  5849 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:32:13.581  3890  5849 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-12 09:32:13.581  3890  5849 I SystemUpdateService: now status is 0 (complete)
10-12 09:32:13.581  3890  5849 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-12 09:32:13.581  3890  5849 I SystemUpdateService: file has been verified
10-12 09:32:13.582  3890  5849 I SystemUpdateService: OTA package size = 21989297
,10-12 09:32:13.586  3890  5849 I SystemUpdateService: showing system update notification
,10-12 09:32:13.587   928  5824 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 13:32:13 GMT], X-Android-Received-Millis=[1476279133587], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476279133563]}
10-12 09:32:13.588   928  3006 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 09:32:13.588   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-12 09:32:13.588   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-12 09:32:13.589   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 09:32:13.601  3890  3890 D SystemUpdateService: onDestroy
,10-12 09:32:13.649  4929  5853 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-12 09:32:13.665  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-12 09:32:13.767  5812  5836 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 09:32:13.767  5812  5836 D bt_hwcfg: Settlement delay -- 100 ms
10-12 09:32:13.767  5812  5836 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 09:32:13.891  5812  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:32:13.891  5812  5836 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-12 09:32:13.893  5812  5836 I bt_hwcfg: vendor lib fwcfg completed
10-12 09:32:13.893  5812  5836 I bt_vendor: firmware callback
10-12 09:32:13.893  5812  5836 I bt_hci  : firmware_config_callback
,10-12 09:32:13.903  5812  5861 I bt_btu  : btu_task pending for preload complete event
10-12 09:32:13.903  5812  5861 I bt_btu_task: Bluetooth chip preload is complete
10-12 09:32:13.903  5812  5861 I bt_btu  : btu_task received preload complete event
,10-12 09:32:13.909  5812  5861 I         : BTE_InitTraceLevels -- TRC_HCI
,10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_A2D
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_BTM
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_GAP
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_GATT
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_SMP
,10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-12 09:32:13.910  5812  5861 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 09:32:13.991  5812  5861 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3abb549
,10-12 09:32:13.991  5812  5861 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3abb549 
,10-12 09:32:14.013  5812  5832 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 09:32:14.014  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 09:32:14.015  5812  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:32:14.017  5812  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 09:32:14.020  5812  5832 D BluetoothAdapterProperties: Scan Mode:20
,10-12 09:32:14.021  5812  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-12 09:32:14.021  5812  5832 D bt_hci  : do_postload posting postload work item
,10-12 09:32:14.021  5812  5836 I bt_hci  : event_postload
10-12 09:32:14.021  5812  5836 I bt_vendor: sco_config_cb
10-12 09:32:14.021  5812  5836 I bt_hci  : sco_config_callback postload finished.
,10-12 09:32:14.025  5812  5832 D bt_bte_conf: Device ID record 1 : primary
10-12 09:32:14.025  5812  5832 D bt_bte_conf:   vendorId            = 000f
10-12 09:32:14.025  5812  5832 D bt_bte_conf:   vendorIdSource      = 0001
10-12 09:32:14.025  5812  5832 D bt_bte_conf:   product             = 1200
10-12 09:32:14.025  5812  5832 D bt_bte_conf:   version             = 1436
10-12 09:32:14.025  5812  5832 D bt_bte_conf:   clientExecutableURL = 
10-12 09:32:14.025  5812  5832 D bt_bte_conf:   serviceDescription  = 
10-12 09:32:14.026  5812  5832 D bt_bte_conf:   documentationURL    = 
10-12 09:32:14.026  5812  5832 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-12 09:32:14.026  5812  5829 D bt_stack_manager: event_start_up_stack finished
10-12 09:32:14.027  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-12 09:32:14.027  5812  5828 D BluetoothAdapterProperties: Setting state to 15
10-12 09:32:14.028  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-12 09:32:14.030  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.033  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.036  5812  5836 I bt_vendor: low_power_mode_cb
10-12 09:32:14.036  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.036  5812  5828 I BluetoothAdapterState: Entering BleOnState
10-12 09:32:14.036  5812  5828 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-12 09:32:14.036  5812  5828 D BluetoothAdapterProperties: Setting state to 11
10-12 09:32:14.036  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-12 09:32:14.037   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:14.041  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:14.042  5812  5812 D HeadsetService: Received start request. Starting profile...
10-12 09:32:14.043  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.044  5812  5812 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 09:32:14.045  5812  5812 D HeadsetStateMachine: make
10-12 09:32:14.046  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.050  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.051  5812  5828 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:32:14.055  5812  5812 D HeadsetStateMachine: max_hf_connections = 1
,10-12 09:32:14.055  5812  5812 I bt_bluedroid: get_profile_interface handsfree
10-12 09:32:14.055  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 09:32:14.055  5812  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-12 09:32:14.058  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:14.059  5812  5812 D A2dpService: Received start request. Starting profile...
,10-12 09:32:14.060  5812  5812 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-12 09:32:14.060  5812  5812 I bt_bluedroid: get_profile_interface avrcp
,10-12 09:32:14.064  5812  5812 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 09:32:14.065  5812  5812 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 09:32:14.065  5812  5812 D A2dpStateMachine: make
10-12 09:32:14.066  5812  5812 I bt_bluedroid: get_profile_interface a2dp
,10-12 09:32:14.067  5812  5868 D A2dpStateMachine: Enter Disconnected: -2
,10-12 09:32:14.067  5812  5812 I BluetoothHidServiceJni: classInitNative: succeeds
,10-12 09:32:14.068  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:14.069  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 09:32:14.069  5812  5812 D HidService: Received start request. Starting profile...
,10-12 09:32:14.070  5812  5812 I bt_bluedroid: get_profile_interface hidhost
10-12 09:32:14.070  5812  5812 D HidService: setHidService(): set to: null
10-12 09:32:14.070  5812  5832 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a9c56d
10-12 09:32:14.070  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-12 09:32:14.070  5766  5766 D BluetoothInputDevice: Proxy object connected
10-12 09:32:14.070  5812  5812 I BluetoothHealthServiceJni: classInitNative: succeeds
10-12 09:32:14.070  5766  5766 D HidProfile: Bluetooth service connected
,10-12 09:32:14.071  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:14.072  5812  5812 D HealthService: Received start request. Starting profile...
,10-12 09:32:14.073  5812  5812 I bt_bluedroid: get_profile_interface health
,10-12 09:32:14.074  5812  5812 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-12 09:32:14.074  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:14.075  5766  5766 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:32:14.075  5812  5812 D PanService: Received start request. Starting profile...
10-12 09:32:14.076  5812  5812 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 09:32:14.076  5812  5812 I bt_bluedroid: get_profile_interface pan
10-12 09:32:14.076  5766  5766 D PanProfile: Bluetooth service connected
10-12 09:32:14.076  5812  5832 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-12 09:32:14.079  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:14.080  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:14.082  5766  5766 D BluetoothMap: Proxy object connected
,10-12 09:32:14.082  5812  5812 D BluetoothMapService: Received start request. Starting profile...
10-12 09:32:14.082  5812  5812 D BluetoothMapService: start()
10-12 09:32:14.082  5766  5766 D MapProfile: Bluetooth service connected
10-12 09:32:14.083  5766  5766 D BluetoothMap: getConnectedDevices()
10-12 09:32:14.083  5766  5766 D BluetoothMap: Bluetooth is Not enabled
,10-12 09:32:14.085  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-12 09:32:14.085  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-12 09:32:14.086  5812  5812 D BluetoothMapAppObserver: createReceiver()
10-12 09:32:14.087  5812  5812 D BluetoothMapAppObserver: initObservers()
10-12 09:32:14.087  5812  5812 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 09:32:14.092  5812  5812 V SapService: SapBinder()
,10-12 09:32:14.093  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:14.093  5812  5812 D SapService: Received start request. Starting profile...
10-12 09:32:14.093  5812  5812 V SapService: start()
,10-12 09:32:14.095  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.096  5812  5866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:14.096  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.097  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.097  5812  5812 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:14.097  5812  5812 V BluetoothAdapterState: isTurningOn()=true
,10-12 09:32:14.097  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.097  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.098  5812  5812 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:14.098  5812  5812 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:14.098  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.098  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:32:14.098  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-12 09:32:14.098  5812  5828 D BluetoothAdapterProperties: ScanMode =  20
10-12 09:32:14.098  5812  5828 D BluetoothAdapterProperties: State =  11
,10-12 09:32:14.099  5812  5828 D BluetoothAdapterProperties: Setting state to 12
10-12 09:32:14.099  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 09:32:14.099  5812  5828 I BluetoothAdapterState: Entering OnState
10-12 09:32:14.099  3118  3133 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:32:14.100  5812  5832 D BluetoothAdapterProperties: Scan Mode:21
10-12 09:32:14.100  5812  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 09:32:14.101  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 09:32:14.102  5766  5776 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 09:32:14.104  5639  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-12 09:32:14.105  3118  3924 D BluetoothMap: onBluetoothStateChange: up=true
,10-12 09:32:14.105  3118  3118 D BluetoothA2dp: Proxy object connected
10-12 09:32:14.107  5639  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-12 09:32:14.108  3118  3118 D BluetoothMap: Proxy object connected
10-12 09:32:14.108  3118  3118 D MapProfile: Bluetooth service connected
10-12 09:32:14.108  3118  3118 D BluetoothMap: getConnectedDevices()
10-12 09:32:14.108   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 09:32:14.109  3780  4017 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:14.109  5766  5777 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:32:14.110   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 09:32:14.110   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:14.110   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-12 09:32:14.111   928   928 D BluetoothA2dp: Proxy object connected
10-12 09:32:14.111  3118  3131 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:14.111  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:14.113  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 09:32:14.113  5812  5812 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 09:32:14.114  5766  5776 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:32:14.115  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:14.115  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.115  3118  3133 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:14.116  3118  3924 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:32:14.116  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:14.118  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:32:14.118  3118  3118 D PanProfile: Bluetooth service connected
10-12 09:32:14.118  5812  5812 D ObexServerSockets: Succeed to create listening sockets 
,10-12 09:32:14.118  5812  5812 D ObexServerSockets0: startAccept()
10-12 09:32:14.118  5812  5812 D ObexServerSockets0: prepareForNewConnect()
10-12 09:32:14.118  3118  3133 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:14.119  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:14.121  5812  5812 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 09:32:14.121  5766  5777 D BluetoothMap: onBluetoothStateChange: up=true
,10-12 09:32:14.121  3118  3118 D BluetoothInputDevice: Proxy object connected
10-12 09:32:14.121  3118  3118 D HidProfile: Bluetooth service connected
10-12 09:32:14.121  5812  5812 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 09:32:14.122  5812  5874 D ObexServerSockets0: Accepting socket connection...
10-12 09:32:14.123  5812  5875 D ObexServerSockets0: Accepting socket connection...
,10-12 09:32:14.123   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-12 09:32:14.124  5812  5812 D BluetoothMapService: onReceive
,10-12 09:32:14.124  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:32:14.124  5812  5812 D BluetoothMapService: STATE_ON
10-12 09:32:14.125  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.126  5766  5766 D LocalBluetoothProfileManager: Adding local A2DP profile
10-12 09:32:14.128  5812  5878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:14.130  5812  5878 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-12 09:32:14.130  5766  5766 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-12 09:32:14.130  5812  5878 D BluetoothSdpJni: SDP Create record success - handle: 1
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:14.131  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:32:14.133  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:14.134  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 09:32:14.135  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.138  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.139  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 09:32:14.142  5766  5766 D BluetoothA2dp: Proxy object connected
,10-12 09:32:14.142  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.145  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 09:32:14.145  5812  5812 D ObexServerSockets0: prepareForNewConnect()
,10-12 09:32:14.146  5766  5766 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:32:14.146  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:14.154  5766  5766 D BluetoothPbap: Proxy object connected
10-12 09:32:14.154  3118  3118 D BluetoothPbap: Proxy object connected
10-12 09:32:14.154  3118  3118 D PbapServerProfile: Bluetooth service connected
10-12 09:32:14.155  5766  5766 D PbapServerProfile: Bluetooth service connected
,10-12 09:32:14.160  5812  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:14.168  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.170  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:32:14.170  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:32:14.171  5639  5685 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
10-12 09:32:14.172  5639  5685 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-12 09:32:14.174  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.175  5812  5828 D BluetoothAdapterState: Current state: ON, message: 23
10-12 09:32:14.175  5812  5828 D BluetoothAdapterProperties: Setting state to 13
10-12 09:32:14.175  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-12 09:32:14.175  5812  5828 D BluetoothAdapterProperties: onBluetoothDisable()
10-12 09:32:14.176  5812  5828 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:32:14.178  5812  5812 D BluetoothMapService: onReceive
,10-12 09:32:14.178  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:32:14.178  5812  5812 D BluetoothMapService: STATE_TURNING_OFF
10-12 09:32:14.178  5812  5812 D BluetoothMapService: MAP Service closeService in
10-12 09:32:14.178  5812  5812 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 09:32:14.179  5812  5832 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:32:14.179  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-12 09:32:14.179  5812  5812 D ObexServerSockets0: shutdown(block = true)
10-12 09:32:14.180  5812  5812 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:32:14.180  5812  5874 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-12 09:32:14.181  5812  5875 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-12 09:32:14.181  5812  5812 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:32:14.181  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:32:14.182  5812  5863 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 09:32:14.183  5812  5812 D HeadsetService: Received stop request...Stopping profile...
10-12 09:32:14.185  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:14.185  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:14.186  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:14.186  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:14.187  5766  5766 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:32:14.189  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:14.189  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:14.189  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:14.189  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:14.191  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.194  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.196  5812  5812 D A2dpService: Received stop request...Stopping profile...
,10-12 09:32:14.196  5812  5868 D A2dpStateMachine: Exit Disconnected: -1
,10-12 09:32:14.197   928   928 D BluetoothA2dp: Proxy object disconnected
10-12 09:32:14.198  5766  5766 D BluetoothA2dp: Proxy object disconnected
,10-12 09:32:14.198  5812  5812 D HidService: Received stop request...Stopping profile...
10-12 09:32:14.198  5812  5812 D HidService: Stopping Bluetooth HidService
10-12 09:32:14.199  5766  5766 D BluetoothInputDevice: Proxy object disconnected
10-12 09:32:14.199  5766  5766 D HidProfile: Bluetooth service disconnected
10-12 09:32:14.200  5812  5812 D HealthService: Received stop request...Stopping profile...
,10-12 09:32:14.202  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:14.203  5812  5812 D PanService: Received stop request...Stopping profile...
,10-12 09:32:14.204  5812  5812 V BluetoothAdapterState: isTurningOff()=true
,10-12 09:32:14.205  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.205  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.205  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.206  5812  5812 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-12 09:32:14.206  5812  5812 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-12 09:32:14.206  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 09:32:14.206  5812  5861 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:14.206  5812  5861 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:14.206  5812  5861 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:14.206  3118  3118 D BluetoothA2dp: Proxy object disconnected
10-12 09:32:14.207  3118  3118 D BluetoothInputDevice: Proxy object disconnected
10-12 09:32:14.207  5812  5812 D BluetoothMapService: Received stop request...Stopping profile...
10-12 09:32:14.207  3118  3118 D HidProfile: Bluetooth service disconnected
10-12 09:32:14.207  5812  5812 D BluetoothMapService: stop()
10-12 09:32:14.207  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-12 09:32:14.207  3118  3118 D PanProfile: Bluetooth service disconnected
10-12 09:32:14.207  5812  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
10-12 09:32:14.207  5812  5812 D BluetoothMapAppObserver: deinitObservers()
10-12 09:32:14.207  5812  5812 D BluetoothMapAppObserver: removeReceiver()
10-12 09:32:14.208  3118  3118 D BluetoothMap: Proxy object disconnected
10-12 09:32:14.208  3118  3118 D MapProfile: Bluetooth service disconnected
10-12 09:32:14.209  5812  5812 D SapService: Received stop request...Stopping profile...
10-12 09:32:14.209  5766  5766 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 09:32:14.209  5812  5812 V SapService: stop()
10-12 09:32:14.209  5766  5766 D PanProfile: Bluetooth service disconnected
10-12 09:32:14.209  5766  5766 D BluetoothMap: Proxy object disconnected
10-12 09:32:14.209  5766  5766 D MapProfile: Bluetooth service disconnected
10-12 09:32:14.210  5812  5812 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:14.210  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.210  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.210  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.211  5812  5861 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:14.212  5812  5861 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:14.212  5812  5812 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:14.212  5812  5812 V BluetoothAdapterState: isTurningOn()=false
,10-12 09:32:14.212  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.212  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 09:32:14.212  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.212  5812  5861 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 09:32:14.212  5812  5812 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 09:32:14.212  5812  5812 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 09:32:14.212  5812  5861 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:32:14.212  5812  5861 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 09:32:14.212  5812  5861 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:32:14.212  5812  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 09:32:14.217  3118  3118 D BluetoothPbap: Proxy object disconnected
,10-12 09:32:14.217  3118  3118 D PbapServerProfile: Bluetooth service disconnected
10-12 09:32:14.218  5766  5766 D BluetoothPbap: Proxy object disconnected
10-12 09:32:14.218  5766  5766 D PbapServerProfile: Bluetooth service disconnected
10-12 09:32:14.218  5812  5812 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:14.218  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.218  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.218  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.218  5812  5812 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-12 09:32:14.218  5812  5832 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 09:32:14.218  5812  5812 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-12 09:32:14.219  5812  5812 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:14.219  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.219  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 09:32:14.219  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.219  5812  5812 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 09:32:14.219  5812  5812 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 09:32:14.220  5812  5812 D BluetoothMapService: MAP Service closeService in
10-12 09:32:14.220  5812  5812 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:14.220  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.221  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.221  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.221  5812  5812 D BluetoothMapService: cleanup()
10-12 09:32:14.221  5812  5812 D BluetoothMapService: MAP Service closeService in
10-12 09:32:14.221  5812  5812 V BluetoothAdapterState: isTurningOff()=true
10-12 09:32:14.221  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.221  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.221  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:32:14.221  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-12 09:32:14.221  5812  5828 D BluetoothAdapterProperties: Setting state to 15
10-12 09:32:14.221  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 09:32:14.222  3118  3924 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:32:14.222  5812  5828 I BluetoothAdapterState: Entering BleOnState
10-12 09:32:14.223  5766  5776 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 09:32:14.224  3118  3133 D BluetoothMap: onBluetoothStateChange: up=false
10-12 09:32:14.224   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:14.224  3780  3807 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-12 09:32:14.225  5766  5777 D BluetoothPan: onBluetoothStateChange on: false
10-12 09:32:14.225   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:14.225   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:14.225   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:32:14.225  5766  5776 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:32:14.226  3118  3131 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 09:32:14.226  5766  5777 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 09:32:14.227  5766  5776 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-12 09:32:14.227  3118  3924 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:32:14.227  3118  3133 D BluetoothPan: onBluetoothStateChange on: false
10-12 09:32:14.227  3118  3131 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 09:32:14.228  5766  5777 D BluetoothMap: onBluetoothStateChange: up=false
10-12 09:32:14.228  5812  5828 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 09:32:14.228  5812  5828 D BluetoothAdapterProperties: Setting state to 16
10-12 09:32:14.228  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 09:32:14.229  5812  5828 D BluetoothAdapterProperties: onBleDisable
10-12 09:32:14.229  5812  5828 I BluetoothAdapterState: Entering PendingCommandState
10-12 09:32:14.229  5812  5829 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 09:32:14.230  5812  5861 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 09:32:14.230  5812  5861 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:32:14.231  5812  5832 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:32:14.231  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:32:14.233  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.236  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.237  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 09:32:14.239  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:14.239  5766  5766 D DockEventReceiver: finishStartingService: stopping service
10-12 09:32:14.241  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.430  5812  5832 I bt_hci  : shut_down
,10-12 09:32:14.430  5812  5836 D bt_hwcfg: hw_epilog_process
10-12 09:32:14.431  5812  5836 I bt_vendor: low_power_mode_cb
,10-12 09:32:14.433  5812  5836 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-12 09:32:14.433  5812  5836 I bt_vendor: epilog_cb
10-12 09:32:14.433  5812  5836 I bt_hci  : epilog_finished_callback
10-12 09:32:14.434  5812  5832 I bt_hci_h4: hal_close
10-12 09:32:14.434  5812  5832 I bt_userial_vendor: device fd = 54 close
,10-12 09:32:14.486   928  3006 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-12 09:32:14.552  5812  5829 D bt_stack_manager: event_shut_down_stack finished.
,10-12 09:32:14.553  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-12 09:32:14.556  5812  5828 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-12 09:32:14.556  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 09:32:14.557  5812  5812 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 09:32:14.557  5812  5812 D BtGatt.GattService: stop()
,10-12 09:32:14.557  5812  5812 D BtGatt.AdvertiseManager: advertise clients cleared
,10-12 09:32:14.561  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:32:14.562  5812  5812 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.562  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:14.562  5812  5812 V BluetoothAdapterState: isBleTurningOff()=true
10-12 09:32:14.562  5812  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-12 09:32:14.563  5812  5828 D BluetoothAdapterProperties: Setting state to 10
10-12 09:32:14.563  5812  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 09:32:14.564  5812  5828 I BluetoothAdapterState: Entering OffState
10-12 09:32:14.565   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-12 09:32:14.579  5812  5812 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-12 09:32:14.579  5812  5812 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-12 09:32:14.580  5812  5812 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-12 09:32:14.582  5812  5829 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-12 09:32:14.588  5812  5812 I art     : System.exit called, status: 0
,10-12 09:32:14.588  5812  5812 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 09:32:14.609   928  3801 I ActivityManager: Process com.android.bluetooth (pid 5812) has died
,10-12 09:32:14.675  5639  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:14.675  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:32:14.675  5639  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:32:14.675  5639  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:14.679  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:14.700   928   945 I ActivityManager: Start proc 5890:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 09:32:14.763  5890  5890 D AdapterServiceConfig: Adding HeadsetService
,10-12 09:32:14.764  5890  5890 D AdapterServiceConfig: Adding A2dpService
10-12 09:32:14.764  5890  5890 D AdapterServiceConfig: Adding HidService
10-12 09:32:14.764  5890  5890 D AdapterServiceConfig: Adding HealthService
10-12 09:32:14.764  5890  5890 D AdapterServiceConfig: Adding PanService
,10-12 09:32:14.765  5890  5890 D AdapterServiceConfig: Adding GattService
10-12 09:32:14.765  5890  5890 D AdapterServiceConfig: Adding BluetoothMapService
,10-12 09:32:14.765  5890  5890 D AdapterServiceConfig: Adding SapService
,10-12 09:32:14.778   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a50f9a7:true
,10-12 09:32:14.778  5890  5890 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 09:32:14.781  5890  5890 I bt_bluedroid: init
,10-12 09:32:14.781  5890  5902 I BluetoothAdapterState: Entering OffState
,10-12 09:32:14.783  5890  5903 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-12 09:32:14.784  5890  5903 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 09:32:14.784  5890  5903 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 09:32:14.784  5890  5903 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-12 09:32:14.784  5890  5890 I bt_bluedroid: get_profile_interface socket
,10-12 09:32:14.785  5890  5890 I bt_bluedroid: get_profile_interface sdp
,10-12 09:32:14.785  5890  5906 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:32:14.787  5890  5906 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 09:32:14.790  5890  5901 I bt_bluedroid: config_hci_snoop_log
,10-12 09:32:14.791   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 09:32:14.795  5890  5902 D BluetoothAdapterState: Current state: OFF, message: 0
,10-12 09:32:14.795  5890  5902 D BluetoothAdapterProperties: Setting state to 14
10-12 09:32:14.795  5890  5902 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-12 09:32:14.796  5890  5902 D BluetoothBondStateMachine: make
,10-12 09:32:14.798  5890  5907 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 09:32:14.800  5890  5902 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:32:14.801  5890  5890 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 09:32:14.803  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:14.803  5890  5890 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 09:32:14.803  5890  5890 D BtGatt.GattService: Received start request. Starting profile...
10-12 09:32:14.803  5890  5890 D BtGatt.GattService: start()
10-12 09:32:14.804  5890  5890 I bt_bluedroid: get_profile_interface gatt
10-12 09:32:14.804  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:14.804  5890  5890 D BtGatt.AdvertiseManager: advertise manager created
,10-12 09:32:14.809  5890  5890 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:32:14.809  5890  5890 V BluetoothAdapterState: isTurningOn()=false
10-12 09:32:14.809  5890  5890 V BluetoothAdapterState: isBleTurningOn()=true
10-12 09:32:14.809  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:14.809  5890  5902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 09:32:14.810  5890  5902 I bt_bluedroid: bt_bluedroid
10-12 09:32:14.810  5890  5903 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-12 09:32:14.811  5890  5903 I bt_hci  : start_up
,10-12 09:32:14.816  5890  5903 I bt_vendor: alloc value 0xf3b3d871
10-12 09:32:14.816  5890  5903 I bt_vendor: init
,10-12 09:32:14.817  5890  5903 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 09:32:14.817  5890  5903 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 09:32:14.930  5890  5903 D bt_hci  : start_up starting async portion
10-12 09:32:14.931  5890  5910 I bt_hci  : event_finish_startup
,10-12 09:32:14.931  5890  5910 I bt_hci_h4: hal_open
10-12 09:32:14.931  5890  5910 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-12 09:32:14.927  5911  5911 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:32:14.933  5890  5910 I bt_userial_vendor: device fd = 54 open
,10-12 09:32:14.946  5890  5910 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:32:14.949  5890  5910 D bt_hwcfg: Chipset BCM4358A3
,10-12 09:32:14.949  5890  5910 D bt_hwcfg: Target name = [BCM4358A3]
10-12 09:32:14.949  5890  5910 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 09:32:15.038   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:15.184  5890  5902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-12 09:32:15.360  5890  5910 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 09:32:15.360  5890  5910 D bt_hwcfg: Settlement delay -- 100 ms
10-12 09:32:15.360  5890  5910 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 09:32:15.483  5890  5910 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-12 09:32:15.483  5890  5910 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-12 09:32:15.485  5890  5910 I bt_hwcfg: vendor lib fwcfg completed
10-12 09:32:15.485  5890  5910 I bt_vendor: firmware callback
10-12 09:32:15.485  5890  5910 I bt_hci  : firmware_config_callback
,10-12 09:32:15.494  5890  5913 I bt_btu  : btu_task pending for preload complete event
,10-12 09:32:15.494  5890  5913 I bt_btu_task: Bluetooth chip preload is complete
10-12 09:32:15.494  5890  5913 I bt_btu  : btu_task received preload complete event
,10-12 09:32:15.500  5890  5913 I         : BTE_InitTraceLevels -- TRC_HCI
,10-12 09:32:15.501  5890  5913 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-12 09:32:15.501  5890  5913 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 09:32:15.501  5890  5913 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 09:32:15.501  5890  5913 I         : BTE_InitTraceLevels -- TRC_AVRC
10-12 09:32:15.501  5890  5913 I         : BTE_InitTraceLevels -- TRC_A2D
,10-12 09:32:15.501  5890  5913 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_BTM
,10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_GAP
10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_GATT
,10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_SMP
10-12 09:32:15.502  5890  5913 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-12 09:32:15.503  5890  5913 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 09:32:15.579  5890  5913 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3abb549
10-12 09:32:15.580  5890  5913 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3abb549 
,10-12 09:32:15.600  5890  5906 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 09:32:15.601  5890  5906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 09:32:15.602  5890  5906 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:32:15.605  5890  5906 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 09:32:15.607  5890  5906 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:32:15.607  5890  5906 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-12 09:32:15.608  5890  5906 D bt_hci  : do_postload posting postload work item
10-12 09:32:15.608  5890  5910 I bt_hci  : event_postload
10-12 09:32:15.608  5890  5910 I bt_vendor: sco_config_cb
10-12 09:32:15.608  5890  5910 I bt_hci  : sco_config_callback postload finished.
,10-12 09:32:15.614  5890  5910 I bt_vendor: low_power_mode_cb
,10-12 09:32:15.615  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:15.620  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:15.620  5890  5906 D bt_bte_conf: Device ID record 1 : primary
10-12 09:32:15.620  5890  5906 D bt_bte_conf:   vendorId            = 000f
10-12 09:32:15.620  5890  5906 D bt_bte_conf:   vendorIdSource      = 0001
10-12 09:32:15.621  5890  5906 D bt_bte_conf:   product             = 1200
10-12 09:32:15.621  5890  5906 D bt_bte_conf:   version             = 1436
10-12 09:32:15.621  5890  5906 D bt_bte_conf:   clientExecutableURL = 
10-12 09:32:15.621  5890  5906 D bt_bte_conf:   serviceDescription  = 
10-12 09:32:15.621  5890  5906 D bt_bte_conf:   documentationURL    = 
10-12 09:32:15.621  5890  5906 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-12 09:32:15.621  5890  5903 D bt_stack_manager: event_start_up_stack finished
,10-12 09:32:15.623  5890  5902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-12 09:32:15.624  5890  5902 D BluetoothAdapterProperties: Setting state to 15
10-12 09:32:15.624  5890  5902 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-12 09:32:15.624  5890  5902 I BluetoothAdapterState: Entering BleOnState
,10-12 09:32:15.627  5890  5902 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-12 09:32:15.627  5890  5902 D BluetoothAdapterProperties: Setting state to 11
10-12 09:32:15.627  5890  5902 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-12 09:32:15.631  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:15.637  3780  4017 D BluetoothHeadset: Proxy object connected
,10-12 09:32:15.637  5890  5890 D HeadsetService: Received start request. Starting profile...
10-12 09:32:15.637   928   928 D BluetoothHeadset: Proxy object connected
10-12 09:32:15.637  5766  5776 D BluetoothHeadset: Proxy object connected
,10-12 09:32:15.638   928   928 D BluetoothHeadset: Proxy object connected
10-12 09:32:15.638   928   928 D BluetoothHeadset: Proxy object connected
10-12 09:32:15.639  3118  3131 D BluetoothHeadset: Proxy object connected
10-12 09:32:15.639  3118  3118 D HeadsetProfile: Bluetooth service connected
10-12 09:32:15.640  5766  5766 D HeadsetProfile: Bluetooth service connected
10-12 09:32:15.640  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:15.643  5890  5890 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-12 09:32:15.643  5890  5890 D HeadsetStateMachine: make
10-12 09:32:15.644  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:15.647  5890  5902 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:32:15.652  5890  5890 D HeadsetStateMachine: max_hf_connections = 1
10-12 09:32:15.652  5890  5890 I bt_bluedroid: get_profile_interface handsfree
10-12 09:32:15.652  5890  5906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 09:32:15.653  5890  5906 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-12 09:32:15.655  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:15.656  5890  5890 D A2dpService: Received start request. Starting profile...
,10-12 09:32:15.657  5890  5890 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-12 09:32:15.657  5890  5890 I bt_bluedroid: get_profile_interface avrcp
,10-12 09:32:15.662  5890  5890 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 09:32:15.662  5890  5890 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 09:32:15.662  5890  5890 D A2dpStateMachine: make
,10-12 09:32:15.663  5890  5890 I bt_bluedroid: get_profile_interface a2dp
10-12 09:32:15.664  5890  5906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 09:32:15.665  5890  5922 D A2dpStateMachine: Enter Disconnected: -2
,10-12 09:32:15.666  5890  5890 I BluetoothHidServiceJni: classInitNative: succeeds
,10-12 09:32:15.667  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:15.667  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:15.668  5890  5890 D HidService: Received start request. Starting profile...
,10-12 09:32:15.668  5890  5890 I bt_bluedroid: get_profile_interface hidhost
10-12 09:32:15.668  5890  5906 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a9c56d
10-12 09:32:15.668  5890  5890 D HidService: setHidService(): set to: null
10-12 09:32:15.668  5890  5906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-12 09:32:15.669  5890  5890 I BluetoothHealthServiceJni: classInitNative: succeeds
10-12 09:32:15.670  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:15.670  5890  5890 D HealthService: Received start request. Starting profile...
,10-12 09:32:15.672  5890  5890 I bt_bluedroid: get_profile_interface health
,10-12 09:32:15.672  5890  5890 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-12 09:32:15.673  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:15.674  5890  5890 D PanService: Received start request. Starting profile...
,10-12 09:32:15.674  5890  5890 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 09:32:15.674  5890  5890 I bt_bluedroid: get_profile_interface pan
10-12 09:32:15.674  5890  5906 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-12 09:32:15.676  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:15.677  5890  5890 D BluetoothMapService: Received start request. Starting profile...
,10-12 09:32:15.677  5890  5890 D BluetoothMapService: start()
10-12 09:32:15.680  5890  5890 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-12 09:32:15.681  5890  5890 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-12 09:32:15.681  5890  5890 D BluetoothMapAppObserver: createReceiver()
10-12 09:32:15.682  5890  5890 D BluetoothMapAppObserver: initObservers()
10-12 09:32:15.682  5890  5890 D BluetoothMapAppObserver: getEnabledAccountItems()
10-12 09:32:15.686  5890  5902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-12 09:32:15.688  5890  5890 V SapService: SapBinder()
,10-12 09:32:15.688  5890  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
10-12 09:32:15.689  5890  5890 D SapService: Received start request. Starting profile...
,10-12 09:32:15.689  5890  5890 V SapService: start()
,10-12 09:32:15.692  5890  5890 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:32:15.692  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.692  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.692  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:15.692  5890  5920 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.693  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isTurningOff()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isTurningOn()=true
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:32:15.694  5890  5890 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:32:15.695  5890  5902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-12 09:32:15.695  5890  5902 D BluetoothAdapterProperties: ScanMode =  20
10-12 09:32:15.695  5890  5902 D BluetoothAdapterProperties: State =  11
10-12 09:32:15.695  5890  5902 D BluetoothAdapterProperties: Setting state to 12
10-12 09:32:15.695  5890  5902 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 09:32:15.696  5890  5902 I BluetoothAdapterState: Entering OnState
,10-12 09:32:15.696  3118  3924 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-12 09:32:15.699  5890  5906 D BluetoothAdapterProperties: Scan Mode:21
10-12 09:32:15.699  5890  5906 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 09:32:15.699  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-12 09:32:15.700  5766  5777 D BluetoothPbap: onBluetoothStateChange: up=true
,10-12 09:32:15.700  3118  3118 D BluetoothA2dp: Proxy object connected
10-12 09:32:15.702  3118  3131 D BluetoothMap: onBluetoothStateChange: up=true
10-12 09:32:15.703   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:15.704  3780  3810 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:15.704  5766  5776 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:32:15.705  3118  3118 D BluetoothMap: Proxy object connected
10-12 09:32:15.705  3118  3118 D MapProfile: Bluetooth service connected
10-12 09:32:15.705  3118  3118 D BluetoothMap: getConnectedDevices()
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:15.705  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:15.707  5890  5890 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 09:32:15.708  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:15.708  5890  5890 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:15.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:15.712  5890  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:15.713   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:15.714   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 09:32:15.714   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:32:15.714  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:15.714   928   928 D BluetoothA2dp: Proxy object connected
10-12 09:32:15.714  5766  5777 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:32:15.715  5890  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:15.717  3118  3924 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 09:32:15.717  5890  5890 D ObexServerSockets: Succeed to create listening sockets 
10-12 09:32:15.717  5890  5890 D ObexServerSockets0: startAccept()
10-12 09:32:15.717  5890  5890 D ObexServerSockets0: prepareForNewConnect()
10-12 09:32:15.718  5766  5766 D BluetoothA2dp: Proxy object connected
10-12 09:32:15.719  5890  5890 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 09:32:15.719  5890  5890 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-12 09:32:15.719  5766  5776 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:32:15.720  5890  5929 D ObexServerSockets0: Accepting socket connection...
10-12 09:32:15.720  5890  5930 D ObexServerSockets0: Accepting socket connection...
10-12 09:32:15.721  5766  5777 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:15.721  3118  3131 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:32:15.721  3118  3133 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:32:15.722  3118  3131 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:32:15.723  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:32:15.723  3118  3118 D PanProfile: Bluetooth service connected
10-12 09:32:15.723  3118  3118 D BluetoothInputDevice: Proxy object connected
10-12 09:32:15.723  5766  5777 D BluetoothMap: onBluetoothStateChange: up=true
10-12 09:32:15.723  3118  3118 D HidProfile: Bluetooth service connected
,10-12 09:32:15.724  5766  5766 D BluetoothPan: BluetoothPAN Proxy object connected
,10-12 09:32:15.724  5766  5766 D PanProfile: Bluetooth service connected
10-12 09:32:15.724  5766  5766 D BluetoothInputDevice: Proxy object connected
10-12 09:32:15.724  5766  5766 D HidProfile: Bluetooth service connected
10-12 09:32:15.727   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-12 09:32:15.727  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 09:32:15.727  5890  5890 D BluetoothMapService: onReceive
10-12 09:32:15.727  5890  5890 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:32:15.727  5890  5890 D BluetoothMapService: STATE_ON
10-12 09:32:15.727   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,10-12 09:32:15.731  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:15.731  5890  5931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:15.731  5766  5766 D BluetoothMap: Proxy object connected
10-12 09:32:15.731  5766  5766 D MapProfile: Bluetooth service connected
10-12 09:32:15.731  5766  5766 D BluetoothMap: getConnectedDevices()
10-12 09:32:15.732  5890  5931 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 09:32:15.732  5890  5931 D BluetoothSdpJni: SDP Create record success - handle: 1
10-12 09:32:15.733  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:15.736  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 09:32:15.741  5766  5766 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:32:15.741  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:32:15.747  5766  5766 D BluetoothPbap: Proxy object connected
,10-12 09:32:15.747  5766  5766 D PbapServerProfile: Bluetooth service connected
10-12 09:32:15.748  3118  3118 D BluetoothPbap: Proxy object connected
10-12 09:32:15.748  3118  3118 D PbapServerProfile: Bluetooth service connected
,10-12 09:32:15.752  5890  5890 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 09:32:15.752  5890  5890 D ObexServerSockets0: prepareForNewConnect()
,10-12 09:32:15.753  5890  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:15.764  5890  5940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:15.765  5890  5940 I BtOppRfcommListener: Accept thread started.
,10-12 09:32:16.039   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:16.198  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:32:16.203  5639  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:16.206  5639  5685 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,10-12 09:32:16.210   928  3748 D WifiService: setWifiEnabled: false pid=5639, uid=10077
10-12 09:32:16.210   928  3748 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-12 09:32:16.213  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:16.215   928  2986 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-12 09:32:16.216   928  2986 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-12 09:32:16.216   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 09:32:16.217   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:16.236   506   922 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:32:16.235   928  5826 D DhcpClient: Clearing IP address
,10-12 09:32:16.244   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:16.246   928  5827 D DhcpClient: Receive thread stopped
,10-12 09:32:16.256  3578  5860 V NativeCrypto: Read error: ssl=0x7fa21ce400: I/O error during system call, Connection timed out
,10-12 09:32:16.258  3578  5860 V NativeCrypto: SSL shutdown failed: ssl=0x7fa21ce400: I/O error during system call, Broken pipe
,10-12 09:32:16.261   928   939 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-12 09:32:16.261   928  5824 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,10-12 09:32:16.264   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-12 09:32:16.264   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-12 09:32:16.264   928  5824 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-12 09:32:16.269   535   535 E Parcel  : Reading a NULL string not supported here.
10-12 09:32:16.272   928   928 D RttService: SCAN_AVAILABLE : 1
,10-12 09:32:16.272   928  3084 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-12 09:32:16.275   928  3006 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-12 09:32:16.278  3731  3909 W QCNEJ   : |CORE| network lost: 101
10-12 09:32:16.279  3731  3909 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-12 09:32:16.286   928  2986 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-12 09:32:16.296   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 09:32:16.307   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:16.330   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:16.331   506   922 D CommandListener: Clearing all IP addresses on wlan0
10-12 09:32:16.331   928  3006 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-12 09:32:16.331   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 09:32:16.333   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-12 09:32:16.336   928  2986 D DhcpClient: doQuit
10-12 09:32:16.336   928  2986 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 09:32:16.337  5762  5762 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 09:32:16.337   928  5826 D DhcpClient: onQuitting
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:16.340  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:16.343  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:16.347  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:16.349  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:16.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:16.353  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:32:16.354  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:16.356  3890  3890 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 09:32:16.357  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-12 09:32:16.358  4980  4999 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:32:16.358  4980  4999 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:32:16.358  4980  4999 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 09:32:16.358  4980  4999 E SarControlService: no key has been found,reset the power
10-12 09:32:16.358  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:32:16.359  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:32:16.359  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-12 09:32:16.359  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:16.359  5005  5005 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 09:32:16.360  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 09:32:16.360  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:32:16.360  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:32:16.361  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:16.361  5005  5005 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:32:16.362  5762  5762 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-12 09:32:16.364  3890  3890 D SystemUpdateService: onCreate
,10-12 09:32:16.367  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000ee03000000000000ffffffff]
10-12 09:32:16.367  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:16.367  5005  5019 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-12 09:32:16.367  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:16.368  4980  4990 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 09:32:16.370  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000ef03000000000000ffffffff]
10-12 09:32:16.370  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-12 09:32:16.371  5005  5019 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-12 09:32:16.371  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:16.371  4980  4991 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:32:16.372  3890  3890 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 09:32:16.375  3890  5950 I SystemUpdateService: active receiver: enabled
,10-12 09:32:16.380  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 09:32:16.385  3890  5404 I iu.UploadsManager: num queued entries: 0
,10-12 09:32:16.386  3890  5950 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:32:16.388  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-12 09:32:16.388  5762  5762 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 09:32:16.389  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 09:32:16.391  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:32:16.395  5717  5717 D SprintDMHelper: simOperator: 
10-12 09:32:16.395  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:32:16.396   506   922 E Netd    : netlink response contains error (No such file or directory)
,10-12 09:32:16.397   928  3006 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-12 09:32:16.397   928  3006 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 09:32:16.399  5762  5762 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-12 09:32:16.402  3890  5404 I iu.UploadsManager: num updated entries: 0
,10-12 09:32:16.404  3890  5950 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-12 09:32:16.405  3890  5950 I SystemUpdateService: now status is 0 (complete)
,10-12 09:32:16.405  3890  5950 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:32:16.405  3890  5950 I SystemUpdateService: file has been verified
10-12 09:32:16.406  3890  5404 I iu.SyncManager: NEXT; no task
,10-12 09:32:16.408  4929  5953 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 09:32:16.409  3890  5950 I SystemUpdateService: OTA package size = 21989297
,10-12 09:32:16.428  3890  5950 I SystemUpdateService: showing system update notification
,10-12 09:32:16.435  3890  3890 D SystemUpdateService: onDestroy
,10-12 09:32:16.504   928  2986 D wifi    : In wifi stop Hal
,10-12 09:32:16.504   928  2986 D wifi    : halHandle = 0x7f8bd08400, mVM = 0x7fa838d140, mCls = 0x20192e
,10-12 09:32:16.504   928  5761 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 09:32:16.504   928  5761 D WifiHAL : Got a signal to exit!!!
10-12 09:32:16.504   928  5761 I WifiHAL : Exit wifi_event_loop
10-12 09:32:16.504   928  2986 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-12 09:32:16.504   928  2986 E WifiHAL : Event processing terminated
10-12 09:32:16.504   928  2986 D wifi    : In wifi cleaned up handler
10-12 09:32:16.505   928  2986 I WifiHAL : Internal cleanup completed
10-12 09:32:16.505  4053  4221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:32:16.506  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:16.508  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:16.509  4929  4929 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 09:32:16.528   928  5761 D wifi    : set interface wlan0 flags (DOWN)
,10-12 09:32:16.528   928  2986 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:16.723  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:16.735  5639  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:16.735   928   945 D Tethering: InitialState.processMessage what=4
,10-12 09:32:16.739   928  3407 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-12 09:32:16.739   928  3407 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-12 09:32:16.742  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:16.746   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 09:32:16.748   506   922 D SoftapController: Softap fwReload - Ok
,10-12 09:32:16.753   506   922 D CommandListener: Setting iface cfg
10-12 09:32:16.753   506   922 D CommandListener: Trying to bring down wlan0
,10-12 09:32:16.755   506   922 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:32:16.759   928  2986 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 09:32:17.040   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:17.248   928  3155 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-12 09:32:17.248   928  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:32:17.376   928  2986 D wifi    : set interface wlan0 flags (UP)
10-12 09:32:17.376   928  2986 I WifiHAL : Initializing wifi
,10-12 09:32:17.376   928  2986 I WifiHAL : Creating socket
,10-12 09:32:17.382   928  2986 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-12 09:32:17.382   928  2986 D wifi    : Did set static halHandle = 0x7f8bd08400
,10-12 09:32:17.383   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 09:32:17.382   928  2986 D wifi    : halHandle = 0x7f8bd08400, mVM = 0x7fa838d140, mCls = 0x15ca
10-12 09:32:17.405   928  2986 D wifi    : array field set
,10-12 09:32:17.405   928  2986 I WifiNative-HAL: interface[0] = wlan0
10-12 09:32:17.407   928  5957 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547806544896
10-12 09:32:17.407   928  5957 D wifi    : waitForHalEvents called, vm = 0x7fa838d140, obj = 0x15ca, env = 0x7f8cb1a880
,10-12 09:32:17.461  5958  5958 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 09:32:17.482  5958  5958 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:32:17.493  5958  5958 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:32:17.493  5958  5958 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 09:32:17.508   928  2986 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 09:32:17.515  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:17.522   928  2986 D WifiConfigStore: Loading config and enabling all networks 
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:17.525  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:17.527  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:17.531  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:17.533   928  2986 D WifiConfigStore: loaded 0 passpoint configs
,10-12 09:32:17.533   928  2986 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 09:32:17.534   928  2986 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 09:32:17.534  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:17.535   928  2986 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-12 09:32:17.535  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:17.536   928  2986 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-12 09:32:17.536   928  2986 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 09:32:17.536   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 09:32:17.536   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 09:32:17.541   928  2986 D WifiNative-HAL: Setting external_sim to 1
,10-12 09:32:17.541  4929  4929 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:32:17.541   928  2986 D wifi    : setting dfs flag to true, 0x7f8da71120
10-12 09:32:17.542   928  2986 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 09:32:17.542   928  2986 D wifi    : setting scan oui 0x7f8da71120
,10-12 09:32:17.542   928  2986 D WifiHAL : Sending mac address OUI
,10-12 09:32:17.546   928  2986 E native  : do suspend false
,10-12 09:32:17.552   928  2986 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 09:32:17.553   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 09:32:17.553   928   928 D RttService: SCAN_AVAILABLE : 3
,10-12 09:32:17.553   928  3084 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-12 09:32:17.554   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:17.558   928  2977 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-12 09:32:17.558   928  2977 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 09:32:17.566   928  2977 D WifiNative-HAL: p2pGetDeviceAddress
10-12 09:32:17.566   928  2977 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 09:32:17.571   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=232749 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:17.753  5639  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:32:17.754  5639  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:17.756  5639  5685 D BluetoothAdapter: enable(): BT is already enabled..!
,10-12 09:32:17.756   928   939 D WifiService: setWifiEnabled: true pid=5639, uid=10077
10-12 09:32:17.757   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-12 09:32:17.757  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:32:17.758  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:32:17.758  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:32:17.758  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:32:17.758  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:32:17.758  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9cac51 removed from the list
10-12 09:32:17.758  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:32:17.759  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc3cb6 removed from the list
10-12 09:32:17.759  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:32:17.759  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:32:17.759  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:32:17.762  5639  5685 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,10-12 09:32:17.764  5639  5685 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,10-12 09:32:17.766  5639  5685 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,10-12 09:32:17.768  5639  5685 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,10-12 09:32:17.771  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-12 09:32:17.772  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-12 09:32:17.774  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,10-12 09:32:17.774  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-12 09:32:17.774  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,10-12 09:32:17.777  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,10-12 09:32:17.777  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@354d491 Bundle[{}]
10-12 09:32:17.777  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-12 09:32:17.778  5639  5685 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 09:32:17.778  5639  5685 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-12 09:32:17.779  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,10-12 09:32:17.779  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-12 09:32:17.780  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,10-12 09:32:17.780  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-12 09:32:17.781  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-12 09:32:17.781  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-12 09:32:17.782  5639  5685 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,10-12 09:32:17.782  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-12 09:32:17.784  5639  5685 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-12 09:32:17.786  5639  5685 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,10-12 09:32:17.787  5639  5685 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
10-12 09:32:17.788  5639  5685 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
10-12 09:32:17.788  5639  5685 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
10-12 09:32:17.789  5639  5685 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-12 09:32:17.790  5639  5685 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,10-12 09:32:17.791  5639  5685 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,10-12 09:32:17.792  5639  5685 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,10-12 09:32:17.794  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-12 09:32:17.795  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,10-12 09:32:17.795  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-12 09:32:17.795  5639  5685 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,10-12 09:32:17.796  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,10-12 09:32:17.796  5639  5685 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-12 09:32:17.796  5639  5685 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
10-12 09:32:17.797  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
10-12 09:32:17.798  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
10-12 09:32:17.798  5639  5685 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
10-12 09:32:17.798  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:32:17.799  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ebc8d added. We now have 3 listener(s)
,10-12 09:32:17.800  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 09:32:17.800  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:32:17.800  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:32:17.800  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:32:17.801  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@676e42 added. We now have 3 listener(s)
10-12 09:32:17.801  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:32:17.801  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 09:32:17.804  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:32:17.807  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:32:17.809  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:32:17.809  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 09:32:17.811  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:32:17.812  5639  5685 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,10-12 09:32:17.812  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:32:17.813  5639  5685 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-12 09:32:17.813  5639  5685 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-12 09:32:17.813  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
10-12 09:32:17.814  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:17.814  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 09:32:17.814  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:32:17.814  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:17.815  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-12 09:32:17.815  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 09:32:17.815  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 09:32:17.815  5639  5960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:32:17.815  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 09:32:17.816  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 09:32:17.816  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 09:32:17.816  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 09:32:17.816  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:17.816  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:32:17.816  5639  5960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:32:17.817  5900  5900 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33319]" dev="sockfs" ino=33319 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:17.817  5900  5900 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33319]" dev="sockfs" ino=33319 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:17.819  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:32:17.819  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 09:32:17.820  5639  5960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-12 09:32:17.824  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 09:32:17.824  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 09:32:17.824  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:32:17.827  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-12 09:32:17.827  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:32:17.827  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
10-12 09:32:17.827  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 09:32:17.827  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-12 09:32:17.827  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-12 09:32:17.827  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:17.828  5639  5685 D BluetoothAdapter: STATE_ON
,10-12 09:32:17.832  5890  5901 D BtGatt.GattService: registerClient() - UUID=c073dc29-6c29-4cd4-90a7-97330d450b92
,10-12 09:32:17.832  5890  5906 D BtGatt.GattService: onClientRegistered() - UUID=c073dc29-6c29-4cd4-90a7-97330d450b92, clientIf=5
,10-12 09:32:17.833  5639  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 09:32:17.835  5890  5908 D BtGatt.AdvertiseManager: message : 0
,10-12 09:32:17.838  5890  5908 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 09:32:17.848  5890  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 09:32:17.854  5890  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 09:32:17.854  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-12 09:32:17.854  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-12 09:32:17.855  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-12 09:32:17.855  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-12 09:32:17.855  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:32:17.856  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 09:32:17.857  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:17.857  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-12 09:32:17.857  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-12 09:32:17.857  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 09:32:17.857  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-12 09:32:17.857  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:17.857  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 09:32:17.857  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:32:17.857  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-12 09:32:17.857  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-12 09:32:17.860  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 09:32:17.860  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 09:32:18.041   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 09:32:18.361  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-12 09:32:18.361  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 09:32:18.361  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:32:20.715  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:20.721  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:20.726  5958  5958 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:32:20.802   928  2986 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-12 09:32:20.803   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-12 09:32:20.803   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:20.816   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 09:32:20.851   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 09:32:20.853  5958  5958 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 09:32:21.274  5958  5958 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 09:32:21.304  5958  5958 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 09:32:21.304  5958  5958 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 09:32:21.313   928  2986 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:32:21.313   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 09:32:21.313   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 09:32:21.332   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:32:21.343   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:21.350   928  2986 D WifiStateMachine: Start Dhcp Watchdog 3
,10-12 09:32:21.355   928  5967 D DhcpClient: Receive thread started
,10-12 09:32:21.359  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-12 09:32:21.359  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-12 09:32:21.359  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 09:32:21.359  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 09:32:21.359  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-12 09:32:21.360  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:32:21.360  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:32:21.360  5639  5960 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-12 09:32:21.360  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 09:32:21.360  5639  5960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:32:21.360  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-12 09:32:21.360  5639  5960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 09:32:21.360  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:32:21.360  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-12 09:32:21.360  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:32:21.360  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:32:21.360   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-12 09:32:21.361   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-12 09:32:21.361   928  3006 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
10-12 09:32:21.361  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 09:32:21.362  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:21.362  5639  5685 D BluetoothLeScanner: could not find callback wrapper
10-12 09:32:21.362  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:32:21.362  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 09:32:21.363  5890  5908 D BtGatt.AdvertiseManager: message : 1
10-12 09:32:21.364  5890  5908 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-12 09:32:21.376  5890  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-12 09:32:21.376  5890  5906 D BtGatt.GattService: Client app is not null!
,10-12 09:32:21.378  5890  5901 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:32:21.378  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 09:32:21.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-12 09:32:21.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:21.379  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-12 09:32:21.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:21.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:32:21.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 09:32:21.379  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-12 09:32:21.379  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-12 09:32:21.381  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:21.381  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:32:21.381  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:32:21.382  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:32:21.384  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:32:21.385  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:32:21.385  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 09:32:21.385  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:32:21.385  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:21.386  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:21.386  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:21.387  5639  5685 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
10-12 09:32:21.387  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:32:21.388  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-12 09:32:21.388  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 09:32:21.388  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 09:32:21.388  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:32:21.388  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 09:32:21.394  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 09:32:21.394  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 09:32:21.399  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:32:21.400  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 09:32:21.400  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:32:21.405  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 09:32:21.405  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:32:21.405  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-12 09:32:21.406  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-12 09:32:21.406  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 09:32:21.407  5639  5685 D BluetoothAdapter: STATE_ON
,10-12 09:32:21.411  5890  5900 D BtGatt.GattService: registerClient() - UUID=e4af6c39-c7cd-4a50-aee3-fda15a56e955
10-12 09:32:21.411  5890  5906 D BtGatt.GattService: onClientRegistered() - UUID=e4af6c39-c7cd-4a50-aee3-fda15a56e955, clientIf=5
,10-12 09:32:21.412  5639  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 09:32:21.413  5890  5901 D BtGatt.GattService: start scan with filters
,10-12 09:32:21.416  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 09:32:21.416  5890  5909 D BtGatt.ScanManager: handling starting scan
,10-12 09:32:21.417  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:32:21.417  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:21.417  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-12 09:32:21.417  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:32:21.417  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 09:32:21.417  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 09:32:21.418  5890  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9aa3b2a
,10-12 09:32:21.420  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:32:21.420  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:32:21.420  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 09:32:21.421  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 09:32:21.425  5890  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-12 09:32:21.425  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:21.426  5890  5909 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 09:32:21.432  5890  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 09:32:21.432  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:21.433  5890  5909 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:32:21.433  5890  5909 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 09:32:21.437   928  3006 D ConnectivityService: handlePromptUnvalidated 101
,10-12 09:32:21.441   928  2986 E native  : do suspend false
,10-12 09:32:21.444  5890  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-12 09:32:21.444  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:32:21.450  5890  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-12 09:32:21.451  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:21.451   928  5966 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 09:32:21.468   928  5967 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,10-12 09:32:21.468   928  5966 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,10-12 09:32:21.469   928  5966 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 09:32:21.538   928  5967 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
10-12 09:32:21.539   928  5966 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-12 09:32:21.542   506   922 D CommandListener: Setting iface cfg
,10-12 09:32:21.548   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 09:32:21.553   928  5966 D DhcpClient: Scheduling renewal in 86399s
,10-12 09:32:21.562   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 09:32:21.563   928  2986 D WifiConfigStore: No blacklist allowed without epno enabled
,10-12 09:32:21.564   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-12 09:32:21.566   928  3006 D ConnectivityService: Adding iface wlan0 to network 102
10-12 09:32:21.572   928  2986 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 09:32:21.624   928  3006 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-12 09:32:21.624   928  3006 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
10-12 09:32:21.629   928  3006 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-12 09:32:21.631   928  3006 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-12 09:32:21.633   928  3006 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-12 09:32:21.640   928  3006 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:32:21.644   928  3006 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-12 09:32:21.644   928  3006 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-12 09:32:21.644   928  3006 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-12 09:32:21.644   928  2986 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-12 09:32:21.644   928  3006 D ConnectivityService:    accepting network in place of null
10-12 09:32:21.645   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:32:21.645   928  3006 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -68]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:32:21.668   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:21.672   928  5965 D NetlinkSocketObserver: NeighborEvent{elapsedMs=236849, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 09:32:21.690   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:32:21.693   928  3006 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-12 09:32:21.693  3731  3909 W QCNEJ   : |CORE| network available: 102
10-12 09:32:21.693   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:32:21.695  3731  3909 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-12 09:32:21.695   928  3006 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-12 09:32:21.695   928   945 D Tethering: MasterInitialState.processMessage what=3
10-12 09:32:21.699  3731  3909 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 09:32:21.699  3731  3909 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:21.703  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:32:21.705  4980  4999 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-12 09:32:21.705  4980  4999 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:32:21.705  4980  4999 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 09:32:21.705  4980  4999 E SarControlService: no key has been found,reset the power
10-12 09:32:21.705  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:21.706  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:32:21.706  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:32:21.706  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 09:32:21.709  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:21.709  5005  5005 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-12 09:32:21.712  4980  5016 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:21.712  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:21.713  3890  3890 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 09:32:21.714  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:21.717  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000f003000000000000ffffffff]
10-12 09:32:21.717  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:21.717  5005  5019 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-12 09:32:21.717  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:21.718  4980  4990 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-12 09:32:21.718  3890  3890 D SystemUpdateService: onCreate
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:32:21.719  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:32:21.712  4980  5016 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:32:21.719  4980  5016 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:32:21.720  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:32:21.720  5005  5005 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:32:21.720  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:32:21.722  5005  5019 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@de2ee5d HexData = [00000000f103000000000000ffffffff]
,10-12 09:32:21.722  5005  5019 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:32:21.722  5005  5019 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-12 09:32:21.723  5005  5005 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:32:21.723  4980  4991 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:32:21.725  3890  3890 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 09:32:21.735  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 09:32:21.741  3890  5404 I iu.UploadsManager: num queued entries: 0
,10-12 09:32:21.741  3890  5404 I iu.UploadsManager: num updated entries: 0
10-12 09:32:21.742  3890  5978 I SystemUpdateService: active receiver: enabled
,10-12 09:32:21.745  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 09:32:21.746  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-12 09:32:21.748  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:32:21.751  5717  5717 D SprintDMHelper: simOperator: 
10-12 09:32:21.751  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:32:21.771  3890  5978 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:32:21.774  3890  5404 I iu.SyncManager: NEXT; no task
,10-12 09:32:21.787  3890  5978 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-12 09:32:21.787  3890  5978 I SystemUpdateService: now status is 0 (complete)
10-12 09:32:21.787  3890  5978 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:32:21.787  3890  5978 I SystemUpdateService: file has been verified
10-12 09:32:21.787  3890  5978 I SystemUpdateService: OTA package size = 21989297
,10-12 09:32:21.791   928  5964 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-12 09:32:21.792  3890  5978 I SystemUpdateService: showing system update notification
,10-12 09:32:21.802  3890  3890 D SystemUpdateService: onDestroy
,10-12 09:32:21.899   928  5964 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 13:32:21 GMT], X-Android-Received-Millis=[1476279141897], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476279141816]}
,10-12 09:32:21.899   928  3006 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 09:32:21.900   928  3006 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-12 09:32:21.900   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:32:21.902   928  3006 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 09:32:21.919  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 09:32:21.920  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:32:21.920  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:32:21.953  5890  5890 D BtGatt.ScanManager: awakened up at time 237131
,10-12 09:32:21.954  5890  5909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:32:21.963  5890  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,10-12 09:32:21.963  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:21.964  5890  5906 D BtGatt.GattService: current time is 237141746585
10-12 09:32:21.964  5890  5906 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -13, -123, -114, 102, -38, 97, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0]
10-12 09:32:21.965  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
10-12 09:32:21.966  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
,10-12 09:32:21.967  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
10-12 09:32:21.968  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-12 09:32:21.968  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-89, mTimestampNanos=236692061376}
10-12 09:32:21.968  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:21.968  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=61:DA:66:8E:85:F3, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=237092061376}
,10-12 09:32:21.969  5639  5639 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-12 09:32:21.969  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6]
,10-12 09:32:21.969  5639  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
,10-12 09:32:21.970  5639  5639 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
,10-12 09:32:22.138  4929  5982 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
,10-12 09:32:22.467  5890  5890 D BtGatt.ScanManager: awakened up at time 237645
,10-12 09:32:22.469  5890  5909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:32:22.504  5890  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-12 09:32:22.505  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:22.505  5890  5906 D BtGatt.GattService: current time is 237682866326
10-12 09:32:22.505  5890  5906 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -13, -123, -114, 102, -38, 97, 1, -128, -54, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 53, -65, 85, -45, -33, 107, 1, -128, -47, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 53, -65, 85, -45, -33, 107, 1, -128, -47, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0]
,10-12 09:32:22.506  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-12 09:32:22.506  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
10-12 09:32:22.507  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-12 09:32:22.507  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
10-12 09:32:22.507  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,10-12 09:32:22.508  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
10-12 09:32:22.508  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-12 09:32:22.509  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
10-12 09:32:22.509  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6B:DF:D3:55:BF:35, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-47, mTimestampNanos=237533579555}
,10-12 09:32:22.510  5639  5639 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-12 09:32:22.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
10-12 09:32:22.511  5639  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
10-12 09:32:22.511  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.511  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=237183579555}
,10-12 09:32:22.511  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.512  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=237483579555}
10-12 09:32:22.512  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.512  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=61:DA:66:8E:85:F3, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=237683579555}
10-12 09:32:22.513  5639  5639 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null]
,10-12 09:32:22.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6]
10-12 09:32:22.514  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.514  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=237233579555}
10-12 09:32:22.514  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.514  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=237533579555}
,10-12 09:32:22.514  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-12 09:32:22.515  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=6B:DF:D3:55:BF:35, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-47, mTimestampNanos=237633579555}
10-12 09:32:22.515  5639  5639 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-12 09:32:22.515  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
10-12 09:32:22.516  5639  5639 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
10-12 09:32:22.516  5639  5639 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> 44:78:3E:94:4A:3E 6], device name: '', device address: ''
,10-12 09:32:22.517  5639  5639 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 6], device name: '', device address: ''
,10-12 09:32:22.694   928  3006 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,10-12 09:32:23.042   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:24.043   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:24.376   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:32:24.428  5639  5685 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,10-12 09:32:24.428  5639  5685 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,10-12 09:32:24.429  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 09:32:24.429  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 09:32:24.431  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:24.433  5890  5927 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:32:24.434  5890  5932 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:32:24.435  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:32:24.435  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:24.436  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 09:32:24.436  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 09:32:24.436  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:32:24.436  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:32:24.436  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 09:32:24.436  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 09:32:24.438  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:24.444  5890  5932 D BtGatt.GattService: registerClient() - UUID=43f7333d-7131-44d7-8225-82255b9381c8
10-12 09:32:24.445  5890  5906 D BtGatt.GattService: onClientRegistered() - UUID=43f7333d-7131-44d7-8225-82255b9381c8, clientIf=5
10-12 09:32:24.447  5890  5890 D BtGatt.ScanManager: awakened up at time 239624
10-12 09:32:24.447  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 09:32:24.448  5890  5900 D BtGatt.GattService: start scan with filters
,10-12 09:32:24.449   928  2986 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 17 -> obsolete
10-12 09:32:24.450  5890  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:32:24.450  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:24.451  5890  5909 D BtGatt.ScanManager: stopping BLe Batch
10-12 09:32:24.452  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-12 09:32:24.452  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:32:24.452  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:24.452  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:32:24.452  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:32:24.452  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:24.452  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,10-12 09:32:24.452  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:32:24.452  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:32:24.454  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 09:32:24.455  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-12 09:32:24.455  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 09:32:24.456  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 09:32:24.456  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 09:32:24.456  5639  5990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:32:24.456  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-12 09:32:24.456  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 09:32:24.456  5639  5990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:32:24.457  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:32:24.458  5890  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 09:32:24.458  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:24.459  5890  5909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:32:24.462  5639  5990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-12 09:32:24.457  5932  5932 W Binder_6: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31713]" dev="sockfs" ino=31713 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:24.457  5932  5932 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31713]" dev="sockfs" ino=31713 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 09:32:24.469  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,10-12 09:32:24.469  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 09:32:24.469  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:32:24.469  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
10-12 09:32:24.470  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:24.470  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-12 09:32:24.470  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-12 09:32:24.470  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 09:32:24.470  5639  5685 D BluetoothAdapter: STATE_ON
,10-12 09:32:24.470  5890  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
10-12 09:32:24.470  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:24.471  5890  5906 D BtGatt.GattService: current time is 239648628970
10-12 09:32:24.471  5890  5906 D BtGatt.GattService: Batch record : [53, -65, 85, -45, -33, 107, 1, -128, -44, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, -13, -123, -114, 102, -38, 97, 1, -128, -54, 31, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0]
10-12 09:32:24.471  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-12 09:32:24.471  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-12 09:32:24.471  5890  5909 D BtGatt.ScanManager: handling starting scan
,10-12 09:32:24.474  5890  5927 D BtGatt.GattService: registerClient() - UUID=ae6e663e-61b1-4bc9-86f6-edbbb3ec0b61
10-12 09:32:24.474  5890  5906 D BtGatt.GattService: onClientRegistered() - UUID=ae6e663e-61b1-4bc9-86f6-edbbb3ec0b61, clientIf=6
,10-12 09:32:24.475  5639  5649 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,10-12 09:32:24.476  5890  5908 D BtGatt.AdvertiseManager: message : 0
,10-12 09:32:24.478  5890  5906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-12 09:32:24.478  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:32:24.480  5890  5909 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 09:32:24.480  5890  5908 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 09:32:24.485  5890  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 09:32:24.485  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:24.485  5890  5909 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:32:24.485  5890  5909 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 09:32:24.493  5890  5906 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-12 09:32:24.501  5890  5906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-12 09:32:24.501  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:32:24.505  5890  5906 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,10-12 09:32:24.506  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-12 09:32:24.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-12 09:32:24.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-12 09:32:24.506  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-12 09:32:24.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-12 09:32:24.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-12 09:32:24.506  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser, adv = true, disc = true
10-12 09:32:24.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:32:24.507  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:32:24.509  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:24.509  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-12 09:32:24.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-12 09:32:24.510  5890  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-12 09:32:24.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 09:32:24.510  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-12 09:32:24.510  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:24.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:24.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-12 09:32:24.510  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:32:24.511  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
10-12 09:32:24.511  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,10-12 09:32:24.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-12 09:32:24.513  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-12 09:32:24.848   928  2986 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 17 -> obsolete
,10-12 09:32:25.014  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-12 09:32:25.014  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 09:32:25.014  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:32:25.044   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:26.045   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:27.046   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:27.401   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:32:27.515  5639  5685 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-12 09:32:27.515  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:32:27.516  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 09:32:27.516  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 09:32:27.516  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-12 09:32:27.516  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:32:27.516  5639  5990 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 09:32:27.516  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:32:27.516  5639  5990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:32:27.517  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 09:32:27.517  5639  5990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-12 09:32:27.517  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:32:27.517  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ebc8d removed from the list
10-12 09:32:27.517  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:32:27.517  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-12 09:32:27.517  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-12 09:32:27.518  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 09:32:27.518  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:32:27.518  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:32:27.518  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:32:27.518  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:32:27.518  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 09:32:27.521  5639  5685 D BluetoothAdapter: STATE_ON
10-12 09:32:27.523  5890  5927 D BtGatt.GattService: stopScan() - queue size =1
,10-12 09:32:27.528  5890  5932 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:32:27.529  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:32:27.529  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:27.529  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 09:32:27.529  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:27.530  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 09:32:27.530  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-12 09:32:27.530  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
10-12 09:32:27.530  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
10-12 09:32:27.536  5890  5890 D BtGatt.ScanManager: awakened up at time 242714
,10-12 09:32:27.540  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 09:32:27.541  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 09:32:27.543  5890  5908 D BtGatt.AdvertiseManager: message : 1
,10-12 09:32:27.543  5890  5906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:32:27.544  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:27.544  5890  5908 D BtGatt.AdvertiseManager: stop advertise for client 6
10-12 09:32:27.545  5890  5909 D BtGatt.ScanManager: stopping BLe Batch
,10-12 09:32:27.554  5890  5906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-12 09:32:27.554  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:27.554  5890  5909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:32:27.561  5890  5906 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,10-12 09:32:27.561  5890  5906 D BtGatt.GattService: Client app is not null!
10-12 09:32:27.562  5890  5919 D BtGatt.GattService: unregisterClient() - clientIf=6
10-12 09:32:27.563  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:32:27.563  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-12 09:32:27.563  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 09:32:27.563  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,10-12 09:32:27.563  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:32:27.563  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:32:27.563  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 09:32:27.564  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-12 09:32:27.564  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-12 09:32:27.566  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:27.566  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-12 09:32:27.566  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:32:27.567  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:32:27.567  5639  5685 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
10-12 09:32:27.569  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:27.569  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@676e42 removed from the list
10-12 09:32:27.569  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:32:27.569  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:32:27.569  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:32:27.569  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 09:32:27.569  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:32:27.571  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,10-12 09:32:27.571  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 09:32:27.572  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 09:32:27.572  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 09:32:27.572  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:32:27.572  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-12 09:32:27.572  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 09:32:27.573  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
10-12 09:32:27.574  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,10-12 09:32:27.577  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,10-12 09:32:27.578  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-12 09:32:27.579  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-12 09:32:27.580  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
10-12 09:32:27.580  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
10-12 09:32:27.581  5639  5685 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-12 09:32:27.597  5890  5906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,10-12 09:32:27.597  5890  5906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:32:27.597  5890  5906 D BtGatt.GattService: current time is 242775404548
10-12 09:32:27.598  5890  5906 D BtGatt.GattService: Batch record : [53, -65, 85, -45, -33, 107, 1, -128, -46, 46, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, -13, -123, -114, 102, -38, 97, 1, -128, -54, 57, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, -46, -4, -117, 6, 105, -37, 1, -128, -79, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -90, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -84, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
10-12 09:32:27.598  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
,10-12 09:32:27.598  5890  5906 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-12 09:32:27.598  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-12 09:32:27.599  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-12 09:32:27.599  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-12 09:32:27.599  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-12 09:32:27.599  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-12 09:32:27.600  5890  5906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,10-12 09:32:28.046   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 09:32:28.070  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:32:29.586  5639  5685 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-12 09:32:29.647   928  3006 D ConnectivityService: handlePromptUnvalidated 102
,10-12 09:32:29.750  5639  5992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 09:32:29.750  5639  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:32:30.416   928  3006 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:32:30.558  5639  5992 W !!      : call onHalfStreamCopied
,10-12 09:32:30.558  5639  5992 I testCopyDataAndClose: closing input stream
,10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 09:32:31.334  5639  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 09:32:32.568   928  2986 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,10-12 09:32:33.399   928  2986 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 17 -> obsolete
,10-12 09:32:35.223  5639  5685 I StreamCopyingThreadTest: Starting test: testRun
,10-12 09:32:35.230  5639  5993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:35.230  5639  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:32:38.048   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:39.049   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:40.051   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:40.236  5639  5994 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-12 09:32:40.239  5639  5685 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-12 09:32:40.389  5639  5995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 09:32:40.389  5639  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:32:41.053   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:42.039  5639  5995 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 09:32:42.039  5639  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 09:32:42.040  5639  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
10-12 09:32:42.055   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:32:43.056   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 09:32:45.768  5639  5685 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 09:32:45.771  5639  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-12 09:32:45.772  5639  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 09:32:45.772  5639  5996 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 09:32:45.772  5639  5996 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-12 09:32:45.772  5639  5996 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:45.772  5639  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-12 09:32:45.774  5639  5685 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-12 09:32:45.774  5639  5685 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 09:32:45.775  5639  5685 I StreamCopyingThreadTest: Starting test: testRunWithException
10-12 09:32:45.777  5639  5997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:45.777  5639  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:32:45.778  5639  5997 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
10-12 09:32:45.778  5639  5997 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:45.778  5639  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-12 09:32:45.778  5639  5997 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-12 09:32:45.778  5639  5997 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:32:45.778  5639  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-12 09:32:45.780  5639  5685 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
10-12 09:32:45.780  5639  5685 E com.test.thalitest.ThaliTestRunner: 
10-12 09:32:45.780  5639  5685 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-12 09:32:45.780  5639  5685 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-12 09:32:45.781  5639,  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-12 09:32:45.781  5639  5685 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
,10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
,10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20),
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57),
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jx,core.evalEngine(Native Method)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:45.782  5639  5685 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-12 09:32:45.785  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG UnitTest_app: 'Running unit tests'
10-12 09:32:45.785  5639  5685 I jxcore-log: 
10-12 09:32:45.785  5639  5685 I jxcore-log: *Native tests were executed*
10-12 09:32:45.785  5639  5685 I jxcore-log: 
10-12 09:32:45.785  5639  5685 I jxcore-log: Total number of executed tests:  82
10-12 09:32:45.785  5639  5685 I jxcore-log: 
10-12 09:32:45.785  5639  5685 I jxcore-log: Number of passed tests:  80
10-12 09:32:45.785  5639  5685 I jxcore-log: 
10-12 09:32:45.785  5639  5685 I jxcore-log: Number of failed tests:  2
10-12 09:32:45.785  5639  5685 I jxcore-log: 
10-12 09:32:45.786  5639  5685 I jxcore-log: Number of ignored tests:  0
10-12 09:32:45.786  5639  5685 I jxcore-log: 
10-12 09:32:45.786  5639  5685 I jxcore-log: Total duration:  44602
10-12 09:32:45.786  5639  5685 I jxcore-log: 
10-12 09:32:45.786  5639  5685 I jxcore-log: Failed to execute UT.
10-12 09:32:45.786  5639  5685 I jxcore-log: 
10-12 09:32:45.787  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-12 09:32:45.787  5639  5685 I jxcore-log: 
10-12 09:32:45.788  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-12 09:32:45.788  5639  5685 I jxcore-log: 
10-12 09:32:45.791  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.791  5639  5685 I jxcore-log: 
10-12 09:32:45.792  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.792  5639  5685 I jxcore-log: 
10-12 09:32:45.792  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.792  5639  5685 I jxcore-log: 
10-12 09:32:45.793  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-12 09:32:45.793  5639  5685 I jxcore-log: 
10-12 09:32:45.794  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-12 09:32:45.794  5639  5685 I jxcore-log: 
,10-12 09:32:45.794  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-12 09:32:45.794  5639  5685 I jxcore-log: 
10-12 09:32:45.794  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:32:45.794  5639  5685 I jxcore-log: 
10-12 09:32:45.795  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.795  5639  5685 I jxcore-log: 
,10-12 09:32:45.795  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.795  5639  5685 I jxcore-log: 
10-12 09:32:45.795  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:32:45.795  5639  5685 I jxcore-log: 
10-12 09:32:45.795  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:32:45.795  5639  5685 I jxcore-log: 
10-12 09:32:45.796  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:32:45.796  5639  5685 I jxcore-log: 
,10-12 09:32:45.796  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:32:45.796  5639  5685 I jxcore-log: 
10-12 09:32:45.796  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.796  5639  5685 I jxcore-log: 
10-12 09:32:45.796  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.796  5639  5685 I jxcore-log: 
10-12 09:32:45.797  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.797  5639  5685 I jxcore-log: 
10-12 09:32:45.797  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.797  5639  5685 I jxcore-log: 
10-12 09:32:45.797  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.797  5639  5685 I jxcore-log: 
,10-12 09:32:45.798  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.798  5639  5685 I jxcore-log: 
10-12 09:32:45.798  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.798  5639  5685 I jxcore-log: 
10-12 09:32:45.798  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.798  5639  5685 I jxcore-log: 
10-12 09:32:45.798  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.798  5639  5685 I jxcore-log: 
10-12 09:32:45.798  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.798  5639  5685 I jxcore-log: 
10-12 09:32:45.799  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.799  5639  5685 I jxcore-log: 
10-12 09:32:45.799  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.799  5639  5685 I jxcore-log: 
10-12 09:32:45.799  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}',
10-12 09:32:45.799  5639  5685 I jxcore-log: 
10-12 09:32:45.801  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.801  5639  5685 I jxcore-log: 
10-12 09:32:45.801  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.801  5639  5685 I jxcore-log: 
10-12 09:32:45.801  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.801  5639  5685 I jxcore-log: 
10-12 09:32:45.801  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.801  5639  5685 I jxcore-log: 
10-12 09:32:45.802  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.802  5639  5685 I jxcore-log: 
,10-12 09:32:45.802  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.802  5639  5685 I jxcore-log: 
10-12 09:32:45.802  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:32:45.802  5639  5685 I jxcore-log: 
10-12 09:32:45.802  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:32:45.802  5639  5685 I jxcore-log: 
10-12 09:32:45.803  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:32:45.803  5639  5685 I jxcore-log: 
10-12 09:32:45.803  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.803  5639  5685 I jxcore-log: 
10-12 09:32:45.803  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.803  5639  5685 I jxcore-log: 
,10-12 09:32:45.803  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.803  5639  5685 I jxcore-log: 
10-12 09:32:45.804  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:32:45.804  5639  5685 I jxcore-log: 
10-12 09:32:45.804  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-12 09:32:45.804  5639  5685 I jxcore-log: 
10-12 09:32:45.804  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.804  5639  5685 I jxcore-log: 
10-12 09:32:45.804  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:32:45.804  5639  5685 I jxcore-log: 
10-12 09:32:45.804  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
,10-12 09:32:45.804  5639  5685 I jxcore-log: 
10-12 09:32:45.805  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 09:32:45.805  5639  5685 I jxcore-log: 
10-12 09:32:45.805  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-12 09:32:45.805  5639  5685 I jxcore-log: 
10-12 09:32:45.806  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-12 09:32:45.806  5639  5685 I jxcore-log: 
10-12 09:32:45.806  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-12 09:32:45.806  5639  5685 I jxcore-log: 
10-12 09:32:45.806  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-12 09:32:45.806  5639  5685 I jxcore-log: 
10-12 09:32:45.806  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}',
10-12 09:32:45.806  5639  5685 I jxcore-log: 
10-12 09:32:45.806  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:32:45.806  5639  5685 I jxcore-log: 
10-12 09:32:45.811  5639  5639 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-12 09:32:45.811  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-12 09:32:45.811  5639  5685 I jxcore-log: 
10-12 09:32:45.812  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - WARN testUtils: 'myNameCallback not set!'
10-12 09:32:45.812  5639  5685 I jxcore-log: 
10-12 09:32:45.813  5639  5685 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-12 09:32:45.813  5639  5685 I jxcore-log: 2016-10-12 13:32:45 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-12 09:32:45.813  5639  5685 I jxcore-log: 
,10-12 09:32:47.835  5639  5685 I jxcore-log: 2016-10-12 13:32:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-12 09:32:47.835  5639  5685 I jxcore-log: 
,10-12 09:32:48.176  5639  5685 I jxcore-log: 2016-10-12 13:32:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-12 09:32:48.176  5639  5685 I jxcore-log: 
,10-12 09:32:48.189  5639  5685 I jxcore-log: 2016-10-12 13:32:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-12 09:32:48.189  5639  5685 I jxcore-log: 
,10-12 09:32:49.291  5639  5685 I jxcore-log: 2016-10-12 13:32:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-12 09:32:49.291  5639  5685 I jxcore-log: 
,10-12 09:32:49.437  5639  5685 I jxcore-log: 2016-10-12 13:32:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-12 09:32:49.437  5639  5685 I jxcore-log: 
,10-12 09:32:49.442  5639  5685 I jxcore-log: 2016-10-12 13:32:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-12 09:32:49.442  5639  5685 I jxcore-log: 
,10-12 09:32:49.447  5639  5685 I jxcore-log: 2016-10-12 13:32:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-12 09:32:49.447  5639  5685 I jxcore-log: 
,10-12 09:32:50.002  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-12 09:32:50.002  5639  5685 I jxcore-log: 
,10-12 09:32:50.053  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-12 09:32:50.053  5639  5685 I jxcore-log: 
,10-12 09:32:50.066  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-12 09:32:50.066  5639  5685 I jxcore-log: 
,10-12 09:32:50.070  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-12 09:32:50.070  5639  5685 I jxcore-log: 
,10-12 09:32:50.347  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-12 09:32:50.347  5639  5685 I jxcore-log: 
,10-12 09:32:50.470  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-12 09:32:50.470  5639  5685 I jxcore-log: 
,10-12 09:32:50.697  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-12 09:32:50.697  5639  5685 I jxcore-log: 
,10-12 09:32:50.706  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-12 09:32:50.706  5639  5685 I jxcore-log: 
,10-12 09:32:50.710  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-12 09:32:50.710  5639  5685 I jxcore-log: 
,10-12 09:32:50.848  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-12 09:32:50.848  5639  5685 I jxcore-log: 
,10-12 09:32:50.856  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-12 09:32:50.856  5639  5685 I jxcore-log: 
,10-12 09:32:50.883  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-12 09:32:50.883  5639  5685 I jxcore-log: 
,10-12 09:32:50.917  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-12 09:32:50.917  5639  5685 I jxcore-log: 
,10-12 09:32:50.924  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-12 09:32:50.924  5639  5685 I jxcore-log: 
,10-12 09:32:50.929  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-12 09:32:50.929  5639  5685 I jxcore-log: 
,10-12 09:32:50.943  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-12 09:32:50.943  5639  5685 I jxcore-log: 
,10-12 09:32:50.947  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-12 09:32:50.947  5639  5685 I jxcore-log: 
,10-12 09:32:50.952  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-12 09:32:50.952  5639  5685 I jxcore-log: 
,10-12 09:32:50.957  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-12 09:32:50.957  5639  5685 I jxcore-log: 
,10-12 09:32:50.969  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-12 09:32:50.969  5639  5685 I jxcore-log: 
,10-12 09:32:50.989  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-12 09:32:50.989  5639  5685 I jxcore-log: 
,10-12 09:32:50.999  5639  5685 I jxcore-log: 2016-10-12 13:32:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-12 09:32:50.999  5639  5685 I jxcore-log: 
,10-12 09:32:51.010  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-12 09:32:51.010  5639  5685 I jxcore-log: 
,10-12 09:32:51.019  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-12 09:32:51.019  5639  5685 I jxcore-log: 
,10-12 09:32:51.031  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-12 09:32:51.031  5639  5685 I jxcore-log: 
,10-12 09:32:51.042  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-12 09:32:51.042  5639  5685 I jxcore-log: 
,10-12 09:32:51.047  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-12 09:32:51.047  5639  5685 I jxcore-log: 
,10-12 09:32:51.067  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-12 09:32:51.067  5639  5685 I jxcore-log: 
,10-12 09:32:51.072  5639  5685 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-12 09:32:51.073  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - INFO testUtils: 'BLE multiple advertisement supported'
10-12 09:32:51.073  5639  5685 I jxcore-log: 
,10-12 09:32:51.172  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - DEBUG CoordinatedClient: 'connected to the test server'
10-12 09:32:51.172  5639  5685 I jxcore-log: 
,10-12 09:32:51.251  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-12 09:32:51.251  5639  5685 I jxcore-log: 
,10-12 09:32:51.252  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - DEBUG CoordinatedClient: 'test client failed'
10-12 09:32:51.252  5639  5685 I jxcore-log: 
10-12 09:32:51.253  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-12 09:32:51.253  5639  5685 I jxcore-log: 
,10-12 09:32:51.254  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-12 09:32:51.254  5639  5685 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-12 09:32:51.254  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-12 09:32:51.254  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-12 09:32:51.254  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-12 09:32:51.254  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-12 09:32:51.254  5639  5685 I jxcore-log: 
,10-12 09:32:51.255  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-12 09:32:51.255  5639  5685 I jxcore-log: 
10-12 09:32:51.255  5639  5685 I jxcore-log: 2016-10-12 13:32:51 - ERROR runTests: 'Test client failed: Native unit tests failed
10-12 09:32:51.255  5639  5685 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-12 09:32:51.255  5639  5685 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-12 09:32:51.255  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-12 09:32:51.255  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-12 09:32:51.255  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-12 09:32:51.255  5639  5685 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
10-12 09:32:51.255  5639  5685 I jxcore-log: 
,10-12 09:32:51.797  6006  6006 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-12 09:32:51.803  6006  6006 D AndroidRuntime: CheckJNI is OFF
,10-12 09:32:51.832  6006  6006 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-12 09:32:51.866  6006  6006 I Radio-JNI: register_android_hardware_Radio DONE
,10-12 09:32:51.884  6006  6006 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-12 09:32:51.893   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-12 09:32:51.894   928   941 I ActivityManager: Killing 5639:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-12 09:32:51.954   928  3805 I WindowState: WIN DEATH: Window{ab8b168 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-12 09:32:51.955   928  2998 D WifiService: Client connection lost with reason: 4
,10-12 09:32:51.955   928   939 D GraphicsStats: Buffer count: 2
,10-12 09:32:52.044   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-12 09:32:52.045   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-12 09:32:52.046   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-12 09:32:52.046   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-12 09:32:52.046   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:52.046   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:52.046   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 09:32:52.046   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-12 09:32:52.047   928   941 I ActivityManager:   Force finishing activity ActivityRecord{babbd25 u0 com.test.thalitest/.MainActivity t2}
10-12 09:32:52.047   928   951 I art     : Starting a blocking GC Explicit
,10-12 09:32:52.057   928  3738 W ActivityManager: Spurious death for ProcessRecord{5ad5dbe 0:com.test.thalitest/u0a77}, curProc for 5639: null
,10-12 09:32:52.061   928   946 W WindowManager: Attempted to add application window with unknown token Token{b5efefa ActivityRecord{babbd25 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-12 09:32:52.061   928   946 W WindowManager: Token{b5efefa ActivityRecord{babbd25 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{b5efefa ActivityRecord{babbd25 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-12 09:32:52.061   928   946 W WindowManager: view not successfully added to wm, removing view
10-12 09:32:52.062   928   946 W WindowManager: Exception when adding starting window
10-12 09:32:52.062   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{2cad1b1 V.E...... R.....ID 0,0-0,0} not attached to window manager
10-12 09:32:52.062   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-12 09:32:52.062   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-12 09:32:52.062   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-12 09:32:52.062   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-12 09:32:52.062   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-12 09:32:52.062   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:52.062   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:52.062   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 09:32:52.062   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-12 09:32:52.141   928   951 I art     : Explicit concurrent mark sweep GC freed 62156(3MB) AllocSpace objects, 15(476KB) LOS objects, 33% free, 28MB/43MB, paused 1.725ms total 93.406ms
,10-12 09:32:52.161   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-12 09:32:52.163  6006  6006 I art     : System.exit called, status: 0
10-12 09:32:52.163  6006  6006 I AndroidRuntime: VM exiting with result code 0.
,10-12 09:32:52.172   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-12 09:32:52.188   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-12 09:32:52.190  3664  3664 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-12 09:32:52.192  5890  5890 D BluetoothMapAppObserver: onReceive
,10-12 09:32:52.193  5890  5890 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-12 09:32:52.197  4053  4165 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-12 09:32:52.202   928  2967 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-12 09:32:52.238  3780  3780 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-12 09:32:52.243  3393  6018 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
10-12 09:32:52.241  3664  6017 I Keyboard.Facilitator.DecoderInitializer: run()
,10-12 09:32:52.244  3578  3578 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-12 09:32:52.244  3578  3578 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
10-12 09:32:52.249   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-12 09:32:52.257  3890  6023 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-12 09:32:52.257  3890  6023 D AccountUtils: Clearing selected account for com.test.thalitest
,10-12 09:32:52.284  3664  6017 I Decoder : createOrResetDecoder
,10-12 09:32:52.284    17    17 W kworker/2:0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:32:52.287    17    17 W kworker/2:0: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:32:52.308  3808  3927 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-12 09:32:52.323   928  3155 I ActivityManager: Start proc 6027:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-12 09:32:52.320    17    17 W kworker/2:0: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
--------- beginning of crash
10-12 09:32:52.324  3808  3927 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-12 09:32:52.324  3808  3927 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3808
10-12 09:32:52.324  3808  3927 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:52.324  3808  3927 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 09:32:52.325  3890  6023 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-12 09:32:52.327  3578  3578 I ConfigService: onCreate
,10-12 09:32:52.333   928   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-12 09:32:52.339   928  6034 E DropBoxManagerService: Can't write: system_app_crash
10-12 09:32:52.339   928  6034 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
10-12 09:32:52.339   928  6034 E DropBoxManagerService: 	... 8 more
,10-12 09:32:52.341  3808  3927 I Process : Sending signal. PID: 3808 SIG: 9
,10-12 09:32:52.360  3664  6017 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-12 09:32:52.369  3890  6023 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:52.369  3890  6023 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:32:52.369  3890  6023 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:52.369  3890  6023 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 09:32:52.370  3890  6023 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-12 09:32:52.380  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
10-12 09:32:52.380  3890  3890 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,10-12 09:32:52.395  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,10-12 09:32:52.395  3890  3890 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,10-12 09:32:52.425  3393  3418 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-12 09:32:52.425  3393  3418 E AndroidRuntime: Process: android.process.acore, PID: 3393
10-12 09:32:52.425  3393  3418 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:32:52.425  3393  3418 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 09:32:52.452   380   380 E lowmemorykiller: Error writing /proc/3808/oom_score_adj; errno=22
,10-12 09:32:52.452   928  3592 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
10-12 09:32:52.453   928  3592 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
10-12 09:32:52.453   928  3592 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
10-12 09:32:52.453   928  3592 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,10-12 09:32:52.484  3393  3418 I Process : Sending signal. PID: 3393 SIG: 9
,10-12 09:32:52.504   928  3748 D GraphicsStats: Buffer count: 1
10-12 09:32:52.504   928  3738 I WindowState: WIN DEATH: Window{b973e26 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-12 09:32:52.511   928  3592 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-12 09:32:52.524   928  3592 I ActivityManager: Start proc 6050:com.google.android.googlequicksearchbox/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,10-12 09:32:52.528   380   380 E lowmemorykiller: Error writing /proc/3393/oom_score_adj; errno=22
10-12 09:32:52.529   928   939 W ActivityManager: Spurious death for ProcessRecord{ec06902 6050:com.google.android.googlequicksearchbox/u0a29}, curProc for 3808: null
,10-12 09:32:52.531  3963  6044 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,10-12 09:32:52.559   380   380 E lowmemorykiller: Error writing /proc/3393/oom_score_adj; errno=22
,10-12 09:32:52.576   380   380 E lowmemorykiller: Error writing /proc/3393/oom_score_adj; errno=22
,10-12 09:32:52.588  3890  6045 W BaseAppContext: Using Auth Proxy for data requests.
,10-12 09:32:52.602  3890  6045 W BaseAppContext: Using Auth Proxy for data requests.
,10-12 09:32:52.626  3890  3890 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,10-12 09:32:52.642  3890  6064 I GMPM-SVC: App measurement is starting up
,10-12 09:32:52.657  3890  6064 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-12 09:32:52.661  3890  6064 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-12 09:32:52.681   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
