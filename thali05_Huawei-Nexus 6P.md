#### Test 89361553ea76302_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-14 07:16:37.026   928  5367 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-14 07:16:37.491   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-14 07:16:37.492   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-14 07:16:37.548  5605  5605 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-14 07:16:37.554  5605  5605 D AndroidRuntime: CheckJNI is OFF
10-14 07:16:37.585  5605  5605 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-14 07:16:37.623  5605  5605 I Radio-JNI: register_android_hardware_Radio DONE
10-14 07:16:37.639  5605  5605 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-14 07:16:37.644   928  3788 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-14 07:16:37.683   928  3788 I ActivityManager: Start proc 5614:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-14 07:16:37.691  5605  5605 D AndroidRuntime: Shutting down VM
,10-14 07:16:38.020   928  3389 I WindowManager: Screenshot max retries 4 of Token{22b38c2 ActivityRecord{4d1210d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{31664c5 u0 Starting com.test.thalitest} drawState=2
,10-14 07:16:38.097  5614  5614 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 07:16:38.125  5614  5614 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 07:16:38.152  5614  5614 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 9503-9523)
,10-14 07:16:38.152  5614  5614 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 07:16:38.170  5614  5614 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a1c3c24}
,10-14 07:16:38.170  5614  5614 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 07:16:38.170  5614  5614 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-14 07:16:38.174  5614  5614 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 07:16:38.175  5614  5614 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 07:16:38.205  5614  5614 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 07:16:38.213   928  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 07:16:38.214  5614  5614 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 07:16:38.214  5614  5614 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 07:16:38.214  5614  5614 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 07:16:38.214  5614  5614 I Adreno  : Build Date                       : 12/06/15
10-14 07:16:38.214  5614  5614 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 07:16:38.214  5614  5614 I Adreno  : Local Branch                     : mybranch17112971
10-14 07:16:38.214  5614  5614 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 07:16:38.214  5614  5614 I Adreno  : Remote Branch                    : NONE
10-14 07:16:38.214  5614  5614 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 07:16:38.250   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c31f40:true
,10-14 07:16:38.287   407   407 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16982]" dev="sockfs" ino=16982 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 07:16:38.287   407   407 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[16982]" dev="sockfs" ino=16982 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 07:16:38.299  5614  5614 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-14 07:16:38.307  5614  5614 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-14 07:16:38.330   407   407 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31970]" dev="sockfs" ino=31970 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-14 07:16:38.333  5614  5651 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-14 07:16:38.330   407   407 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31970]" dev="sockfs" ino=31970 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 07:16:38.334  3124  3124 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16993]" dev="sockfs" ino=16993 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 07:16:38.334  3124  3124 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16993]" dev="sockfs" ino=16993 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 07:16:38.339  5614  5638 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-14 07:16:38.366  5614  5651 I OpenGLRenderer: Initialized EGL, version 1.4
,10-14 07:16:38.445   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +418ms (total +784ms)
,10-14 07:16:38.476  5614  5614 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5614
,10-14 07:16:38.564  5614  5614 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-14 07:16:38.812  5614  5653 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -584316624
,10-14 07:16:38.823  5614  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-14 07:16:38.823  5614  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-14 07:16:38.823  5614  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-14 07:16:38.823  5614  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-14 07:16:38.823  5614  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-14 07:16:38.823  5614  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8d105 added. We now have 1 listener(s)
,10-14 07:16:38.828  5614  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-14 07:16:38.829  5614  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:16:38.830  5614  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-14 07:16:38.831  5614  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-14 07:16:38.840  5614  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba7881 added. We now have 1 listener(s)
10-14 07:16:38.840  5614  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 07:16:38.847   928  2972 D WifiService: New client listening to asynchronous messages
,10-14 07:16:38.850  5614  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 07:16:38.850  5614  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-14 07:16:38.850  5614  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-14 07:16:38.850  5614  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-14 07:16:38.850  5614  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-14 07:16:38.854  5614  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:16:38.854  5614  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-14 07:16:38.861  5614  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:38.861  5614  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:16:38.862  5614  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-14 07:16:38.862  5614  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 07:16:38.862  5614  5653 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-14 07:16:39.110  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:39.119  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:39.124  5614  5614 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-14 07:16:39.306  5614  5623 I art     : Background sticky concurrent mark sweep GC freed 87569(8MB) AllocSpace objects, 17(1308KB) LOS objects, 21% free, 25MB/32MB, paused 2.059ms total 112.390ms
,10-14 07:16:39.487  5614  5660 W jxcore-log: Initializing JXcore engine
10-14 07:16:39.487  5614  5660 W jxcore-log: JXcore engine is ready
,10-14 07:16:39.517  5660  5660 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1187 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-14 07:16:39.517  5660  5660 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13754]" dev="sockfs" ino=13754 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-14 07:16:39.517  5660  5660 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-14 07:16:39.517  5660  5660 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33986]" dev="sockfs" ino=33986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-14 07:16:39.526  5614  5660 W jxcore-log: Starting JXcore engine
,10-14 07:16:39.578  5614  5660 W jxcore-log: Platform android
10-14 07:16:39.578  5614  5660 W jxcore-log: 
,10-14 07:16:39.578  5614  5660 W jxcore-log: Process ARCH arm
10-14 07:16:39.578  5614  5660 W jxcore-log: 
,10-14 07:16:39.720  5614  5660 I jxcore-log: JXcore Cordova bridge is ready!
10-14 07:16:39.720  5614  5660 I jxcore-log: 
10-14 07:16:39.720  5614  5660 W jxcore-log: JXcore engine is started
,10-14 07:16:39.734  5614  5653 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-14 07:16:39.740  5614  5614 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-14 07:16:47.493   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:48.494   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:49.371  5614  5660 I jxcore-log: 2016-10-14 11:16:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-14 07:16:49.371  5614  5660 I jxcore-log: 
,10-14 07:16:49.373  5614  5660 I jxcore-log: 2016-10-14 11:16:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-14 07:16:49.373  5614  5660 I jxcore-log: 
,10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:49.377  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 07:16:49.378  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,10-14 07:16:49.380  5614  5660 I jxcore-log: 2016-10-14 11:16:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-14 07:16:49.380  5614  5660 I jxcore-log: 
,10-14 07:16:49.381  5614  5660 I jxcore-log: 2016-10-14 11:16:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-14 07:16:49.381  5614  5660 I jxcore-log: 
,10-14 07:16:49.495   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:49.630  5614  5660 I jxcore-log: 2016-10-14 11:16:49 - DEBUG UnitTest_app: 'Running unit tests'
10-14 07:16:49.630  5614  5660 I jxcore-log: 
,10-14 07:16:49.630  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:16:49.631  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e163be7 added. We now have 2 listener(s)
,10-14 07:16:49.631  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 07:16:49.631  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:16:49.631  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:16:49.632  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:16:49.632  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1621394 added. We now have 2 listener(s)
,10-14 07:16:49.632  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:16:49.632  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 07:16:49.634  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:49.637  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 07:16:49.638  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:16:49.638  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:16:49.639  5614  5660 D executeNativeTests: Running unit tests
,10-14 07:16:49.645  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:49.652  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:49.678  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 07:16:49.678  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 added. We now have 3 listener(s)
,10-14 07:16:49.679  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 07:16:49.679  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-14 07:16:49.679  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:16:49.679  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:16:49.679  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 added. We now have 3 listener(s)
10-14 07:16:49.679  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:16:49.680  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 07:16:49.681  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:49.683  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:16:49.684  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:16:49.684  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:16:49.686  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-14 07:16:49.686  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 07:16:49.686  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 07:16:49.686  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 07:16:49.686  5614  5660 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-14 07:16:49.686  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 07:16:49.687  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 07:16:49.687  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 07:16:49.687  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 07:16:49.687  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 07:16:49.687  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:16:49.687  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:16:49.687  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:16:49.688  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:16:49.688  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.688  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:16:49.688  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:16:49.688  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:16:49.688  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 removed from the list
10-14 07:16:49.688  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:49.688  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 removed from the list
10-14 07:16:49.690  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:16:49.696  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:16:49.696  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:16:49.696  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.697  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.697  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.697  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:16:49.697  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:16:49.697  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:49.697  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:49.698  5614  5660 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-14 07:16:49.699  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:16:49.699  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 07:16:49.699  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:16:49.699  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:16:49.699  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.699  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.699  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:16:49.699  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
,10-14 07:16:49.699  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:49.699  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:49.699  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:16:49.699  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.699  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.699  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.699  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.699  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:16:49.700  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:16:49.700  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:49.700  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-14 07:16:49.702  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 07:16:49.703  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:16:49.703  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 07:16:49.703  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:16:49.703  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:16:49.703  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.703  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.703  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:16:49.703  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:16:49.703  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:16:49.703  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:49.703  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:16:49.703  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.703  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.703  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:49.703  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:49.704  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:16:49.704  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:16:49.704  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:49.704  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:49.704  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-14 07:16:49.705  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:49.707  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:16:49.709  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:16:49.709  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:16:49.710  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-14 07:16:49.710  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 07:16:49.710  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 07:16:49.710  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:16:49.710  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 07:16:49.714  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 07:16:49.714  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 07:16:49.716  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 07:16:49.717  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:16:49.717  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 07:16:49.717  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 07:16:49.718  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,10-14 07:16:49.720  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-14 07:16:49.720  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 07:16:49.720  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-14 07:16:49.720  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 07:16:49.720  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:49.720  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 07:16:49.721  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 07:16:49.721  5614  5660 D BluetoothAdapter: STATE_ON
,10-14 07:16:49.723  4544  4559 D BtGatt.GattService: registerClient() - UUID=aa56fbe8-064d-4b39-a7cb-a34c4b32b167
,10-14 07:16:49.724  4544  4605 D BtGatt.GattService: onClientRegistered() - UUID=aa56fbe8-064d-4b39-a7cb-a34c4b32b167, clientIf=5
,10-14 07:16:49.725  5614  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 07:16:49.726  4544  4761 D BtGatt.GattService: start scan with filters
,10-14 07:16:49.730  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 07:16:49.730  4544  4608 D BtGatt.ScanManager: handling starting scan
10-14 07:16:49.731  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 07:16:49.731  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:16:49.731  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 07:16:49.731  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 07:16:49.731  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 07:16:49.731  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 07:16:49.732  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:16:49.732  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-14 07:16:49.733  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:16:49.733  4544  4608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:16:49.733  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 07:16:49.734  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 07:16:49.740  4544  4605 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-14 07:16:49.740  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:49.741  4544  4608 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 07:16:49.747  4544  4605 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 07:16:49.747  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:49.748  4544  4608 D BtGatt.ScanManager: Starting BLE batch scan
10-14 07:16:49.748  4544  4608 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-14 07:16:49.759  4544  4605 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 07:16:49.759  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:16:49.765  4544  4605 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 07:16:49.765  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:16:50.234  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 07:16:50.235  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:16:50.235  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 07:16:50.496   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:51.497   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:52.075   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 07:16:52.498   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 07:16:54.738  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 07:16:54.739  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 07:16:54.739  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 07:16:54.739  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:54.739  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 07:16:54.739  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 07:16:54.739  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 07:16:54.739  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:16:54.739  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 07:16:54.739  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-14 07:16:54.740  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 07:16:54.740  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 07:16:54.741  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:16:54.742  4544  4559 D BtGatt.GattService: stopScan() - queue size =1
10-14 07:16:54.744  4544  4761 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-14 07:16:54.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-14 07:16:54.748  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 07:16:54.748  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 07:16:54.749  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:16:54.749  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 07:16:54.749  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-14 07:16:54.749  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 07:16:54.749  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 07:16:54.750  4544  4544 D BtGatt.ScanManager: awakened up at time 236122
,10-14 07:16:54.757  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 07:16:54.757  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 07:16:54.757  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 07:16:54.758  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-14 07:16:54.758  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 07:16:54.758  4544  4605 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 07:16:54.758  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:16:54.759  4544  4608 D BtGatt.ScanManager: stopping BLe Batch
10-14 07:16:54.759  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 07:16:54.761  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 07:16:54.761  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:16:54.762  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:54.762  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:16:54.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 07:16:54.762  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:16:54.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:16:54.762  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:16:54.762  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:54.762  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:54.762  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:16:54.762  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:54.767  4544  4605 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 07:16:54.767  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:54.767  4544  4608 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 07:16:54.788  4544  4605 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-14 07:16:54.788  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:54.788  4544  4605 D BtGatt.GattService: current time is 236160307134
10-14 07:16:54.788  4544  4605 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -91, 10, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -84, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 07:16:54.789  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
10-14 07:16:54.790  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-14 07:16:54.790  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-14 07:16:54.790  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-14 07:16:54.791  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 07:16:54.791  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 07:16:54.791  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-14 07:16:55.110   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 07:16:55.116   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-14 07:16:55.263  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 07:16:57.499   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:58.135   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 07:16:58.141   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-14 07:16:58.213   928  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 07:16:58.500   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:59.502   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:16:59.764  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-14 07:16:59.770  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:59.780  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 07:16:59.785  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:16:59.785  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:16:59.786  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:16:59.786  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 07:16:59.786  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-14 07:16:59.786  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:16:59.786  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-14 07:16:59.792  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:59.796  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:16:59.797  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 07:16:59.797  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 07:16:59.804  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 07:16:59.806  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 07:16:59.806  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 07:16:59.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-14 07:16:59.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 07:16:59.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 07:16:59.811  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 07:16:59.811  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-14 07:16:59.812  5614  5660 D BluetoothAdapter: STATE_ON
,10-14 07:16:59.816  4544  4761 D BtGatt.GattService: registerClient() - UUID=8583c34f-d6d0-4a91-943f-dce5696aee89
,10-14 07:16:59.817  4544  4605 D BtGatt.GattService: onClientRegistered() - UUID=8583c34f-d6d0-4a91-943f-dce5696aee89, clientIf=5
10-14 07:16:59.817  5614  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 07:16:59.818  4544  4559 D BtGatt.GattService: start scan with filters
,10-14 07:16:59.822  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 07:16:59.822  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 07:16:59.822  4544  4608 D BtGatt.ScanManager: handling starting scan
10-14 07:16:59.822  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:16:59.822  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 07:16:59.822  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 07:16:59.823  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 07:16:59.823  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 07:16:59.826  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:16:59.826  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-14 07:16:59.827  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:16:59.829  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 07:16:59.830  4544  4605 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 07:16:59.831  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.831  4544  4608 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 07:16:59.832  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 07:16:59.839  4544  4605 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 07:16:59.840  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.840  4544  4608 D BtGatt.ScanManager: Starting BLE batch scan
10-14 07:16:59.840  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:16:59.840  4544  4608 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 07:16:59.840  5614  5660 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-14 07:16:59.840  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-14 07:16:59.840  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 07:16:59.840  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:59.841  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 07:16:59.841  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:16:59.841  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 07:16:59.841  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:16:59.841  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 07:16:59.841  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 07:16:59.841  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 07:16:59.841  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 07:16:59.842  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:16:59.843  4544  4559 D BtGatt.GattService: stopScan() - queue size =1
,10-14 07:16:59.844  4544  4557 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-14 07:16:59.845  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 07:16:59.846  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 07:16:59.846  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 07:16:59.846  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:16:59.846  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 07:16:59.846  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-14 07:16:59.846  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 07:16:59.846  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 07:16:59.847  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:16:59.847  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 07:16:59.847  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 07:16:59.847  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 07:16:59.847  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 07:16:59.849  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:16:59.850  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 07:16:59.850  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:16:59.850  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:59.850  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:16:59.851  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:16:59.851  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:16:59.851  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:16:59.851  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:16:59.851  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:59.851  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:59.851  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:16:59.851  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:59.852  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:16:59.852  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:16:59.853  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:16:59.853  4544  4605 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 07:16:59.853  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:16:59.853  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.853  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:16:59.854  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:16:59.854  5614  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-14 07:16:59.856  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:16:59.860  4544  4605 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 07:16:59.860  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:16:59.861  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:16:59.861  5614  5660 V i,o.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:16:59.864  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:16:59.864  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:16:59.864  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:16:59.864  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 07:16:59.864  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 07:16:59.864  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:16:59.864  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 07:16:59.868  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 07:16:59.868  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 07:16:59.869  4544  4605 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 07:16:59.869  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.869  4544  4608 D BtGatt.ScanManager: stopping BLe Batch
10-14 07:16:59.869  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:16:59.873  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:16:59.873  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 07:16:59.874  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 07:16:59.874  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 07:16:59.875  4544  4605 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 07:16:59.875  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.875  4544  4608 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 07:16:59.877  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 07:16:59.878  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 07:16:59.878  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 07:16:59.878  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 07:16:59.878  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 07:16:59.878  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:16:59.880  4544  4761 D BtGatt.GattService: registerClient() - UUID=a5d1a752-47d3-42fa-a239-04bece32c134
10-14 07:16:59.881  4544  4605 D BtGatt.GattService: onClientRegistered() - UUID=a5d1a752-47d3-42fa-a239-04bece32c134, clientIf=5
10-14 07:16:59.881  5614  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 07:16:59.882  4544  4559 D BtGatt.GattService: start scan with filters
10-14 07:16:59.882  4544  4605 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 07:16:59.882  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.885  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 07:16:59.885  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 07:16:59.885  4544  4608 D BtGatt.ScanManager: handling starting scan
10-14 07:16:59.885  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:16:59.886  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 07:16:59.886  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 07:16:59.886  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 07:16:59.886  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 07:16:59.889  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:16:59.890  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 07:16:59.890  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:16:59.891  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 07:16:59.892  4544  4605 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 07:16:59.892  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.892  4544  4608 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 07:16:59.894  5614  5660 I io.jxcore.node.ConnectionHelper: start: OK
10-14 07:16:59.898  4544  4605 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 07:16:59.898  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.898  4544  4608 D BtGatt.ScanManager: Starting BLE batch scan
10-14 07:16:59.898  4544  4608 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-14 07:16:59.907  4544  4605 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 07:16:59.907  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:16:59.912  4544  4605 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 07:16:59.912  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:17:00.391  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 07:17:00.392  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:17:00.392  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 07:17:00.503   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:01.165   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 07:17:01.504   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:02.505   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 07:17:04.193   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-14 07:17:04.199   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-14 07:17:04.894  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 07:17:04.894  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-14 07:17:04.895  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 07:17:04.895  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:04.895  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 07:17:04.895  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:04.895  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 07:17:04.895  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:17:04.895  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 07:17:04.895  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 07:17:04.896  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-14 07:17:04.896  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 07:17:04.897  5614  5660 D BluetoothAdapter: STATE_ON
,10-14 07:17:04.899  4544  4557 D BtGatt.GattService: stopScan() - queue size =1
,10-14 07:17:04.900  4544  4743 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-14 07:17:04.901  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 07:17:04.901  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-14 07:17:04.902  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 07:17:04.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:17:04.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 07:17:04.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 07:17:04.902  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 07:17:04.902  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 07:17:04.905  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:17:04.905  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 07:17:04.905  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-14 07:17:04.905  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 07:17:04.905  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 07:17:04.909  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:17:04.910  4544  4544 D BtGatt.ScanManager: awakened up at time 246282
10-14 07:17:04.912  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:17:04.912  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:17:04.913  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:17:04.914  4544  4605 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 07:17:04.914  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:17:04.914  4544  4608 D BtGatt.ScanManager: stopping BLe Batch
,10-14 07:17:04.923  4544  4605 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 07:17:04.923  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:17:04.923  4544  4608 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 07:17:04.945  4544  4605 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-14 07:17:04.945  4544  4605 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:17:04.945  4544  4605 D BtGatt.GattService: current time is 246317606769
,10-14 07:17:04.946  4544  4605 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -87, 15, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
10-14 07:17:04.946  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-14 07:17:04.947  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-14 07:17:04.947  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 07:17:04.948  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 07:17:04.948  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 07:17:04.948  4544  4605 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,10-14 07:17:05.414  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 07:17:05.414  5614  5614 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:05.414  5614  5614 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 07:17:07.227   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 07:17:07.231   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-14 07:17:09.914  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 07:17:09.914  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.914  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.915  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.915  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 07:17:09.915  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.915  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.915  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.916  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.916  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.916  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.917  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.918  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.922  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:17:09.922  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.922  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:09.923  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:09.924  5614  5660 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-14 07:17:09.927  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 07:17:09.928  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.928  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.928  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.928  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.929  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.929  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.929  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.929  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.929  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.930  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:09.930  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.930  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.930  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.930  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.933  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.933  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.933  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:09.933  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.935  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-14 07:17:09.935  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.935  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.935  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.935  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.935  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.935  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.935  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 07:17:09.935  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.935  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.936  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.936  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.936  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.936  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.936  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.936  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.937  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.937  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.937  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.937  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:09.938  5614  5660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-14 07:17:09.938  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.938  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.939  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.939  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.939  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.939  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.939  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 07:17:09.939  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.939  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.939  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.939  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.939  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.939  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.939  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.939  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.941  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.941  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.941  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.941  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:09.942  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-14 07:17:09.942  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 07:17:09.942  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.942  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.942  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.942  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.942  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.942  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.942  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.942  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.943  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.943  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.943  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.943  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.943  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.943  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.944  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.944  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.944  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.944  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.945  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 07:17:09.945  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 07:17:09.945  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 07:17:09.946  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 07:17:09.946  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 07:17:09.946  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 07:17:09.946  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 07:17:09.946  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 07:17:09.946  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10,-14 07:17:09.946  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.946  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.946  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.946  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.946  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.947  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.947  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.947  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.947  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.947  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.947  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.947  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.947  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.947  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.947  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.948  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.948  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.949  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.949  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:09.949  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 07:17:09.950  5614  5660 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 07:17:09.950  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-14 07:17:09.953  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 07:17:09.953  5614  5660 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 07:17:09.954  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-14 07:17:09.955  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 07:17:09.955  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-14 07:17:09.956  5614  5660 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-14 07:17:09.956  5614  5660 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-14 07:17:09.956  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 07:17:09.956  5614  5660 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 07:17:09.956  5614  5660 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,10-14 07:17:09.956  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 07:17:09.956  5614  5660 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 07:17:09.956  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-14 07:17:09.960  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-14 07:17:09.961  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,10-14 07:17:09.961  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-14 07:17:09.962  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-14 07:17:09.962  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-14 07:17:09.962  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-14 07:17:09.962  5614  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 07:17:09.962  5614  5660 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-14 07:17:09.963  5614  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-14 07:17:09.963  5614  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-14 07:17:09.963  5614  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-14 07:17:09.963  5614  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-14 07:17:09.963  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.963  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.963  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.963  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.964  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.964  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.964  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.964  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-14 07:17:09.965  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.965  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.965  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.965  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.965  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.965  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.965  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.965  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.965  5614  5662 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothCl,ientThread: shutdown: Thread ID: 125
10-14 07:17:09.965  5614  5661 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-14 07:17:09.965  5614  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 07:17:09.967  4761  4761 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34028]" dev="sockfs" ino=34028 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 07:17:09.967  4761  4761 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34028]" dev="sockfs" ino=34028 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 07:17:09.967  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:17:09.967  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.967  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:09.967  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.968  5614  5660 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-14 07:17:09.968  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.968  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.969  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.969  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.969  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:09.969  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.969  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.969  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.969  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.969  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.969  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.969  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.969  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.969  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.969  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.970  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.970  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.970  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.970  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.971  5614  5660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-14 07:17:09.972  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.972  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.972  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.972  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.972  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.972  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:09.972  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.972  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.972  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.972  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.972  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.972  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.972  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.972  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.972  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.973  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.973  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 07:17:09.973  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.973  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.974  5614  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-14 07:17:09.974  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-14 07:17:09.974  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 07:17:09.975  5614  5660 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-14 07:17:09.975  5614  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-14 07:17:09.975  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-14 07:17:09.975  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 07:17:09.975  5614  5660 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-14 07:17:09.975  5614  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-14 07:17:09.975  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 07:17:09.975  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 07:17:09.975  5614  5660 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,10-14 07:17:09.975  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:09.975  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:09.975  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:09.975  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:09.975  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.975  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.975  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.975  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.976  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.976  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.976  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:09.976  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.976  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.976  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.976  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.977  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:09.977  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:09.977  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.977  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.978  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 07:17:09.978  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:09.978  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:09.978  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:09.978  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:09.978  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:09.978  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:09.978  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:09.978  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:09.978  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:10.626   928  5367 D NetlinkSocketObserver: NeighborEvent{elapsedMs=251997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-14 07:17:12.506   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:13.507   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:14.508   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:14.979  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:14.979  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:14.979  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 07:17:14.980  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:14.980  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:14.980  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:14.980  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
,10-14 07:17:14.980  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:14.980  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:14.981  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:14.981  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 07:17:14.981  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:14.981  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:14.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:14.982  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:14.982  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:14.982  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:14.982  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:14.982  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:14.982  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:14.983  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:14.983  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:14.986  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:17:14.986  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:14.986  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:14.987  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:14.991  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 07:17:14.992  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:17:14.994  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-14 07:17:14.997  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 07:17:14.997  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 07:17:14.997  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-14 07:17:14.998  5614  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 07:17:14.998  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 07:17:14.999  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 07:17:14.999  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 07:17:14.999  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:15.000  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-14 07:17:15.000  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 07:17:15.000  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 07:17:15.000  5614  5663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 07:17:15.000  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.000  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-14 07:17:15.000  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 07:17:15.000  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:15.000  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:15.000  5614  5614 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 07:17:15.000  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:17:15.001  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 07:17:15.001  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 07:17:15.001  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.001  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.004  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 07:17:15.000  4557  4557 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32937]" dev="sockfs" ino=32937 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 07:17:15.004  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.004  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:17:15.004  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:17:15.005  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:17:15.004  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:15.005  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 07:17:15.000  4557  4557 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32937]" dev="sockfs" ino=32937 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 07:17:15.005  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:15.005  5614  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-14 07:17:15.005  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:15.005  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.005  5614  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 07:17:15.005  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.005  5614  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 07:17:15.005  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-14 07:17:15.005  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
,10-14 07:17:15.005  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.006  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.006  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:15.006  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.006  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.006  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.006  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.007  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 07:17:15.007  5614  5614 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:15.008  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:15.008  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:15.008  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.008  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:15.010  5614  5660 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-14 07:17:15.010  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 07:17:15.010  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 07:17:15.010  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-14 07:17:15.010  5614  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 07:17:15.010  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:15.011  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:15.011  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:15.011  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:15.011  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:15.011  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.011  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:15.011  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:15.011  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.011  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
,10-14 07:17:15.011  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:15.011  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.011  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.011  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.012  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.013  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:17:15.013  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:15.013  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.013  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.017  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:15.018  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:15.018  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:15.018  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:15.018  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:15.018  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.018  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:15.018  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:15.018  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.018  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.018  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:15.018  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.018  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.018  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.018  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:15.019  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:17:15.020  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:15.020  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.020  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.021  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:17:15.021  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:17:15.021  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:17:15.021  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:17:15.021  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.021  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:15.021  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:17:15.021  5614  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef7fe2 not in the list
10-14 07:17:15.021  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.021  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.021  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:15.021  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.021  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:15.021  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:15.022  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:15.023  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:17:15.023  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:17:15.023  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:15.023  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bc7f73 not in the list
10-14 07:17:15.024  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-14 07:17:15.024  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 07:17:15.024  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-14 07:17:15.024  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-14 07:17:15.024  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-14 07:17:15.025  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 07:17:15.027  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-14 07:17:15.027  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-14 07:17:15.028  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-14 07:17:15.028  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-14 07:17:15.029  5614  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-14 07:17:15.029  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-14 07:17:15.029  5614  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-14 07:17:15.029  5614  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-14 07:17:15.029  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-14 07:17:15.029  5614  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-14 07:17:15.030  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-14 07:17:15.030  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-14 07:17:15.030  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-14 07:17:15.030  5614  5660 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-14 07:17:15.031  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:17:15.031  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7eff1d added. We now have 3 listener(s)
,10-14 07:17:15.031  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:17:15.033  5614  5660 D BluetoothAdapter: enable(): BT is already enabled..!
10-14 07:17:15.034   928  3788 D WifiService: setWifiEnabled: true pid=5614, uid=10077
10-14 07:17:15.034   928  3788 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 07:17:15.095  4544  4735 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-14 07:17:15.096  4544  4740 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
10-14 07:17:15.096  5614  5661 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-14 07:17:15.096  5614  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-14 07:17:15.096  5614  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,10-14 07:17:15.505  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 07:17:15.509   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:16.510   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:17.510   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 07:17:20.040  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 07:17:20.040  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13ba592 added. We now have 4 listener(s)
,10-14 07:17:20.040  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 07:17:20.053  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:20.053  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13ba592 removed from the list
,10-14 07:17:20.053  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:20.053  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:17:20.053  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:20.055  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:17:20.055  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c42b63 added. We now have 4 listener(s)
,10-14 07:17:20.056  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:17:20.059  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:20.059  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c42b63 removed from the list
10-14 07:17:20.059  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:20.060  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:20.060  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:20.064  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 07:17:20.064  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@150d360 added. We now have 4 listener(s)
10-14 07:17:20.064  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 07:17:20.068   928  5343 D WifiService: setWifiEnabled: false pid=5614, uid=10077
,10-14 07:17:20.068   928  5343 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 07:17:20.074   928  2971 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-14 07:17:20.075   928  2971 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-14 07:17:20.075   928  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 07:17:20.075   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 07:17:20.080  4544  4600 D BluetoothAdapterState: Current state: ON, message: 23
10-14 07:17:20.081  4544  4600 D BluetoothAdapterProperties: Setting state to 13
,10-14 07:17:20.081  4544  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-14 07:17:20.082  4544  4600 D BluetoothAdapterProperties: onBluetoothDisable()
,10-14 07:17:20.085  4544  4600 I BluetoothAdapterState: Entering PendingCommandState
10-14 07:17:20.086  4544  4544 D BluetoothMapService: onReceive
10-14 07:17:20.086  4544  4544 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 07:17:20.087  4544  4544 D BluetoothMapService: STATE_TURNING_OFF
10-14 07:17:20.087  4544  4544 D BluetoothMapService: MAP Service closeService in
10-14 07:17:20.087  4544  4544 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 07:17:20.087  4544  4544 D ObexServerSockets0: shutdown(block = true)
10-14 07:17:20.088  4544  4764 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-14 07:17:20.092   928  5368 D DhcpClient: Clearing IP address
10-14 07:17:20.092   509   921 D CommandListener: Clearing all IP addresses on wlan0
10-14 07:17:20.093  4544  4544 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 07:17:20.093  4544  4544 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 07:17:20.093  4544  4740 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-14 07:17:20.094  4544  4765 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 07:17:20.095  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:17:20.095  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 07:17:20.096  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.096  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:17:20.096  4544  4544 I BtOppRfcommListener: stopping Accept Thread
10-14 07:17:20.097  4544  5290 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 07:17:20.097  4544  5290 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-14 07:17:20.100   509   921 D CommandListener: Setting iface cfg
10-14 07:17:20.100  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:17:20.101  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:17:20.101  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.102  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,10-14 07:17:20.106   928   941 I ActivityManager: Start proc 5667:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-14 07:17:20.107  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:17:20.108   928  5369 D DhcpClient: Receive thread stopped
10-14 07:17:20.110  4544  4605 D BluetoothAdapterProperties: Scan Mode:20
10-14 07:17:20.110  4544  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-14 07:17:20.111  3559  5422 V NativeCrypto: Read error: ssl=0x7f70d14000: I/O error during system call, Connection timed out
,10-14 07:17:20.113  3559  5422 V NativeCrypto: SSL shutdown failed: ssl=0x7f70d14000: I/O error during system call, Broken pipe
10-14 07:17:20.114  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:17:20.114  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:17:20.115  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:20.115  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,10-14 07:17:20.116  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:17:20.116   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-14 07:17:20.116   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-14 07:17:20.116   928  3124 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-14 07:17:20.117   928  5366 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-14 07:17:20.119  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.119  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:17:20.120   928  5366 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-14 07:17:20.120  4544  4544 D HeadsetService: Received stop request...Stopping profile...
,10-14 07:17:20.120  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.120   928  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-14 07:17:20.120  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:20.122  3709  3845 W QCNEJ   : |CORE| network lost: 100
10-14 07:17:20.123  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.123  3709  3845 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-14 07:17:20.126  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.126  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:20.126   535   535 E Parcel  : Reading a NULL string not supported here.
10-14 07:17:20.127   928   928 D RttService: SCAN_AVAILABLE : 1
10-14 07:17:20.127   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:20.127   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:20.127  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.127   928  3037 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 07:17:20.127  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:20.128  3741  3770 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:20.128  4544  4544 D A2dpService: Received stop request...Stopping profile...
10-14 07:17:20.128   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:20.128  4544  4745 D A2dpStateMachine: Exit Disconnected: -1
10-14 07:17:20.129  3125  3137 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:20.129   928   928 D BluetoothA2dp: Proxy object disconnected
,10-14 07:17:20.130  4544  4544 D HidService: Received stop request...Stopping profile...
10-14 07:17:20.131  4544  4544 D HidService: Stopping Bluetooth HidService
10-14 07:17:20.131  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.131  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:20.132  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.132  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:20.132  4544  4544 D HealthService: Received stop request...Stopping profile...
10-14 07:17:20.134  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.133  4544  4544 D PanService: Received stop request...Stopping profile...
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.135  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:17:20.137  4544  4544 D BluetoothMapService: Received stop request...Stopping profile...
10-14 07:17:20.137  4544  4544 D BluetoothMapService: stop()
10-14 07:17:20.137  4544  4544 D BluetoothMapAppObserver: deinitObservers()
10-14 07:17:20.137  4544  4544 D BluetoothMapAppObserver: removeReceiver()
,10-14 07:17:20.138  3125  3125 D HeadsetProfile: Bluetooth service disconnected
10-14 07:17:20.139  4544  4544 D SapService: Received stop request...Stopping profile...
10-14 07:17:20.139  3125  3125 D BluetoothA2dp: Proxy object disconnected
10-14 07:17:20.139  4544  4544 V SapService: stop()
10-14 07:17:20.139  3125  3125 D BluetoothInputDevice: Proxy object disconnected
10-14 07:17:20.139  3125  3125 D HidProfile: Bluetooth service disconnected
,10-14 07:17:20.139  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 07:17:20.139  3125  3125 D PanProfile: Bluetooth service disconnected
10-14 07:17:20.139  3125  3125 D BluetoothMap: Proxy object disconnected
10-14 07:17:20.139  3125  3125 D MapProfile: Bluetooth service disconnected
10-14 07:17:20.140  4544  4544 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:20.140  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.140  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.140  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 07:17:20.141  4544  4544 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-14 07:17:20.141  4544  4544 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 07:17:20.141  4544  4605 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-14 07:17:20.141  4544  4735 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:20.141  4544  4735 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:20.141  4544  4735 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:20.142  4544  4544 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:20.142  4544  4605 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-14 07:17:20.142  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.142  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.142  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:20.143  4544  4605 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 07:17:20.143  4544  4735 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isTurningOff()=true
,10-14 07:17:20.143  4544  4735 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.143  4544  4735 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.143  4544  4735 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:20.143  4544  4735 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 07:17:20.143  4544  4735 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 07:17:20.143  4544  4544 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 07:17:20.143  4544  4544 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 07:17:20.143  4544  4605 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.143  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:20.143  4544  4544 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-14 07:17:20.144  4544  4605 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-14 07:17:20.144  4544  4544 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 07:17:20.144  4544  4544 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:20.144  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.144  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.144  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 07:17:20.144  4544  4544 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 07:17:20.144  4544  4544 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 07:17:20.145  4544  4544 D BluetoothMapService: MAP Service closeService in
10-14 07:17:20.145  4544  4544 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:20.145  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.145  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.145   928  2971 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-14 07:17:20.145  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:20.146  4544  4544 D BluetoothMapService: cleanup()
,10-14 07:17:20.146  4544  4544 D BluetoothMapService: MAP Service closeService in
,10-14 07:17:20.146  4544  4544 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:20.146  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.146  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.146  4544  4544 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:20.147  4544  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 07:17:20.147  4544  4600 D BluetoothAdapterProperties: Setting state to 15
10-14 07:17:20.147  4544  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 07:17:20.147  4544  4600 I BluetoothAdapterState: Entering BleOnState
10-14 07:17:20.147  3125  3137 D BluetoothMap: onBluetoothStateChange: up=false
10-14 07:17:20.148  3125  3136 D BluetoothPan: onBluetoothStateChange on: false
10-14 07:17:20.149  3125  3939 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:20.149  3125  3937 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 07:17:20.154   928  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 07:17:20.156  3741  3772 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-14 07:17:20.156  3125  3137 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 07:17:20.157   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:20.157   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 07:17:20.157   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:20.157  3125  3136 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 07:17:20.158   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:20.158  4544  4600 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 07:17:20.158  4544  4600 D BluetoothAdapterProperties: Setting state to 16
10-14 07:17:20.159  4544  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 07:17:20.160  4544  4600 D BluetoothAdapterProperties: onBleDisable
10-14 07:17:20.160  4544  4600 I BluetoothAdapterState: Entering PendingCommandState
10-14 07:17:20.160  4544  4601 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 07:17:20.161  4544  4735 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 07:17:20.161  4544  4735 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-14 07:17:20.162   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 07:17:20.161  4544  4605 D BluetoothAdapterProperties: Scan Mode:20
10-14 07:17:20.162  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.163  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.165  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.166  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.166  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.167  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:20.181  5667  5667 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-14 07:17:20.187   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 07:17:20.187   509   921 D CommandListener: Clearing all IP addresses on wlan0
10-14 07:17:20.188   509   921 D TetherController: Setting IP forward enable = 0
10-14 07:17:20.189   928  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-14 07:17:20.189   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-14 07:17:20.192   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-14 07:17:20.194  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.196  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.197  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:20.195  5261  5261 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@549b350 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-14 07:17:20.206  4941  4979 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 07:17:20.206  4941  4979 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 07:17:20.207  4941  4979 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,10-14 07:17:20.207  4941  4979 E SarControlService: no key has been found,reset the power
10-14 07:17:20.207  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-14 07:17:20.207  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 07:17:20.207  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 07:17:20.208  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:17:20.208  4991  4991 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 07:17:20.210  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 07:17:20.210  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 07:17:20.210  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 07:17:20.211  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:17:20.211  4991  4991 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 07:17:20.214  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000ea03000000000000ffffffff]
10-14 07:17:20.214  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-14 07:17:20.214  4991  5006 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-14 07:17:20.214  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:17:20.214  4941  4951 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-14 07:17:20.220  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000eb03000000000000ffffffff]
,10-14 07:17:20.221  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-14 07:17:20.221  4991  5006 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-14 07:17:20.222  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:17:20.222  4941  4952 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 07:17:20.224  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 07:17:20.230   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c27e8:true
,10-14 07:17:20.237  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:20.239   509   921 E Netd    : netlink response contains error (No such file or directory)
,10-14 07:17:20.240   509   921 D TetherController: Setting IP forward enable = 0
,10-14 07:17:20.243   928  2973 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-14 07:17:20.243   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-14 07:17:20.246   928  2971 D DhcpClient: doQuit
,10-14 07:17:20.246   928  2971 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 07:17:20.247   928  5368 D DhcpClient: onQuitting
10-14 07:17:20.247  3434  3434 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-14 07:17:20.255   928  3788 I ActivityManager: Start proc 5699:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-14 07:17:20.258  5667  5667 D LocalBluetoothProfileManager: Adding local MAP profile
,10-14 07:17:20.260  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.260  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:20.260  5667  5667 D BluetoothMap: Create BluetoothMap proxy object
10-14 07:17:20.261  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.261  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:20.264  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:20.265  3434  3434 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.264  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:20.267  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.267  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:20.270  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:20.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:20.271  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:20.271  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:20.271  3434  3434 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-14 07:17:20.273  5667  5667 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-14 07:17:20.296  5667  5667 D DockEventReceiver: finishStartingService: stopping service
,10-14 07:17:20.299   928   939 I ActivityManager: Killing 4881:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-14 07:17:20.305  3434  3434 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 07:17:20.308  5699  5699 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-14 07:17:20.315  3434  3434 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 07:17:20.365  4544  4605 I bt_hci  : shut_down
,10-14 07:17:20.369  4544  4609 D bt_hwcfg: hw_epilog_process
,10-14 07:17:20.369  4544  4609 I bt_vendor: low_power_mode_cb
,10-14 07:17:20.372  4544  4609 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-14 07:17:20.372  4544  4609 I bt_vendor: epilog_cb
10-14 07:17:20.372  4544  4609 I bt_hci  : epilog_finished_callback
,10-14 07:17:20.376  4544  4605 I bt_hci_h4: hal_close
,10-14 07:17:20.377  4544  4605 I bt_userial_vendor: device fd = 54 close
,10-14 07:17:20.419   928  2971 D wifi    : In wifi stop Hal
,10-14 07:17:20.419   928  2971 D wifi    : halHandle = 0x7f5a86f180, mVM = 0x7f76ecd140, mCls = 0x100a06
10-14 07:17:20.420  4916  4916 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-14 07:17:20.421   928  3433 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-14 07:17:20.421   928  3433 D WifiHAL : Got a signal to exit!!!
10-14 07:17:20.421   928  3433 I WifiHAL : Exit wifi_event_loop
10-14 07:17:20.421  4087  4206 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 07:17:20.422   928  2971 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-14 07:17:20.422   928  2971 E WifiHAL : Event processing terminated
,10-14 07:17:20.422   928  2971 D wifi    : In wifi cleaned up handler
10-14 07:17:20.422   928  2971 I WifiHAL : Internal cleanup completed
10-14 07:17:20.423  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:20.424  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:20.426  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:20.440   928  3433 D wifi    : set interface wlan0 flags (DOWN)
10-14 07:17:20.441   928  2971 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 07:17:20.483  4544  4601 D bt_stack_manager: event_shut_down_stack finished.
,10-14 07:17:20.484  4544  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-14 07:17:20.485  4544  4544 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 07:17:20.486  4544  4600 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-14 07:17:20.486  4544  4544 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 07:17:20.486  4544  4544 D BtGatt.GattService: stop()
10-14 07:17:20.486  4544  4544 D BtGatt.AdvertiseManager: advertise clients cleared
10-14 07:17:20.488  4544  4544 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:20.488  4544  4544 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:20.488  4544  4544 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:20.488  4544  4544 V BluetoothAdapterState: isBleTurningOff()=true
10-14 07:17:20.488  4544  4600 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 07:17:20.488  4544  4600 D BluetoothAdapterProperties: Setting state to 10
10-14 07:17:20.488  4544  4600 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 07:17:20.489   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-14 07:17:20.489  4544  4600 I BluetoothAdapterState: Entering OffState
,10-14 07:17:20.495  4544  4544 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-14 07:17:20.495  4544  4544 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 07:17:20.495  4544  4544 I BluetoothServiceJni: cleanupNative: return from cleanup
10-14 07:17:20.496  4544  4601 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-14 07:17:20.505  4544  4544 I art     : System.exit called, status: 0
,10-14 07:17:20.505  4544  4544 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 07:17:20.520  5699  5699 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.520  5699  5699 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.520  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.521  5699  5699 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.521  5699  5699 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.521  5699  5699 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.k.d(PG:583)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.521  5699  5699 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.521  5699  5699 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.521  5699  5699 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:17:20.521  5699  5699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:17:20.527  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 07:17:20.530   928   939 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
10-14 07:17:20.530   928   939 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
10-14 07:17:20.531   928   939 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
10-14 07:17:20.531   928   939 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
10-14 07:17:20.531   928   939 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,10-14 07:17:20.569   928   939 I ActivityManager: Start proc 5732:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
10-14 07:17:20.570  5667  5667 D DockEventReceiver: finishStartingService: stopping service
10-14 07:17:20.570   928  3833 W ActivityManager: Spurious death for ProcessRecord{46fc923 5732:com.android.bluetooth/1002}, curProc for 4544: null
10-14 07:17:20.572   928  3389 I ActivityManager: Killing 5396:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-14 07:17:20.643   928   945 D Tethering: InitialState.processMessage what=4
,10-14 07:17:20.646   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 07:17:20.665  5732  5732 D AdapterServiceConfig: Adding HeadsetService
10-14 07:17:20.665  5732  5732 D AdapterServiceConfig: Adding A2dpService
10-14 07:17:20.666  5732  5732 D AdapterServiceConfig: Adding HidService
10-14 07:17:20.666  5732  5732 D AdapterServiceConfig: Adding HealthService
10-14 07:17:20.666  5732  5732 D AdapterServiceConfig: Adding PanService
10-14 07:17:20.666  5732  5732 D AdapterServiceConfig: Adding GattService
10-14 07:17:20.666  5732  5732 D AdapterServiceConfig: Adding BluetoothMapService
10-14 07:17:20.666  5732  5732 D AdapterServiceConfig: Adding SapService
,10-14 07:17:20.668   928  3122 I ActivityManager: Killing 5409:com.android.chrome/u0a39 (adj 15): empty #17
,10-14 07:17:20.727  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:20.738  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 07:17:20.741  3920  3920 D SystemUpdateService: onCreate
,10-14 07:17:20.746  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 07:17:20.750  3920  5744 I SystemUpdateService: active receiver: enabled
,10-14 07:17:20.755  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 07:17:20.760  3920  5393 I iu.UploadsManager: num queued entries: 0
,10-14 07:17:20.760  3920  5393 I iu.UploadsManager: num updated entries: 0
10-14 07:17:20.761  3920  5393 I iu.SyncManager: NEXT; no task
,10-14 07:17:20.762  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 07:17:20.765  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 07:17:20.769  3920  5744 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 07:17:20.777   928  3788 I ActivityManager: Start proc 5746:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-14 07:17:20.780  3920  5744 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-14 07:17:20.780  3920  5744 I SystemUpdateService: now status is 0 (complete)
10-14 07:17:20.780  3920  5744 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 07:17:20.780  3920  5744 I SystemUpdateService: file has been verified
10-14 07:17:20.780  3920  5744 I SystemUpdateService: OTA package size = 21989297
,10-14 07:17:20.790  3920  5744 I SystemUpdateService: showing system update notification
,10-14 07:17:20.810  5746  5746 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-14 07:17:20.817  5746  5746 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 07:17:20.822  5746  5746 D SprintDMHelper: simOperator: 
,10-14 07:17:20.823  5746  5746 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 07:17:20.834   928  3788 I ActivityManager: Start proc 5758:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-14 07:17:20.845  3920  3920 D SystemUpdateService: onDestroy
10-14 07:17:20.847   928  3593 I ActivityManager: Killing 5261:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-14 07:17:20.956  4916  5772 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-14 07:17:20.968   928   938 I ActivityManager: Start proc 5773:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-14 07:17:20.970   928   938 I ActivityManager: Killing 4615:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-14 07:17:20.986  5699  5718 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-14 07:17:21.011  5773  5773 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-14 07:17:21.018   928  3833 I ActivityManager: Killing 5478:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-14 07:17:21.027   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a7b45c:true
,10-14 07:17:25.118   928  3833 D WifiService: setWifiEnabled: true pid=5614, uid=10077
10-14 07:17:25.118   928  3833 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 07:17:25.129   509   921 D SoftapController: Softap fwReload - Ok
,10-14 07:17:25.134   509   921 D CommandListener: Setting iface cfg
10-14 07:17:25.134   509   921 D CommandListener: Trying to bring down wlan0
,10-14 07:17:25.141   509   921 D CommandListener: Clearing all IP addresses on wlan0
,10-14 07:17:25.150   928  2971 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 07:17:25.712   928  2971 D wifi    : set interface wlan0 flags (UP)
10-14 07:17:25.712   928  2971 I WifiHAL : Initializing wifi
,10-14 07:17:25.712   928  2971 I WifiHAL : Creating socket
,10-14 07:17:25.718   928  2971 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-14 07:17:25.719   928  2971 D wifi    : Did set static halHandle = 0x7f5a86f180
10-14 07:17:25.719   928  2971 D wifi    : halHandle = 0x7f5a86f180, mVM = 0x7f76ecd140, mCls = 0x20191a
,10-14 07:17:25.719   928  2971 D wifi    : array field set
10-14 07:17:25.719   928  2971 I WifiNative-HAL: interface[0] = wlan0
,10-14 07:17:25.720   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-14 07:17:25.721   928  5790 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546979639680
10-14 07:17:25.721   928  5790 D wifi    : waitForHalEvents called, vm = 0x7f76ecd140, obj = 0x20191a, env = 0x7f5b77f7c0
,10-14 07:17:25.806  5791  5791 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 07:17:25.827  5791  5791 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 07:17:25.827   928  2971 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-14 07:17:25.831  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:25.832  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:25.834  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:25.854  5791  5791 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 07:17:25.854  5791  5791 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 07:17:25.869   928  2971 D WifiConfigStore: Loading config and enabling all networks 
,10-14 07:17:25.870  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:25.870  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:25.870  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:25.870  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:25.872  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:25.872  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:17:25.872  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:25.872  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:25.873  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:25.873  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:25.873  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:25.873  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:25.878   928  2971 D WifiConfigStore: loaded 0 passpoint configs
,10-14 07:17:25.878   928  2971 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 07:17:25.879   928  2971 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-14 07:17:25.879   928  2971 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-14 07:17:25.880   928  2971 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-14 07:17:25.880   928  2971 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 07:17:25.881   928  2971 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 07:17:25.881   928  2971 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 07:17:25.884  4916  4916 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-14 07:17:25.885   928  2971 D WifiNative-HAL: Setting external_sim to 1
10-14 07:17:25.885   928  2971 D wifi    : setting dfs flag to true, 0x7f59f48ec0
10-14 07:17:25.886   928  2971 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 07:17:25.886   928  2971 D wifi    : setting scan oui 0x7f59f48ec0
10-14 07:17:25.886   928  2971 D WifiHAL : Sending mac address OUI
,10-14 07:17:25.890   928  2971 E native  : do suspend false
,10-14 07:17:25.897   928  2971 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-14 07:17:25.897   928   928 D RttService: SCAN_AVAILABLE : 3
10-14 07:17:25.897   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-14 07:17:25.898   928  3037 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-14 07:17:25.899   509   921 D CommandListener: Setting iface cfg
,10-14 07:17:25.903   928  2959 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-14 07:17:25.903   928  2959 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 07:17:25.912   928  2959 D WifiNative-HAL: p2pGetDeviceAddress
10-14 07:17:25.913   928  2959 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 07:17:25.918   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267290 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-14 07:17:29.092  5791  5791 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:17:29.099  5791  5791 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:17:29.105  5791  5791 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:17:29.109  5791  5791 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:17:29.157   928  2971 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 07:17:29.158   928  2971 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-14 07:17:29.159   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 07:17:29.176   928  2971 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-14 07:17:29.215   928  2971 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 07:17:29.218  5791  5791 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 07:17:29.642  5791  5791 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 07:17:29.678  5791  5791 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 07:17:29.680  5791  5791 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 07:17:29.689   928  2971 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 07:17:29.689   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 07:17:29.689   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-14 07:17:29.711   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 07:17:29.727   509   921 D CommandListener: Setting iface cfg
,10-14 07:17:29.735   928  2971 D WifiStateMachine: Start Dhcp Watchdog 2
,10-14 07:17:29.743   928  5798 D DhcpClient: Receive thread started
,10-14 07:17:29.751   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 07:17:29.751   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
10-14 07:17:29.751   928  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-14 07:17:29.842   928  2971 E native  : do suspend false
,10-14 07:17:29.865   928  5797 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 07:17:29.883   928  5798 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,10-14 07:17:29.884   928  5797 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
10-14 07:17:29.886   928  5797 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 07:17:29.900   928  5798 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 07:17:29.901   928  5797 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 07:17:29.904   509   921 D CommandListener: Setting iface cfg
10-14 07:17:29.910   928  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 07:17:29.915   928  5797 D DhcpClient: Scheduling renewal in 86399s
,10-14 07:17:29.929   928  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-14 07:17:29.932   928  2971 D WifiConfigStore: No blacklist allowed without epno enabled
10-14 07:17:29.933   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-14 07:17:29.934   928  2973 D ConnectivityService: Adding iface wlan0 to network 101
10-14 07:17:29.941   928  2971 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-14 07:17:29.992   928  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-14 07:17:29.992   928  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-14 07:17:29.999   928  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-14 07:17:30.002   928  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-14 07:17:30.003   928  2973 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-14 07:17:30.010   928  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 07:17:30.015   928  2973 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-14 07:17:30.016   928  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-14 07:17:30.016   928  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-14 07:17:30.016   928  2973 D ConnectivityService:    accepting network in place of null
10-14 07:17:30.016   928  2971 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-14 07:17:30.016   928  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 07:17:30.016   928  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 07:17:30.029   928  5796 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271401, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 07:17:30.042   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 07:17:30.065   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 07:17:30.068   928  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-14 07:17:30.068  3709  3845 W QCNEJ   : |CORE| network available: 101
10-14 07:17:30.068   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 07:17:30.069   928  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-14 07:17:30.071   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-14 07:17:30.072  3709  3845 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-14 07:17:30.073  3709  3845 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-14 07:17:30.074  3709  3845 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-14 07:17:30.076  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:17:30.077  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:17:30.077  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.077  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,10-14 07:17:30.079  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:17:30.079  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:17:30.079  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.079  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,10-14 07:17:30.083  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:17:30.083  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:17:30.083  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.083  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:17:30.086  4941  4979 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 07:17:30.086  4941  4979 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 07:17:30.086  4941  4979 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-14 07:17:30.086  4941  4979 E SarControlService: no key has been found,reset the power
10-14 07:17:30.086  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 07:17:30.086  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 07:17:30.086  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 07:17:30.087  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:17:30.087  4991  4991 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 07:17:30.088  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 07:17:30.089  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 07:17:30.089  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 07:17:30.089  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:17:30.089  4991  4991 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 07:17:30.092  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 07:17:30.095  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000ec03000000000000ffffffff]
10-14 07:17:30.095  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 07:17:30.095  4991  5006 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-14 07:17:30.095  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:17:30.095  4941  4951 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 07:17:30.097  3920  3920 D SystemUpdateService: onCreate
10-14 07:17:30.098  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000ed03000000000000ffffffff]
10-14 07:17:30.098  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 07:17:30.098  4991  5006 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-14 07:17:30.099  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:17:30.099  4941  4952 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 07:17:30.102  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-14 07:17:30.107   928  5795 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.138,2a00:1450:400c:c0c::8b
10-14 07:17:30.114  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-14 07:17:30.120  3920  5808 I SystemUpdateService: active receiver: enabled
10-14 07:17:30.122  3920  5393 I iu.UploadsManager: num queued entries: 0
10-14 07:17:30.123  3920  5393 I iu.UploadsManager: num updated entries: 0
10-14 07:17:30.124  3920  5393 I iu.SyncManager: NEXT; no task
10-14 07:17:30.126   928  3833 D WifiService: setWifiEnabled: false pid=5614, uid=10077
10-14 07:17:30.126   928  3833 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-14 07:17:30.127   928  2971 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-14 07:17:30.127   928  2971 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-14 07:17:30.127   928  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 07:17:30.127   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 07:17:30.130  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-14 07:17:30.132  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-14 07:17:30.134  5746  5746 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-14 07:17:30.135   928  5797 D DhcpClient: Clearing IP address
10-14 07:17:30.136   509   921 D CommandListener: Clearing all IP addresses on wlan0
10-14 07:17:30.137   509   921 D CommandListener: Setting iface cfg
10-14 07:17:30.139  5746  5746 D SprintDMHelper: simOperator: 
10-14 07:17:30.139  5746  5746 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-14 07:17:30.140   928  5795 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400c:c0c::8b (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-14 07:17:30.141   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,10-14 07:17:30.147   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-14 07:17:30.147   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-14 07:17:30.149  3920  5808 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-14 07:17:30.150   535   535 E Parcel  : Reading a NULL string not supported here.
10-14 07:17:30.151   928  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-14 07:17:30.155  3709  3845 W QCNEJ   : |CORE| network lost: 101
10-14 07:17:30.156  3709  3845 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-14 07:17:30.156   928   928 D RttService: SCAN_AVAILABLE : 1
10-14 07:17:30.156   928  3037 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 07:17:30.157   928  5798 D DhcpClient: Receive thread stopped
10-14 07:17:30.160   928  2971 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-14 07:17:30.161  3920  5808 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-14 07:17:30.161  3920  5808 I SystemUpdateService: now status is 0 (complete)
,10-14 07:17:30.161  3920  5808 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 07:17:30.161  3920  5808 I SystemUpdateService: file has been verified
10-14 07:17:30.161  3920  5808 I SystemUpdateService: OTA package size = 21989297
10-14 07:17:30.164   928  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 07:17:30.180  3920  5808 I SystemUpdateService: showing system update notification
,10-14 07:17:30.181   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 07:17:30.191  3920  3920 D SystemUpdateService: onDestroy
,10-14 07:17:30.205   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 07:17:30.206   928  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-14 07:17:30.206   509   921 D CommandListener: Clearing all IP addresses on wlan0
10-14 07:17:30.206   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-14 07:17:30.208   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-14 07:17:30.212  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:30.212  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:17:30.212  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.212  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:30.213  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:30.213  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:30.213  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.213  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:30.215  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:30.215  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:30.215  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:30.215  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:30.221  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 07:17:30.222  4941  4979 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-14 07:17:30.223  4941  4979 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 07:17:30.223  4941  4979 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-14 07:17:30.223  4941  4979 E SarControlService: no key has been found,reset the power
10-14 07:17:30.223  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 07:17:30.223  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 07:17:30.223  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 07:17:30.224  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:17:30.224  4991  4991 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 07:17:30.225  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 07:17:30.226  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 07:17:30.226  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 07:17:30.226  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:17:30.226  4991  4991 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-14 07:17:30.229  3920  3920 D SystemUpdateService: onCreate
,10-14 07:17:30.231  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000ee03000000000000ffffffff]
10-14 07:17:30.232  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-14 07:17:30.232  4991  5006 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,10-14 07:17:30.232  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:17:30.232  4941  4952 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-14 07:17:30.235  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 07:17:30.240  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000ef03000000000000ffffffff]
10-14 07:17:30.240  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-14 07:17:30.240  4991  5006 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-14 07:17:30.241  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:17:30.241  4941  4951 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 07:17:30.242  3920  5822 I SystemUpdateService: active receiver: enabled
,10-14 07:17:30.244  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 07:17:30.250  3920  5393 I iu.UploadsManager: num queued entries: 0
,10-14 07:17:30.250  3920  5393 I iu.UploadsManager: num updated entries: 0
10-14 07:17:30.251  3920  5393 I iu.SyncManager: NEXT; no task
,10-14 07:17:30.253  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 07:17:30.255  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 07:17:30.256  5746  5746 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 07:17:30.259   509   921 E Netd    : netlink response contains error (No such file or directory)
,10-14 07:17:30.260  5746  5746 D SprintDMHelper: simOperator: 
10-14 07:17:30.260  5746  5746 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-14 07:17:30.260   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-14 07:17:30.262   928  2971 D DhcpClient: doQuit
10-14 07:17:30.262   928  2971 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 07:17:30.262   928  5797 D DhcpClient: onQuitting
10-14 07:17:30.263  5791  5791 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-14 07:17:30.263  3920  5822 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 07:17:30.269  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:30.269  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:30.269  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:30.269  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:30.270  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.270  3920  5822 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:30.270  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:30.270  3920  5822 I SystemUpdateService: now status is 0 (complete)
10-14 07:17:30.270  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.270  3920  5822 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 07:17:30.270  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:30.270  3920  5822 I SystemUpdateService: file has been verified
,10-14 07:17:30.271  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:30.271  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:30.271  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:30.271  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:30.274  5791  5791 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-14 07:17:30.277  5791  5791 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-14 07:17:30.278  3920  5822 I SystemUpdateService: OTA package size = 21989297
,10-14 07:17:30.293  3920  5822 I SystemUpdateService: showing system update notification
,10-14 07:17:30.297  5791  5791 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 07:17:30.300  3920  3920 D SystemUpdateService: onDestroy
,10-14 07:17:30.305  5791  5791 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 07:17:30.407  4916  4916 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-14 07:17:30.407   928  2971 D wifi    : In wifi stop Hal
10-14 07:17:30.407   928  2971 D wifi    : halHandle = 0x7f5a86f180, mVM = 0x7f76ecd140, mCls = 0x20191a
10-14 07:17:30.407   928  5790 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-14 07:17:30.407   928  5790 D WifiHAL : Got a signal to exit!!!
,10-14 07:17:30.407   928  5790 I WifiHAL : Exit wifi_event_loop
10-14 07:17:30.408   928  2971 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-14 07:17:30.409   928  2971 E WifiHAL : Event processing terminated
10-14 07:17:30.409   928  2971 D wifi    : In wifi cleaned up handler
10-14 07:17:30.409   928  2971 I WifiHAL : Internal cleanup completed
10-14 07:17:30.411  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:30.412  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:30.413  4087  4206 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 07:17:30.414  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:30.432   928  5790 D wifi    : set interface wlan0 flags (DOWN)
10-14 07:17:30.432   928  2971 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 07:17:30.639   928   945 D Tethering: InitialState.processMessage what=4
,10-14 07:17:30.646   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 07:17:31.069   928  2973 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-14 07:17:32.513   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:33.514   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:34.516   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:35.164   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8b95352:true
,10-14 07:17:35.165  5732  5732 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 07:17:35.171  5732  5732 I bt_bluedroid: init
,10-14 07:17:35.172  5732  5829 I BluetoothAdapterState: Entering OffState
,10-14 07:17:35.175  5732  5830 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 07:17:35.176  5732  5830 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 07:17:35.176  5732  5830 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-14 07:17:35.176  5732  5830 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 07:17:35.177  5732  5732 I bt_bluedroid: get_profile_interface socket
,10-14 07:17:35.181  5732  5732 I bt_bluedroid: get_profile_interface sdp
,10-14 07:17:35.181  5732  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 07:17:35.184  5732  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 07:17:35.191  5732  5743 I bt_bluedroid: config_hci_snoop_log
,10-14 07:17:35.193   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-14 07:17:35.200  5732  5829 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 07:17:35.201  5732  5829 D BluetoothAdapterProperties: Setting state to 14
10-14 07:17:35.201  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 07:17:35.203  5732  5829 D BluetoothBondStateMachine: make
,10-14 07:17:35.206  5732  5834 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 07:17:35.210  5732  5829 I BluetoothAdapterState: Entering PendingCommandState
,10-14 07:17:35.212  5732  5732 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 07:17:35.216  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:35.217  5732  5732 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-14 07:17:35.217  5732  5732 D BtGatt.GattService: Received start request. Starting profile...
10-14 07:17:35.218  5732  5732 D BtGatt.GattService: start()
10-14 07:17:35.218  5732  5732 I bt_bluedroid: get_profile_interface gatt
,10-14 07:17:35.219  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:35.219  5732  5732 D BtGatt.AdvertiseManager: advertise manager created
,10-14 07:17:35.227  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:35.227  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:35.227  5732  5732 V BluetoothAdapterState: isBleTurningOn()=true
,10-14 07:17:35.227  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:35.228  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 07:17:35.230  5732  5829 I bt_bluedroid: bt_bluedroid
,10-14 07:17:35.231  5732  5830 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-14 07:17:35.231  5732  5830 I bt_hci  : start_up
,10-14 07:17:35.239  5732  5830 I bt_vendor: alloc value 0xf3df8871
,10-14 07:17:35.239  5732  5830 I bt_vendor: init
10-14 07:17:35.239  5732  5830 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 07:17:35.240  5732  5830 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 07:17:35.352  5732  5830 D bt_hci  : start_up starting async portion
,10-14 07:17:35.353  5732  5837 I bt_hci  : event_finish_startup
10-14 07:17:35.353  5732  5837 I bt_hci_h4: hal_open
10-14 07:17:35.353  5732  5837 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-14 07:17:35.350  5838  5838 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 07:17:35.356  5732  5837 I bt_userial_vendor: device fd = 54 open
,10-14 07:17:35.370  5732  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 07:17:35.372  5732  5837 D bt_hwcfg: Chipset BCM4358A3
,10-14 07:17:35.373  5732  5837 D bt_hwcfg: Target name = [BCM4358A3]
10-14 07:17:35.373  5732  5837 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 07:17:35.517   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:35.766  5732  5837 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-14 07:17:35.766  5732  5837 D bt_hwcfg: Settlement delay -- 100 ms
10-14 07:17:35.766  5732  5837 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 07:17:35.901  5732  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-14 07:17:35.901  5732  5837 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-14 07:17:35.903  5732  5837 I bt_hwcfg: vendor lib fwcfg completed
10-14 07:17:35.903  5732  5837 I bt_vendor: firmware callback
10-14 07:17:35.903  5732  5837 I bt_hci  : firmware_config_callback
,10-14 07:17:35.912  5732  5840 I bt_btu  : btu_task pending for preload complete event
,10-14 07:17:35.913  5732  5840 I bt_btu_task: Bluetooth chip preload is complete
10-14 07:17:35.913  5732  5840 I bt_btu  : btu_task received preload complete event
,10-14 07:17:35.920  5732  5840 I         : BTE_InitTraceLevels -- TRC_HCI
,10-14 07:17:35.920  5732  5840 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-14 07:17:35.920  5732  5840 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 07:17:35.920  5732  5840 I         : BTE_InitTraceLevels -- TRC_AVDT
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_A2D
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_BNEP
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_BTM
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_PAN
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_SDP
10-14 07:17:35.921  5732  5840 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 07:17:35.922  5732  5840 I         : BTE_InitTraceLevels -- TRC_SMP
10-14 07:17:35.922  5732  5840 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-14 07:17:35.922  5732  5840 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 07:17:36.002  5732  5840 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d76549
,10-14 07:17:36.003  5732  5840 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d76549 
,10-14 07:17:36.022  5732  5833 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 07:17:36.023  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 07:17:36.024  5732  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 07:17:36.026  5732  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
10-14 07:17:36.029  5732  5833 D BluetoothAdapterProperties: Scan Mode:20
,10-14 07:17:36.029  5732  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-14 07:17:36.030  5732  5833 D bt_hci  : do_postload posting postload work item
10-14 07:17:36.030  5732  5837 I bt_hci  : event_postload
10-14 07:17:36.030  5732  5837 I bt_vendor: sco_config_cb
10-14 07:17:36.030  5732  5837 I bt_hci  : sco_config_callback postload finished.
10-14 07:17:36.035  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:36.038  5732  5833 D bt_bte_conf: Device ID record 1 : primary
,10-14 07:17:36.038  5732  5833 D bt_bte_conf:   vendorId            = 000f
10-14 07:17:36.039  5732  5833 D bt_bte_conf:   vendorIdSource      = 0001
10-14 07:17:36.039  5732  5833 D bt_bte_conf:   product             = 1200
10-14 07:17:36.039  5732  5833 D bt_bte_conf:   version             = 1436
10-14 07:17:36.039  5732  5833 D bt_bte_conf:   clientExecutableURL = 
,10-14 07:17:36.039  5732  5833 D bt_bte_conf:   serviceDescription  = 
10-14 07:17:36.039  5732  5833 D bt_bte_conf:   documentationURL    = 
10-14 07:17:36.039  5732  5833 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 07:17:36.039  5732  5830 D bt_stack_manager: event_start_up_stack finished
,10-14 07:17:36.040  5732  5837 I bt_vendor: low_power_mode_cb
10-14 07:17:36.040  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:36.040  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 07:17:36.041  5732  5829 D BluetoothAdapterProperties: Setting state to 15
10-14 07:17:36.041  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-14 07:17:36.045  5732  5829 I BluetoothAdapterState: Entering BleOnState
,10-14 07:17:36.046  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:36.049  5732  5829 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-14 07:17:36.049  5732  5829 D BluetoothAdapterProperties: Setting state to 11
10-14 07:17:36.049  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-14 07:17:36.054  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:36.055  5732  5732 D HeadsetService: Received start request. Starting profile...
10-14 07:17:36.058  5732  5732 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 07:17:36.058  5732  5732 D HeadsetStateMachine: make
,10-14 07:17:36.058  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:36.061  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:36.064  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:36.070  5732  5732 D HeadsetStateMachine: max_hf_connections = 1
10-14 07:17:36.071  5732  5732 I bt_bluedroid: get_profile_interface handsfree
10-14 07:17:36.071  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 07:17:36.071  5732  5833 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,10-14 07:17:36.074  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:36.075  5732  5732 D A2dpService: Received start request. Starting profile...
10-14 07:17:36.075  5732  5829 I BluetoothAdapterState: Entering PendingCommandState
,10-14 07:17:36.076  5732  5732 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-14 07:17:36.076  5732  5732 I bt_bluedroid: get_profile_interface avrcp
,10-14 07:17:36.083  5732  5732 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 07:17:36.083  5732  5732 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 07:17:36.083  5732  5732 D A2dpStateMachine: make
10-14 07:17:36.085  5732  5732 I bt_bluedroid: get_profile_interface a2dp
,10-14 07:17:36.085  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-14 07:17:36.087  5732  5848 D A2dpStateMachine: Enter Disconnected: -2
,10-14 07:17:36.087  5732  5732 I BluetoothHidServiceJni: classInitNative: succeeds
10-14 07:17:36.088  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:36.089  5732  5732 D HidService: Received start request. Starting profile...
,10-14 07:17:36.090  5732  5732 I bt_bluedroid: get_profile_interface hidhost
10-14 07:17:36.090  5732  5732 D HidService: setHidService(): set to: null
10-14 07:17:36.090  5732  5833 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d5756d
10-14 07:17:36.091  5667  5667 D BluetoothInputDevice: Proxy object connected
10-14 07:17:36.092  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-14 07:17:36.092  5667  5667 D HidProfile: Bluetooth service connected
,10-14 07:17:36.092  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 07:17:36.093  5732  5732 I BluetoothHealthServiceJni: classInitNative: succeeds
10-14 07:17:36.093  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:36.094  5732  5732 D HealthService: Received start request. Starting profile...
10-14 07:17:36.096  5732  5732 I bt_bluedroid: get_profile_interface health
10-14 07:17:36.097  5732  5732 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-14 07:17:36.097  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:36.099  5667  5667 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 07:17:36.099  5732  5732 D PanService: Received start request. Starting profile...
,10-14 07:17:36.099  5732  5732 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 07:17:36.099  5732  5732 I bt_bluedroid: get_profile_interface pan
10-14 07:17:36.099  5667  5667 D PanProfile: Bluetooth service connected
10-14 07:17:36.100  5732  5833 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-14 07:17:36.103  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:36.104  5667  5667 D BluetoothMap: Proxy object connected
10-14 07:17:36.106  5667  5667 D MapProfile: Bluetooth service connected
10-14 07:17:36.106  5667  5667 D BluetoothMap: getConnectedDevices()
10-14 07:17:36.106  5732  5732 D BluetoothMapService: Received start request. Starting profile...
10-14 07:17:36.106  5732  5732 D BluetoothMapService: start()
10-14 07:17:36.107  5667  5667 D BluetoothMap: Bluetooth is Not enabled
,10-14 07:17:36.109  5732  5732 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-14 07:17:36.110  5732  5732 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 07:17:36.110  5732  5732 D BluetoothMapAppObserver: createReceiver()
10-14 07:17:36.111  5732  5732 D BluetoothMapAppObserver: initObservers()
10-14 07:17:36.112  5732  5732 D BluetoothMapAppObserver: getEnabledAccountItems()
10-14 07:17:36.116  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:36.117  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.117  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:36.117  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:36.118  5732  5732 V SapService: SapBinder()
10-14 07:17:36.118  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:36.119  5732  5732 D SapService: Received start request. Starting profile...
10-14 07:17:36.119  5732  5732 V SapService: start()
,10-14 07:17:36.121  5732  5732 V BluetoothAdapterState: isTurningOff()=false
,10-14 07:17:36.121  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.121  5732  5846 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 07:17:36.121  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:36.121  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:36.121  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:36.121  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.122  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:36.122  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 07:17:36.122  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:36.122  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.122  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:36.122  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isTurningOff()=false
,10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:36.123  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:36.124  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:36.124  5732  5732 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:36.124  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 07:17:36.124  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 07:17:36.124  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 07:17:36.124  5732  5829 D BluetoothAdapterProperties: ScanMode =  20
10-14 07:17:36.125  5732  5829 D BluetoothAdapterProperties: State =  11
10-14 07:17:36.125  5732  5829 D BluetoothAdapterProperties: Setting state to 12
10-14 07:17:36.125  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 07:17:36.125  5732  5829 I BluetoothAdapterState: Entering OnState
,10-14 07:17:36.126  3125  3939 D BluetoothMap: onBluetoothStateChange: up=true
,10-14 07:17:36.126  5732  5833 D BluetoothAdapterProperties: Scan Mode:21
10-14 07:17:36.127  5732  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 07:17:36.127  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-14 07:17:36.128  5667  5681 D BluetoothPbap: onBluetoothStateChange: up=true
,10-14 07:17:36.130  5667  5679 D BluetoothPan: onBluetoothStateChange on: true
10-14 07:17:36.130  3125  3937 D BluetoothPan: onBluetoothStateChange on: true
10-14 07:17:36.130  3125  3125 D BluetoothMap: Proxy object connected
10-14 07:17:36.130  3125  3125 D MapProfile: Bluetooth service connected
10-14 07:17:36.130  3125  3125 D BluetoothMap: getConnectedDevices()
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:36.130  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:36.132  3125  3137 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:36.133  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 07:17:36.133  3125  3939 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 07:17:36.133  3125  3125 D PanProfile: Bluetooth service connected
,10-14 07:17:36.133  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:36.135  3741  4002 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 07:17:36.135  3125  3937 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-14 07:17:36.135  3125  3125 D BluetoothA2dp: Proxy object connected
10-14 07:17:36.137  5732  5732 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:36.137  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:36.137   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 07:17:36.138   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-14 07:17:36.138  5732  5732 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-14 07:17:36.139   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:36.139  3125  3125 D BluetoothInputDevice: Proxy object connected
10-14 07:17:36.139   928   928 D BluetoothA2dp: Proxy object connected
10-14 07:17:36.139  3125  3125 D HidProfile: Bluetooth service connected
10-14 07:17:36.139  3125  3137 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 07:17:36.140  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:36.140   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:36.141  5667  5681 D BluetoothMap: onBluetoothStateChange: up=true
10-14 07:17:36.141  5667  5679 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 07:17:36.141  5732  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 07:17:36.142   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 07:17:36.145  5667  5667 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:36.145  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:36.147  5732  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 07:17:36.148  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:36.148  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 07:17:36.148  5732  5732 D ObexServerSockets: Succeed to create listening sockets 
10-14 07:17:36.148  5732  5732 D ObexServerSockets0: startAccept()
10-14 07:17:36.148  5732  5732 D ObexServerSockets0: prepareForNewConnect()
10-14 07:17:36.150  5667  5667 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-14 07:17:36.150  5732  5732 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-14 07:17:36.150  5732  5732 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 07:17:36.151  5732  5856 D ObexServerSockets0: Accepting socket connection...
10-14 07:17:36.151  5732  5857 D ObexServerSockets0: Accepting socket connection...
10-14 07:17:36.151  5732  5732 D BluetoothMapService: onReceive
10-14 07:17:36.151  5732  5732 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 07:17:36.151  5732  5732 D BluetoothMapService: STATE_ON
10-14 07:17:36.152  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:36.154  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:36.156  5732  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 07:17:36.156  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:36.158  5732  5858 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-14 07:17:36.158  5732  5858 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-14 07:17:36.159  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 07:17:36.162  5667  5667 D BluetoothA2dp: Proxy object connected
,10-14 07:17:36.166  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:36.170  5667  5667 D DockEventReceiver: finishStartingService: stopping service
,10-14 07:17:36.173  3125  3125 D BluetoothPbap: Proxy object connected
10-14 07:17:36.173  5667  5667 D BluetoothPbap: Proxy object connected
10-14 07:17:36.173  3125  3125 D PbapServerProfile: Bluetooth service connected
10-14 07:17:36.174  5667  5667 D PbapServerProfile: Bluetooth service connected
,10-14 07:17:36.179  5732  5732 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 07:17:36.179  5732  5732 D ObexServerSockets0: prepareForNewConnect()
,10-14 07:17:36.183  5732  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 07:17:36.194  5732  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 07:17:36.195  5732  5866 I BtOppRfcommListener: Accept thread started.
,10-14 07:17:36.234   928   928 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.234   928   928 D BluetoothHeadset: Proxy object connected
10-14 07:17:36.234  3741  3772 D BluetoothHeadset: Proxy object connected
10-14 07:17:36.235   928   928 D BluetoothHeadset: Proxy object connected
10-14 07:17:36.235  3125  3939 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.235  3125  3125 D HeadsetProfile: Bluetooth service connected
10-14 07:17:36.235  3741  3770 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.238   928   945 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.239   928   945 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.240   928   945 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.255  5667  5681 D BluetoothHeadset: Proxy object connected
,10-14 07:17:36.258  5667  5667 D HeadsetProfile: Bluetooth service connected
,10-14 07:17:36.518   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:37.518   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 07:17:38.023   928  2973 D ConnectivityService: handlePromptUnvalidated 101
,10-14 07:17:40.141  5732  5829 D BluetoothAdapterState: Current state: ON, message: 23
,10-14 07:17:40.141  5732  5829 D BluetoothAdapterProperties: Setting state to 13
10-14 07:17:40.141  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-14 07:17:40.142  5732  5829 D BluetoothAdapterProperties: onBluetoothDisable()
,10-14 07:17:40.148  5732  5829 I BluetoothAdapterState: Entering PendingCommandState
,10-14 07:17:40.152  5732  5732 D BluetoothMapService: onReceive
,10-14 07:17:40.152  5732  5732 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-14 07:17:40.152  5732  5732 D BluetoothMapService: STATE_TURNING_OFF
,10-14 07:17:40.152  5732  5732 D BluetoothMapService: MAP Service closeService in
10-14 07:17:40.152  5732  5732 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 07:17:40.153  5732  5732 D ObexServerSockets0: shutdown(block = true)
10-14 07:17:40.153  5732  5732 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-14 07:17:40.153  5732  5856 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-14 07:17:40.153  5732  5732 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 07:17:40.154  5732  5842 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-14 07:17:40.154  5732  5857 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 07:17:40.157  5732  5833 D BluetoothAdapterProperties: Scan Mode:20
10-14 07:17:40.157  5732  5732 I BtOppRfcommListener: stopping Accept Thread
,10-14 07:17:40.157  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-14 07:17:40.158  5732  5866 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 07:17:40.159  5732  5866 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-14 07:17:40.160  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 07:17:40.160  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:40.160  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:40.161  5732  5732 D HeadsetService: Received stop request...Stopping profile...
10-14 07:17:40.162  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:40.162  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:40.165  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:40.165  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:40.166  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:40.166  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:40.167  5667  5681 D BluetoothHeadset: Proxy object disconnected
,10-14 07:17:40.167   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:40.167   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:40.167  3741  4002 D BluetoothHeadset: Proxy object disconnected
,10-14 07:17:40.168   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:40.168  3125  3137 D BluetoothHeadset: Proxy object disconnected
10-14 07:17:40.170  5732  5732 D A2dpService: Received stop request...Stopping profile...
10-14 07:17:40.171  5732  5848 D A2dpStateMachine: Exit Disconnected: -1
,10-14 07:17:40.171  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:40.172  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:40.173  5614  5614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 07:17:40.173  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:40.174   928   928 D BluetoothA2dp: Proxy object disconnected
10-14 07:17:40.174  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:40.175  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.175  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.175  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:40.175  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 07:17:40.176  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.177  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.177  5732  5732 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 07:17:40.177  5732  5732 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 07:17:40.177  5732  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:40.177  5732  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:40.177  5732  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:40.178  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-14 07:17:40.178  5732  5833 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-14 07:17:40.179  5732  5732 D HidService: Received stop request...Stopping profile...
10-14 07:17:40.179  5732  5732 D HidService: Stopping Bluetooth HidService
10-14 07:17:40.181  3125  3125 D HeadsetProfile: Bluetooth service disconnected
10-14 07:17:40.181  3125  3125 D BluetoothA2dp: Proxy object disconnected
10-14 07:17:40.182  3125  3125 D BluetoothInputDevice: Proxy object disconnected
10-14 07:17:40.182  3125  3125 D HidProfile: Bluetooth service disconnected
10-14 07:17:40.182  5732  5732 D HealthService: Received stop request...Stopping profile...
10-14 07:17:40.183  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.183  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.183  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 07:17:40.183  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:40.185  5667  5667 D DockEventReceiver: finishStartingService: stopping service
10-14 07:17:40.186  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 07:17:40.186  5732  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:40.186  5732  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:40.186  5732  5840 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 07:17:40.186  5732  5840 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 07:17:40.186  5732  5840 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 07:17:40.186  5732  5840 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 07:17:40.186  5732  5732 D PanService: Received stop request...Stopping profile...
10-14 07:17:40.187  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:40.187  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 07:17:40.188  3125  3125 D PanProfile: Bluetooth service disconnected
10-14 07:17:40.188  5732  5732 D BluetoothMapService: Received stop request...Stopping profile...
10-14 07:17:40.189  5732  5732 D BluetoothMapService: stop()
10-14 07:17:40.189  5667  5667 D HeadsetProfile: Bluetooth service disconnected
10-14 07:17:40.189  5732  5732 D BluetoothMapAppObserver: deinitObservers()
10-14 07:17:40.189  5732  5732 D BluetoothMapAppObserver: removeReceiver()
10-14 07:17:40.189  5667  5667 D BluetoothA2dp: Proxy object disconnected
10-14 07:17:40.189  5667  5667 D BluetoothInputDevice: Proxy object disconnected
10-14 07:17:40.190  5667  5667 D HidProfile: Bluetooth service disconnected
10-14 07:17:40.190  5667  5667 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 07:17:40.190  5667  5667 D PanProfile: Bluetooth service disconnected
10-14 07:17:40.191  3125  3125 D BluetoothMap: Proxy object disconnected
10-14 07:17:40.191  3125  3125 D MapProfile: Bluetooth service disconnected
10-14 07:17:40.192  5667  5667 D BluetoothMap: Proxy object disconnected
10-14 07:17:40.192  5732  5732 D SapService: Received stop request...Stopping profile...
10-14 07:17:40.192  5667  5667 D MapProfile: Bluetooth service disconnected
10-14 07:17:40.192  5732  5732 V SapService: stop()
10-14 07:17:40.194  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.194  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.194  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 07:17:40.194  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:40.194  5732  5732 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 07:17:40.194  5732  5732 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 07:17:40.194  5732  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 07:17:40.195  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.195  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.195  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:40.195  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:40.195  5732  5732 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-14 07:17:40.195  5732  5833 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-14 07:17:40.195  5732  5732 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 07:17:40.197  5667  5667 D BluetoothPbap: Proxy object disconnected
10-14 07:17:40.197  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.197  5667  5667 D PbapServerProfile: Bluetooth service disconnected
10-14 07:17:40.197  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.197  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:40.197  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:40.197  5732  5732 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 07:17:40.197  5732  5732 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 07:17:40.198  3125  3125 D BluetoothPbap: Proxy object disconnected
10-14 07:17:40.198  3125  3125 D PbapServerProfile: Bluetooth service disconnected
10-14 07:17:40.198  5732  5732 D BluetoothMapService: MAP Service closeService in
10-14 07:17:40.198  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.198  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.199  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:40.199  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:40.199  5732  5732 D BluetoothMapService: cleanup()
10-14 07:17:40.199  5732  5732 D BluetoothMapService: MAP Service closeService in
10-14 07:17:40.199  5732  5732 V BluetoothAdapterState: isTurningOff()=true
10-14 07:17:40.199  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.199  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:40.199  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:40.199  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 07:17:40.199  5732  5829 D BluetoothAdapterProperties: Setting state to 15
10-14 07:17:40.199  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 07:17:40.200  5732  5829 I BluetoothAdapterState: Entering BleOnState
10-14 07:17:40.200  3125  3939 D BluetoothMap: onBluetoothStateChange: up=false
10-14 07:17:40.201  5667  5679 D BluetoothPbap: onBluetoothStateChange: up=false
,10-14 07:17:40.203  5667  5681 D BluetoothPan: onBluetoothStateChange on: false
,10-14 07:17:40.205  3125  3136 D BluetoothPan: onBluetoothStateChange on: false
10-14 07:17:40.206  3125  3937 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:40.215  3125  3939 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 07:17:40.216  3741  3772 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:40.216  3125  3137 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 07:17:40.216   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:40.216   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 07:17:40.216   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:40.217  5667  5679 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 07:17:40.217  3125  3136 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 07:17:40.217   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:40.218  5667  5681 D BluetoothMap: onBluetoothStateChange: up=false
10-14 07:17:40.218  5667  5679 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 07:17:40.218  5667  5681 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 07:17:40.219  5732  5829 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 07:17:40.219  5732  5829 D BluetoothAdapterProperties: Setting state to 16
10-14 07:17:40.219  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 07:17:40.220  5732  5829 D BluetoothAdapterProperties: onBleDisable
10-14 07:17:40.220  5732  5829 I BluetoothAdapterState: Entering PendingCommandState
10-14 07:17:40.220  5732  5830 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 07:17:40.221  5732  5840 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 07:17:40.221  5732  5840 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 07:17:40.221  5732  5833 D BluetoothAdapterProperties: Scan Mode:20
10-14 07:17:40.224  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.225  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.226  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.227  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.229  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:40.230  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:40.236  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 07:17:40.240  5667  5667 D DockEventReceiver: finishStartingService: stopping service
,10-14 07:17:40.240  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:40.434  5732  5833 I bt_hci  : shut_down
,10-14 07:17:40.439  5732  5837 D bt_hwcfg: hw_epilog_process
10-14 07:17:40.440  5732  5837 I bt_vendor: low_power_mode_cb
,10-14 07:17:40.443  5732  5837 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-14 07:17:40.443  5732  5837 I bt_vendor: epilog_cb
10-14 07:17:40.444  5732  5837 I bt_hci  : epilog_finished_callback
,10-14 07:17:40.449  5732  5833 I bt_hci_h4: hal_close
,10-14 07:17:40.450  5732  5833 I bt_userial_vendor: device fd = 54 close
,10-14 07:17:40.570  5732  5830 D bt_stack_manager: event_shut_down_stack finished.
,10-14 07:17:40.570  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-14 07:17:40.576  5732  5732 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 07:17:40.577  5732  5829 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-14 07:17:40.577  5732  5732 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 07:17:40.577  5732  5732 D BtGatt.GattService: stop()
,10-14 07:17:40.577  5732  5732 D BtGatt.AdvertiseManager: advertise clients cleared
10-14 07:17:40.580  5732  5732 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:40.581  5732  5732 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:40.581  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:40.581  5732  5732 V BluetoothAdapterState: isBleTurningOff()=true
,10-14 07:17:40.581  5732  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 07:17:40.582  5732  5829 D BluetoothAdapterProperties: Setting state to 10
,10-14 07:17:40.582  5732  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 07:17:40.583  5732  5829 I BluetoothAdapterState: Entering OffState
,10-14 07:17:40.585   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-14 07:17:40.602  5732  5732 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-14 07:17:40.602  5732  5732 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 07:17:40.602  5732  5732 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-14 07:17:40.605  5732  5830 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-14 07:17:40.612  5732  5732 I art     : System.exit called, status: 0
10-14 07:17:40.613  5732  5732 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 07:17:40.645   928  3833 I ActivityManager: Process com.android.bluetooth (pid 5732) has died
,10-14 07:17:45.140  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:45.141  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:45.146  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:45.147  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@150d360 removed from the list
,10-14 07:17:45.147  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:45.147  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:45.147  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:45.150  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 07:17:45.150  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fea88de added. We now have 4 listener(s)
,10-14 07:17:45.151  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 07:17:45.153  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 07:17:45.153  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fea88de removed from the list
10-14 07:17:45.153  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 07:17:45.153  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:45.153  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:17:45.158  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:17:45.158  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6441abf added. We now have 4 listener(s)
10-14 07:17:45.158  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 07:17:50.166  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:50.197   928   945 I ActivityManager: Start proc 5874:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-14 07:17:50.279  5874  5874 D AdapterServiceConfig: Adding HeadsetService
,10-14 07:17:50.279  5874  5874 D AdapterServiceConfig: Adding A2dpService
10-14 07:17:50.280  5874  5874 D AdapterServiceConfig: Adding HidService
10-14 07:17:50.280  5874  5874 D AdapterServiceConfig: Adding HealthService
10-14 07:17:50.280  5874  5874 D AdapterServiceConfig: Adding PanService
10-14 07:17:50.280  5874  5874 D AdapterServiceConfig: Adding GattService
,10-14 07:17:50.280  5874  5874 D AdapterServiceConfig: Adding BluetoothMapService
10-14 07:17:50.280  5874  5874 D AdapterServiceConfig: Adding SapService
,10-14 07:17:50.291   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11ba212:true
,10-14 07:17:50.292  5874  5874 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 07:17:50.295  5874  5874 I bt_bluedroid: init
,10-14 07:17:50.295  5874  5886 I BluetoothAdapterState: Entering OffState
,10-14 07:17:50.297  5874  5887 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-14 07:17:50.297  5874  5887 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 07:17:50.297  5874  5887 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-14 07:17:50.297  5874  5887 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 07:17:50.298  5874  5874 I bt_bluedroid: get_profile_interface socket
,10-14 07:17:50.299  5874  5890 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 07:17:50.300  5874  5874 I bt_bluedroid: get_profile_interface sdp
10-14 07:17:50.301  5874  5890 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 07:17:50.305  5874  5885 I bt_bluedroid: config_hci_snoop_log
10-14 07:17:50.306   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-14 07:17:50.310  5874  5886 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 07:17:50.311  5874  5886 D BluetoothAdapterProperties: Setting state to 14
10-14 07:17:50.311  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 07:17:50.312  5874  5886 D BluetoothBondStateMachine: make
,10-14 07:17:50.314  5874  5891 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 07:17:50.316  5874  5886 I BluetoothAdapterState: Entering PendingCommandState
,10-14 07:17:50.318  5874  5874 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 07:17:50.320  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:50.320  5874  5874 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 07:17:50.321  5874  5874 D BtGatt.GattService: Received start request. Starting profile...
10-14 07:17:50.321  5874  5874 D BtGatt.GattService: start()
10-14 07:17:50.321  5874  5874 I bt_bluedroid: get_profile_interface gatt
10-14 07:17:50.322  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:50.322  5874  5874 D BtGatt.AdvertiseManager: advertise manager created
,10-14 07:17:50.328  5874  5874 V BluetoothAdapterState: isTurningOff()=false
,10-14 07:17:50.328  5874  5874 V BluetoothAdapterState: isTurningOn()=false
10-14 07:17:50.328  5874  5874 V BluetoothAdapterState: isBleTurningOn()=true
10-14 07:17:50.328  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:50.329  5874  5886 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 07:17:50.330  5874  5886 I bt_bluedroid: bt_bluedroid
10-14 07:17:50.330  5874  5887 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-14 07:17:50.331  5874  5887 I bt_hci  : start_up
,10-14 07:17:50.336  5874  5887 I bt_vendor: alloc value 0xf3e73871
,10-14 07:17:50.336  5874  5887 I bt_vendor: init
10-14 07:17:50.336  5874  5887 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 07:17:50.336  5874  5887 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 07:17:50.447  5874  5887 D bt_hci  : start_up starting async portion
,10-14 07:17:50.447  5874  5894 I bt_hci  : event_finish_startup
10-14 07:17:50.447  5874  5894 I bt_hci_h4: hal_open
10-14 07:17:50.448  5874  5894 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-14 07:17:50.447  5895  5895 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 07:17:50.450  5874  5894 I bt_userial_vendor: device fd = 54 open
,10-14 07:17:50.466  5874  5894 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 07:17:50.469  5874  5894 D bt_hwcfg: Chipset BCM4358A3
,10-14 07:17:50.470  5874  5894 D bt_hwcfg: Target name = [BCM4358A3]
10-14 07:17:50.470  5874  5894 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 07:17:50.990  5874  5894 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-14 07:17:50.991  5874  5894 D bt_hwcfg: Settlement delay -- 100 ms
10-14 07:17:50.991  5874  5894 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 07:17:51.125  5874  5894 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-14 07:17:51.125  5874  5894 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-14 07:17:51.127  5874  5894 I bt_hwcfg: vendor lib fwcfg completed
10-14 07:17:51.127  5874  5894 I bt_vendor: firmware callback
10-14 07:17:51.127  5874  5894 I bt_hci  : firmware_config_callback
,10-14 07:17:51.136  5874  5897 I bt_btu  : btu_task pending for preload complete event
10-14 07:17:51.137  5874  5897 I bt_btu_task: Bluetooth chip preload is complete
,10-14 07:17:51.137  5874  5897 I bt_btu  : btu_task received preload complete event
,10-14 07:17:51.144  5874  5897 I         : BTE_InitTraceLevels -- TRC_HCI
10-14 07:17:51.144  5874  5897 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-14 07:17:51.144  5874  5897 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_AVRC
10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_A2D
10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_BTM
10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_PAN
10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_SDP
,10-14 07:17:51.145  5874  5897 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 07:17:51.146  5874  5897 I         : BTE_InitTraceLevels -- TRC_SMP
10-14 07:17:51.146  5874  5897 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-14 07:17:51.146  5874  5897 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 07:17:51.241  5874  5897 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3df1549
,10-14 07:17:51.242  5874  5897 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3df1549 
,10-14 07:17:51.272  5874  5890 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 07:17:51.275  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 07:17:51.275  5874  5890 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 07:17:51.277  5874  5890 D BluetoothAdapterProperties: Name is: Nexus 6P
10-14 07:17:51.279  5874  5890 D BluetoothAdapterProperties: Scan Mode:20
10-14 07:17:51.280  5874  5890 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-14 07:17:51.280  5874  5890 D bt_hci  : do_postload posting postload work item
10-14 07:17:51.280  5874  5894 I bt_hci  : event_postload
10-14 07:17:51.280  5874  5894 I bt_vendor: sco_config_cb
10-14 07:17:51.280  5874  5894 I bt_hci  : sco_config_callback postload finished.
,10-14 07:17:51.283  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:51.284  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:51.285  5874  5890 D bt_bte_conf: Device ID record 1 : primary
10-14 07:17:51.285  5874  5890 D bt_bte_conf:   vendorId            = 000f
10-14 07:17:51.285  5874  5890 D bt_bte_conf:   vendorIdSource      = 0001
,10-14 07:17:51.286  5874  5890 D bt_bte_conf:   product             = 1200
10-14 07:17:51.286  5874  5890 D bt_bte_conf:   version             = 1436
10-14 07:17:51.286  5874  5890 D bt_bte_conf:   clientExecutableURL = 
10-14 07:17:51.286  5874  5890 D bt_bte_conf:   serviceDescription  = 
10-14 07:17:51.286  5874  5890 D bt_bte_conf:   documentationURL    = 
10-14 07:17:51.286  5874  5890 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 07:17:51.286  5874  5887 D bt_stack_manager: event_start_up_stack finished
10-14 07:17:51.286  5874  5886 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 07:17:51.287  5874  5886 D BluetoothAdapterProperties: Setting state to 15
10-14 07:17:51.287  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-14 07:17:51.287  5874  5894 I bt_vendor: low_power_mode_cb
10-14 07:17:51.288  5874  5886 I BluetoothAdapterState: Entering BleOnState
,10-14 07:17:51.291  5874  5886 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-14 07:17:51.291  5874  5886 D BluetoothAdapterProperties: Setting state to 11
,10-14 07:17:51.291  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-14 07:17:51.295  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:51.296  5874  5874 D HeadsetService: Received start request. Starting profile...
,10-14 07:17:51.300  5874  5874 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 07:17:51.301  5874  5874 D HeadsetStateMachine: make
,10-14 07:17:51.302  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:51.306  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:17:51.312  5874  5886 I BluetoothAdapterState: Entering PendingCommandState
,10-14 07:17:51.318  5874  5874 D HeadsetStateMachine: max_hf_connections = 1
10-14 07:17:51.318  5874  5874 I bt_bluedroid: get_profile_interface handsfree
,10-14 07:17:51.318  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-14 07:17:51.318  5874  5890 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-14 07:17:51.322  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:51.323  5874  5874 D A2dpService: Received start request. Starting profile...
10-14 07:17:51.323  5874  5874 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-14 07:17:51.324  5874  5874 I bt_bluedroid: get_profile_interface avrcp
,10-14 07:17:51.331  5874  5874 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-14 07:17:51.331  5874  5874 I BluetoothA2dpServiceJni: classInitNative: succeeds
,10-14 07:17:51.331  5874  5874 D A2dpStateMachine: make
,10-14 07:17:51.332  5874  5874 I bt_bluedroid: get_profile_interface a2dp
,10-14 07:17:51.334  5874  5905 D A2dpStateMachine: Enter Disconnected: -2
,10-14 07:17:51.334  5874  5874 I BluetoothHidServiceJni: classInitNative: succeeds
10-14 07:17:51.335  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-14 07:17:51.335  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:51.336  5874  5874 D HidService: Received start request. Starting profile...
10-14 07:17:51.336  5874  5874 I bt_bluedroid: get_profile_interface hidhost
,10-14 07:17:51.336  5874  5874 D HidService: setHidService(): set to: null
10-14 07:17:51.336  5874  5890 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dd256d
10-14 07:17:51.337  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-14 07:17:51.338  5874  5874 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-14 07:17:51.341  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:51.342  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:51.343  5874  5874 D HealthService: Received start request. Starting profile...
10-14 07:17:51.345  5874  5874 I bt_bluedroid: get_profile_interface health
10-14 07:17:51.346  5874  5874 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-14 07:17:51.347  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:17:51.347  5874  5874 D PanService: Received start request. Starting profile...
,10-14 07:17:51.347  5874  5874 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 07:17:51.347  5874  5874 I bt_bluedroid: get_profile_interface pan
,10-14 07:17:51.349  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:51.349  5874  5874 D BluetoothMapService: Received start request. Starting profile...
10-14 07:17:51.350  5874  5874 D BluetoothMapService: start()
,10-14 07:17:51.351  5874  5874 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-14 07:17:51.352  5874  5874 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 07:17:51.352  5874  5874 D BluetoothMapAppObserver: createReceiver()
10-14 07:17:51.353  5874  5874 D BluetoothMapAppObserver: initObservers()
10-14 07:17:51.353  5874  5874 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-14 07:17:51.354  5874  5890 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-14 07:17:51.357  5874  5874 V SapService: SapBinder()
10-14 07:17:51.357  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
,10-14 07:17:51.358  5874  5874 D SapService: Received start request. Starting profile...
10-14 07:17:51.358  5874  5874 V SapService: start()
,10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isTurningOff()=false
,10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isTurningOff()=false
,10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.360  5874  5903 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.360  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.361  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:51.362  5874  5874 V BluetoothAdapterState: isTurningOff()=false
10-14 07:17:51.362  5874  5874 V BluetoothAdapterState: isTurningOn()=true
10-14 07:17:51.362  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
10-14 07:17:51.362  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
10-14 07:17:51.362  5874  5886 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 07:17:51.362  5874  5886 D BluetoothAdapterProperties: ScanMode =  20
10-14 07:17:51.362  5874  5886 D BluetoothAdapterProperties: State =  11
,10-14 07:17:51.363  5874  5886 D BluetoothAdapterProperties: Setting state to 12
10-14 07:17:51.363  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 07:17:51.363  5874  5886 I BluetoothAdapterState: Entering OnState
10-14 07:17:51.363  3125  3136 D BluetoothMap: onBluetoothStateChange: up=true
10-14 07:17:51.364  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 07:17:51.364  5874  5890 D BluetoothAdapterProperties: Scan Mode:21
10-14 07:17:51.364  5874  5890 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-14 07:17:51.367  5667  5679 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:51.367  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:51.368  3125  3125 D BluetoothMap: Proxy object connected
10-14 07:17:51.368  3125  3125 D MapProfile: Bluetooth service connected
10-14 07:17:51.368  3125  3125 D BluetoothMap: getConnectedDevices()
,10-14 07:17:51.372  5667  5681 D BluetoothPan: onBluetoothStateChange on: true
10-14 07:17:51.372  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:51.377  5874  5874 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-14 07:17:51.377  3125  3136 D BluetoothPan: onBluetoothStateChange on: true
,10-14 07:17:51.377  5874  5874 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-14 07:17:51.377  5667  5667 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 07:17:51.377  5667  5667 D PanProfile: Bluetooth service connected
10-14 07:17:51.378  5874  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:51.379  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:17:51.379  3125  3939 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:51.379  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 07:17:51.379  3125  3125 D PanProfile: Bluetooth service connected
,10-14 07:17:51.380  3125  3937 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 07:17:51.380  5874  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 07:17:51.382  5874  5874 D ObexServerSockets: Succeed to create listening sockets 
,10-14 07:17:51.382  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:17:51.382  5874  5874 D ObexServerSockets0: startAccept()
10-14 07:17:51.382  5874  5874 D ObexServerSockets0: prepareForNewConnect()
10-14 07:17:51.383  3741  3770 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:51.384  3125  3136 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 07:17:51.385  5874  5874 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-14 07:17:51.385  5874  5874 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 07:17:51.385  5874  5912 D ObexServerSockets0: Accepting socket connection...
,10-14 07:17:51.386   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:51.386  5874  5913 D ObexServerSockets0: Accepting socket connection...
10-14 07:17:51.386   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 07:17:51.386  3125  3125 D BluetoothA2dp: Proxy object connected
10-14 07:17:51.386   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:51.386   928   928 D BluetoothA2dp: Proxy object connected
10-14 07:17:51.387  5667  5679 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-14 07:17:51.388  3125  3125 D BluetoothInputDevice: Proxy object connected
10-14 07:17:51.388  3125  3125 D HidProfile: Bluetooth service connected
,10-14 07:17:51.390  3125  3937 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 07:17:51.391   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 07:17:51.391  5667  5681 D BluetoothMap: onBluetoothStateChange: up=true
,10-14 07:17:51.393  5667  5679 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 07:17:51.393  5667  5911 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 07:17:51.395  5667  5667 D BluetoothA2dp: Proxy object connected
10-14 07:17:51.396  5614  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 07:17:51.396  5874  5874 D BluetoothMapService: onReceive
10-14 07:17:51.396  5874  5874 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 07:17:51.396  5874  5874 D BluetoothMapService: STATE_ON
,10-14 07:17:51.397  5667  5667 D BluetoothMap: Proxy object connected
10-14 07:17:51.397  5667  5667 D MapProfile: Bluetooth service connected
10-14 07:17:51.397  5667  5667 D BluetoothMap: getConnectedDevices()
10-14 07:17:51.397  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:51.398  5874  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 07:17:51.399  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:17:51.399  5667  5667 D BluetoothInputDevice: Proxy object connected
10-14 07:17:51.399  5667  5667 D HidProfile: Bluetooth service connected
10-14 07:17:51.399   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 07:17:51.400  5874  5914 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-14 07:17:51.400  5874  5914 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-14 07:17:51.404  5667  5667 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 07:17:51.411  5667  5667 D DockEventReceiver: finishStartingService: stopping service
,10-14 07:17:51.411  3559  3559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 07:17:51.417  5667  5667 D BluetoothPbap: Proxy object connected
,10-14 07:17:51.417  5667  5667 D PbapServerProfile: Bluetooth service connected
,10-14 07:17:51.422  5874  5874 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 07:17:51.422  5874  5874 D ObexServerSockets0: prepareForNewConnect()
,10-14 07:17:51.423  5874  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 07:17:51.427  3125  3125 D BluetoothPbap: Proxy object connected
,10-14 07:17:51.428  3125  3125 D PbapServerProfile: Bluetooth service connected
,10-14 07:17:51.438  5874  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 07:17:51.439  5874  5924 I BtOppRfcommListener: Accept thread started.
,10-14 07:17:51.481  5667  5681 D BluetoothHeadset: Proxy object connected
10-14 07:17:51.481   928   928 D BluetoothHeadset: Proxy object connected
10-14 07:17:51.481   928   928 D BluetoothHeadset: Proxy object connected
,10-14 07:17:51.482  3741  4002 D BluetoothHeadset: Proxy object connected
10-14 07:17:51.482   928   928 D BluetoothHeadset: Proxy object connected
10-14 07:17:51.482  3125  3137 D BluetoothHeadset: Proxy object connected
,10-14 07:17:51.483  3125  3125 D HeadsetProfile: Bluetooth service connected
10-14 07:17:51.484  3741  3772 D BluetoothHeadset: Proxy object connected
,10-14 07:17:51.485  5667  5667 D HeadsetProfile: Bluetooth service connected
,10-14 07:17:51.486   928   945 D BluetoothHeadset: Proxy object connected
10-14 07:17:51.486   928   945 D BluetoothHeadset: Proxy object connected
,10-14 07:17:51.492   928   945 D BluetoothHeadset: Proxy object connected
,10-14 07:17:51.493  5667  5911 D BluetoothHeadset: Proxy object connected
10-14 07:17:51.494  5667  5667 D HeadsetProfile: Bluetooth service connected
,10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:17:55.183  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:17:55.189  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:17:55.190  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:17:55.190  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6441abf removed from the list
10-14 07:17:55.190  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:17:55.190  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:17:55.190  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:17:55.196  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 07:17:55.196  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dfc58c added. We now have 4 listener(s)
10-14 07:17:55.196  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 07:17:55.200   928  3820 D WifiService: setWifiEnabled: false pid=5614, uid=10077
,10-14 07:17:55.200   928  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 07:17:57.519   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:58.521   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:17:59.522   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:00.210  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:18:00.211   928  3820 D WifiService: setWifiEnabled: true pid=5614, uid=10077
,10-14 07:18:00.211   928  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 07:18:00.218   509   921 D SoftapController: Softap fwReload - Ok
,10-14 07:18:00.223   509   921 D CommandListener: Setting iface cfg
,10-14 07:18:00.224   509   921 D CommandListener: Trying to bring down wlan0
10-14 07:18:00.225   509   921 D CommandListener: Clearing all IP addresses on wlan0
,10-14 07:18:00.230   928  2971 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 07:18:00.524   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:00.893   928  2971 D wifi    : set interface wlan0 flags (UP)
,10-14 07:18:00.894   928  2971 I WifiHAL : Initializing wifi
10-14 07:18:00.894   928  2971 I WifiHAL : Creating socket
,10-14 07:18:00.899   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-14 07:18:00.903   928  2971 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-14 07:18:00.903   928  2971 D wifi    : Did set static halHandle = 0x7f5a86f180
10-14 07:18:00.903   928  2971 D wifi    : halHandle = 0x7f5a86f180, mVM = 0x7f76ecd140, mCls = 0x1716
10-14 07:18:00.904   928  2971 D wifi    : array field set
10-14 07:18:00.904   928  2971 I WifiNative-HAL: interface[0] = wlan0
10-14 07:18:00.907   928  5929 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546979639680
10-14 07:18:00.907   928  5929 D wifi    : waitForHalEvents called, vm = 0x7f76ecd140, obj = 0x1716, env = 0x7f5b77fd00
,10-14 07:18:00.971  5930  5930 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 07:18:00.993  5930  5930 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 07:18:01.008   928  2971 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-14 07:18:01.009   928  2971 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
10-14 07:18:01.016  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:18:01.023  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:18:01.041  5930  5930 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-14 07:18:01.041  5930  5930 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 07:18:01.526   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:02.028   928  2971 D WifiConfigStore: Loading config and enabling all networks 
,10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:02.032  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:18:02.036  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:02.042  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:18:02.043   928  2971 D WifiConfigStore: loaded 0 passpoint configs
10-14 07:18:02.044   928  2971 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 07:18:02.045   928  2971 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-14 07:18:02.045  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:18:02.046   928  2971 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-14 07:18:02.047   928  2971 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-14 07:18:02.048   928  2971 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 07:18:02.048   928  2971 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 07:18:02.048   928  2971 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 07:18:02.053   928  2971 D WifiNative-HAL: Setting external_sim to 1
,10-14 07:18:02.053  4916  4916 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 07:18:02.053   928  2971 D wifi    : setting dfs flag to true, 0x7f59f48560
10-14 07:18:02.054   928  2971 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 07:18:02.054   928  2971 D wifi    : setting scan oui 0x7f59f48560
10-14 07:18:02.054   928  2971 D WifiHAL : Sending mac address OUI
,10-14 07:18:02.060   928  2971 E native  : do suspend false
,10-14 07:18:02.069   928  2971 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-14 07:18:02.069   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-14 07:18:02.070   928   928 D RttService: SCAN_AVAILABLE : 3
10-14 07:18:02.070   928  3037 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-14 07:18:02.071   509   921 D CommandListener: Setting iface cfg
,10-14 07:18:02.075   928  2959 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-14 07:18:02.076   928  2959 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 07:18:02.081   928  2959 D WifiNative-HAL: p2pGetDeviceAddress
,10-14 07:18:02.081   928  2959 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 07:18:02.113   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303485 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=38 mControllerEnergyUsed=144 }
,10-14 07:18:02.527   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:05.228  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:18:05.233  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:18:05.234  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.234  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dfc58c removed from the list
10-14 07:18:05.235  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:18:05.235  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.235  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.243  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-14 07:18:05.245  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-14 07:18:05.247  5930  5930 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:18:05.250  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7fbde9a Bundle[{}]
10-14 07:18:05.251  5930  5930 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:18:05.252  5614  5660 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-14 07:18:05.252  5614  5660 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-14 07:18:05.253  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-14 07:18:05.255  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-14 07:18:05.256  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-14 07:18:05.258  5614  5660 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-14 07:18:05.260  5930  5930 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:18:05.263  5930  5930 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 07:18:05.267  5614  5660 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-14 07:18:05.269  5614  5660 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-14 07:18:05.269  5614  5660 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-14 07:18:05.272  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.272  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bff4d5 added. We now have 3 listener(s)
10-14 07:18:05.273  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.274  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-14 07:18:05.274  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.274  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.274  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81254ea added. We now have 4 listener(s)
10-14 07:18:05.274  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.275  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 07:18:05.279  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:05.283  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:18:05.285  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:18:05.285  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:18:05.285  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 07:18:05.285  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a89ae78 added. We now have 4 listener(s)
10-14 07:18:05.287  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.287  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.287  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.287  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.287  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8980951 added. We now have 5 listener(s)
,10-14 07:18:05.287  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.287  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.288  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:18:05.288  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:05.288  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:18:05.288  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.288  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.288  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.288  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 07:18:05.288  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.288  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bff4d5 removed from the list
10-14 07:18:05.288  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.288  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81254ea removed from the list
10-14 07:18:05.290  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.290  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:18:05.290  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.291  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.291  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.293  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.293  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.293  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.293  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81254ea not in the list
10-14 07:18:05.293  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:18:05.293  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.294  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.294  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.294  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.294  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8980951 removed from the list
10-14 07:18:05.294  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.294  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.295  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.295  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.295  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.295  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a89ae78 removed from the list
,10-14 07:18:05.296  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 07:18:05.296  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138d5b6 added. We now have 3 listener(s)
10-14 07:18:05.297  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.297  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.297  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.297  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.298  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@714a2b7 added. We now have 4 listener(s)
10-14 07:18:05.298  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.298  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 07:18:05.301  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:05.305  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:18:05.305   928  2971 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-14 07:18:05.306   928  2971 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-14 07:18:05.306   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 07:18:05.307  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:18:05.307  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 07:18:05.308  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.308  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b02e98d added. We now have 4 listener(s)
10-14 07:18:05.309  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.309  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.309  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.309  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.309  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3749742 added. We now have 5 listener(s)
10-14 07:18:05.310  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.310  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:05.310  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 07:18:05.310  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 07:18:05.310  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:18:05.310  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 07:18:05.310  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.312  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:18:05.314  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 07:18:05.314  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 07:18:05.316   928  2971 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
10-14 07:18:05.318  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 07:18:05.318  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 07:18:05.319  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 07:18:05.321  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 07:18:05.322  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 07:18:05.322  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 07:18:05.322  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 07:18:05.322  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 07:18:05.322  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:18:05.325  5874  5916 D BtGatt.GattService: registerClient() - UUID=3aadd467-d693-4075-869a-4c6532e7ddca
10-14 07:18:05.326  5874  5890 D BtGatt.GattService: onClientRegistered() - UUID=3aadd467-d693-4075-869a-4c6532e7ddca, clientIf=5
10-14 07:18:05.326  5614  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 07:18:05.327  5874  5885 D BtGatt.GattService: start scan with filters
,10-14 07:18:05.331  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 07:18:05.331  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 07:18:05.331  5874  5893 D BtGatt.ScanManager: handling starting scan
10-14 07:18:05.331  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:18:05.332  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 07:18:05.332  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 07:18:05.332  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 07:18:05.332  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 07:18:05.334  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:18:05.334  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 07:18:05.334  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:18:05.335  5874  5893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@82e3baf
10-14 07:18:05.335  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 07:18:05.338  5614  5660 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-14 07:18:05.338  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:05.338  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 07:18:05.338  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.338  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 07:18:05.338  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.338  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 07:18:05.338  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:18:05.338  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 07:18:05.338  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 07:18:05.338  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 07:18:05.338  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 07:18:05.339  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:18:05.340  5874  5915 D BtGatt.GattService: stopScan() - queue size =1
10-14 07:18:05.341  5874  5916 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 07:18:05.341  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 07:18:05.341  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 07:18:05.341  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-14 07:18:05.341  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:18:05.341  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 07:18:05.341  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 07:18:05.342  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 07:18:05.342  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 07:18:05.342  5874  5890 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 07:18:05.342  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:18:05.343  5874  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 07:18:05.343  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:18:05.343  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 07:18:05.343  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 07:18:05.343  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 07:18:05.343  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 07:18:05.344  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.345  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:18:05.345  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:18:05.345  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:18:05.347  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:18:05.347  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:05.347  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:18:05.347  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.347  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.347  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.348  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.348  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.348  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138d5b6 removed from the list
,10-14 07:18:05.348  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.348  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@714a2b7 removed from the list
10-14 07:18:05.348  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:18:05.348  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.349  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.349  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.349  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 07:18:05.349  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.349  5874  5893 D BtGatt.ScanManager: Starting BLE batch scan
10-14 07:18:05.349  5874  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 07:18:05.350  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 07:18:05.350  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.350  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.350  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@714a2b7 not in the list
10-14 07:18:05.350  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.350  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.350   928  2971 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
10-14 07:18:05.351  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.351  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.351  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.351  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3749742 removed from the list
10-14 07:18:05.351  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.352  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.352  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.352  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.352  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.352  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b02e98d removed from the list
10-14 07:18:05.352  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.352  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb8e58e added. We now have 3 listener(s)
10-14 07:18:05.353  5930  5930 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
10-14 07:18:05.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-14 07:18:05.354  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.354  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17f31af added. We now have 4 listener(s)
10-14 07:18:05.354  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.355  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 07:18:05.357  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:18:05.359  5874  5890 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 07:18:05.359  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:05.362  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:18:05.364  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 07:18:05.364  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:18:05.364  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.365  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:18:05.365  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.365  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8bd45 added. We now have 4 listener(s)
10-14 07:18:05.366  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.366  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.366  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.366  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.366  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.366  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1cc9a added. We now have 5 listener(s)
10-14 07:18:05.366  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.366  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:05.367  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 07:18:05.367  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:05.367  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 07:18:05.367  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 07:18:05.367  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:18:05.367  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 07:18:05.370  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 07:18:05.371  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 07:18:05.375  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 07:18:05.375  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.376  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 07:18:05.376  5874  5893 D BtGatt.ScanManager: stopping BLe Batch
10-14 07:18:05.376  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 07:18:05.376  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 07:18:05.380  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 07:18:05.380  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 07:18:05.380  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.381  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 07:18:05.381  5874  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 07:18:05.381  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 07:18:05.381  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 07:18:05.381  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 07:18:05.382  5614  5660 D BluetoothAdapter: STATE_ON
,10-14 07:18:05.384  5874  5915 D BtGatt.GattService: registerClient() - UUID=3e79138d-3198-4be8-88f2-682cb63c6118
,10-14 07:18:05.384  5874  5890 D BtGatt.GattService: onClientRegistered() - UUID=3e79138d-3198-4be8-88f2-682cb63c6118, clientIf=5
10-14 07:18:05.385  5614  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 07:18:05.385  5874  5902 D BtGatt.GattService: start scan with filters
,10-14 07:18:05.386  5874  5890 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 07:18:05.386  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:18:05.387  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 07:18:05.387  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 07:18:05.387  5874  5893 D BtGatt.ScanManager: handling starting scan
10-14 07:18:05.387  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:18:05.387  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 07:18:05.387  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 07:18:05.387  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 07:18:05.387  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 07:18:05.389  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:18:05.389  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 07:18:05.389  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 07:18:05.390  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 07:18:05.392  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:05.392  5614  5660 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-14 07:18:05.392  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:18:05.392  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:05.392  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:18:05.393  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.393  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.393  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 07:18:05.393  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.393  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.393  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb8e58e removed from the list
10-14 07:18:05.393  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.393  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17f31af removed from the list
10-14 07:18:05.393  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:18:05.393  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.393  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.393  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-14 07:18:05.393  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.393  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.393  5874  5890 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 07:18:05.393  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.394  5874  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 07:18:05.394  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.394  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.394  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.394  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17f31af not in the list
10-14 07:18:05.394  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:18:05.394  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: ,stopForRestart
10-14 07:18:05.394  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 07:18:05.394  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 07:18:05.395  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 07:18:05.395  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:18:05.396  5874  5915 D BtGatt.GattService: stopScan() - queue size =1
10-14 07:18:05.396  5874  5902 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 07:18:05.396  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 07:18:05.396  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 07:18:05.396  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 07:18:05.396  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:18:05.396  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 07:18:05.397  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 07:18:05.397  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 07:18:05.397  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-14 07:18:05.397  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:18:05.398  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 07:18:05.398  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 07:18:05.398  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 07:18:05.398  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 07:18:05.398  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.398  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 07:18:05.398  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.399  5874  5893 D BtGatt.ScanManager: Starting BLE batch scan
10-14 07:18:05.399  5874  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 07:18:05.399  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.399  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.399  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.399  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:18:05.399  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1cc9a removed from the list
10-14 07:18:05.399  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.399  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:18:05.399  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.399  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:18:05.399  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.399  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.399  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.399  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8bd45 removed from the list
10-14 07:18:05.400  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 07:18:05.400  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1801866 added. We now have 3 listener(s)
10-14 07:18:05.401  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.401  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.401  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.402  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.402  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdda7a7 added. We now have 4 listener(s)
,10-14 07:18:05.402  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.402  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 07:18:05.404  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:05.407  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 07:18:05.407  5874  5890 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 07:18:05.407  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.409  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-14 07:18:05.409  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:18:05.409  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.409  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24e4ffd added. We now have 4 listener(s)
10-14 07:18:05.410  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.410  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.410  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-14 07:18:05.410  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.410  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.410  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26554f2 added. We now have 5 listener(s)
10-14 07:18:05.410  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.410  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:05.410  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 07:18:05.411  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 07:18:05.411  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 07:18:05.411  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 07:18:05.411  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.411  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 07:18:05.412  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:18:05.414  5614  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 07:18:05.414  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 07:18:05.417  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 07:18:05.417  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 07:18:05.418  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 07:18:05.418  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 07:18:05.418  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.418  5874  5893 D BtGatt.ScanManager: stopping BLe Batch
,10-14 07:18:05.422  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 07:18:05.422  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 07:18:05.422  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-14 07:18:05.422  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 07:18:05.422  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 07:18:05.423  5614  5660 D BluetoothAdapter: STATE_ON
10-14 07:18:05.424  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 07:18:05.424  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.424  5874  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 07:18:05.425  5874  5885 D BtGatt.GattService: registerClient() - UUID=cf7ffd9d-e537-4cdb-8b76-afa94c06638c
10-14 07:18:05.426  5874  5890 D BtGatt.GattService: onClientRegistered() - UUID=cf7ffd9d-e537-4cdb-8b76-afa94c06638c, clientIf=5
,10-14 07:18:05.426  5614  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 07:18:05.426  5874  5910 D BtGatt.GattService: start scan with filters
10-14 07:18:05.429  5874  5890 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 07:18:05.429  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.429  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 07:18:05.429  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 07:18:05.429  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:18:05.429  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 07:18:05.429  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 07:18:05.429  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 07:18:05.429  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 07:18:05.430  5874  5893 D BtGatt.ScanManager: handling starting scan
10-14 07:18:05.431  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 07:18:05.431  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 07:18:05.431  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 07:18:05.432  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 07:18:05.435  5874  5890 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 07:18:05.435  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.435  5874  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 07:18:05.436  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:18:05.436  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:05.436  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:18:05.436  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 07:18:05.436  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.436  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 07:18:05.436  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.436  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.436  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1801866 removed from the list
10-14 07:18:05.436  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.436  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdda7a7 removed from the list
10-14 07:18:05.436  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:18:05.436  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.436  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.437  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-14 07:18:05.437  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 07:18:05.437  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 07:18:05.440  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 07:18:05.440  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.440  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.440  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.440  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.440  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdda7a7 not in the list
10-14 07:18:05.440  5874  5893 D BtGatt.ScanManager: Starting BLE batch scan
10-14 07:18:05.440  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 07:18:05.440  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 07:18:05.440  5874  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 07:18:05.440  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 07:18:05.440  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 07:18:05.440  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-14 07:18:05.441  5614  5660 D BluetoothAdapter: STATE_ON
,10-14 07:18:05.441  5874  5885 D BtGatt.GattService: stopScan() - queue size =1
10-14 07:18:05.442  5874  5902 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 07:18:05.442  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 07:18:05.442  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 07:18:05.442  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 07:18:05.442  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 07:18:05.443  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 07:18:05.443  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 07:18:05.443  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 07:18:05.443  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 07:18:05.444  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:18:05.444  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 07:18:05.444  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 07:18:05.444  5614  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 07:18:05.444  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-14 07:18:05.445  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.445  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.446  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.446  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.446  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:18:05.446  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26554f2 removed from the list
10-14 07:18:05.446  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.446  5614  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 07:18:05.446  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.446  5614  5614 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 07:18:05.446  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.446  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.446  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.446  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24e4ffd removed from the list
10-14 07:18:05.446  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.447  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@defce3e added. We now have 3 listener(s)
10-14 07:18:05.448  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 07:18:05.448  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.448  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.449  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.449  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e5e49f added. We now have 4 listener(s)
10-14 07:18:05.449  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.449  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 07:18:05.450  5874  5890 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 07:18:05.450  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:18:05.452  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 07:18:05.455  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 07:18:05.456  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 07:18:05.456  5614  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 07:18:05.458  5614  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-14 07:18:05.458  5614  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 07:18:05.459  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 07:18:05.459  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14c81b5 added. We now have 4 listener(s)
10-14 07:18:05.460  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.460  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 07:18:05.460  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 07:18:05.460  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 07:18:05.460  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 07:18:05.460  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416904a added. We now have 5 listener(s)
10-14 07:18:05.460  5614  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 07:18:05.460  5614  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 07:18:05.460  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:05.460  5614  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 07:18:05.460  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.460  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.460  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 07:18:05.461  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 07:18:05.461  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.461  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@defce3e removed from the list
10-14 07:18:05.461  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.461  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 07:18:05.461  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e5e49f removed from the list
10-14 07:18:05.461  5614  5660 D io.jxcore.node.ConnectivityMonitor: stop
10-14 07:18:05.461  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.461  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 07:18:05.461  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.461  5874  5893 D BtGatt.ScanManager: stopping BLe Batch
10-14 07:18:05.461  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.461  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.464  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.464  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.464  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.464  5614  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e5e49f not in the list
,10-14 07:18:05.464  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.464  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 07:18:05.465  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 07:18:05.465  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 07:18:05.465  5614  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 07:18:05.465  5614  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@416904a removed from the list
10-14 07:18:05.466  5614  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 07:18:05.466  5614  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 07:18:05.466  5614  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 07:18:05.466  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 07:18:05.466  5614  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 07:18:05.466  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 07:18:05.466  5614  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 07:18:05.466  5614  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14c81b5 removed from the list
,10-14 07:18:05.466  5874  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 07:18:05.467  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-14 07:18:05.467  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-14 07:18:05.467  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-14 07:18:05.467  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:05.467  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-14 07:18:05.467  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-14 07:18:05.471  5874  5890 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 07:18:05.471  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 07:18:05.794  5930  5930 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 07:18:05.844  5930  5930 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 07:18:05.846  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-14 07:18:05.846  5930  5930 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 07:18:05.856   928  2971 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 07:18:05.857   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
10-14 07:18:05.857   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 07:18:05.879   928  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 07:18:05.895   509   921 D CommandListener: Setting iface cfg
,10-14 07:18:05.899  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 07:18:05.901   928  2971 D WifiStateMachine: Start Dhcp Watchdog 3
,10-14 07:18:05.909   928  5937 D DhcpClient: Receive thread started
,10-14 07:18:05.913   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-14 07:18:05.913   928  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-14 07:18:05.913   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-14 07:18:05.947  5614  5614 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 07:18:06.002   928  2971 E native  : do suspend false
,10-14 07:18:06.024   928  5936 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 07:18:06.053   928  5937 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,10-14 07:18:06.054   928  5936 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,10-14 07:18:06.056   928  5936 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 07:18:06.072   928  5937 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 07:18:06.073   928  5936 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 07:18:06.076   509   921 D CommandListener: Setting iface cfg
10-14 07:18:06.082   928  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 07:18:06.085   928  5936 D DhcpClient: Scheduling renewal in 86399s
,10-14 07:18:06.099   928  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-14 07:18:06.100   928  2971 D WifiConfigStore: No blacklist allowed without epno enabled
10-14 07:18:06.101   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-14 07:18:06.103   928  2973 D ConnectivityService: Adding iface wlan0 to network 102
,10-14 07:18:06.109   928  2971 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-14 07:18:06.148   928  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-14 07:18:06.148   928  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-14 07:18:06.152   928  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-14 07:18:06.155   928  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
10-14 07:18:06.157   928  2973 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-14 07:18:06.164   928  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 07:18:06.168   928  2973 D ConnectivityService: scheduleUnvalidatedPrompt 102
10-14 07:18:06.169   928  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,10-14 07:18:06.169   928  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-14 07:18:06.169   928  2973 D ConnectivityService:    accepting network in place of null
10-14 07:18:06.169   928  2971 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-14 07:18:06.169   928  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 07:18:06.169   928  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 07:18:06.192   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 07:18:06.193   928  5935 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307565, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 07:18:06.213   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 07:18:06.217   928  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-14 07:18:06.217   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 07:18:06.218  3709  3845 W QCNEJ   : |CORE| network available: 102
10-14 07:18:06.218   928  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-14 07:18:06.219   928   945 D Tethering: MasterInitialState.processMessage what=3
10-14 07:18:06.223  3709  3845 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-14 07:18:06.224  3709  3845 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-14 07:18:06.225  3709  3845 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-14 07:18:06.226  4941  4979 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 07:18:06.227  4941  4979 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 07:18:06.227  4941  4979 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-14 07:18:06.227  4941  4979 E SarControlService: no key has been found,reset the power
10-14 07:18:06.227  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 07:18:06.227  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-14 07:18:06.227  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:18:06.228  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 07:18:06.229  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-14 07:18:06.230  4991  4991 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 07:18:06.231  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:18:06.233  4941  5004 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 07:18:06.233  4941  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 07:18:06.233  4941  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-14 07:18:06.236  3920  3920 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 07:18:06.237  5614  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 07:18:06.240  5614  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
10-14 07:18:06.240  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 07:18:06.240  4991  4991 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 07:18:06.241  3920  3920 D SystemUpdateService: onCreate
,10-14 07:18:06.245  3920  3920 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 07:18:06.246  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000f003000000000000ffffffff]
10-14 07:18:06.246  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 07:18:06.246  4991  5006 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-14 07:18:06.247  4991  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c5187b6 HexData = [00000000f103000000000000ffffffff]
10-14 07:18:06.247  4991  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 07:18:06.247  4991  5006 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-14 07:18:06.248  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:18:06.248  4941  4952 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-14 07:18:06.248  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 07:18:06.249  4941  4951 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 07:18:06.258  3920  3920 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-14 07:18:06.264  3920  5393 I iu.UploadsManager: num queued entries: 0
10-14 07:18:06.265  3920  5393 I iu.UploadsManager: num updated entries: 0
10-14 07:18:06.265  3920  5393 I iu.SyncManager: NEXT; no task
,10-14 07:18:06.267  3920  5947 I SystemUpdateService: active receiver: enabled
,10-14 07:18:06.268   928  5934 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.138,2a00:1450:400c:c0c::64
,10-14 07:18:06.271  3920  3920 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-14 07:18:06.272  3920  3920 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-14 07:18:06.274  5746  5746 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 07:18:06.277  5746  5746 D SprintDMHelper: simOperator: 
10-14 07:18:06.277  5746  5746 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 07:18:06.297  3920  5947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 07:18:06.310  3920  5947 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-14 07:18:06.310  3920  5947 I SystemUpdateService: now status is 0 (complete)
10-14 07:18:06.310  3920  5947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 07:18:06.310  3920  5947 I SystemUpdateService: file has been verified
10-14 07:18:06.310  3920  5947 I SystemUpdateService: OTA package size = 21989297
,10-14 07:18:06.316  3920  5947 I SystemUpdateService: showing system update notification
,10-14 07:18:06.325  3920  3920 D SystemUpdateService: onDestroy
,10-14 07:18:06.365   928  5934 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 11:18:06 GMT], X-Android-Received-Millis=[1476443886364], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476443886314]}
,10-14 07:18:06.366   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-14 07:18:06.366   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-14 07:18:06.366   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 07:18:06.367   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-14 07:18:06.403  4916  5952 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-14 07:18:07.613  5614  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 07:18:07.613  5614  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:08.423  5614  5959 W !!      : call onHalfStreamCopied
,10-14 07:18:08.423  5614  5959 I testCopyDataAndClose: closing input stream
,10-14 07:18:09.195  5614  5959 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 07:18:09.195  5614  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 07:18:09.196  5614  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 07:18:12.966  5614  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:12.966  5614  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:14.175   928  2973 D ConnectivityService: handlePromptUnvalidated 102
,10-14 07:18:14.966  5614  5660 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-14 07:18:14.966  5614  5660 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:14.966  5614  5660 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-14 07:18:15.049  5614  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-14 07:18:15.049  5614  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:15.049  5614  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 209 and the total number of bytes written 209
,10-14 07:18:15.084  5614  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 07:18:15.084  5614  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:16.736  5614  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 07:18:16.736  5614  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 07:18:16.737  5614  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 07:18:17.115   928  2971 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-14 07:18:20.503  5614  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:20.503  5614  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 07:18:20.504  5614  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 07:18:20.505  5614  5962 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-14 07:18:20.505  5614  5962 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 07:18:20.505  5614  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:20.505  5614  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-14 07:18:20.507  5614  5660 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-14 07:18:20.509  5614  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:20.509  5614  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 07:18:20.510  5614  5963 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
10-14 07:18:20.510  5614  5963 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:20.510  5614  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-14 07:18:20.510  5614  5963 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-14 07:18:20.511  5614  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-14 07:18:20.511  5614  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-14 07:18:20.515  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-14 07:18:20.515  5614  5660 I jxcore-log: 
10-14 07:18:20.516  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-14 07:18:20.516  5614  5660 I jxcore-log: 
10-14 07:18:20.516  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-14 07:18:20.516  5614  5660 I jxcore-log: 
10-14 07:18:20.516  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-14 07:18:20.516  5614  5660 I jxcore-log: 
,10-14 07:18:20.517  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Total duration:  90835'
10-14 07:18:20.517  5614  5660 I jxcore-log: 
,10-14 07:18:20.519  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-14 07:18:20.519  5614  5660 I jxcore-log: 
,10-14 07:18:20.523  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.523  5614  5660 I jxcore-log: 
,10-14 07:18:20.524  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.524  5614  5660 I jxcore-log: 
10-14 07:18:20.525  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.525  5614  5660 I jxcore-log: 
,10-14 07:18:20.525  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.525  5614  5660 I jxcore-log: 
,10-14 07:18:20.525  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 07:18:20.525  5614  5660 I jxcore-log: 
10-14 07:18:20.526  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 07:18:20.526  5614  5660 I jxcore-log: 
10-14 07:18:20.526  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.526  5614  5660 I jxcore-log: 
10-14 07:18:20.526  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.526  5614  5660 I jxcore-log: 
10-14 07:18:20.526  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 07:18:20.526  5614  5660 I jxcore-log: 
10-14 07:18:20.527  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 07:18:20.527  5614  5660 I jxcore-log: 
10-14 07:18:20.527  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 07:18:20.527  5614  5660 I jxcore-log: 
,10-14 07:18:20.527  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.527  5614  5660 I jxcore-log: 
10-14 07:18:20.527  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.527  5614  5660 I jxcore-log: 
10-14 07:18:20.527  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.527  5614  5660 I jxcore-log: 
10-14 07:18:20.528  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.528  5614  5660 I jxcore-log: 
10-14 07:18:20.528  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.528  5614  5660 I jxcore-log: 
10-14 07:18:20.528  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.528  5614  5660 I jxcore-log: 
10-14 07:18:20.529  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.529  5614  5660 I jxcore-log: 
,10-14 07:18:20.529  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.529  5614  5660 I jxcore-log: 
10-14 07:18:20.529  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.529  5614  5660 I jxcore-log: 
10-14 07:18:20.529  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.529  5614  5660 I jxcore-log: 
10-14 07:18:20.529  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.529  5614  5660 I jxcore-log: 
,10-14 07:18:20.530  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.530  5614  5660 I jxcore-log: 
10-14 07:18:20.531  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.531  5614  5660 I jxcore-log: 
10-14 07:18:20.531  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.531  5614  5660 I jxcore-log: 
10-14 07:18:20.532  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.532  5614  5660 I jxcore-log: 
10-14 07:18:20.532  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.532  5614  5660 I jxcore-log: 
10-14 07:18:20.532  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.532  5614  5660 I jxcore-log: 
10-14 07:18:20.532  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.532  5614  5660 I jxcore-log: 
,10-14 07:18:20.533  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.533  5614  5660 I jxcore-log: 
10-14 07:18:20.533  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.533  5614  5660 I jxcore-log: 
10-14 07:18:20.533  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.533  5614  5660 I jxcore-log: 
10-14 07:18:20.533  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.533  5614  5660 I jxcore-log: 
10-14 07:18:20.533  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.533  5614  5660 I jxcore-log: 
10-14 07:18:20.534  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.534  5614  5660 I jxcore-log: 
10-14 07:18:20.534  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.534  5614  5660 I jxcore-log: 
10-14 07:18:20.534  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.534  5614  5660 I jxcore-log: 
,10-14 07:18:20.535  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.535  5614  5660 I jxcore-log: 
10-14 07:18:20.535  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.535  5614  5660 I jxcore-log: 
10-14 07:18:20.535  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.535  5614  5660 I jxcore-log: 
10-14 07:18:20.535  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 07:18:20.535  5614  5660 I jxcore-log: 
10-14 07:18:20.535  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.535  5614  5660 I jxcore-log: 
10-14 07:18:20.536  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.536  5614  5660 I jxcore-log: 
10-14 07:18:20.536  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.536  5614  5660 I jxcore-log: 
,10-14 07:18:20.536  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.536  5614  5660 I jxcore-log: 
10-14 07:18:20.536  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.536  5614  5660 I jxcore-log: 
10-14 07:18:20.536  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 07:18:20.536  5614  5660 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-14 07:18:20.537  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.537  5614  5660 I jxcore-log: 
10-14 07:18:20.537  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.537  5614  5660 I jxcore-log: 
10-14 07:18:20.537  5614  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 07:18:20.537  5614  5660 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-14 07:18:20.537  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 07:18:20.537  5614  5660 I jxcore-log: 
10-14 07:18:20.538  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 07:18:20.538  5614  5660 I jxcore-log: 
10-14 07:18:20.538  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 07:18:20.538  5614  5660 I jxcore-log: 
10-14 07:18:20.538  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 07:18:20.538  5614  5660 I jxcore-log: 
10-14 07:18:20.538  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.538  5614  5660 I jxcore-log: 
10-14 07:18:20.538  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
10-14 07:18:20.538  5614  5660 I jxcore-log: 
,10-14 07:18:20.544  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-14 07:18:20.544  5614  5660 I jxcore-log: 
10-14 07:18:20.544  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - WARN testUtils: 'myNameCallback not set!'
10-14 07:18:20.544  5614  5660 I jxcore-log: 
10-14 07:18:20.545  5614  5660 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-14 07:18:20.545  5614  5660 I jxcore-log: 2016-10-14 11:18:20 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-14 07:18:20.545  5614  5660 I jxcore-log: 
10-14 07:18:20.546  5614  5614 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-14 07:18:22.548  5614  5660 I jxcore-log: 2016-10-14 11:18:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-14 07:18:22.548  5614  5660 I jxcore-log: 
,10-14 07:18:22.873  5614  5660 I jxcore-log: 2016-10-14 11:18:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-14 07:18:22.873  5614  5660 I jxcore-log: 
,10-14 07:18:22.886  5614  5660 I jxcore-log: 2016-10-14 11:18:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-14 07:18:22.886  5614  5660 I jxcore-log: 
,10-14 07:18:23.971  5614  5660 I jxcore-log: 2016-10-14 11:18:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-14 07:18:23.971  5614  5660 I jxcore-log: 
,10-14 07:18:24.130  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-14 07:18:24.130  5614  5660 I jxcore-log: 
,10-14 07:18:24.136  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-14 07:18:24.136  5614  5660 I jxcore-log: 
,10-14 07:18:24.140  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-14 07:18:24.140  5614  5660 I jxcore-log: 
,10-14 07:18:24.604  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-14 07:18:24.604  5614  5660 I jxcore-log: 
,10-14 07:18:24.646  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-14 07:18:24.646  5614  5660 I jxcore-log: 
,10-14 07:18:24.659  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-14 07:18:24.659  5614  5660 I jxcore-log: 
,10-14 07:18:24.663  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-14 07:18:24.663  5614  5660 I jxcore-log: 
,10-14 07:18:24.945  5614  5660 I jxcore-log: 2016-10-14 11:18:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-14 07:18:24.945  5614  5660 I jxcore-log: 
,10-14 07:18:25.067  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-14 07:18:25.067  5614  5660 I jxcore-log: 
,10-14 07:18:25.297  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-14 07:18:25.297  5614  5660 I jxcore-log: 
,10-14 07:18:25.306  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-14 07:18:25.306  5614  5660 I jxcore-log: 
,10-14 07:18:25.310  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-14 07:18:25.310  5614  5660 I jxcore-log: 
,10-14 07:18:25.444  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-14 07:18:25.444  5614  5660 I jxcore-log: 
,10-14 07:18:25.450  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-14 07:18:25.450  5614  5660 I jxcore-log: 
,10-14 07:18:25.476  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-14 07:18:25.476  5614  5660 I jxcore-log: 
,10-14 07:18:25.510  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-14 07:18:25.510  5614  5660 I jxcore-log: 
,10-14 07:18:25.516  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-14 07:18:25.516  5614  5660 I jxcore-log: 
,10-14 07:18:25.521  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-14 07:18:25.521  5614  5660 I jxcore-log: 
,10-14 07:18:25.535  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-14 07:18:25.535  5614  5660 I jxcore-log: 
,10-14 07:18:25.538  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-14 07:18:25.538  5614  5660 I jxcore-log: 
,10-14 07:18:25.543  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-14 07:18:25.543  5614  5660 I jxcore-log: 
,10-14 07:18:25.548  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-14 07:18:25.548  5614  5660 I jxcore-log: 
,10-14 07:18:25.560  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-14 07:18:25.560  5614  5660 I jxcore-log: 
,10-14 07:18:25.579  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-14 07:18:25.579  5614  5660 I jxcore-log: 
,10-14 07:18:25.589  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-14 07:18:25.589  5614  5660 I jxcore-log: 
,10-14 07:18:25.600  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-14 07:18:25.600  5614  5660 I jxcore-log: 
,10-14 07:18:25.610  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-14 07:18:25.610  5614  5660 I jxcore-log: 
,10-14 07:18:25.622  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-14 07:18:25.622  5614  5660 I jxcore-log: 
,10-14 07:18:25.632  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-14 07:18:25.632  5614  5660 I jxcore-log: 
,10-14 07:18:25.637  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-14 07:18:25.637  5614  5660 I jxcore-log: 
,10-14 07:18:25.658  5614  5660 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-14 07:18:25.659  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - INFO testUtils: 'BLE multiple advertisement supported'
10-14 07:18:25.659  5614  5660 I jxcore-log: 
,10-14 07:18:25.771  5614  5660 I jxcore-log: 2016-10-14 11:18:25 - DEBUG CoordinatedClient: 'connected to the test server'
10-14 07:18:25.771  5614  5660 I jxcore-log: 
,10-14 07:18:26.271  5614  5660 I jxcore-log: TAP version 13
10-14 07:18:26.271  5614  5660 I jxcore-log: 
,10-14 07:18:26.311  5614  5660 I jxcore-log: # setup
10-14 07:18:26.311  5614  5660 I jxcore-log: 
,10-14 07:18:26.673  5614  5660 I jxcore-log: # calling createNativeListener directly rejects
10-14 07:18:26.673  5614  5660 I jxcore-log: 
,10-14 07:18:27.200  5614  5660 I jxcore-log: 2016-10-14 11:18:27 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:27.200  5614  5660 I jxcore-log: 
,10-14 07:18:27.207  5614  5660 I jxcore-log: 2016-10-14 11:18:27 - DEBUG createNativeListener: 'listening 43408'
10-14 07:18:27.207  5614  5660 I jxcore-log: 
,10-14 07:18:27.215  5614  5660 I jxcore-log: ok 1 Should throw
10-14 07:18:27.215  5614  5660 I jxcore-log: 
,10-14 07:18:27.226  5614  5660 I jxcore-log: # teardown
10-14 07:18:27.226  5614  5660 I jxcore-log: 
,10-14 07:18:27.528   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-14 07:18:27.528   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-14 07:18:27.718  5614  5660 I jxcore-log: # setup
10-14 07:18:27.718  5614  5660 I jxcore-log: 
,10-14 07:18:27.884  5614  5660 I jxcore-log: # emits incomingConnectionState
10-14 07:18:27.884  5614  5660 I jxcore-log: 
,10-14 07:18:28.037  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:28.037  5614  5660 I jxcore-log: 
,10-14 07:18:28.042  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'listening 37970'
10-14 07:18:28.042  5614  5660 I jxcore-log: 
,10-14 07:18:28.052  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:28.052  5614  5660 I jxcore-log: 
,10-14 07:18:28.055  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:28.055  5614  5660 I jxcore-log: 
,10-14 07:18:28.064  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'new mux'
10-14 07:18:28.064  5614  5660 I jxcore-log: 
,10-14 07:18:28.069  5614  5660 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-14 07:18:28.069  5614  5660 I jxcore-log: 
,10-14 07:18:28.084  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:28.084  5614  5660 I jxcore-log: 
,10-14 07:18:28.085  5614  5660 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-14 07:18:28.085  5614  5660 I jxcore-log: 
,10-14 07:18:28.093  5614  5660 I jxcore-log: # teardown
10-14 07:18:28.093  5614  5660 I jxcore-log: 
,10-14 07:18:28.171  5614  5660 I jxcore-log: # setup
10-14 07:18:28.171  5614  5660 I jxcore-log: 
,10-14 07:18:28.330  5614  5660 I jxcore-log: # emits routerPortConnectionFailed
10-14 07:18:28.330  5614  5660 I jxcore-log: 
,10-14 07:18:28.571  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:28.571  5614  5660 I jxcore-log: 
,10-14 07:18:28.575  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'listening 46226'
10-14 07:18:28.575  5614  5660 I jxcore-log: 
,10-14 07:18:28.583  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:28.583  5614  5660 I jxcore-log: 
,10-14 07:18:28.584  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:28.584  5614  5660 I jxcore-log: 
,10-14 07:18:28.586  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'new mux'
10-14 07:18:28.586  5614  5660 I jxcore-log: 
,10-14 07:18:28.610  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:28.610  5614  5660 I jxcore-log: 
,10-14 07:18:28.612  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:28.612  5614  5660 I jxcore-log: 
,10-14 07:18:28.616  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: ' $c@net.js:837:7
10-14 07:18:28.616  5614  5660 I jxcore-log: $09@net.js:829:13
10-14 07:18:28.616  5614  5660 I jxcore-log: '
10-14 07:18:28.616  5614  5660 I jxcore-log: 
,10-14 07:18:28.617  5614  5660 I jxcore-log: ok 4 tried to connect to right port
10-14 07:18:28.617  5614  5660 I jxcore-log: 
10-14 07:18:28.618  5614  5660 I jxcore-log: ok 5 failed due to refused connection
10-14 07:18:28.618  5614  5660 I jxcore-log: 
10-14 07:18:28.619  5614  5660 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-14 07:18:28.619  5614  5660 I jxcore-log: 
,10-14 07:18:28.622  5614  5660 I jxcore-log: # teardown
10-14 07:18:28.622  5614  5660 I jxcore-log: 
,10-14 07:18:28.624  5614  5660 I jxcore-log: 2016-10-14 11:18:28 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:28.624  5614  5660 I jxcore-log: 
,10-14 07:18:29.565  5614  5660 I jxcore-log: 2016-10-14 11:18:29 - DEBUG createNativeListener: 'mux close'
10-14 07:18:29.565  5614  5660 I jxcore-log: 
,10-14 07:18:29.573  5614  5660 I jxcore-log: 2016-10-14 11:18:29 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:29.573  5614  5660 I jxcore-log: 
,10-14 07:18:29.588  5614  5660 I jxcore-log: # setup
10-14 07:18:29.588  5614  5660 I jxcore-log: 
,10-14 07:18:30.721  5614  5660 I jxcore-log: # native server connections all up
10-14 07:18:30.721  5614  5660 I jxcore-log: 
,10-14 07:18:30.819  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:30.819  5614  5660 I jxcore-log: 
,10-14 07:18:30.824  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'listening 43767'
10-14 07:18:30.824  5614  5660 I jxcore-log: 
,10-14 07:18:30.834  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:30.834  5614  5660 I jxcore-log: 
,10-14 07:18:30.835  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:30.835  5614  5660 I jxcore-log: 
,10-14 07:18:30.837  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'new mux'
10-14 07:18:30.837  5614  5660 I jxcore-log: 
,10-14 07:18:30.868  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:30.868  5614  5660 I jxcore-log: 
,10-14 07:18:30.872  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:30.872  5614  5660 I jxcore-log: 
,10-14 07:18:30.875  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:30.875  5614  5660 I jxcore-log: 
,10-14 07:18:30.878  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:30.878  5614  5660 I jxcore-log: 
,10-14 07:18:30.902  5614  5660 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-14 07:18:30.902  5614  5660 I jxcore-log: 
,10-14 07:18:30.902  5614  5660 I jxcore-log: ok 8 Send/recvd #1 should be same
10-14 07:18:30.902  5614  5660 I jxcore-log: 
10-14 07:18:30.905  5614  5660 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-14 07:18:30.905  5614  5660 I jxcore-log: 
10-14 07:18:30.906  5614  5660 I jxcore-log: ok 10 Send/recvd #2 should be same
10-14 07:18:30.906  5614  5660 I jxcore-log: 
,10-14 07:18:30.909  5614  5660 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-14 07:18:30.909  5614  5660 I jxcore-log: 
,10-14 07:18:30.919  5614  5660 I jxcore-log: # teardown
10-14 07:18:30.919  5614  5660 I jxcore-log: 
,10-14 07:18:30.975  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:30.975  5614  5660 I jxcore-log: 
,10-14 07:18:30.977  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:30.977  5614  5660 I jxcore-log: 
,10-14 07:18:30.979  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'mux close'
10-14 07:18:30.979  5614  5660 I jxcore-log: 
10-14 07:18:30.984  5614  5660 I jxcore-log: 2016-10-14 11:18:30 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:30.984  5614  5660 I jxcore-log: 
,10-14 07:18:30.996  5614  5660 I jxcore-log: # setup
10-14 07:18:30.996  5614  5660 I jxcore-log: 
,10-14 07:18:31.119  5614  5660 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-14 07:18:31.119  5614  5660 I jxcore-log: 
,10-14 07:18:31.167  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:31.167  5614  5660 I jxcore-log: 
,10-14 07:18:31.171  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'listening 48464'
10-14 07:18:31.171  5614  5660 I jxcore-log: 
,10-14 07:18:31.178  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:31.178  5614  5660 I jxcore-log: 
,10-14 07:18:31.180  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:31.180  5614  5660 I jxcore-log: 
,10-14 07:18:31.185  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new mux'
10-14 07:18:31.185  5614  5660 I jxcore-log: 
,10-14 07:18:31.198  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:31.198  5614  5660 I jxcore-log: 
,10-14 07:18:31.202  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:31.202  5614  5660 I jxcore-log: 
,10-14 07:18:31.214  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:31.214  5614  5660 I jxcore-log: 
,10-14 07:18:31.226  5614  5660 I jxcore-log: ok 12 socket shouldn't close until after stream
10-14 07:18:31.226  5614  5660 I jxcore-log: 
,10-14 07:18:31.227  5614  5660 I jxcore-log: ok 13 incoming remains open
10-14 07:18:31.227  5614  5660 I jxcore-log: 
,10-14 07:18:31.234  5614  5660 I jxcore-log: # teardown
10-14 07:18:31.234  5614  5660 I jxcore-log: 
,10-14 07:18:31.268  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'mux close'
10-14 07:18:31.268  5614  5660 I jxcore-log: 
,10-14 07:18:31.274  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:31.274  5614  5660 I jxcore-log: 
,10-14 07:18:31.285  5614  5660 I jxcore-log: # setup
10-14 07:18:31.285  5614  5660 I jxcore-log: 
,10-14 07:18:31.374  5614  5660 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-14 07:18:31.374  5614  5660 I jxcore-log: 
,10-14 07:18:31.447  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:31.447  5614  5660 I jxcore-log: 
,10-14 07:18:31.452  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'listening 41565'
10-14 07:18:31.452  5614  5660 I jxcore-log: 
,10-14 07:18:31.459  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:31.459  5614  5660 I jxcore-log: 
,10-14 07:18:31.460  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:31.460  5614  5660 I jxcore-log: 
,10-14 07:18:31.463  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new mux'
10-14 07:18:31.463  5614  5660 I jxcore-log: 
,10-14 07:18:31.474  5614  5660 I jxcore-log: ok 14 we should not have gotten an error
10-14 07:18:31.474  5614  5660 I jxcore-log: 
,10-14 07:18:31.480  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:31.480  5614  5660 I jxcore-log: 
,10-14 07:18:31.485  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:31.485  5614  5660 I jxcore-log: 
,10-14 07:18:31.494  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:31.494  5614  5660 I jxcore-log: 
,10-14 07:18:31.496  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:31.496  5614  5660 I jxcore-log: 
,10-14 07:18:31.503  5614  5660 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-14 07:18:31.503  5614  5660 I jxcore-log: 
,10-14 07:18:31.504  5614  5660 I jxcore-log: ok 16 incoming is cleaned up
10-14 07:18:31.504  5614  5660 I jxcore-log: 
,10-14 07:18:31.508  5614  5660 I jxcore-log: # teardown
10-14 07:18:31.508  5614  5660 I jxcore-log: 
,10-14 07:18:31.569  5614  5660 I jxcore-log: # setup
10-14 07:18:31.569  5614  5660 I jxcore-log: 
,10-14 07:18:31.628  5614  5660 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-14 07:18:31.628  5614  5660 I jxcore-log: 
,10-14 07:18:31.712  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:31.712  5614  5660 I jxcore-log: 
,10-14 07:18:31.717  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'listening 39452'
10-14 07:18:31.717  5614  5660 I jxcore-log: 
,10-14 07:18:31.723  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:31.723  5614  5660 I jxcore-log: 
,10-14 07:18:31.725  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:31.725  5614  5660 I jxcore-log: 
,10-14 07:18:31.728  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new mux'
10-14 07:18:31.728  5614  5660 I jxcore-log: 
,10-14 07:18:31.740  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:31.740  5614  5660 I jxcore-log: 
,10-14 07:18:31.743  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:31.743  5614  5660 I jxcore-log: 
,10-14 07:18:31.757  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:31.757  5614  5660 I jxcore-log: 
,10-14 07:18:31.764  5614  5660 I jxcore-log: ok 17 stream was closed
10-14 07:18:31.764  5614  5660 I jxcore-log: 
,10-14 07:18:31.765  5614  5660 I jxcore-log: ok 18 incoming should survive
10-14 07:18:31.765  5614  5660 I jxcore-log: 
10-14 07:18:31.765  5614  5660 I jxcore-log: ok 19 mux should have no streams
10-14 07:18:31.765  5614  5660 I jxcore-log: 
,10-14 07:18:31.770  5614  5660 I jxcore-log: # teardown
10-14 07:18:31.770  5614  5660 I jxcore-log: 
,10-14 07:18:31.895  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'mux close'
10-14 07:18:31.895  5614  5660 I jxcore-log: 
,10-14 07:18:31.912  5614  5660 I jxcore-log: 2016-10-14 11:18:31 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:31.912  5614  5660 I jxcore-log: 
,10-14 07:18:31.925  5614  5660 I jxcore-log: # setup
10-14 07:18:31.925  5614  5660 I jxcore-log: 
,10-14 07:18:32.124  5614  5660 I jxcore-log: # native server - closing the whole server cleans everything up
10-14 07:18:32.124  5614  5660 I jxcore-log: 
,10-14 07:18:32.197  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:32.197  5614  5660 I jxcore-log: 
,10-14 07:18:32.204  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'listening 40509'
10-14 07:18:32.204  5614  5660 I jxcore-log: 
,10-14 07:18:32.212  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.212  5614  5660 I jxcore-log: 
,10-14 07:18:32.213  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.213  5614  5660 I jxcore-log: 
10-14 07:18:32.215  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.215  5614  5660 I jxcore-log: 
,10-14 07:18:32.226  5614  5660 I jxcore-log: ok 20 we should not have gotten an error
10-14 07:18:32.226  5614  5660 I jxcore-log: 
,10-14 07:18:32.232  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.232  5614  5660 I jxcore-log: 
,10-14 07:18:32.235  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.235  5614  5660 I jxcore-log: 
,10-14 07:18:32.243  5614  5660 I jxcore-log: ok 21 Buffers are identical
10-14 07:18:32.243  5614  5660 I jxcore-log: 
,10-14 07:18:32.245  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.245  5614  5660 I jxcore-log: 
,10-14 07:18:32.247  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.247  5614  5660 I jxcore-log: 
,10-14 07:18:32.249  5614  5660 I jxcore-log: ok 22 native server is nulled out
10-14 07:18:32.249  5614  5660 I jxcore-log: 
,10-14 07:18:32.249  5614  5660 I jxcore-log: ok 23 native server should be closed
10-14 07:18:32.249  5614  5660 I jxcore-log: 
10-14 07:18:32.250  5614  5660 I jxcore-log: ok 24 incoming has been removed
10-14 07:18:32.250  5614  5660 I jxcore-log: 
,10-14 07:18:32.250  5614  5660 I jxcore-log: ok 25 Incoming should be done
10-14 07:18:32.250  5614  5660 I jxcore-log: 
10-14 07:18:32.250  5614  5660 I jxcore-log: ok 26 The mux object should be closed
10-14 07:18:32.250  5614  5660 I jxcore-log: 
10-14 07:18:32.251  5614  5660 I jxcore-log: ok 27 The mux stream should be closed
10-14 07:18:32.251  5614  5660 I jxcore-log: 
,10-14 07:18:32.252  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.252  5614  5660 I jxcore-log: 
,10-14 07:18:32.264  5614  5660 I jxcore-log: # teardown
10-14 07:18:32.264  5614  5660 I jxcore-log: 
,10-14 07:18:32.322  5614  5660 I jxcore-log: # setup
10-14 07:18:32.322  5614  5660 I jxcore-log: 
,10-14 07:18:32.373  5614  5660 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-14 07:18:32.373  5614  5660 I jxcore-log: 
,10-14 07:18:32.456  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:32.456  5614  5660 I jxcore-log: 
,10-14 07:18:32.461  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'listening 39932'
10-14 07:18:32.461  5614  5660 I jxcore-log: 
,10-14 07:18:32.490  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.490  5614  5660 I jxcore-log: 
,10-14 07:18:32.490  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.490  5614  5660 I jxcore-log: 
10-14 07:18:32.492  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.492  5614  5660 I jxcore-log: 
,10-14 07:18:32.494  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.494  5614  5660 I jxcore-log: 
,10-14 07:18:32.495  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.495  5614  5660 I jxcore-log: 
,10-14 07:18:32.496  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.496  5614  5660 I jxcore-log: 
,10-14 07:18:32.499  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.499  5614  5660 I jxcore-log: 
,10-14 07:18:32.499  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.499  5614  5660 I jxcore-log: 
10-14 07:18:32.500  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.500  5614  5660 I jxcore-log: 
,10-14 07:18:32.503  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.503  5614  5660 I jxcore-log: 
,10-14 07:18:32.503  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.503  5614  5660 I jxcore-log: 
,10-14 07:18:32.505  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.505  5614  5660 I jxcore-log: 
,10-14 07:18:32.507  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.507  5614  5660 I jxcore-log: 
,10-14 07:18:32.508  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.508  5614  5660 I jxcore-log: 
,10-14 07:18:32.511  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.511  5614  5660 I jxcore-log: 
,10-14 07:18:32.514  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.514  5614  5660 I jxcore-log: 
,10-14 07:18:32.515  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.515  5614  5660 I jxcore-log: 
,10-14 07:18:32.516  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.516  5614  5660 I jxcore-log: 
,10-14 07:18:32.524  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.524  5614  5660 I jxcore-log: 
,10-14 07:18:32.525  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.525  5614  5660 I jxcore-log: 
,10-14 07:18:32.526  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.526  5614  5660 I jxcore-log: 
,10-14 07:18:32.529  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.529  5614  5660 I jxcore-log: 
,10-14 07:18:32.529  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.529  5614  5660 I jxcore-log: 
,10-14 07:18:32.529  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.529  5614  5660 I jxcore-log: 
,10-14 07:18:32.531  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.531  5614  5660 I jxcore-log: 
10-14 07:18:32.531  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.531  5614  5660 I jxcore-log: 
,10-14 07:18:32.532  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.532  5614  5660 I jxcore-log: 
,10-14 07:18:32.533  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:32.533  5614  5660 I jxcore-log: 
,10-14 07:18:32.533  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:32.533  5614  5660 I jxcore-log: 
10-14 07:18:32.534  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new mux'
10-14 07:18:32.534  5614  5660 I jxcore-log: 
,10-14 07:18:32.588  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.588  5614  5660 I jxcore-log: 
,10-14 07:18:32.590  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.590  5614  5660 I jxcore-log: 
,10-14 07:18:32.592  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.592  5614  5660 I jxcore-log: 
,10-14 07:18:32.593  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.593  5614  5660 I jxcore-log: 
,10-14 07:18:32.594  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.594  5614  5660 I jxcore-log: 
,10-14 07:18:32.595  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.595  5614  5660 I jxcore-log: 
,10-14 07:18:32.596  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.596  5614  5660 I jxcore-log: 
,10-14 07:18:32.597  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.597  5614  5660 I jxcore-log: 
,10-14 07:18:32.599  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.599  5614  5660 I jxcore-log: 
,10-14 07:18:32.600  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.600  5614  5660 I jxcore-log: 
,10-14 07:18:32.601  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.601  5614  5660 I jxcore-log: 
10-14 07:18:32.602  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.602  5614  5660 I jxcore-log: 
,10-14 07:18:32.602  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.602  5614  5660 I jxcore-log: 
10-14 07:18:32.603  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.603  5614  5660 I jxcore-log: 
,10-14 07:18:32.604  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.604  5614  5660 I jxcore-log: 
10-14 07:18:32.605  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.605  5614  5660 I jxcore-log: 
,10-14 07:18:32.606  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.606  5614  5660 I jxcore-log: 
,10-14 07:18:32.607  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.607  5614  5660 I jxcore-log: 
,10-14 07:18:32.608  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.608  5614  5660 I jxcore-log: 
10-14 07:18:32.609  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.609  5614  5660 I jxcore-log: 
,10-14 07:18:32.609  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.609  5614  5660 I jxcore-log: 
10-14 07:18:32.610  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.610  5614  5660 I jxcore-log: 
,10-14 07:18:32.611  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.611  5614  5660 I jxcore-log: 
,10-14 07:18:32.612  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.612  5614  5660 I jxcore-log: 
,10-14 07:18:32.613  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.613  5614  5660 I jxcore-log: 
10-14 07:18:32.614  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.614  5614  5660 I jxcore-log: 
,10-14 07:18:32.615  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.615  5614  5660 I jxcore-log: 
,10-14 07:18:32.615  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.615  5614  5660 I jxcore-log: 
,10-14 07:18:32.616  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.616  5614  5660 I jxcore-log: 
10-14 07:18:32.617  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.617  5614  5660 I jxcore-log: 
10-14 07:18:32.617  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.617  5614  5660 I jxcore-log: 
,10-14 07:18:32.618  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.618  5614  5660 I jxcore-log: 
,10-14 07:18:32.619  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.619  5614  5660 I jxcore-log: 
,10-14 07:18:32.620  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.620  5614  5660 I jxcore-log: 
10-14 07:18:32.621  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.621  5614  5660 I jxcore-log: 
,10-14 07:18:32.622  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.622  5614  5660 I jxcore-log: 
10-14 07:18:32.622  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.622  5614  5660 I jxcore-log: 
,10-14 07:18:32.623  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.623  5614  5660 I jxcore-log: 
10-14 07:18:32.624  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.624  5614  5660 I jxcore-log: 
,10-14 07:18:32.625  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.625  5614  5660 I jxcore-log: 
,10-14 07:18:32.626  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.626  5614  5660 I jxcore-log: 
,10-14 07:18:32.627  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.627  5614  5660 I jxcore-log: 
10-14 07:18:32.627  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.627  5614  5660 I jxcore-log: 
,10-14 07:18:32.628  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.628  5614  5660 I jxcore-log: 
10-14 07:18:32.629  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.629  5614  5660 I jxcore-log: 
,10-14 07:18:32.630  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.630  5614  5660 I jxcore-log: 
,10-14 07:18:32.630  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.630  5614  5660 I jxcore-log: 
10-14 07:18:32.631  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.631  5614  5660 I jxcore-log: 
,10-14 07:18:32.638  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.638  5614  5660 I jxcore-log: 
,10-14 07:18:32.639  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.639  5614  5660 I jxcore-log: 
,10-14 07:18:32.640  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.640  5614  5660 I jxcore-log: 
,10-14 07:18:32.641  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.641  5614  5660 I jxcore-log: 
,10-14 07:18:32.642  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.642  5614  5660 I jxcore-log: 
,10-14 07:18:32.642  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.642  5614  5660 I jxcore-log: 
,10-14 07:18:32.643  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.643  5614  5660 I jxcore-log: 
10-14 07:18:32.644  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.644  5614  5660 I jxcore-log: 
10-14 07:18:32.645  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.645  5614  5660 I jxcore-log: 
10-14 07:18:32.646  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.646  5614  5660 I jxcore-log: 
,10-14 07:18:32.647  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.647  5614  5660 I jxcore-log: 
10-14 07:18:32.647  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.647  5614  5660 I jxcore-log: 
10-14 07:18:32.648  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.648  5614  5660 I jxcore-log: 
10-14 07:18:32.649  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.649  5614  5660 I jxcore-log: 
,10-14 07:18:32.649  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.649  5614  5660 I jxcore-log: 
10-14 07:18:32.650  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.650  5614  5660 I jxcore-log: 
10-14 07:18:32.651  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.651  5614  5660 I jxcore-log: 
,10-14 07:18:32.652  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.652  5614  5660 I jxcore-log: 
10-14 07:18:32.652  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.652  5614  5660 I jxcore-log: 
10-14 07:18:32.653  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.653  5614  5660 I jxcore-log: 
,10-14 07:18:32.653  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.653  5614  5660 I jxcore-log: 
10-14 07:18:32.654  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.654  5614  5660 I jxcore-log: 
10-14 07:18:32.655  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.655  5614  5660 I jxcore-log: 
,10-14 07:18:32.655  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.655  5614  5660 I jxcore-log: 
10-14 07:18:32.656  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.656  5614  5660 I jxcore-log: 
10-14 07:18:32.657  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.657  5614  5660 I jxcore-log: 
10-14 07:18:32.657  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.657  5614  5660 I jxcore-log: 
,10-14 07:18:32.658  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.658  5614  5660 I jxcore-log: 
,10-14 07:18:32.659  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.659  5614  5660 I jxcore-log: 
,10-14 07:18:32.660  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.660  5614  5660 I jxcore-log: 
10-14 07:18:32.660  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:32.660  5614  5660 I jxcore-log: 
,10-14 07:18:32.661  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:32.661  5614  5660 I jxcore-log: 
,10-14 07:18:32.705  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.705  5614  5660 I jxcore-log: 
,10-14 07:18:32.706  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.706  5614  5660 I jxcore-log: 
10-14 07:18:32.707  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.707  5614  5660 I jxcore-log: 
,10-14 07:18:32.708  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.708  5614  5660 I jxcore-log: 
10-14 07:18:32.708  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.708  5614  5660 I jxcore-log: 
,10-14 07:18:32.709  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.709  5614  5660 I jxcore-log: 
10-14 07:18:32.709  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.709  5614  5660 I jxcore-log: 
,10-14 07:18:32.710  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.710  5614  5660 I jxcore-log: 
10-14 07:18:32.710  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.710  5614  5660 I jxcore-log: 
,10-14 07:18:32.711  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.711  5614  5660 I jxcore-log: 
,10-14 07:18:32.711  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.711  5614  5660 I jxcore-log: 
10-14 07:18:32.712  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.712  5614  5660 I jxcore-log: 
,10-14 07:18:32.712  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.712  5614  5660 I jxcore-log: 
10-14 07:18:32.712  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.712  5614  5660 I jxcore-log: 
10-14 07:18:32.713  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.713  5614  5660 I jxcore-log: 
10-14 07:18:32.714  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.714  5614  5660 I jxcore-log: 
,10-14 07:18:32.714  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.714  5614  5660 I jxcore-log: 
10-14 07:18:32.715  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.715  5614  5660 I jxcore-log: 
10-14 07:18:32.715  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.715  5614  5660 I jxcore-log: 
,10-14 07:18:32.715  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.715  5614  5660 I jxcore-log: 
,10-14 07:18:32.716  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.716  5614  5660 I jxcore-log: 
10-14 07:18:32.716  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.716  5614  5660 I jxcore-log: 
10-14 07:18:32.717  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.717  5614  5660 I jxcore-log: 
,10-14 07:18:32.717  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.717  5614  5660 I jxcore-log: 
10-14 07:18:32.718  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.718  5614  5660 I jxcore-log: 
10-14 07:18:32.718  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.718  5614  5660 I jxcore-log: 
,10-14 07:18:32.719  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.719  5614  5660 I jxcore-log: 
10-14 07:18:32.719  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.719  5614  5660 I jxcore-log: 
10-14 07:18:32.719  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.719  5614  5660 I jxcore-log: 
10-14 07:18:32.720  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.720  5614  5660 I jxcore-log: 
,10-14 07:18:32.720  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.720  5614  5660 I jxcore-log: 
10-14 07:18:32.721  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.721  5614  5660 I jxcore-log: 
10-14 07:18:32.721  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.721  5614  5660 I jxcore-log: 
10-14 07:18:32.722  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.722  5614  5660 I jxcore-log: 
,10-14 07:18:32.722  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.722  5614  5660 I jxcore-log: 
10-14 07:18:32.722  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.722  5614  5660 I jxcore-log: 
10-14 07:18:32.723  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.723  5614  5660 I jxcore-log: 
10-14 07:18:32.723  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.723  5614  5660 I jxcore-log: 
,10-14 07:18:32.724  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.724  5614  5660 I jxcore-log: 
10-14 07:18:32.724  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.724  5614  5660 I jxcore-log: 
10-14 07:18:32.724  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.724  5614  5660 I jxcore-log: 
,10-14 07:18:32.725  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.725  5614  5660 I jxcore-log: 
10-14 07:18:32.725  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.725  5614  5660 I jxcore-log: 
,10-14 07:18:32.726  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.726  5614  5660 I jxcore-log: 
10-14 07:18:32.727  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.727  5614  5660 I jxcore-log: 
,10-14 07:18:32.728  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.728  5614  5660 I jxcore-log: 
,10-14 07:18:32.730  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.730  5614  5660 I jxcore-log: 
,10-14 07:18:32.731  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.731  5614  5660 I jxcore-log: 
10-14 07:18:32.731  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:32.731  5614  5660 I jxcore-log: 
10-14 07:18:32.732  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'mux close'
10-14 07:18:32.732  5614  5660 I jxcore-log: 
,10-14 07:18:32.734  5614  5660 I jxcore-log: ok 28 native server is nulled out
10-14 07:18:32.734  5614  5660 I jxcore-log: 
,10-14 07:18:32.734  5614  5660 I jxcore-log: ok 29 native server should be closed
10-14 07:18:32.734  5614  5660 I jxcore-log: 
10-14 07:18:32.734  5614  5660 I jxcore-log: ok 30 incoming has been removed
10-14 07:18:32.734  5614  5660 I jxcore-log: 
10-14 07:18:32.735  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.735  5614  5660 I jxcore-log: 
,10-14 07:18:32.736  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.736  5614  5660 I jxcore-log: 
10-14 07:18:32.736  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.736  5614  5660 I jxcore-log: 
,10-14 07:18:32.736  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.736  5614  5660 I jxcore-log: 
10-14 07:18:32.736  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.736  5614  5660 I jxcore-log: 
,10-14 07:18:32.737  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.737  5614  5660 I jxcore-log: 
,10-14 07:18:32.737  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.737  5614  5660 I jxcore-log: 
10-14 07:18:32.737  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.737  5614  5660 I jxcore-log: 
10-14 07:18:32.737  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.737  5614  5660 I jxcore-log: 
,10-14 07:18:32.737  5614  5660 I jxcore-log: 2016-10-14 11:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:32.737  5614  5660 I jxcore-log: 
,10-14 07:18:32.810  5614  5660 I jxcore-log: # teardown
10-14 07:18:32.810  5614  5660 I jxcore-log: 
,10-14 07:18:32.912  5614  5660 I jxcore-log: # setup
10-14 07:18:32.912  5614  5660 I jxcore-log: 
,10-14 07:18:34.714  5614  5660 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-14 07:18:34.714  5614  5660 I jxcore-log: 
,10-14 07:18:35.627  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:35.627  5614  5660 I jxcore-log: 
,10-14 07:18:35.632  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'listening 48477'
10-14 07:18:35.632  5614  5660 I jxcore-log: 
,10-14 07:18:35.643  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:35.643  5614  5660 I jxcore-log: 
,10-14 07:18:35.644  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:35.644  5614  5660 I jxcore-log: 
,10-14 07:18:35.647  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'new mux'
10-14 07:18:35.647  5614  5660 I jxcore-log: 
,10-14 07:18:35.656  5614  5660 I jxcore-log: ok 31 we should not have gotten an error
10-14 07:18:35.656  5614  5660 I jxcore-log: 
,10-14 07:18:35.661  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:35.661  5614  5660 I jxcore-log: 
,10-14 07:18:35.665  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:35.665  5614  5660 I jxcore-log: 
,10-14 07:18:35.673  5614  5660 I jxcore-log: ok 32 Buffers are identical
10-14 07:18:35.673  5614  5660 I jxcore-log: 
,10-14 07:18:35.674  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:35.674  5614  5660 I jxcore-log: 
,10-14 07:18:35.677  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'mux close'
10-14 07:18:35.677  5614  5660 I jxcore-log: 
,10-14 07:18:35.689  5614  5660 I jxcore-log: 2016-10-14 11:18:35 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:35.689  5614  5660 I jxcore-log: 
,10-14 07:18:35.690  5614  5660 I jxcore-log: ok 33 server should be fine
10-14 07:18:35.690  5614  5660 I jxcore-log: 
10-14 07:18:35.690  5614  5660 I jxcore-log: ok 34 server should be open
10-14 07:18:35.690  5614  5660 I jxcore-log: 
10-14 07:18:35.690  5614  5660 I jxcore-log: ok 35 incoming has been removed
10-14 07:18:35.690  5614  5660 I jxcore-log: 
10-14 07:18:35.690  5614  5660 I jxcore-log: ok 36 The mux object should be closed
10-14 07:18:35.690  5614  5660 I jxcore-log: 
10-14 07:18:35.691  5614  5660 I jxcore-log: ok 37 The mux stream should be closed
10-14 07:18:35.691  5614  5660 I jxcore-log: 
,10-14 07:18:35.696  5614  5660 I jxcore-log: # teardown
10-14 07:18:35.696  5614  5660 I jxcore-log: 
,10-14 07:18:36.770  5614  5660 I jxcore-log: # setup
10-14 07:18:36.770  5614  5660 I jxcore-log: 
,10-14 07:18:37.067  5614  5660 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-14 07:18:37.067  5614  5660 I jxcore-log: 
,10-14 07:18:37.988  5614  5660 I jxcore-log: 2016-10-14 11:18:37 - DEBUG createNativeListener: 'creating native server'
10-14 07:18:37.988  5614  5660 I jxcore-log: 
,10-14 07:18:37.996  5614  5660 I jxcore-log: 2016-10-14 11:18:37 - DEBUG createNativeListener: 'listening 37316'
10-14 07:18:37.996  5614  5660 I jxcore-log: 
,10-14 07:18:38.005  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'new incoming socket'
10-14 07:18:38.005  5614  5660 I jxcore-log: 
,10-14 07:18:38.006  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'creating incoming mux'
10-14 07:18:38.006  5614  5660 I jxcore-log: 
10-14 07:18:38.008  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'new mux'
10-14 07:18:38.008  5614  5660 I jxcore-log: 
,10-14 07:18:38.017  5614  5660 I jxcore-log: ok 38 we should not have gotten an error
10-14 07:18:38.017  5614  5660 I jxcore-log: 
,10-14 07:18:38.021  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'new stream: '
10-14 07:18:38.021  5614  5660 I jxcore-log: 
,10-14 07:18:38.024  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'new outgoing socket'
10-14 07:18:38.024  5614  5660 I jxcore-log: 
,10-14 07:18:38.031  5614  5660 I jxcore-log: ok 39 Buffers are identical
10-14 07:18:38.031  5614  5660 I jxcore-log: 
,10-14 07:18:38.036  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'incoming socket timeout'
10-14 07:18:38.036  5614  5660 I jxcore-log: 
,10-14 07:18:38.037  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'stream close:'
10-14 07:18:38.037  5614  5660 I jxcore-log: 
,10-14 07:18:38.040  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'mux close'
10-14 07:18:38.040  5614  5660 I jxcore-log: 
,10-14 07:18:38.045  5614  5660 I jxcore-log: 2016-10-14 11:18:38 - DEBUG createNativeListener: 'incoming socket close'
10-14 07:18:38.045  5614  5660 I jxcore-log: 
10-14 07:18:38.045  5614  5660 I jxcore-log: ok 40 server should be fine
10-14 07:18:38.045  5614  5660 I jxcore-log: 
,10-14 07:18:38.046  5614  5660 I jxcore-log: ok 41 server should be open
10-14 07:18:38.046  5614  5660 I jxcore-log: 
10-14 07:18:38.046  5614  5660 I jxcore-log: ok 42 incoming has been removed
10-14 07:18:38.046  5614  5660 I jxcore-log: 
10-14 07:18:38.046  5614  5660 I jxcore-log: ok 43 The mux object should be closed
10-14 07:18:38.046  5614  5660 I jxcore-log: 
10-14 07:18:38.047  5614  5660 I jxcore-log: ok 44 The mux stream should be closed
10-14 07:18:38.047  5614  5660 I jxcore-log: 
,10-14 07:18:38.054  5614  5660 I jxcore-log: # teardown
10-14 07:18:38.054  5614  5660 I jxcore-log: 
,10-14 07:18:38.398  5614  5660 I jxcore-log: # setup
10-14 07:18:38.398  5614  5660 I jxcore-log: 
,10-14 07:18:39.124  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-14 07:18:39.124  5614  5660 I jxcore-log: 
,10-14 07:18:39.746  5614  5660 I jxcore-log: 2016-10-14 11:18:39 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-14 07:18:39.746  5614  5660 I jxcore-log: 
,10-14 07:18:39.747  5614  5660 I jxcore-log: ok 45 Got right error
10-14 07:18:39.747  5614  5660 I jxcore-log: 
,10-14 07:18:39.752  5614  5660 I jxcore-log: # teardown
10-14 07:18:39.752  5614  5660 I jxcore-log: 
,10-14 07:18:40.547  5614  5660 I jxcore-log: # setup
10-14 07:18:40.547  5614  5660 I jxcore-log: 
,10-14 07:18:40.853  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-14 07:18:40.853  5614  5660 I jxcore-log: 
,10-14 07:18:41.308  5614  5660 I jxcore-log: 2016-10-14 11:18:41 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-14 07:18:41.308  5614  5660 I jxcore-log: 
,10-14 07:18:41.309  5614  5660 I jxcore-log: ok 46 Got socket hang up
10-14 07:18:41.309  5614  5660 I jxcore-log: 
,10-14 07:18:41.314  5614  5660 I jxcore-log: # teardown
10-14 07:18:41.314  5614  5660 I jxcore-log: 
,10-14 07:18:42.183  5614  5660 I jxcore-log: # setup
10-14 07:18:42.183  5614  5660 I jxcore-log: 
,10-14 07:18:42.497  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-14 07:18:42.497  5614  5660 I jxcore-log: 
,10-14 07:18:42.529   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:43.530   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:43.560  5614  5660 I jxcore-log: 2016-10-14 11:18:43 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-14 07:18:43.560  5614  5660 I jxcore-log: 
,10-14 07:18:43.561  5614  5660 I jxcore-log: ok 47 Got 500 as expected
10-14 07:18:43.561  5614  5660 I jxcore-log: 
,10-14 07:18:43.566  5614  5660 I jxcore-log: # teardown
10-14 07:18:43.566  5614  5660 I jxcore-log: 
,10-14 07:18:44.140  5614  5660 I jxcore-log: # setup
10-14 07:18:44.140  5614  5660 I jxcore-log: 
,10-14 07:18:44.531   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:44.641  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-14 07:18:44.641  5614  5660 I jxcore-log: 
,10-14 07:18:45.532   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:46.152   928  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 07:18:46.533   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:46.671  5614  5660 I jxcore-log: ok 48 should be equal
10-14 07:18:46.671  5614  5660 I jxcore-log: 
,10-14 07:18:46.671  5614  5660 I jxcore-log: ok 49 revs are equal
10-14 07:18:46.671  5614  5660 I jxcore-log: 
,10-14 07:18:46.675  5614  5660 I jxcore-log: # teardown
10-14 07:18:46.675  5614  5660 I jxcore-log: 
,10-14 07:18:46.705  5614  5660 I jxcore-log: # setup
10-14 07:18:46.705  5614  5660 I jxcore-log: 
,10-14 07:18:47.212  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-14 07:18:47.212  5614  5660 I jxcore-log: 
,10-14 07:18:47.534   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 07:18:48.696  5614  5660 I jxcore-log: ok 50 should be equal
10-14 07:18:48.696  5614  5660 I jxcore-log: 
,10-14 07:18:48.697  5614  5660 I jxcore-log: ok 51 revs are equal
10-14 07:18:48.697  5614  5660 I jxcore-log: 
,10-14 07:18:48.701  5614  5660 I jxcore-log: # teardown
10-14 07:18:48.701  5614  5660 I jxcore-log: 
,10-14 07:18:48.737  5614  5660 I jxcore-log: # setup
10-14 07:18:48.737  5614  5660 I jxcore-log: 
,10-14 07:18:48.800  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-14 07:18:48.800  5614  5660 I jxcore-log: 
,10-14 07:18:49.495  5614  5660 I jxcore-log: ok 52 should be equal
10-14 07:18:49.495  5614  5660 I jxcore-log: 
,10-14 07:18:49.496  5614  5660 I jxcore-log: ok 53 revs are equal
10-14 07:18:49.496  5614  5660 I jxcore-log: 
,10-14 07:18:49.674  5614  5660 I jxcore-log: ok 54 should be equal
10-14 07:18:49.674  5614  5660 I jxcore-log: 
,10-14 07:18:49.674  5614  5660 I jxcore-log: ok 55 revs are equal
10-14 07:18:49.674  5614  5660 I jxcore-log: 
,10-14 07:18:49.870  5614  5660 I jxcore-log: ok 56 should be equal
10-14 07:18:49.870  5614  5660 I jxcore-log: 
,10-14 07:18:49.870  5614  5660 I jxcore-log: ok 57 revs are equal
10-14 07:18:49.870  5614  5660 I jxcore-log: 
,10-14 07:18:49.880  5614  5660 I jxcore-log: # teardown
10-14 07:18:49.880  5614  5660 I jxcore-log: 
,10-14 07:18:50.019  5614  5660 I jxcore-log: # setup
10-14 07:18:50.019  5614  5660 I jxcore-log: 
,10-14 07:18:50.971  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-14 07:18:50.971  5614  5660 I jxcore-log: 
,10-14 07:18:51.771  5614  5660 I jxcore-log: 2016-10-14 11:18:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-14 07:18:51.771  5614  5660 I jxcore-log: 
,10-14 07:18:51.772  5614  5660 I jxcore-log: ok 58 Our rev is old so we should fail
10-14 07:18:51.772  5614  5660 I jxcore-log: 
,10-14 07:18:51.793  5614  5660 I jxcore-log: # teardown
10-14 07:18:51.793  5614  5660 I jxcore-log: 
,10-14 07:18:51.836  5614  5660 I jxcore-log: # setup
10-14 07:18:51.836  5614  5660 I jxcore-log: 
,10-14 07:18:51.936  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-14 07:18:51.936  5614  5660 I jxcore-log: 
,10-14 07:18:52.050  5614  5660 I jxcore-log: ok 59 confirm stop caused failure
10-14 07:18:52.050  5614  5660 I jxcore-log: 
,10-14 07:18:52.062  5614  5660 I jxcore-log: # teardown
10-14 07:18:52.062  5614  5660 I jxcore-log: 
,10-14 07:18:52.108  5614  5660 I jxcore-log: # setup
10-14 07:18:52.108  5614  5660 I jxcore-log: 
,10-14 07:18:52.168  5614  5660 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-14 07:18:52.168  5614  5660 I jxcore-log: 
,10-14 07:18:52.535   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:52.599  5614  5660 I jxcore-log: 2016-10-14 11:18:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-14 07:18:52.599  5614  5660 I jxcore-log: 
,10-14 07:18:52.600  5614  5660 I jxcore-log: ok 60 stop caused us to fail
10-14 07:18:52.600  5614  5660 I jxcore-log: 
10-14 07:18:52.601  5614  5660 I jxcore-log: ok 61 We specifically failed on a stop before put
10-14 07:18:52.601  5614  5660 I jxcore-log: 
,10-14 07:18:52.618  5614  5660 I jxcore-log: # teardown
10-14 07:18:52.618  5614  5660 I jxcore-log: 
,10-14 07:18:52.668  5614  5660 I jxcore-log: # setup
10-14 07:18:52.668  5614  5660 I jxcore-log: 
,10-14 07:18:52.720  5614  5660 I jxcore-log: # #update - fail if stop is called
10-14 07:18:52.720  5614  5660 I jxcore-log: 
,10-14 07:18:52.787  5614  5660 I jxcore-log: ok 62 failed due to stop
10-14 07:18:52.787  5614  5660 I jxcore-log: 
,10-14 07:18:52.788  5614  5660 I jxcore-log: ok 63 failed due to stop
10-14 07:18:52.788  5614  5660 I jxcore-log: 
,10-14 07:18:52.798  5614  5660 I jxcore-log: # teardown
10-14 07:18:52.798  5614  5660 I jxcore-log: 
,10-14 07:18:52.907  5614  5660 I jxcore-log: # setup
10-14 07:18:52.907  5614  5660 I jxcore-log: 
,10-14 07:18:52.943  5614  5660 I jxcore-log: # #update - set seq for first time
10-14 07:18:52.943  5614  5660 I jxcore-log: 
,10-14 07:18:53.536   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:53.604  5614  5660 I jxcore-log: ok 64 should be equal
10-14 07:18:53.604  5614  5660 I jxcore-log: 
,10-14 07:18:53.632  5614  5660 I jxcore-log: # teardown
10-14 07:18:53.632  5614  5660 I jxcore-log: 
,10-14 07:18:53.665  5614  5660 I jxcore-log: # setup
10-14 07:18:53.665  5614  5660 I jxcore-log: 
,10-14 07:18:53.703  5614  5660 I jxcore-log: # #update - Fail on bad seq value
10-14 07:18:53.703  5614  5660 I jxcore-log: 
,10-14 07:18:54.284  5614  5660 I jxcore-log: 2016-10-14 11:18:54 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-14 07:18:54.284  5614  5660 I jxcore-log: 
,10-14 07:18:54.286  5614  5660 I jxcore-log: ok 65 Expected bad seq error
10-14 07:18:54.286  5614  5660 I jxcore-log: 
,10-14 07:18:54.306  5614  5660 I jxcore-log: # teardown
10-14 07:18:54.306  5614  5660 I jxcore-log: 
,10-14 07:18:54.356  5614  5660 I jxcore-log: # setup
10-14 07:18:54.356  5614  5660 I jxcore-log: 
,10-14 07:18:54.408  5614  5660 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-14 07:18:54.408  5614  5660 I jxcore-log: 
,10-14 07:18:54.537   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:55.538   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:55.577  5614  5660 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-14 07:18:55.577  5614  5660 E jxcore-log: 
,10-14 07:18:55.579  5614  5660 E jxcore-log: Trace: 
10-14 07:18:55.579  5614  5660 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-14 07:18:55.579  5614  5660 E jxcore-log:     at addListener@events.js:140:1
10-14 07:18:55.579  5614  5660 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-14 07:18:55.579  5614  5660 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-14 07:18:55.579  5614  5660 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-14 07:18:55.579  5614  5660 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-14 07:18:55.579  5614  5660 E jxcore-log: 
,10-14 07:18:56.068  5614  5660 I jxcore-log: ok 66 Different promises
10-14 07:18:56.068  5614  5660 I jxcore-log: 
10-14 07:18:56.070  5614  5660 I jxcore-log: ok 67 Timer was cancelled
10-14 07:18:56.070  5614  5660 I jxcore-log: 
,10-14 07:18:56.539   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:18:56.664  5614  5660 I jxcore-log: ok 68 should be equal
10-14 07:18:56.664  5614  5660 I jxcore-log: 
,10-14 07:18:56.685  5614  5660 I jxcore-log: # teardown
10-14 07:18:56.685  5614  5660 I jxcore-log: 
,10-14 07:18:56.980  5614  5660 I jxcore-log: # setup
10-14 07:18:56.980  5614  5660 I jxcore-log: 
,10-14 07:18:57.540   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 07:18:58.364  5614  5660 I jxcore-log: # #update - do we wait for blocked update
10-14 07:18:58.364  5614  5660 I jxcore-log: 
,10-14 07:18:58.536  5614  5660 I jxcore-log: ok 69 One go and one blocked
10-14 07:18:58.536  5614  5660 I jxcore-log: 
,10-14 07:18:58.537  5614  5660 I jxcore-log: ok 70 All blocked
10-14 07:18:58.537  5614  5660 I jxcore-log: 
10-14 07:18:58.537  5614  5660 I jxcore-log: ok 71 Still blocked
10-14 07:18:58.537  5614  5660 I jxcore-log: 
,10-14 07:18:58.552  5614  5660 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-14 07:18:58.552  5614  5660 E jxcore-log: 
,10-14 07:18:58.553  5614  5660 E jxcore-log: Trace: 
10-14 07:18:58.553  5614  5660 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-14 07:18:58.553  5614  5660 E jxcore-log:     at addListener@events.js:140:1
10-14 07:18:58.553  5614  5660 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-14 07:18:58.553  5614  5660 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-14 07:18:58.553  5614  5660 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-14 07:18:58.553  5614  5660 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-14 07:18:58.553  5614  5660 E jxcore-log: 
,10-14 07:18:59.184  5614  5660 I jxcore-log: ok 72 should be equal
10-14 07:18:59.184  5614  5660 I jxcore-log: 
,10-14 07:18:59.212  5614  5660 I jxcore-log: # teardown
10-14 07:18:59.212  5614  5660 I jxcore-log: 
,10-14 07:19:00.980  5614  5660 I jxcore-log: # setup
10-14 07:19:00.980  5614  5660 I jxcore-log: 
,10-14 07:19:02.154  5614  5660 I jxcore-log: # #update - test that we wait long enough
10-14 07:19:02.154  5614  5660 I jxcore-log: 
,10-14 07:19:04.141  5614  5660 I jxcore-log: ok 73 We waited long enough
10-14 07:19:04.141  5614  5660 I jxcore-log: 
,10-14 07:19:04.333  5614  5660 I jxcore-log: ok 74 should be equal
10-14 07:19:04.333  5614  5660 I jxcore-log: 
,10-14 07:19:04.357  5614  5660 I jxcore-log: # teardown
10-14 07:19:04.357  5614  5660 I jxcore-log: 
,10-14 07:19:04.845  5614  5660 I jxcore-log: # setup
10-14 07:19:04.845  5614  5660 I jxcore-log: 
,10-14 07:19:04.983  5614  5660 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-14 07:19:04.983  5614  5660 I jxcore-log: 
,10-14 07:19:05.899  5614  5660 I jxcore-log: ok 75 Should have gotten same timer promise
10-14 07:19:05.899  5614  5660 I jxcore-log: 
,10-14 07:19:05.899  5614  5660 I jxcore-log: ok 76 Still same timer promise
10-14 07:19:05.899  5614  5660 I jxcore-log: 
,10-14 07:19:06.482  5614  5660 I jxcore-log: ok 77 We waited long enough
10-14 07:19:06.482  5614  5660 I jxcore-log: 
,10-14 07:19:06.609  5614  5660 I jxcore-log: ok 78 should be equal
10-14 07:19:06.609  5614  5660 I jxcore-log: 
,10-14 07:19:06.679  5614  5660 I jxcore-log: # teardown
10-14 07:19:06.679  5614  5660 I jxcore-log: 
,10-14 07:19:07.379  5614  5660 I jxcore-log: # setup
10-14 07:19:07.379  5614  5660 I jxcore-log: 
,10-14 07:19:07.541   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:08.542   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:09.021  5614  5660 I jxcore-log: # Coordinated seq test
10-14 07:19:09.021  5614  5660 I jxcore-log: 
,10-14 07:19:09.307  5614  5660 I jxcore-log: 2016-10-14 11:19:09 - DEBUG thaliWifiInfrastructure: 'listening 48539'
10-14 07:19:09.307  5614  5660 I jxcore-log: 
,10-14 07:19:09.543   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:10.545   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:11.546   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:12.546   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 07:19:12.853  5614  5660 I jxcore-log: ok 79 should be equal
10-14 07:19:12.853  5614  5660 I jxcore-log: 
,10-14 07:19:13.847  5614  5660 I jxcore-log: ok 80 should be equal
10-14 07:19:13.847  5614  5660 I jxcore-log: 
,10-14 07:19:13.869  5614  5660 I jxcore-log: # teardown
10-14 07:19:13.869  5614  5660 I jxcore-log: 
,10-14 07:19:26.158   928  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 07:19:27.547   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:28.549   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:29.550   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:30.551   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:31.553   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:32.553   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 07:19:46.159   928  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 07:19:52.555   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:53.556   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:54.557   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:55.558   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:56.560   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 07:19:57.561   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-14 07:20:13.886  5614  5660 I jxcore-log: 2016-10-14 11:20:13 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-14 07:20:13.886  5614  5660 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-14 07:20:13.886  5614  5660 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-14 07:20:13.886  5614  5660 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-14 07:20:13.886  5614  5660 I jxcore-log:     at $9@timers.js:120:1
10-14 07:20:13.886  5614  5660 I jxcore-log: ''
10-14 07:20:13.886  5614  5660 I jxcore-log: 
,10-14 07:20:13.889  5614  5660 I jxcore-log: 2016-10-14 11:20:13 - DEBUG CoordinatedClient: 'test client failed'
10-14 07:20:13.889  5614  5660 I jxcore-log: 
,10-14 07:20:13.901  5614  5660 I jxcore-log: 2016-10-14 11:20:13 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-14 07:20:13.901  5614  5660 I jxcore-log: 
,10-14 07:20:13.907  5614  5660 I jxcore-log: 2016-10-14 11:20:13 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-14 07:20:13.907  5614  5660 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-14 07:20:13.907  5614  5660 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-14 07:20:13.907  5614  5660 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-14 07:20:13.907  5614  5660 I jxcore-log:     at $9@timers.js:120:1
10-14 07:20:13.907  5614  5660 I jxcore-log: ''
10-14 07:20:13.907  5614  5660 I jxcore-log: 
10-14 07:20:13.909  5614  5660 I jxcore-log: 2016-10-14 11:20:13 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-14 07:20:13.909  5614  5660 I jxcore-log: 
,10-14 07:20:13.987   928  2972 D WifiService: Client connection lost with reason: 4
10-14 07:20:13.987   928   939 D GraphicsStats: Buffer count: 2
10-14 07:20:13.987   928  3389 I WindowState: WIN DEATH: Window{67cd870 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-14 07:20:14.003   529   529 I Zygote  : Process 5614 exited cleanly (139)
,10-14 07:20:14.004   928  3124 I ActivityManager: Process com.test.thalitest (pid 5614) has died
,10-14 07:20:14.031   928  3124 I ActivityManager: Start proc 5976:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-14 07:20:14.365   928   939 I WindowManager: Screenshot max retries 4 of Token{22b38c2 ActivityRecord{4d1210d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{1a033bc u0 Starting com.test.thalitest} drawState=4
,10-14 07:20:14.406  5976  5976 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 07:20:14.423  5976  5976 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 07:20:14.429  5976  5976 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5798-5801)
,10-14 07:20:14.429  5976  5976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 07:20:14.438  5976  5976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d46cb7}
10-14 07:20:14.438  5976  5976 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 07:20:14.438  5976  5976 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-14 07:20:14.441  5976  5976 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 07:20:14.442  5976  5976 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 07:20:14.455  5976  5976 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 07:20:14.462  5976  5976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-14 07:20:14.463  5976  5976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 07:20:14.463  5976  5976 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 07:20:14.463  5976  5976 I Adreno  : Build Date                       : 12/06/15
10-14 07:20:14.463  5976  5976 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 07:20:14.463  5976  5976 I Adreno  : Local Branch                     : mybranch17112971
10-14 07:20:14.463  5976  5976 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 07:20:14.463  5976  5976 I Adreno  : Remote Branch                    : NONE
10-14 07:20:14.463  5976  5976 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 07:20:14.484  5973  5973 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-14 07:20:14.500  5973  5973 D AndroidRuntime: CheckJNI is OFF
,10-14 07:20:14.504   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11d51fd:true
,10-14 07:20:14.517  4112  4112 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[17032]" dev="sockfs" ino=17032 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 07:20:14.517  4112  4112 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[17032]" dev="sockfs" ino=17032 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 07:20:14.527  5973  5973 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-14 07:20:14.528  5976  5976 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-14 07:20:14.535  5976  5976 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-14 07:20:14.553  5973  5973 I Radio-JNI: register_android_hardware_Radio DONE
,10-14 07:20:14.560  4112  4112 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33238]" dev="sockfs" ino=33238 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 07:20:14.560  4112  4112 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33238]" dev="sockfs" ino=33238 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-14 07:20:14.564  5976  6017 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-14 07:20:14.564  3122  3122 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35619]" dev="sockfs" ino=35619 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 07:20:14.564  3122  3122 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35619]" dev="sockfs" ino=35619 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 07:20:14.569  5973  5973 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
10-14 07:20:14.569  5976  5999 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-14 07:20:14.575   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-14 07:20:14.576   928   941 I ActivityManager: Killing 5976:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-14 07:20:14.613   928  5343 D GraphicsStats: Buffer count: 2
,10-14 07:20:14.613   928   938 I WindowState: WIN DEATH: Window{ac3c4f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-14 07:20:14.620   928   941 W ActivityManager: Force removing ActivityRecord{4d1210d u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,10-14 07:20:14.626   928  3833 W ActivityManager: Spurious death for ProcessRecord{2803cee 0:com.test.thalitest/u0a77}, curProc for 5976: null
,10-14 07:20:14.742   928   951 I art     : Starting a blocking GC Explicit
,10-14 07:20:14.841   928   951 I art     : Explicit concurrent mark sweep GC freed 75411(5MB) AllocSpace objects, 38(1112KB) LOS objects, 33% free, 29MB/43MB, paused 1.538ms total 98.253ms
,10-14 07:20:14.863   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-14 07:20:14.866  5973  5973 I art     : System.exit called, status: 0
,10-14 07:20:14.866  5973  5973 I AndroidRuntime: VM exiting with result code 0.
,10-14 07:20:14.880   928   951 I ActivityManager: Start proc 6021:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-14 07:20:14.880   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-14 07:20:14.896  5874  5874 D BluetoothMapAppObserver: onReceive
,10-14 07:20:14.897  5874  5874 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-14 07:20:14.901   928  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-14 07:20:14.901  3646  3646 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-14 07:20:14.944  3375  6034 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-14 07:20:14.945  3646  6033 I Keyboard.Facilitator.DecoderInitializer: run()
,10-14 07:20:14.952   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-14 07:20:14.953  3741  3741 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
10-14 07:20:14.965  4087  4149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-14 07:20:14.967    28    28 W kworker/2:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 07:20:14.974  3646  6033 I Decoder : createOrResetDecoder
,10-14 07:20:14.977    28    28 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 07:20:14.997    28    28 W kworker/2:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 07:20:15.003   928  3820 I ActivityManager: Start proc 6039:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-14 07:20:15.003  3779  3911 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-14 07:20:15.003  3779  3911 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3779
10-14 07:20:15.003  3779  3911 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.003  3779  3911 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 07:20:15.012   928  6050 E DropBoxManagerService: Can't write: system_app_crash
10-14 07:20:15.012   928  6050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 07:20:15.012   928  6050 E DropBoxManagerService: 	... 5 more
,10-14 07:20:15.013   928  5343 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 07:20:15.017  3559  3559 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
10-14 07:20:15.017  3559  3559 D AndroidRuntime: Shutting down VM
,10-14 07:20:15.019  3559  3559 E AndroidRuntime: FATAL EXCEPTION: main
10-14 07:20:15.019  3559  3559 E AndroidRuntime: Process: com.google.process.gapps, PID: 3559
10-14 07:20:15.019  3559  3559 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-14 07:20:15.019  3559  3559 E AndroidRuntime: 	... 8 more
,10-14 07:20:15.021  3779  3911 I Process : Sending signal. PID: 3779 SIG: 9
,10-14 07:20:15.024  3559  3559 I Process : Sending signal. PID: 3559 SIG: 9
,10-14 07:20:15.026   928  6054 E DropBoxManagerService: Can't write: system_app_crash
10-14 07:20:15.026   928  6054 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 07:20:15.026   928  6054 E DropBoxManagerService: 	... 5 more
,10-14 07:20:15.037  3375  3398 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjAC1DFA988) - 
,10-14 07:20:15.043   928  2972 D WifiService: Client connection lost with reason: 4
,10-14 07:20:15.044   928   939 W ActivityManager: Application dead when creating service ServiceRecord{996e829 u0 com.google.android.gms/.config.ConfigService}
,10-14 07:20:15.056   928   939 I ActivityManager: Process com.google.process.gapps (pid 3559) has died
10-14 07:20:15.056   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,10-14 07:20:15.056   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
10-14 07:20:15.057   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
10-14 07:20:15.057   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 30999ms
10-14 07:20:15.058   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 40998ms
,10-14 07:20:15.058   928   939 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
10-14 07:20:15.058   928   939 W ActivityManager: android.os.DeadObjectException
10-14 07:20:15.058   928   939 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
10-14 07:20:15.058   928   939 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
10-14 07:20:15.058   928   939 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
10-14 07:20:15.058   928   939 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
10-14 07:20:15.058   928   939 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
10-14 07:20:15.058   928   939 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
10-14 07:20:15.058   928   939 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
10-14 07:20:15.058   928   939 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
10-14 07:20:15.058   928   939 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
10-14 07:20:15.058   928   939 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
10-14 07:20:15.059   928  5343 W ActivityManager: Spurious death for ProcessRecord{d926b67 0:com.google.process.gapps/u0a12}, curProc for 3559: null
,10-14 07:20:15.080  3375  3398 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-14 07:20:15.080  3375  3398 E AndroidRuntime: Process: android.process.acore, PID: 3375
10-14 07:20:15.080  3375  3398 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.080  3375  3398 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 07:20:15.080   928   939 I ActivityManager: Start proc 6056:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,10-14 07:20:15.115   928  6069 E DropBoxManagerService: Can't write: system_app_crash
10-14 07:20:15.115   928  6069 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 07:20:15.115   928  6069 E DropBoxManagerService: 	... 5 more
,10-14 07:20:15.118  3375  3398 I Process : Sending signal. PID: 3375 SIG: 9
,10-14 07:20:15.126   928   938 D GraphicsStats: Buffer count: 1
,10-14 07:20:15.126   928  3788 I WindowState: WIN DEATH: Window{c1409d2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-14 07:20:15.131   928   938 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3779) has died
10-14 07:20:15.132   928   938 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
10-14 07:20:15.133   928   938 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 07:20:15.148   928   941 I ActivityManager: Start proc 6070:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 07:20:15.193  6070  6070 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:20:15.193  6070  6070 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 07:20:15.193  6070  6070 D AndroidRuntime: Shutting down VM
,10-14 07:20:15.198  6070  6070 E AndroidRuntime: FATAL EXCEPTION: main
10-14 07:20:15.198  6070  6070 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6070
10-14 07:20:15.198  6070  6070 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 07:20:15.198  6070  6070 E AndroidRuntime: 	... 10 more
,10-14 07:20:15.201   928  3820 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 07:20:15.201   928  6083 E DropBoxManagerService: Can't write: system_app_crash
10-14 07:20:15.201   928  6083 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 07:20:15.201   928  6083 E DropBoxManagerService: 	... 5 more
,10-14 07:20:15.203  6070  6070 I Process : Sending signal. PID: 6070 SIG: 9
,10-14 07:20:15.217   928  3124 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6070) has died
,10-14 07:20:15.218   928  3124 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 07:20:15.235   928   941 I ActivityManager: Start proc 6084:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 07:20:15.292  6084  6084 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:20:15.292  6084  6084 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 07:20:15.292  6084  6084 D AndroidRuntime: Shutting down VM
,10-14 07:20:15.303  6084  6084 E AndroidRuntime: FATAL EXCEPTION: main
10-14 07:20:15.303  6084  6084 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6084
10-14 07:20:15.303  6084  6084 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 07:20:15.303  6084  6084 E AndroidRuntime: 	... 10 more
,10-14 07:20:15.306   928  3833 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-14 07:20:15.307   928  6096 E DropBoxManagerService: Can't write: system_app_crash
10-14 07:20:15.307   928  6096 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 07:20:15.307   928  6096 E DropBoxManagerService: 	... 5 more
10-14 07:20:15.307  6084  6084 I Process : Sending signal. PID: 6084 SIG: 9
,10-14 07:20:15.333   928  3593 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6084) has died
10-14 07:20:15.335   928  3593 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 07:20:15.350   928   941 I ActivityManager: Start proc 6097:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
