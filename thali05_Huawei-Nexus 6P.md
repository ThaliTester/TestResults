#### Test 85046911aaecdb3_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 03:26:17.998   929  5314 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196745, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-27 03:26:19.091  5547  5547 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 03:26:19.097  5547  5547 D AndroidRuntime: CheckJNI is OFF
09-27 03:26:19.123  5547  5547 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 03:26:19.156  5547  5547 I Radio-JNI: register_android_hardware_Radio DONE
09-27 03:26:19.171  5547  5547 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-27 03:26:19.187   929   939 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 03:26:19.222   929   939 I ActivityManager: Start proc 5556:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 03:26:19.224  5547  5547 D AndroidRuntime: Shutting down VM
,09-27 03:26:19.565   929  3693 I WindowManager: Screenshot max retries 4 of Token{8b7f646 ActivityRecord{8b41221 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{d9be459 u0 Starting com.test.thalitest} drawState=4
,09-27 03:26:19.639  5556  5556 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 03:26:19.670  5556  5556 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 03:26:19.698  5556  5556 I LibraryLoader: Time to load native libraries: 23 ms (timestamps 8422-8445)
,09-27 03:26:19.698  5556  5556 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 03:26:19.723  5556  5556 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3eb77f}
,09-27 03:26:19.724  5556  5556 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 03:26:19.724  5556  5556 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-27 03:26:19.728  5556  5556 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-27 03:26:19.729  5556  5556 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 03:26:19.766  5556  5556 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 03:26:19.774  5556  5556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-27 03:26:19.774  5556  5556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 03:26:19.774  5556  5556 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 03:26:19.774  5556  5556 I Adreno  : Build Date                       : 12/06/15
09-27 03:26:19.774  5556  5556 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 03:26:19.774  5556  5556 I Adreno  : Local Branch                     : mybranch17112971
09-27 03:26:19.774  5556  5556 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 03:26:19.774  5556  5556 I Adreno  : Remote Branch                    : NONE
09-27 03:26:19.774  5556  5556 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 03:26:19.833   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f75364:true
,09-27 03:26:19.864   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23377]" dev="sockfs" ino=23377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 03:26:19.864   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23377]" dev="sockfs" ino=23377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 03:26:19.875  5556  5556 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 03:26:19.884  5556  5556 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 03:26:19.908   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32097]" dev="sockfs" ino=32097 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 03:26:19.910  5556  5593 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-27 03:26:19.908   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32097]" dev="sockfs" ino=32097 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 03:26:19.911  3071  3071 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14977]" dev="sockfs" ino=14977 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-27 03:26:19.911  3071  3071 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14977]" dev="sockfs" ino=14977 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 03:26:19.917  5556  5580 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 03:26:19.941  5556  5593 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 03:26:20.013   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +447ms (total +815ms)
,09-27 03:26:20.056  5556  5556 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5556
,09-27 03:26:20.169  5556  5556 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 03:26:20.524  5556  5595 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -560727760
,09-27 03:26:20.544  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 03:26:20.544  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 03:26:20.544  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 03:26:20.544  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 03:26:20.544  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-27 03:26:20.545  5556  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16aa0a4 added. We now have 1 listener(s)
,09-27 03:26:20.556  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 03:26:20.560  5556  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 03:26:20.563  5556  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 03:26:20.564  5556  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-27 03:26:20.570  5556  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5742bd3 added. We now have 1 listener(s)
09-27 03:26:20.570  5556  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 03:26:20.577   929  2898 D WifiService: New client listening to asynchronous messages
,09-27 03:26:20.579  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 03:26:20.579  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-27 03:26:20.579  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 03:26:20.580  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 03:26:20.580  5556  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-27 03:26:20.584  5556  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 03:26:20.584  5556  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-27 03:26:20.597  5556  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 03:26:20.597  5556  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 03:26:20.598  5556  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 03:26:20.598  5556  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 03:26:20.598  5556  5595 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 03:26:20.602  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 03:26:20.607  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 03:26:20.970  5556  5556 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 03:26:21.389  5556  5565 I art     : Background sticky concurrent mark sweep GC freed 80555(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 2.395ms total 300.664ms
,09-27 03:26:21.622  5556  5602 W jxcore-log: Initializing JXcore engine
,09-27 03:26:21.622  5556  5602 W jxcore-log: JXcore engine is ready
,09-27 03:26:21.688  5602  5602 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-27 03:26:21.688  5602  5602 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15386]" dev="sockfs" ino=15386 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-27 03:26:21.688  5602  5602 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 03:26:21.688  5602  5602 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31277]" dev="sockfs" ino=31277 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 03:26:21.705  5556  5602 W jxcore-log: Starting JXcore engine
,09-27 03:26:21.772  5556  5602 W jxcore-log: Platform android
09-27 03:26:21.772  5556  5602 W jxcore-log: 
,09-27 03:26:21.772  5556  5602 W jxcore-log: Process ARCH arm
09-27 03:26:21.772  5556  5602 W jxcore-log: 
,09-27 03:26:21.872  5556  5602 I jxcore-log: JXcore Cordova bridge is ready!
09-27 03:26:21.872  5556  5602 I jxcore-log: 
,09-27 03:26:21.872  5556  5602 W jxcore-log: JXcore engine is started
,09-27 03:26:21.884  5556  5595 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 03:26:21.892  5556  5556 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 03:26:22.535   929  2897 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 03:26:22.874   929  2899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 03:26:25.898   929  2899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 03:26:28.954  5556  5602 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-27 03:26:28.954  5556  5602 I jxcore-log: 
,09-27 03:26:28.955  5556  5602 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-27 03:26:28.955  5556  5602 I jxcore-log: 
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 03:26:28.959  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 03:26:28.961  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 03:26:28.963  5556  5602 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-27 03:26:28.963  5556  5602 I jxcore-log: 
09-27 03:26:28.964  5556  5602 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-27 03:26:28.964  5556  5602 I jxcore-log: 
,09-27 03:26:29.206  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 03:26:29.207  5556  5602 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2faabea added. We now have 2 listener(s)
,09-27 03:26:29.207  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 03:26:29.207  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 03:26:29.207  5556  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 03:26:29.208  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 03:26:29.208  5556  5602 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@618aedb added. We now have 2 listener(s)
09-27 03:26:29.208  5556  5602 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 03:26:29.208  5556  5602 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 03:26:29.210  5556  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 03:26:29.213  5556  5602 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 03:26:29.215  5556  5602 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 03:26:29.215  5556  5602 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 03:26:29.216  5556  5602 D ExecuteNativeTests: Running unit tests
09-27 03:26:29.217  5556  5602 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 03:26:29.217   929  3067 D WifiService: setWifiEnabled: true pid=5556, uid=10077
09-27 03:26:29.217   929  3067 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 03:26:29.222  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 03:26:29.228  5556  5556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 03:26:39.227  5556  5602 I com.test.thalitest.ThaliTestRunner: Running UT
,09-27 03:26:39.256  5556  5602 I jxcore-log: *Native tests were executed*
09-27 03:26:39.256  5556  5602 I jxcore-log: 
,09-27 03:26:39.256  5556  5602 I jxcore-log: Total number of executed tests:  1
09-27 03:26:39.256  5556  5602 I jxcore-log: 
09-27 03:26:39.257  5556  5602 I jxcore-log: Number of passed tests:  1
09-27 03:26:39.257  5556  5602 I jxcore-log: 
09-27 03:26:39.257  5556  5602 I jxcore-log: Number of failed tests:  0
09-27 03:26:39.257  5556  5602 I jxcore-log: 
09-27 03:26:39.257  5556  5602 I jxcore-log: Number of ignored tests:  0
09-27 03:26:39.257  5556  5602 I jxcore-log: 
09-27 03:26:39.257  5556  5602 I jxcore-log: Total duration:  3
09-27 03:26:39.257  5556  5602 I jxcore-log: 
09-27 03:26:39.258  5556  5602 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-27 03:26:39.258  5556  5602 I jxcore-log: 
,09-27 03:26:39.262  5556  5602 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 03:26:39.262  5556  5602 I jxcore-log: 
09-27 03:26:39.264  5556  5602 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 03:26:39.264  5556  5602 I jxcore-log: 
,09-27 03:26:39.289  5556  5556 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-27 03:26:39.752  5605  5605 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-27 03:26:39.757  5605  5605 D AndroidRuntime: CheckJNI is OFF
,09-27 03:26:39.785  5605  5605 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-27 03:26:39.821  5605  5605 I Radio-JNI: register_android_hardware_Radio DONE
,09-27 03:26:39.839  5605  5605 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-27 03:26:39.852   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-27 03:26:39.853   929   942 I ActivityManager: Killing 5556:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-27 03:26:39.934   929  3071 I WindowState: WIN DEATH: Window{2885d94 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-27 03:26:39.934   929  2898 D WifiService: Client connection lost with reason: 4
09-27 03:26:39.934   929  3331 D GraphicsStats: Buffer count: 2
,09-27 03:26:39.987   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-27 03:26:39.987   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-27 03:26:39.988   929   953 I art     : Starting a blocking GC Explicit
09-27 03:26:39.988   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-27 03:26:39.988   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-27 03:26:39.988   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 03:26:39.988   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 03:26:39.988   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 03:26:39.988   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 03:26:39.991   929   942 I ActivityManager:   Force finishing activity ActivityRecord{8b41221 u0 com.test.thalitest/.MainActivity t2}
,09-27 03:26:40.001   929  3765 W ActivityManager: Spurious death for ProcessRecord{4f1ae56 0:com.test.thalitest/u0a77}, curProc for 5556: null
,09-27 03:26:40.005   929   947 W WindowManager: Attempted to add application window with unknown token Token{8b7f646 ActivityRecord{8b41221 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-27 03:26:40.005   929   947 W WindowManager: Token{8b7f646 ActivityRecord{8b41221 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{8b7f646 ActivityRecord{8b41221 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-27 03:26:40.005   929   947 W WindowManager: view not successfully added to wm, removing view
09-27 03:26:40.006   929   947 W WindowManager: Exception when adding starting window
09-27 03:26:40.006   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{cb9aca9 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-27 03:26:40.006   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-27 03:26:40.006   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-27 03:26:40.006   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-27 03:26:40.006   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-27 03:26:40.006   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-27 03:26:40.006   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 03:26:40.006   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 03:26:40.006   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 03:26:40.006   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 03:26:40.074   929   953 I art     : Explicit concurrent mark sweep GC freed 57702(4MB) AllocSpace objects, 29(780KB) LOS objects, 33% free, 28MB/43MB, paused 1.619ms total 86.307ms
,09-27 03:26:40.093   929   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-27 03:26:40.096  5605  5605 I art     : System.exit called, status: 0
,09-27 03:26:40.096  5605  5605 I AndroidRuntime: VM exiting with result code 0.
,09-27 03:26:40.100   929   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-27 03:26:40.111   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-27 03:26:40.116  3581  3581 I Keyboard.Facilitator: resetDictionaries() : en_US
09-27 03:26:40.116  4508  4508 D BluetoothMapAppObserver: onReceive
09-27 03:26:40.116  4508  4508 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-27 03:26:40.125  4003  4099 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-27 03:26:40.129   929  2863 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-27 03:26:40.142  3581  5616 I Keyboard.Facilitator.DecoderInitializer: run()
,09-27 03:26:40.154  3317  5617 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-27 03:26:40.155  3581  5616 I Decoder : createOrResetDecoder
,09-27 03:26:40.173  3733  3733 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-27 03:26:40.188    28    28 W kworker/2:1: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 03:26:40.194    28    28 W kworker/2:1: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 03:26:40.200  3495  3495 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-27 03:26:40.200  3495  3495 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-27 03:26:40.207  3764  3874 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-27 03:26:40.208   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-27 03:26:40.211    28    28 W kworker/2:1: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 03:26:40.220   929  5086 I ActivityManager: Start proc 5622:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-27 03:26:40.221  3764  3874 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-27 03:26:40.221  3764  3874 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3764
09-27 03:26:40.221  3764  3874 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 03:26:40.221  3764  3874 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 03:26:40.225  3317  3341 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj83C3539AB) - 
09-27 03:26:40.226   929  5631 E DropBoxManagerService: Can't write: system_app_crash
09-27 03:26:40.226   929  5631 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 03:26:40.226   929  5631 E DropBoxManagerService: 	... 5 more
09-27 03:26:40.227   929  3071 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-27 03:26:40.231  3764  3874 I Process : Sending signal. PID: 3764 SIG: 9
09-27 03:26:40.235  3495  3495 I ConfigService: onCreate
09-27 03:26:40.236  3654  5635 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-27 03:26:40.237  3654  5635 D AccountUtils: Clearing selected account for com.test.thalitest
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 03:26:40.238  3495  5636 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 03:26:40.239  3495  5636 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-27 03:26:40.242  3495  5636 W SQLiteOpenHelper: Opened config.db in read-only mode
09-27 03:26:40.261  3581  5616 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-27 03:26:40.347  3317  3341 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-27 03:26:40.347  3317  3341 E AndroidRuntime: Process: android.process.acore, PID: 3317
09-27 03:26:40.347  3317  3341 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 03:26:40.347  3317  3341 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 03:26:40.360   929  2862 W InputDispatcher: channel 'c5d862e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-27 03:26:40.360   929  2862 E InputDispatcher: channel 'c5d862e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-27 03:26:40.360   929  3693 I WindowState: WIN DEATH: Window{c5d862e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-27 03:26:40.360   929  3071 D GraphicsStats: Buffer count: 1
09-27 03:26:40.360   929  3693 W InputDispatcher: Attempted to unregister already unregistered input channel 'c5d862e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-27 03:26:40.361  3317  3341 I Process : Sending signal. PID: 3317 SIG: 9
,09-27 03:26:40.366   929   940 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3764) has died
,09-27 03:26:40.366   929   940 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-27 03:26:40.595   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
