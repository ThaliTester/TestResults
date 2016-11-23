#### Test 949810482209bfa_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 06:24:00.091   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 06:24:00.560  5680  5680 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 06:24:00.566  5680  5680 D AndroidRuntime: CheckJNI is OFF
11-23 06:24:00.591  5680  5680 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 06:24:00.634  5680  5680 I Radio-JNI: register_android_hardware_Radio DONE
11-23 06:24:00.648  5680  5680 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-23 06:24:00.665   929  3202 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 06:24:00.724   929  3202 I ActivityManager: Start proc 5689:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 06:24:00.734  5680  5680 D AndroidRuntime: Shutting down VM
,11-23 06:24:01.070   929  3986 I WindowManager: Screenshot max retries 4 of Token{d6cf5cb ActivityRecord{7c8f89a u0 com.test.thalitest/.MainActivity t10}} appWin=Window{18600f2 u0 Starting com.test.thalitest} drawState=2
,11-23 06:24:01.155  5689  5689 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-23 06:24:01.182  5689  5689 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-23 06:24:01.256  5689  5689 I LibraryLoader: Time to load native libraries: 67 ms (timestamps 313-380)
,11-23 06:24:01.256  5689  5689 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 06:24:01.301  5689  5689 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9864510}
11-23 06:24:01.301  5689  5689 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 06:24:01.302  5689  5689 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 06:24:01.306  5689  5689 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 06:24:01.306  5689  5689 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 06:24:01.344  5689  5689 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 06:24:01.362  5689  5689 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 06:24:01.362  5689  5689 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 06:24:01.362  5689  5689 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 06:24:01.362  5689  5689 I Adreno  : Build Date                       : 12/06/15
11-23 06:24:01.362  5689  5689 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 06:24:01.362  5689  5689 I Adreno  : Local Branch                     : mybranch17112971
11-23 06:24:01.362  5689  5689 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 06:24:01.362  5689  5689 I Adreno  : Remote Branch                    : NONE
11-23 06:24:01.362  5689  5689 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 06:24:01.410   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e61d4d8:true
,11-23 06:24:01.445  3227  3227 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[35226]" dev="sockfs" ino=35226 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:01.445  3227  3227 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[35226]" dev="sockfs" ino=35226 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:01.454  5689  5689 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 06:24:01.463  5689  5689 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 06:24:01.498  3227  3227 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32086]" dev="sockfs" ino=32086 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:01.502  5689  5726 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-23 06:24:01.498  3227  3227 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32086]" dev="sockfs" ino=32086 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:01.505  3976  3976 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14117]" dev="sockfs" ino=14117 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:01.505  3976  3976 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14117]" dev="sockfs" ino=14117 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:01.509  5689  5713 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 06:24:01.536  5689  5726 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 06:24:01.617   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +545ms (total +915ms)
,11-23 06:24:01.647  5689  5689 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5689
,11-23 06:24:01.743  5689  5689 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-23 06:24:01.976  5689  5729 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -580122320
,11-23 06:24:01.988  5689  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 06:24:01.988  5689  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 06:24:01.988  5689  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 06:24:01.988  5689  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 06:24:01.988  5689  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 06:24:01.988  5689  5729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@687ade7 added. We now have 1 listener(s)
,11-23 06:24:01.990  5689  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-23 06:24:01.991  5689  5729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 06:24:01.991  5689  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:24:01.992  5689  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-23 06:24:01.994  5689  5729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272c032 added. We now have 1 listener(s)
11-23 06:24:01.994  5689  5729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:24:01.999   929  3018 D WifiService: New client listening to asynchronous messages
,11-23 06:24:01.999  5689  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 06:24:01.999  5689  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 06:24:02.000  5689  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 06:24:02.000  5689  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-23 06:24:02.000  5689  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 06:24:02.000  5689  5729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 06:24:02.000  5689  5729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-23 06:24:02.001  5689  5729 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 06:24:02.140  5689  5689 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-23 06:24:02.584  5689  5698 I art     : Background sticky concurrent mark sweep GC freed 82936(8MB) AllocSpace objects, 16(1076KB) LOS objects, 22% free, 25MB/32MB, paused 2.206ms total 367.971ms
,11-23 06:24:03.746  5689  5698 I art     : Background partial concurrent mark sweep GC freed 49396(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.655ms total 268.539ms
,11-23 06:24:05.708  5689  5735 W jxcore-log: Initializing JXcore engine
,11-23 06:24:05.709  5689  5735 W jxcore-log: JXcore engine is ready
,11-23 06:24:05.758  5735  5735 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12609 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 06:24:05.758  5735  5735 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13516]" dev="sockfs" ino=13516 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-23 06:24:05.758  5735  5735 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 06:24:05.758  5735  5735 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32062]" dev="sockfs" ino=32062 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 06:24:05.777  5689  5735 W jxcore-log: Starting JXcore engine
,11-23 06:24:05.836  5689  5735 W jxcore-log: Platform android
11-23 06:24:05.836  5689  5735 W jxcore-log: 
,11-23 06:24:05.836  5689  5735 W jxcore-log: Process ARCH arm
11-23 06:24:05.836  5689  5735 W jxcore-log: 
,11-23 06:24:06.024  5689  5735 I jxcore-log: JXcore Cordova bridge is ready!
11-23 06:24:06.024  5689  5735 I jxcore-log: 
,11-23 06:24:06.024  5689  5735 W jxcore-log: JXcore engine is started
,11-23 06:24:06.032  5689  5729 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-23 06:24:06.039  5689  5689 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 06:24:12.579   929  5437 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:24:12.971   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:24:15.534  5689  5735 I jxcore-log: 2016-11-23 11:24:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 06:24:15.534  5689  5735 I jxcore-log: 
,11-23 06:24:15.535  5689  5735 I jxcore-log: 2016-11-23 11:24:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 06:24:15.535  5689  5735 I jxcore-log: 
,11-23 06:24:15.541  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:24:15.541  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 06:24:15.542  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 06:24:15.544  5689  5735 I jxcore-log: 2016-11-23 11:24:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 06:24:15.544  5689  5735 I jxcore-log: 
11-23 06:24:15.545  5689  5735 I jxcore-log: 2016-11-23 11:24:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 06:24:15.545  5689  5735 I jxcore-log: 
,11-23 06:24:15.782  5689  5735 I jxcore-log: 2016-11-23 11:24:15 - DEBUG UnitTest_app: 'Running unit tests'
11-23 06:24:15.782  5689  5735 I jxcore-log: 
,11-23 06:24:15.782  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:24:15.782  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19203ae added. We now have 2 listener(s)
11-23 06:24:15.783  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:24:15.783  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:24:15.783  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 06:24:15.783  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:24:15.783  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edec54f added. We now have 2 listener(s)
11-23 06:24:15.783  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:24:15.784  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 06:24:15.784  5689  5735 D executeNativeTests: Running unit tests,
,11-23 06:24:15.821  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 06:24:15.821  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c added. We now have 3 listener(s)
11-23 06:24:15.821  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:24:15.821  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 06:24:15.821  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:24:15.821  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:24:15.821  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 added. We now have 3 listener(s)
11-23 06:24:15.822  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:24:15.822  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 06:24:15.824  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 06:24:15.824  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 06:24:15.824  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 06:24:15.824  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 06:24:15.825  5689  5735 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 06:24:15.825  5689  5735 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-23 06:24:15.825  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 06:24:15.825  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-23 06:24:15.825  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 06:24:15.825  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 06:24:15.825  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:15.825  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 06:24:15.825  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:15.825  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:15.826  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:15.826  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:24:15.826  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c removed from the list
,11-23 06:24:15.826  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:15.826  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 removed from the list
11-23 06:24:15.826  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:15.826  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.826  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.827  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.827  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.827  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.827  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:15.827  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 06:24:15.827  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:15.827  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:15.828  5689  5735 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 06:24:15.828  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:15.828  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:15.828  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:15.828  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:15.828  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:15.828  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:15.828  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:15.828  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:15.828  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:15.828  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.828  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.829  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.829  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.829  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.829  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:15.829  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:15.829  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:15.829  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:15.831  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 06:24:15.831  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 06:24:15.831  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 06:24:15.831  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 06:24:15.831  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-23 06:24:15.831  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-23 06:24:15.832  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 06:24:15.832  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:15.832  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:15.832  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:15.832  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:15.832  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:15.833  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:15.833  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:15.833  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:15.833  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 06:24:15.833  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.833  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:15.833  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.833  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.833  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.833  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:15.833  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:15.833  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:15.833  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:15.834  5689  5735 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 06:24:15.835  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:15.835  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:24:15.848  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 06:24:15.850  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 06:24:15.851  5689  5735 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 06:24:15.851  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:24:15.851  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 06:24:15.851  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 06:24:15.851  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:15.851  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 06:24:15.853  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 06:24:15.854  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 06:24:15.854  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 06:24:15.857  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:24:15.857  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.858  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 06:24:15.860  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 06:24:15.861  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-23 06:24:15.861  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 06:24:15.861  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:15.864  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-23 06:24:15.865  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 06:24:15.865  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.865  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 06:24:15.866  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 06:24:15.866  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 06:24:15.866  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 06:24:15.866  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.866  5689  5735 D BluetoothAdapter: STATE_ON
,11-23 06:24:15.868  4665  4681 D BtGatt.GattService: registerClient() - UUID=d137da72-a96b-4414-bef7-b8e2595933a3
,11-23 06:24:15.869  4665  4731 D BtGatt.GattService: onClientRegistered() - UUID=d137da72-a96b-4414-bef7-b8e2595933a3, clientIf=5
11-23 06:24:15.871  5689  5700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 06:24:15.872  4665  4892 D BtGatt.GattService: start scan with filters
,11-23 06:24:15.877  4665  4734 D BtGatt.ScanManager: handling starting scan
11-23 06:24:15.877  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 06:24:15.878  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:15.878  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 06:24:15.878  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.878  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 06:24:15.878  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 06:24:15.878  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.879  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 06:24:15.879  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-23 06:24:15.879  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 06:24:15.879  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.879  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.879  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.879  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.879  4665  4734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:24:15.879  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.880  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.880  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.880  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:15.880  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.880  5689  5735 I io.jxcore.node.ConnectionHelper: start: OK
11-23 06:24:15.883  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.883  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:24:15.883  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.883  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:15.884  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 06:24:15.886  4665  4731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-23 06:24:15.886  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:15.887  4665  4734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 06:24:15.893  4665  4731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 06:24:15.894  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:15.894  4665  4734 D BtGatt.ScanManager: Starting BLE batch scan
11-23 06:24:15.894  4665  4734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 06:24:15.907  4665  4731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 06:24:15.907  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:15.913  4665  4731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 06:24:15.913  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:16.389  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 06:24:16.390  5689  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:24:16.390  5689  5689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 06:24:20.095   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:24:20.886  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 06:24:20.887  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:20.887  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 06:24:20.887  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:24:20.887  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 06:24:20.887  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 06:24:20.887  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 06:24:20.887  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 06:24:20.888  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.888  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:24:20.888  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 06:24:20.888  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:20.889  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:20.889  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.889  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-23 06:24:20.889  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.890  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:24:20.890  4665  4680 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 06:24:20.891  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 06:24:20.892  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:24:20.892  4665  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:24:20.893  4665  4891 D BtGatt.GattService: stopScan() - queue size =1
11-23 06:24:20.893  4665  4882 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 06:24:20.894  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 06:24:20.894  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:20.894  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 06:24:20.894  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.894  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.894  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.895  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.895  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-23 06:24:20.895  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.896  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.896  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.896  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-23 06:24:20.896  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 06:24:20.897  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:24:20.897  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.899  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.899  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:20.899  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.899  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:20.899  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:20.900  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:24:20.900  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:24:20.900  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 06:24:20.900  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:24:20.900  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:20.900  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:20.900  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:20.900  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 06:24:20.900  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:20.900  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:24:20.900  4665  4665 D BtGatt.ScanManager: awakened up at time 190025
11-23 06:24:20.900  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 06:24:20.901  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.901  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 06:24:20.901  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 06:24:20.901  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.901  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.902  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.902  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:20.902  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.902  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.906  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.906  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:20.906  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 06:24:20.937  4665  4731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-23 06:24:20.937  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:20.938  4665  4731 D BtGatt.GattService: current time is 190062544290
11-23 06:24:20.938  4665  4731 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -67, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 53, 33, -121, 80, 73, -44, 1, 0, -98, 77, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -10, -40, 94, 3, 2, -25, 21, 63, -83, -76, 48, 28, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 35, 97, 126, -92, 22, -56, 1, -128, -73, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -67, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -69, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -74, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -71, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-23 06:24:20.940  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 06:24:20.942  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -10, -40, 94, 3, 2, -25, 21, 63, -83, -76, 48, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 06:24:20.943  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 06:24:20.943  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 06:24:20.944  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 06:24:20.944  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 06:24:20.944  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-23 06:24:20.954  4665  4731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 06:24:20.954  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:20.954  4665  4734 D BtGatt.ScanManager: stopping BLe Batch
,11-23 06:24:20.962  4665  4731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 06:24:20.962  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:20.963  4665  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 06:24:20.970  4665  4731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:24:20.970  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:21.096   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:24:21.402  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 06:24:22.100   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:24:23.103   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:24:24.105   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:24:25.108   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 06:24:25.912  5689  5735 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 06:24:25.920  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 06:24:25.920  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:24:25.936  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 06:24:25.942  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 06:24:25.942  5689  5735 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 06:24:25.943  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 06:24:25.943  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 06:24:25.943  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 06:24:25.943  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:25.943  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 06:24:25.950  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:25.954  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 06:24:25.954  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 06:24:25.954  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 06:24:25.956  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:25.963  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:25.963  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 06:24:25.964  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 06:24:25.965  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 06:24:25.965  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 06:24:25.971  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:25.971  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 06:24:25.972  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 06:24:25.972  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 06:24:25.972  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 06:24:25.972  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:25.973  5689  5735 D BluetoothAdapter: STATE_ON
,11-23 06:24:25.978  4665  4892 D BtGatt.GattService: registerClient() - UUID=0968e191-d189-400a-9f9b-f5fb30f73574
,11-23 06:24:25.980  4665  4731 D BtGatt.GattService: onClientRegistered() - UUID=0968e191-d189-400a-9f9b-f5fb30f73574, clientIf=5
,11-23 06:24:25.981  5689  5700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 06:24:25.981  4665  4681 D BtGatt.GattService: start scan with filters
11-23 06:24:25.986  4665  4734 D BtGatt.ScanManager: handling starting scan
11-23 06:24:25.986  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 06:24:25.986  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:25.986  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 06:24:25.987  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:25.987  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 06:24:25.987  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 06:24:25.987  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:24:25.987  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 06:24:25.987  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 06:24:25.988  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:24:25.988  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 06:24:25.988  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:24:25.988  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 06:24:25.989  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 06:24:25.990  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:25.995  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:25.995  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:24:25.996  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:25.996  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:25.996  5689  5735 I io.jxcore.node.ConnectionHelper: start: OK
11-23 06:24:25.996  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 06:24:25.998  4665  4731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 06:24:25.999  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:25.999  4665  4734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 06:24:26.001  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.001  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 06:24:26.001  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.001  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 06:24:26.003  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 06:24:26.003  5689  5735 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 06:24:26.003  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:26.003  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 06:24:26.003  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:24:26.004  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 06:24:26.004  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:26.004  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 06:24:26.004  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 06:24:26.004  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.004  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:24:26.004  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 06:24:26.005  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.005  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.005  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.005  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 06:24:26.005  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.007  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:24:26.007  4665  4680 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 06:24:26.008  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 06:24:26.008  4665  4731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 06:24:26.008  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:26.009  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:24:26.010  4665  4734 D BtGatt.ScanManager: Starting BLE batch scan
11-23 06:24:26.010  4665  4734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 06:24:26.011  4665  4882 D BtGatt.GattService: stopScan() - queue size =1
11-23 06:24:26.013  4665  4681 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 06:24:26.013  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.014  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.015  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.015  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 06:24:26.015  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 06:24:26.017  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:24:26.017  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.021  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.021  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:26.021  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.021  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.022  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:26.022  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:24:26.022  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:24:26.022  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:26.022  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
,11-23 06:24:26.022  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:26.022  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:24:26.022  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:26.022  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:24:26.022  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:26.022  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:24:26.022  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 06:24:26.022  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.022  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 06:24:26.023  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-23 06:24:26.024  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.023  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.026  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.026  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.026  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.026  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:26.026  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.027  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.027  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.027  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.028  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:26.028  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 06:24:26.028  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:26.028  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.028  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:26.029  5689  5735 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 06:24:26.030  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.030  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 06:24:26.030  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.030  4665  4731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 06:24:26.030  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:26.032  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:26.032  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 06:24:26.040  4665  4731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 06:24:26.040  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:24:26.041  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 06:24:26.041  4665  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 06:24:26.043  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 06:24:26.044  5689  5735 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 06:24:26.044  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:24:26.044  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 06:24:26.044  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 06:24:26.044  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:26.044  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 06:24:26.047  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:26.047  4665  4731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:24:26.047  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:26.047  4665  4731 E BtGatt.ContextMap: Context not found for ID 5
11-23 06:24:26.049  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 06:24:26.049  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 06:24:26.049  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 06:24:26.050  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:26.053  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.053  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 06:24:26.054  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 06:24:26.054  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 06:24:26.054  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 06:24:26.054  4665  4731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 06:24:26.055  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:26.055  4665  4734 D BtGatt.ScanManager: stopping BLe Batch
11-23 06:24:26.059  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.059  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 06:24:26.059  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 06:24:26.059  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 06:24:26.059  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-23 06:24:26.059  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.060  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:24:26.062  4665  4731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 06:24:26.062  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:26.063  4665  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 06:24:26.063  4665  4681 D BtGatt.GattService: registerClient() - UUID=ac550406-b949-42b8-bf29-d214979a6836
11-23 06:24:26.063  4665  4731 D BtGatt.GattService: onClientRegistered() - UUID=ac550406-b949-42b8-bf29-d214979a6836, clientIf=5
11-23 06:24:26.064  5689  5699 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 06:24:26.064  4665  4680 D BtGatt.GattService: start scan with filters
11-23 06:24:26.068  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 06:24:26.069  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.069  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 06:24:26.069  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.069  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 06:24:26.069  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 06:24:26.069  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.069  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 06:24:26.069  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 06:24:26.069  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.070  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.070  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.070  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.070  4665  4731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:24:26.070  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:26.070  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 06:24:26.070  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.072  4665  4734 D BtGatt.ScanManager: handling starting scan
,11-23 06:24:26.074  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.074  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:24:26.074  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:26.074  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:26.074  5689  5735 I io.jxcore.node.ConnectionHelper: start: OK
11-23 06:24:26.074  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.077  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.077  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.077  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:26.077  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 06:24:26.080  4665  4731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 06:24:26.080  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:26.081  4665  4734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 06:24:26.086  4665  4731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 06:24:26.086  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:26.087  4665  4734 D BtGatt.ScanManager: Starting BLE batch scan
11-23 06:24:26.087  4665  4734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 06:24:26.097  4665  4731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 06:24:26.097  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:26.102  4665  4731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 06:24:26.102  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:26.583  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 06:24:26.584  5689  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:24:26.584  5689  5689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 06:24:27.522   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 06:24:30.569   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 06:24:31.076  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 06:24:31.076  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:31.077  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 06:24:31.077  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:24:31.077  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 06:24:31.077  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:31.077  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 06:24:31.077  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 06:24:31.078  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.078  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:24:31.078  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 06:24:31.078  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.079  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.079  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.079  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 06:24:31.079  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:31.083  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:24:31.084  4665  4681 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 06:24:31.085  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 06:24:31.086  4665  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:24:31.087  5689  5735 D BluetoothAdapter: STATE_ON
,11-23 06:24:31.089  4665  4891 D BtGatt.GattService: stopScan() - queue size =1
,11-23 06:24:31.092  4665  4892 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 06:24:31.093  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 06:24:31.095  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.096  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 06:24:31.096  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.097  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:31.097  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.097  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:31.097  4665  4665 D BtGatt.ScanManager: awakened up at time 200221
,11-23 06:24:31.097  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 06:24:31.097  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.097  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.098  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:31.098  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 06:24:31.098  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 06:24:31.104  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:24:31.104  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.107  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.107  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:31.107  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.107  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:31.108  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:24:31.108  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 06:24:31.108  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 06:24:31.108  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.108  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 06:24:31.109  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 06:24:31.109  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.109  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.109  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.110  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:31.110  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.110  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.114  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.114  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:24:31.114  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 06:24:31.134  4665  4731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,11-23 06:24:31.134  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:31.134  4665  4731 D BtGatt.GattService: current time is 200258959725
11-23 06:24:31.135  4665  4731 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -67, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -70, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -67, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -71, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -80, -54, -100, -120, -128, -10, 1, 0, -97, 78, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, -15, -112, 94, 3, 1, -29, 24, 62, 48, -61, -36, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 53, 33, -121, 80, 73, -44, 1, 0, -98, 74, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 0, -39, 94, 3, 2, -25, 21, 63, 39, -1, -58, 28, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 50, -35, 86, -77, -92, -11, 1, 0, -100, 72, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 55, -108, 94, 3, 2, -33, 21, 61, 121, 28, 50, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 37, -47, 14, -113, 116, -46, 1, -128, -73, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 06:24:31.135  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 06:24:31.136  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-23 06:24:31.136  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 06:24:31.136  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 06:24:31.137  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 06:24:31.137  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, -15, -112, 94, 3, 1, -29, 24, 62, 48, -61, -36, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 06:24:31.138  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 0, -39, 94, 3, 2, -25, 21, 63, 39, -1, -58, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 06:24:31.138  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 55, -108, 94, 3, 2, -33, 21, 61, 121, 28, 50, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-23 06:24:31.139  4665  4731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-23 06:24:31.146  4665  4731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 06:24:31.147  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:24:31.147  4665  4734 D BtGatt.ScanManager: stopping BLe Batch
,11-23 06:24:31.155  4665  4731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 06:24:31.155  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:31.155  4665  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 06:24:31.163  4665  4731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:24:31.163  4665  4731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:24:31.613  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 06:24:31.614  5689  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:31.614  5689  5689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 06:24:32.975   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:24:36.113  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 06:24:36.113  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.113  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 06:24:36.114  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 06:24:36.114  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:24:36.114  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:24:36.114  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.114  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.115  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.115  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.115  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.115  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:24:36.119  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.119  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.123  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.123  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.124  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.124  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.124  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.124  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:36.124  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.126  5689  5735 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 06:24:36.127  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.128  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.128  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.128  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.128  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 06:24:36.128  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.129  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.130  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.130  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.130  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.130  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.132  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.132  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.132  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.132  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.132  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.132  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.132  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:36.134  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-23 06:24:36.134  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.134  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.134  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.134  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.134  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.134  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.135  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.135  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.135  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 06:24:36.135  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.135  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.137  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.137  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.137  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.137  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.137  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.137  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.137  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.138  5689  5735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-23 06:24:36.138  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.139  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.139  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.139  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.139  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.139  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.139  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.139  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.139  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.139  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.139  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.141  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.142  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.142  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.142  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.142  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.142  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.142  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:36.143  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 06:24:36.143  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.143  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.143  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.143  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.144  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.144  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.144  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:36.144  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.144  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.144  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.144  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.146  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.146  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.146  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.146  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.146  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 06:24:36.147  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.147  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.147  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 06:24:36.148  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 06:24:36.148  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 06:24:36.148  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 06:24:36.148  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 06:24:36.148  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 06:24:36.148  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 06:24:36.148  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 06:24:36.148  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 06:24:36.148  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.149  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.149  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.149  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.149  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.149  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.149  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.149  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:36.149  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.149  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.149  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.152  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.152  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.152  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.152  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.152  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.152  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.153  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.153  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 06:24:36.154  5689  5735 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 06:24:36.154  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-23 06:24:36.157  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 06:24:36.157  5689  5735 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 06:24:36.157  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 06:24:36.157  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 06:24:36.158  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 06:24:36.159  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 06:24:36.159  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,11-23 06:24:36.160  5689  5735 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 06:24:36.160  5689  5735 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 06:24:36.160  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 06:24:36.160  5689  5735 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 06:24:36.160  5689  5735 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 06:24:36.160  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 06:24:36.160  5689  5735 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 06:24:36.160  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-23 06:24:36.164  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-23 06:24:36.165  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 06:24:36.166  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-23 06:24:36.166  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 06:24:36.167  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 06:24:36.167  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 06:24:36.167  5689  5735 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-23 06:24:36.167  5689  5735 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,11-23 06:24:36.167  5689  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-23 06:24:36.167  5689  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 06:24:36.167  5689  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 06:24:36.167  5689  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 06:24:36.168  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.168  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.168  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.168  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.168  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.168  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 06:24:36.169  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.169  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:36.170  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.170  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.170  5689  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 06:24:36.170  5689  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 06:24:36.170  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.170  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.172  4891  4891 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32110]" dev="sockfs" ino=32110 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 06:24:36.172  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.173  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.173  5689  5738 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 06:24:36.173  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.173  5689  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 06:24:36.173  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.173  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.173  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.173  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.174  5689  5735 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-23 06:24:36.175  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.175  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.175  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.175  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.175  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.175  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.175  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.175  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.175  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.175  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.176  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.175  4891  4891 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32110]" dev="sockfs" ino=32110 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 06:24:36.178  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.178  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.178  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.178  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.178  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.178  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.178  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.179  5689  5735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 06:24:36.179  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.179  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.179  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.179  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.180  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.180  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.180  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.180  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.180  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.180  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.180  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.183  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.183  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.183  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.183  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.183  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.183  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.183  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.184  5689  5735 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 06:24:36.184  5689  5735 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 06:24:36.184  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 06:24:36.184  5689  5735 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 06:24:36.184  5689  5735 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 06:24:36.184  5689  5735 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 06:24:36.184  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 06:24:36.184  5689  5735 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 06:24:36.184  5689  5735 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 06:24:36.184  5689  5735 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-23 06:24:36.184  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 06:24:36.184  5689  5735 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 06:24:36.185  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:36.185  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:36.185  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:36.185  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.185  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.185  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.185  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.185  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.185  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:36.185  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.185  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.187  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:36.187  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.188  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:36.188  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:36.188  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:36.188  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.188  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.188  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:36.189  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:36.189  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:36.189  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:36.189  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:36.189  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 06:24:41.191  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.191  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:41.191  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:41.191  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:41.192  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:41.192  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:41.193  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:41.193  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:41.193  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:41.193  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:41.193  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:41.194  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:41.194  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.194  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:41.194  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.195  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:41.199  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.200  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:41.200  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.200  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:41.200  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:41.200  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.201  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:41.207  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-23 06:24:41.209  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:41.209  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 06:24:41.213  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-23 06:24:41.214  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-23 06:24:41.214  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 06:24:41.214  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-23 06:24:41.215  5689  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-23 06:24:41.215  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 06:24:41.215  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 06:24:41.215  5689  5689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-23 06:24:41.215  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:41.216  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 06:24:41.216  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 06:24:41.216  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 06:24:41.216  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:24:41.216  5689  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 06:24:41.216  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 06:24:41.217  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-23 06:24:41.217  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:41.217  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.217  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 06:24:41.217  5689  5689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 06:24:41.217  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.217  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:24:41.217  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 06:24:41.217  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:41.219  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.218  4681  4681 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32112]" dev="sockfs" ino=32112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 06:24:41.219  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:41.219  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.219  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.220  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:41.220  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:41.220  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:41.220  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:41.220  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 06:24:41.218  4681  4681 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32112]" dev="sockfs" ino=32112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 06:24:41.220  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:41.220  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:24:41.220  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 06:24:41.220  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
,11-23 06:24:41.220  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.220  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.220  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:41.220  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.220  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.220  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:24:41.222  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.222  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.223  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.223  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:41.223  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:41.223  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.223  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.223  5689  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-23 06:24:41.223  5689  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 06:24:41.224  5689  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 06:24:41.224  5689  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 06:24:41.224  5689  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:41.224  5689  5735 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 06:24:41.224  5689  5735 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 06:24:41.224  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 06:24:41.225  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 06:24:41.225  5689  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 06:24:41.225  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:41.225  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:41.225  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:41.225  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:41.225  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:41.226  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:41.226  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:41.226  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.226  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:41.226  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.226  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.228  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.228  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.228  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.228  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:41.228  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:41.228  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.228  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.234  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:41.234  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:41.234  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:41.234  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 06:24:41.234  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:41.234  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
11-23 06:24:41.234  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.235  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.235  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:41.235  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.235  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:41.236  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:41.236  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.236  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.237  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:41.237  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:41.237  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.237  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.238  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:24:41.239  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:24:41.239  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:24:41.239  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:24:41.239  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:24:41.239  5689  5735 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75e9d0c not in the list
,11-23 06:24:41.239  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.239  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
11-23 06:24:41.239  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:41.239  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.239  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:24:41.241  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.241  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.241  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:24:41.241  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:24:41.241  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:24:41.241  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:41.241  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ab655 not in the list
,11-23 06:24:41.242  5689  5735 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-23 06:24:41.243  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 06:24:41.243  5689  5735 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 06:24:41.243  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 06:24:41.243  5689  5735 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 06:24:41.243  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 06:24:41.245  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 06:24:41.245  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 06:24:41.245  5689  5735 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 06:24:41.245  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-23 06:24:41.246  5689  5735 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 06:24:41.246  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 06:24:41.246  5689  5735 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 06:24:41.246  5689  5735 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 06:24:41.246  5689  5735 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-23 06:24:41.246  5689  5735 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-23 06:24:41.246  5689  5735 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 06:24:41.247  5689  5735 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 06:24:41.247  5689  5735 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 06:24:41.247  5689  5735 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-23 06:24:41.247  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 06:24:41.247  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6b101a added. We now have 3 listener(s)
11-23 06:24:41.248  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:24:41.250  5689  5735 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 06:24:41.250   929  3618 D WifiService: setWifiEnabled: true pid=5689, uid=10077
11-23 06:24:41.251   929  3618 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 06:24:41.305  4665  4874 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-23 06:24:41.305  4665  4880 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-23 06:24:41.305  5689  5738 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-23 06:24:41.306  5689  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 06:24:41.306  5689  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-23 06:24:41.724  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 06:24:46.258  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:24:46.258  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999f74b added. We now have 4 listener(s)
11-23 06:24:46.259  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:24:46.276  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:24:46.276  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999f74b removed from the list
11-23 06:24:46.276  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:46.278  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 06:24:46.278  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee95528 added. We now have 4 listener(s)
11-23 06:24:46.279  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:24:46.284  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:24:46.284  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee95528 removed from the list
11-23 06:24:46.284  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:24:46.286  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:24:46.286  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63ba241 added. We now have 4 listener(s)
11-23 06:24:46.286  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:24:46.293   929   939 D WifiService: setWifiEnabled: false pid=5689, uid=10077
11-23 06:24:46.294   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 06:24:46.298   929  3017 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 06:24:46.299   929  3017 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 06:24:46.299   929  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 06:24:46.299   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:24:46.307  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:24:46.308  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 06:24:46.311  4665  4726 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 06:24:46.311  4665  4726 D BluetoothAdapterProperties: Setting state to 13
,11-23 06:24:46.312  4665  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 06:24:46.314  4665  4726 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 06:24:46.315  4665  4726 I BluetoothAdapterState: Entering PendingCommandState
11-23 06:24:46.318  4665  4665 D BluetoothMapService: onReceive
,11-23 06:24:46.318  4665  4665 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 06:24:46.318  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.318  4665  4665 D BluetoothMapService: STATE_TURNING_OFF
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:24:46.319  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 06:24:46.319  4665  4665 D BluetoothMapService: MAP Service closeService in
11-23 06:24:46.319  4665  4665 D BluetoothMapMasInstance0: MAP Service shutdown
,11-23 06:24:46.319  4665  4665 D ObexServerSockets0: shutdown(block = true)
11-23 06:24:46.320  4665  4665 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 06:24:46.320  4665  4665 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 06:24:46.320   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-23 06:24:46.320  4665  4880 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 06:24:46.321   929  5438 D DhcpClient: Clearing IP address
11-23 06:24:46.323  4665  4894 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-23 06:24:46.325  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.325  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 06:24:46.325  5689  5735 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 06:24:46.325  4665  4895 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 06:24:46.327  4665  4665 I BtOppRfcommListener: stopping Accept Thread
11-23 06:24:46.327  4665  5365 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 06:24:46.328  4665  5365 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 06:24:46.328   506   921 D CommandListener: Setting iface cfg
11-23 06:24:46.332  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:24:46.332   929  5439 D DhcpClient: Receive thread stopped
,11-23 06:24:46.335  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:24:46.336  3623  5492 V NativeCrypto: Read error: ssl=0x7f89a46180: I/O error during system call, Connection timed out
11-23 06:24:46.338  3623  5492 V NativeCrypto: SSL shutdown failed: ssl=0x7f89a46180: I/O error during system call, Broken pipe
11-23 06:24:46.339  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:24:46.341   929  3985 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-23 06:24:46.341   929  5436 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 06:24:46.343   929  5436 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-23 06:24:46.344   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-23 06:24:46.344   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 06:24:46.346   929  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 06:24:46.348   929   942 I ActivityManager: Start proc 5745:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-23 06:24:46.349  4665  4731 D BluetoothAdapterProperties: Scan Mode:20
,11-23 06:24:46.349  4665  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 06:24:46.353   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 06:24:46.353   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 06:24:46.357  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:24:46.357  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 06:24:46.358  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.358  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-23 06:24:46.358   929   929 D RttService: SCAN_AVAILABLE : 1
11-23 06:24:46.358   532   532 E Parcel  : Reading a NULL string not supported here.
11-23 06:24:46.359  4665  4665 D HeadsetService: Received stop request...Stopping profile...
11-23 06:24:46.359   929  3127 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 06:24:46.361   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 06:24:46.362  3162  3173 D BluetoothHeadset: Proxy object disconnected,
11-23 06:24:46.362  3833  3853 D BluetoothHeadset: Proxy object disconnected
11-23 06:24:46.362  4665  4665 D A2dpService: Received stop request...Stopping profile...
11-23 06:24:46.363  4665  4886 D A2dpStateMachine: Exit Disconnected: -1
11-23 06:24:46.363   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 06:24:46.363   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 06:24:46.364   929   929 D BluetoothA2dp: Proxy object disconnected
11-23 06:24:46.364  4665  4665 D HidService: Received stop request...Stopping profile...
11-23 06:24:46.364  4665  4665 D HidService: Stopping Bluetooth HidService
11-23 06:24:46.365  3162  3162 D HeadsetProfile: Bluetooth service disconnected
11-23 06:24:46.365   929  3019 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-23 06:24:46.365  3162  3162 D BluetoothA2dp: Proxy object disconnected
,11-23 06:24:46.366  3162  3162 D BluetoothInputDevice: Proxy object disconnected
11-23 06:24:46.367  4665  4665 D HealthService: Received stop request...Stopping profile...
11-23 06:24:46.367  3162  3162 D HidProfile: Bluetooth service disconnected
11-23 06:24:46.367  3805  3945 W QCNEJ   : |CORE| network lost: 100
,11-23 06:24:46.369  3805  3945 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 06:24:46.369  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.369  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.369  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:24:46.369  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 06:24:46.371  4665  4665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 06:24:46.371  4665  4665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 06:24:46.371  4665  4731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 06:24:46.372  4665  4874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:24:46.372  4665  4874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:24:46.372  4665  4874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:24:46.372  4665  4731 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 06:24:46.372  4665  4665 D PanService: Received stop request...Stopping profile...
11-23 06:24:46.375  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.375  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.375  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:24:46.375  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:24:46.376  4665  4665 D BluetoothMapService: Received stop request...Stopping profile...
11-23 06:24:46.376  4665  4665 D BluetoothMapService: stop()
11-23 06:24:46.377  4665  4665 D BluetoothMapAppObserver: deinitObservers()
11-23 06:24:46.377  4665  4665 D BluetoothMapAppObserver: removeReceiver()
,11-23 06:24:46.380  4665  4731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-23 06:24:46.380  4665  4874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:24:46.380  4665  4874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:24:46.380  4665  4874 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 06:24:46.380  4665  4874 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 06:24:46.380  4665  4874 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 06:24:46.380  4665  4874 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 06:24:46.380  4665  4665 D SapService: Received stop request...Stopping profile...
11-23 06:24:46.380  4665  4665 V SapService: stop()
11-23 06:24:46.382  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.382  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.382  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 06:24:46.382  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:24:46.383  4665  4665 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 06:24:46.383  4665  4665 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 06:24:46.383  4665  4731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 06:24:46.383  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.383  4665  4665 V BluetoothAdapterState: isTurningOn()=false
,11-23 06:24:46.383  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 06:24:46.383  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:24:46.383  4665  4665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 06:24:46.384  4665  4731 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-23 06:24:46.384  4665  4665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-23 06:24:46.384  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.384  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.384  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:24:46.384  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:24:46.384  4665  4665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 06:24:46.385  4665  4665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-23 06:24:46.385  4665  4665 D BluetoothMapService: MAP Service closeService in
11-23 06:24:46.385  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.385  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.385  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:24:46.385  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:24:46.386  4665  4665 D BluetoothMapService: cleanup()
11-23 06:24:46.386  4665  4665 D BluetoothMapService: MAP Service closeService in
11-23 06:24:46.386  4665  4665 V BluetoothAdapterState: isTurningOff()=true
11-23 06:24:46.386  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.386  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:24:46.386  4665  4665 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:24:46.386  4665  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 06:24:46.386  4665  4726 D BluetoothAdapterProperties: Setting state to 15
11-23 06:24:46.386  4665  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-23 06:24:46.387   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 06:24:46.387  3162  3174 D BluetoothPan: onBluetoothStateChange on: false
11-23 06:24:46.387   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:24:46.388  3162  4020 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 06:24:46.388  3162  3173 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 06:24:46.388   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:24:46.388  3162  3965 D BluetoothMap: onBluetoothStateChange: up=false
11-23 06:24:46.389  4665  4726 I BluetoothAdapterState: Entering BleOnState
11-23 06:24:46.389   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:24:46.389  3162  3174 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 06:24:46.390  3162  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:24:46.390  3833  3857 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 06:24:46.390  4665  4726 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 06:24:46.390  4665  4726 D BluetoothAdapterProperties: Setting state to 16
11-23 06:24:46.391  4665  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 06:24:46.391  4665  4726 D BluetoothAdapterProperties: onBleDisable
11-23 06:24:46.392  4665  4726 I BluetoothAdapterState: Entering PendingCommandState
11-23 06:24:46.392  4665  4727 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 06:24:46.392  4665  4731 D BluetoothAdapterProperties: Scan Mode:20
11-23 06:24:46.394   929  3017 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 06:24:46.394   929  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 06:24:46.394  4665  4874 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 06:24:46.394  4665  4874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:24:46.396  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:24:46.396  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 06:24:46.396  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.396  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 06:24:46.399  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:46.411   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 06:24:46.421  5745  5745 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 06:24:46.430   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 06:24:46.430   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-23 06:24:46.431   506   921 D TetherController: Setting IP forward enable = 0
,11-23 06:24:46.432   929  3019 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-23 06:24:46.432   929  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 06:24:46.433  5745  5745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 06:24:46.433   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 06:24:46.436  5350  5350 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8b2eafc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-23 06:24:46.437  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:46.438   929  3017 D DhcpClient: doQuit
11-23 06:24:46.438   929  3017 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 06:24:46.439   929  5438 D DhcpClient: onQuitting
11-23 06:24:46.439  3949  3949 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-23 06:24:46.439  3494  3494 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-23 06:24:46.444  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:24:46.444  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 06:24:46.444  5100  5127 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 06:24:46.444  5100  5127 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 06:24:46.444  5100  5127 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 06:24:46.444  5100  5127 E SarControlService: no key has been found,reset the power
11-23 06:24:46.444  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:46.445  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 06:24:46.445  5100  5140 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 06:24:46.445  5100  5140 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 06:24:46.445  5100  5140 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 06:24:46.446  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 06:24:46.446  5128  5128 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 06:24:46.447  5100  5140 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 06:24:46.447  5100  5140 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 06:24:46.447  5100  5140 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 06:24:46.447  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 06:24:46.447  5128  5128 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 06:24:46.450  5128  5142 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ea03000000000000ffffffff]
11-23 06:24:46.450  5128  5142 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 06:24:46.450  5128  5142 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 06:24:46.451  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 06:24:46.451  5100  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 06:24:46.454  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 06:24:46.454   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba3beac:true
,11-23 06:24:46.457  5128  5142 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000eb03000000000000ffffffff]
,11-23 06:24:46.457  5128  5142 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 06:24:46.457  5128  5142 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 06:24:46.458  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 06:24:46.458  5100  5112 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 06:24:46.461  3494  3494 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 06:24:46.465  3494  3494 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 06:24:46.467   929  3985 I ActivityManager: Start proc 5773:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-23 06:24:46.468   506   914 W SocketClient: write error (Broken pipe)
,11-23 06:24:46.468   506   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-23 06:24:46.468   506   914 W SocketListener: Error sending broadcast (Broken pipe)
,11-23 06:24:46.481   506   921 E Netd    : netlink response contains error (No such file or directory)
,11-23 06:24:46.483   929  3019 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 06:24:46.484   506   921 D TetherController: Setting IP forward enable = 0
,11-23 06:24:46.490  5745  5745 D LocalBluetoothProfileManager: Adding local MAP profile
,11-23 06:24:46.492  5745  5745 D BluetoothMap: Create BluetoothMap proxy object
,11-23 06:24:46.501  3494  3494 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 06:24:46.509  3494  3494 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-23 06:24:46.509  5745  5745 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 06:24:46.513  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 06:24:46.513   929  3017 D wifi    : In wifi stop Hal
11-23 06:24:46.513   929  3017 D wifi    : halHandle = 0x7f734c3b80, mVM = 0x7f8fb0d140, mCls = 0x100a02
11-23 06:24:46.514   929  3493 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 06:24:46.514   929  3493 D WifiHAL : Got a signal to exit!!!
11-23 06:24:46.514   929  3493 I WifiHAL : Exit wifi_event_loop
,11-23 06:24:46.514   929  3017 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 06:24:46.514   929  3017 E WifiHAL : Event processing terminated
11-23 06:24:46.514   929  3017 D wifi    : In wifi cleaned up handler
11-23 06:24:46.514   929  3017 I WifiHAL : Internal cleanup completed
,11-23 06:24:46.516  5773  5773 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-23 06:24:46.517  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:24:46.518  4183  4276 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 06:24:46.528  5745  5745 D DockEventReceiver: finishStartingService: stopping service
,11-23 06:24:46.530   929  3637 I ActivityManager: Killing 5028:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-23 06:24:46.535   929  3493 D wifi    : set interface wlan0 flags (DOWN)
11-23 06:24:46.536   929  3017 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 06:24:46.601  4665  4731 I bt_hci  : shut_down
,11-23 06:24:46.606  4665  4735 D bt_hwcfg: hw_epilog_process
,11-23 06:24:46.606  4665  4735 I bt_vendor: low_power_mode_cb
,11-23 06:24:46.610  4665  4735 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 06:24:46.610  4665  4735 I bt_vendor: epilog_cb
,11-23 06:24:46.610  4665  4735 I bt_hci  : epilog_finished_callback
11-23 06:24:46.612  4665  4731 I bt_hci_h4: hal_close
11-23 06:24:46.612  4665  4731 I bt_userial_vendor: device fd = 54 close
,11-23 06:24:46.723  4665  4727 D bt_stack_manager: event_shut_down_stack finished.
,11-23 06:24:46.724  4665  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 06:24:46.725  4665  4726 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 06:24:46.726  4665  4665 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 06:24:46.726  4665  4665 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 06:24:46.727  4665  4665 D BtGatt.GattService: stop()
,11-23 06:24:46.727  4665  4665 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 06:24:46.729  4665  4665 V BluetoothAdapterState: isTurningOff()=false
11-23 06:24:46.729  4665  4665 V BluetoothAdapterState: isTurningOn()=false
11-23 06:24:46.729  4665  4665 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 06:24:46.729  4665  4665 V BluetoothAdapterState: isBleTurningOff()=true
11-23 06:24:46.730  4665  4726 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 06:24:46.730  4665  4726 D BluetoothAdapterProperties: Setting state to 10
,11-23 06:24:46.730  4665  4726 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 06:24:46.732  4665  4726 I BluetoothAdapterState: Entering OffState
11-23 06:24:46.733   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-23 06:24:46.739   929   946 D Tethering: InitialState.processMessage what=4
11-23 06:24:46.742   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 06:24:46.744  4665  4665 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-23 06:24:46.744  4665  4665 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-23 06:24:46.744  4665  4665 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 06:24:46.745  4665  4727 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 06:24:46.753  4665  4665 I art     : System.exit called, status: 0
11-23 06:24:46.753  4665  4665 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 06:24:46.774  5773  5773 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.774  5773  5773 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.774  5773  5773 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.774  5773  5773 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.774  5773  5773 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.k.d(PG:583)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.774  5773  5773 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.774  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.775  5773  5773 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:24:46.775  5773  5773 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:24:46.775  5773  5773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 06:24:46.812   929  3985 I ActivityManager: Process com.android.bluetooth (pid 4665) has died
11-23 06:24:46.818  5745  5745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 06:24:46.835   929   940 I ActivityManager: Start proc 5809:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-23 06:24:46.836  5745  5745 D DockEventReceiver: finishStartingService: stopping service
11-23 06:24:46.837   929  3986 I ActivityManager: Killing 5464:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 06:24:46.914  5809  5809 D AdapterServiceConfig: Adding HeadsetService
,11-23 06:24:46.914  5809  5809 D AdapterServiceConfig: Adding A2dpService
11-23 06:24:46.915  5809  5809 D AdapterServiceConfig: Adding HidService
11-23 06:24:46.915  5809  5809 D AdapterServiceConfig: Adding HealthService
11-23 06:24:46.915  5809  5809 D AdapterServiceConfig: Adding PanService
11-23 06:24:46.915  5809  5809 D AdapterServiceConfig: Adding GattService
11-23 06:24:46.915  5809  5809 D AdapterServiceConfig: Adding BluetoothMapService
11-23 06:24:46.915  5809  5809 D AdapterServiceConfig: Adding SapService
11-23 06:24:46.918   929  3976 I ActivityManager: Killing 5477:com.android.chrome/u0a39 (adj 15): empty #17
,11-23 06:24:46.946  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 06:24:46.962  3998  3998 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 06:24:46.966  3998  3998 D SystemUpdateService: onCreate
,11-23 06:24:46.969  3998  3998 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 06:24:46.974  3998  5821 I SystemUpdateService: active receiver: enabled
,11-23 06:24:46.980  3998  3998 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 06:24:46.985  3998  5462 I iu.UploadsManager: num queued entries: 0
,11-23 06:24:46.986  3998  5462 I iu.UploadsManager: num updated entries: 0
11-23 06:24:46.987  3998  5462 I iu.SyncManager: NEXT; no task
11-23 06:24:46.988  3998  3998 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 06:24:46.990  3998  3998 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 06:24:47.003   929  3985 I ActivityManager: Start proc 5823:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 06:24:47.005  3998  5821 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 06:24:47.007  3998  5821 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 06:24:47.008  3998  5821 I SystemUpdateService: now status is 0 (complete)
11-23 06:24:47.008  3998  5821 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 06:24:47.008  3998  5821 I SystemUpdateService: file has been verified
11-23 06:24:47.008  3998  5821 I SystemUpdateService: OTA package size = 21989297
,11-23 06:24:47.014  3998  5821 I SystemUpdateService: showing system update notification
,11-23 06:24:47.040  5823  5823 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 06:24:47.044  5823  5823 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 06:24:47.050  5823  5823 D SprintDMHelper: simOperator: 
11-23 06:24:47.050  5823  5823 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 06:24:47.063   929  3242 I ActivityManager: Start proc 5835:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
11-23 06:24:47.066  3998  3998 D SystemUpdateService: onDestroy
,11-23 06:24:47.069   929  3985 I ActivityManager: Killing 5498:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-23 06:24:47.166  5069  5849 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 06:24:47.174   929  3242 I ActivityManager: Start proc 5850:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-23 06:24:47.177   929  3242 I ActivityManager: Killing 5350:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 06:24:47.206  5773  5802 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-23 06:24:47.228  5850  5850 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-23 06:24:47.302   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@edcde3f:true
,11-23 06:24:47.433   929  3985 I ActivityManager: Killing 4741:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 06:24:47.472   929   939 I ActivityManager: Start proc 5864:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 06:24:47.502  5864  5864 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 06:24:47.510   929  3985 I ActivityManager: Killing 5546:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-23 06:24:50.111   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 06:24:50.111   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 06:24:51.328   929  3984 D WifiService: setWifiEnabled: true pid=5689, uid=10077
11-23 06:24:51.329   929  3984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 06:24:51.338   506   921 D SoftapController: Softap fwReload - Ok
,11-23 06:24:51.344   506   921 D CommandListener: Setting iface cfg
,11-23 06:24:51.344   506   921 D CommandListener: Trying to bring down wlan0
11-23 06:24:51.347   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-23 06:24:51.354   929  3017 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 06:24:52.043   929  3017 D wifi    : set interface wlan0 flags (UP)
,11-23 06:24:52.048   929  3017 I WifiHAL : Initializing wifi
,11-23 06:24:52.050   929  3017 I WifiHAL : Creating socket
,11-23 06:24:52.052   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 06:24:52.056   929  3017 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 06:24:52.057   929  3017 D wifi    : Did set static halHandle = 0x7f734c3b80
,11-23 06:24:52.057   929  3017 D wifi    : halHandle = 0x7f734c3b80, mVM = 0x7f8fb0d140, mCls = 0x101972
11-23 06:24:52.057   929  3017 D wifi    : array field set
11-23 06:24:52.057   929  3017 I WifiNative-HAL: interface[0] = wlan0
11-23 06:24:52.060   929  5882 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547395222400
11-23 06:24:52.060   929  5882 D wifi    : waitForHalEvents called, vm = 0x7f8fb0d140, obj = 0x101972, env = 0x7f70e76e00
,11-23 06:24:52.135  5883  5883 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 06:24:52.147  5883  5883 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 06:24:52.162   929  3017 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 06:24:52.166  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:24:52.183  5883  5883 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 06:24:52.183  5883  5883 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 06:24:52.205  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:24:52.205  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 06:24:52.205  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:52.205  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 06:24:52.206   929  3017 D WifiConfigStore: Loading config and enabling all networks 
,11-23 06:24:52.222   929  3017 D WifiConfigStore: loaded 0 passpoint configs
,11-23 06:24:52.222   929  3017 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-23 06:24:52.223   929  3017 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 06:24:52.224   929  3017 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 06:24:52.225   929  3017 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 06:24:52.225   929  3017 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 06:24:52.225   929  3017 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 06:24:52.225   929  3017 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 06:24:52.228   929  3017 D WifiNative-HAL: Setting external_sim to 1
,11-23 06:24:52.229   929  3017 D wifi    : setting dfs flag to true, 0x7f785e4740
11-23 06:24:52.229  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 06:24:52.229   929  3017 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 06:24:52.229   929  3017 D wifi    : setting scan oui 0x7f785e4740
11-23 06:24:52.229   929  3017 D WifiHAL : Sending mac address OUI
,11-23 06:24:52.235   929  3017 E native  : do suspend false
,11-23 06:24:52.246   929  3017 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 06:24:52.246   929   929 D RttService: SCAN_AVAILABLE : 3
11-23 06:24:52.246   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 06:24:52.247   929  3127 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 06:24:52.247   506   921 D CommandListener: Setting iface cfg
,11-23 06:24:52.253   929  3016 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
11-23 06:24:52.253   929  3016 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 06:24:52.267   929  3016 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 06:24:52.275   929  3016 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-23 06:24:52.275   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=221399 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
,11-23 06:24:52.978   929  3017 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-23 06:24:55.297  5883  5883 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 06:24:55.324  5883  5883 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 06:24:55.374   929  3017 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 06:24:55.376   929  3017 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 06:24:55.376   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:24:55.393   929  3017 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 06:24:55.430   929  3017 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 06:24:55.434  5883  5883 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 06:24:56.013  5883  5883 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 06:24:56.277  5883  5883 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 06:24:56.280  5883  5883 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 06:24:56.298   929  3017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 06:24:56.299   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:24:56.299   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 06:24:56.320   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:24:56.334   929  3984 D WifiService: setWifiEnabled: false pid=5689, uid=10077
,11-23 06:24:56.335   929  3984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 06:24:56.338   506   921 D CommandListener: Setting iface cfg
,11-23 06:24:56.345   929  3017 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 06:24:56.353   929  5892 D DhcpClient: Receive thread started
,11-23 06:24:56.359   929  3017 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,11-23 06:24:56.359   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 06:24:56.359   929  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-23 06:24:56.359   929  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 06:24:56.360   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:24:56.372   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-23 06:24:56.379   929  5892 D DhcpClient: Receive thread stopped
,11-23 06:24:56.382   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,11-23 06:24:56.382   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,11-23 06:24:56.386   929   929 D RttService: SCAN_AVAILABLE : 1
11-23 06:24:56.386   929  3127 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 06:24:56.389   929  3019 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 06:24:56.389   929  3019 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-23 06:24:56.394   929  3017 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 06:24:56.399   929  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 06:24:56.400   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-23 06:24:56.403   929  3017 D DhcpClient: doQuit
,11-23 06:24:56.404   929  3017 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 06:24:56.404   929  5891 D DhcpClient: onQuitting
11-23 06:24:56.405  5883  5883 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-23 06:24:56.410  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:24:56.410  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 06:24:56.410  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 06:24:56.411  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 06:24:56.415  5883  5883 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 06:24:56.419  5883  5883 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 06:24:56.514  5883  5883 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 06:24:56.528  5883  5883 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 06:24:56.635   929  3017 D wifi    : In wifi stop Hal
11-23 06:24:56.636   929  3017 D wifi    : halHandle = 0x7f734c3b80, mVM = 0x7f8fb0d140, mCls = 0x101972
,11-23 06:24:56.636   929  5882 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 06:24:56.636   929  5882 D WifiHAL : Got a signal to exit!!!
11-23 06:24:56.636   929  5882 I WifiHAL : Exit wifi_event_loop
11-23 06:24:56.638   929  3017 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 06:24:56.639   929  3017 E WifiHAL : Event processing terminated
11-23 06:24:56.640   929  3017 D wifi    : In wifi cleaned up handler
11-23 06:24:56.640  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 06:24:56.640   929  3017 I WifiHAL : Internal cleanup completed
11-23 06:24:56.645  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:24:56.646  4183  4276 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 06:24:56.682   929  5882 D wifi    : set interface wlan0 flags (DOWN)
11-23 06:24:56.683   929  3017 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 06:24:56.891   929   946 D Tethering: InitialState.processMessage what=4
,11-23 06:24:56.899   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 06:25:00.113   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:01.116   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:01.383   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fc3dd2:true
,11-23 06:25:01.384  5809  5809 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 06:25:01.388  5809  5809 I bt_bluedroid: init
,11-23 06:25:01.389  5809  5893 I BluetoothAdapterState: Entering OffState
,11-23 06:25:01.393  5809  5894 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 06:25:01.393  5809  5894 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 06:25:01.393  5809  5894 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 06:25:01.393  5809  5894 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 06:25:01.395  5809  5809 I bt_bluedroid: get_profile_interface socket
,11-23 06:25:01.398  5809  5897 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 06:25:01.399  5809  5809 I bt_bluedroid: get_profile_interface sdp
,11-23 06:25:01.401  5809  5897 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 06:25:01.407  5809  5819 I bt_bluedroid: config_hci_snoop_log
,11-23 06:25:01.409   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 06:25:01.415  5809  5893 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 06:25:01.415  5809  5893 D BluetoothAdapterProperties: Setting state to 14
11-23 06:25:01.415  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 06:25:01.417  5809  5893 D BluetoothBondStateMachine: make
,11-23 06:25:01.420  5809  5898 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 06:25:01.424  5809  5893 I BluetoothAdapterState: Entering PendingCommandState
,11-23 06:25:01.425  5809  5809 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 06:25:01.428  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:01.429  5809  5809 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 06:25:01.430  5809  5809 D BtGatt.GattService: Received start request. Starting profile...
,11-23 06:25:01.430  5809  5809 D BtGatt.GattService: start()
11-23 06:25:01.430  5809  5809 I bt_bluedroid: get_profile_interface gatt
11-23 06:25:01.432  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:01.432  5809  5809 D BtGatt.AdvertiseManager: advertise manager created
,11-23 06:25:01.441  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,11-23 06:25:01.441  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:01.441  5809  5809 V BluetoothAdapterState: isBleTurningOn()=true
11-23 06:25:01.441  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:01.441  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 06:25:01.443  5809  5893 I bt_bluedroid: bt_bluedroid
,11-23 06:25:01.444  5809  5894 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 06:25:01.444  5809  5894 I bt_hci  : start_up
,11-23 06:25:01.452  5809  5894 I bt_vendor: alloc value 0xf41f8871
11-23 06:25:01.452  5809  5894 I bt_vendor: init
11-23 06:25:01.452  5809  5894 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 06:25:01.452  5809  5894 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 06:25:01.566  5809  5894 D bt_hci  : start_up starting async portion
,11-23 06:25:01.567  5809  5901 I bt_hci  : event_finish_startup
,11-23 06:25:01.567  5809  5901 I bt_hci_h4: hal_open
11-23 06:25:01.567  5809  5901 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 06:25:01.568  5902  5902 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-23 06:25:01.571  5809  5901 I bt_userial_vendor: device fd = 54 open
,11-23 06:25:01.590  5809  5901 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 06:25:01.594  5809  5901 D bt_hwcfg: Chipset BCM4358A3
,11-23 06:25:01.594  5809  5901 D bt_hwcfg: Target name = [BCM4358A3]
11-23 06:25:01.595  5809  5901 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 06:25:02.117   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:02.374  5809  5901 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-23 06:25:02.375  5809  5901 D bt_hwcfg: Settlement delay -- 100 ms
11-23 06:25:02.375  5809  5901 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 06:25:02.512  5809  5901 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 06:25:02.513  5809  5901 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-23 06:25:02.515  5809  5901 I bt_hwcfg: vendor lib fwcfg completed
,11-23 06:25:02.515  5809  5901 I bt_vendor: firmware callback
11-23 06:25:02.515  5809  5901 I bt_hci  : firmware_config_callback
11-23 06:25:02.529  5809  5904 I bt_btu  : btu_task pending for preload complete event
11-23 06:25:02.529  5809  5904 I bt_btu_task: Bluetooth chip preload is complete
11-23 06:25:02.529  5809  5904 I bt_btu  : btu_task received preload complete event
,11-23 06:25:02.536  5809  5904 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 06:25:02.536  5809  5904 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 06:25:02.536  5809  5904 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 06:25:02.536  5809  5904 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 06:25:02.536  5809  5904 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_PAN
,11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 06:25:02.537  5809  5904 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 06:25:02.538  5809  5904 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 06:25:02.641  5809  5904 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4176549
11-23 06:25:02.641  5809  5904 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4176549 
,11-23 06:25:02.656  5809  5897 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 06:25:02.659  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 06:25:02.660  5809  5897 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 06:25:02.663  5809  5897 D BluetoothAdapterProperties: Name is: Nexus 6P
11-23 06:25:02.667  5809  5897 D BluetoothAdapterProperties: Scan Mode:20
11-23 06:25:02.667  5809  5897 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 06:25:02.667  5809  5897 D bt_hci  : do_postload posting postload work item
11-23 06:25:02.667  5809  5901 I bt_hci  : event_postload
11-23 06:25:02.668  5809  5901 I bt_vendor: sco_config_cb
11-23 06:25:02.668  5809  5901 I bt_hci  : sco_config_callback postload finished.
11-23 06:25:02.670  5809  5897 D bt_bte_conf: Device ID record 1 : primary
11-23 06:25:02.670  5809  5897 D bt_bte_conf:   vendorId            = 000f
,11-23 06:25:02.670  5809  5897 D bt_bte_conf:   vendorIdSource      = 0001
,11-23 06:25:02.670  5809  5897 D bt_bte_conf:   product             = 1200
,11-23 06:25:02.670  5809  5897 D bt_bte_conf:   version             = 1436
,11-23 06:25:02.670  5809  5897 D bt_bte_conf:   clientExecutableURL = 
11-23 06:25:02.670  5809  5897 D bt_bte_conf:   serviceDescription  = 
11-23 06:25:02.670  5809  5897 D bt_bte_conf:   documentationURL    = 
11-23 06:25:02.671  5809  5897 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 06:25:02.671  5809  5894 D bt_stack_manager: event_start_up_stack finished
11-23 06:25:02.673  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 06:25:02.673  5809  5893 D BluetoothAdapterProperties: Setting state to 15
11-23 06:25:02.673  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 06:25:02.674  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:25:02.675  5809  5893 I BluetoothAdapterState: Entering BleOnState
11-23 06:25:02.681  5809  5901 I bt_vendor: low_power_mode_cb
11-23 06:25:02.681  5809  5893 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 06:25:02.681  5809  5893 D BluetoothAdapterProperties: Setting state to 11
11-23 06:25:02.681  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 06:25:02.689  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:02.692  5809  5809 D HeadsetService: Received start request. Starting profile...
11-23 06:25:02.693  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:25:02.695  5809  5809 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-23 06:25:02.696  5809  5809 D HeadsetStateMachine: make
,11-23 06:25:02.702  5809  5893 I BluetoothAdapterState: Entering PendingCommandState
,11-23 06:25:02.707  5809  5809 D HeadsetStateMachine: max_hf_connections = 1
11-23 06:25:02.707  5809  5809 I bt_bluedroid: get_profile_interface handsfree
11-23 06:25:02.707  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 06:25:02.708  5809  5897 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 06:25:02.711  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:02.712  5809  5809 D A2dpService: Received start request. Starting profile...
,11-23 06:25:02.712  5809  5809 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 06:25:02.713  5809  5809 I bt_bluedroid: get_profile_interface avrcp
,11-23 06:25:02.719  5809  5809 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 06:25:02.719  5809  5809 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 06:25:02.720  5809  5809 D A2dpStateMachine: make
,11-23 06:25:02.721  5809  5809 I bt_bluedroid: get_profile_interface a2dp
,11-23 06:25:02.722  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 06:25:02.723  5809  5912 D A2dpStateMachine: Enter Disconnected: -2
11-23 06:25:02.724  5809  5809 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 06:25:02.725  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:02.726  5745  5745 D BluetoothInputDevice: Proxy object connected
,11-23 06:25:02.727  5809  5809 D HidService: Received start request. Starting profile...
11-23 06:25:02.727  5745  5745 D HidProfile: Bluetooth service connected
11-23 06:25:02.727  5809  5809 I bt_bluedroid: get_profile_interface hidhost
11-23 06:25:02.727  5809  5809 D HidService: setHidService(): set to: null
11-23 06:25:02.727  5809  5897 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf415756d
11-23 06:25:02.727  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 06:25:02.728  5809  5809 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-23 06:25:02.729  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:02.730  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 06:25:02.730  5809  5809 D HealthService: Received start request. Starting profile...
,11-23 06:25:02.732  5809  5809 I bt_bluedroid: get_profile_interface health
,11-23 06:25:02.733  5809  5809 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 06:25:02.734  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:02.735  5809  5809 D PanService: Received start request. Starting profile...
,11-23 06:25:02.735  5809  5809 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 06:25:02.735  5745  5745 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 06:25:02.735  5809  5809 I bt_bluedroid: get_profile_interface pan
11-23 06:25:02.736  5745  5745 D PanProfile: Bluetooth service connected
,11-23 06:25:02.736  5809  5897 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 06:25:02.738  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:02.739  5745  5745 D BluetoothMap: Proxy object connected
11-23 06:25:02.739  5809  5809 D BluetoothMapService: Received start request. Starting profile...
11-23 06:25:02.739  5809  5809 D BluetoothMapService: start()
11-23 06:25:02.739  5745  5745 D MapProfile: Bluetooth service connected
11-23 06:25:02.740  5745  5745 D BluetoothMap: getConnectedDevices()
11-23 06:25:02.740  5745  5745 D BluetoothMap: Bluetooth is Not enabled
,11-23 06:25:02.742  5809  5809 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 06:25:02.743  5809  5809 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 06:25:02.743  5809  5809 D BluetoothMapAppObserver: createReceiver()
11-23 06:25:02.745  5809  5809 D BluetoothMapAppObserver: initObservers()
11-23 06:25:02.745  5809  5809 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 06:25:02.753  5809  5809 V SapService: SapBinder()
,11-23 06:25:02.753  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:02.754  5809  5809 D SapService: Received start request. Starting profile...
11-23 06:25:02.754  5809  5809 V SapService: start()
,11-23 06:25:02.757  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,11-23 06:25:02.757  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.757  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.757  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:02.757  5809  5910 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.758  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:02.759  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:02.760  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.760  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.760  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 06:25:02.760  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:02.761  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:02.761  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:02.761  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 06:25:02.761  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 06:25:02.761  5809  5893 D BluetoothAdapterProperties: ScanMode =  20
11-23 06:25:02.761  5809  5893 D BluetoothAdapterProperties: State =  11
11-23 06:25:02.761  5809  5893 D BluetoothAdapterProperties: Setting state to 12
11-23 06:25:02.761  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 06:25:02.762   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 06:25:02.762  5809  5893 I BluetoothAdapterState: Entering OnState
,11-23 06:25:02.764  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-23 06:25:02.765  5809  5897 D BluetoothAdapterProperties: Scan Mode:21
11-23 06:25:02.766  5809  5897 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:25:02.769  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 06:25:02.769  3162  3965 D BluetoothPan: onBluetoothStateChange on: true
,11-23 06:25:02.771  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 06:25:02.771   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:02.771  3162  3162 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 06:25:02.771  3162  3162 D PanProfile: Bluetooth service connected
11-23 06:25:02.771  5745  5755 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 06:25:02.772  3162  3174 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 06:25:02.772   929   929 D BluetoothA2dp: Proxy object connected
11-23 06:25:02.773  5809  5809 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 06:25:02.773  5809  5809 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 06:25:02.774  3162  3965 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 06:25:02.774  3162  3162 D BluetoothA2dp: Proxy object connected
11-23 06:25:02.775  5809  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 06:25:02.776   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:02.776  3162  3174 D BluetoothMap: onBluetoothStateChange: up=true
11-23 06:25:02.776  3162  3162 D BluetoothInputDevice: Proxy object connected
11-23 06:25:02.776  3162  3162 D HidProfile: Bluetooth service connected
11-23 06:25:02.778   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 06:25:02.778  3162  4020 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 06:25:02.778  3162  3162 D BluetoothMap: Proxy object connected
11-23 06:25:02.778  3162  3162 D MapProfile: Bluetooth service connected
11-23 06:25:02.778  3162  3162 D BluetoothMap: getConnectedDevices()
11-23 06:25:02.779  5809  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 06:25:02.781  5745  5759 D BluetoothPan: onBluetoothStateChange on: true
11-23 06:25:02.781  5745  5755 D BluetoothMap: onBluetoothStateChange: up=true
11-23 06:25:02.781  5809  5809 D ObexServerSockets: Succeed to create listening sockets 
11-23 06:25:02.781  5809  5809 D ObexServerSockets0: startAccept()
11-23 06:25:02.781  5809  5809 D ObexServerSockets0: prepareForNewConnect()
11-23 06:25:02.781  3162  3173 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:02.782  3833  4047 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 06:25:02.782  5745  5759 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 06:25:02.783  5809  5809 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 06:25:02.783  5809  5809 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 06:25:02.785   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 06:25:02.786  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 06:25:02.787  5809  5918 D ObexServerSockets0: Accepting socket connection...
11-23 06:25:02.787  5809  5809 D BluetoothMapService: onReceive
,11-23 06:25:02.787  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:25:02.787  5809  5919 D ObexServerSockets0: Accepting socket connection...
11-23 06:25:02.787  5809  5809 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 06:25:02.787  5809  5809 D BluetoothMapService: STATE_ON
,11-23 06:25:02.788  5745  5745 D LocalBluetoothProfileManager: Adding local A2DP profile
11-23 06:25:02.790  5809  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 06:25:02.791  5809  5920 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 06:25:02.791  5809  5920 D BluetoothSdpJni: SDP Create record success - handle: 1
11-23 06:25:02.792  5745  5745 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-23 06:25:02.799  5745  5745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 06:25:02.809  5809  5809 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 06:25:02.809  5809  5809 D ObexServerSockets0: prepareForNewConnect()
,11-23 06:25:02.809  5745  5745 D BluetoothA2dp: Proxy object connected
,11-23 06:25:02.814  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 06:25:02.822  3162  3162 D BluetoothPbap: Proxy object connected
,11-23 06:25:02.822  3162  3162 D PbapServerProfile: Bluetooth service connected
,11-23 06:25:02.823  5745  5745 D DockEventReceiver: finishStartingService: stopping service
11-23 06:25:02.824  5745  5745 D BluetoothPbap: Proxy object connected
,11-23 06:25:02.825  5745  5745 D PbapServerProfile: Bluetooth service connected
,11-23 06:25:02.832  5809  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 06:25:02.848  5809  5928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 06:25:02.850  5809  5928 I BtOppRfcommListener: Accept thread started.
,11-23 06:25:02.873   929   929 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.874  3162  3965 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.874  3162  3162 D HeadsetProfile: Bluetooth service connected
,11-23 06:25:02.874  3833  3857 D BluetoothHeadset: Proxy object connected
11-23 06:25:02.875   929   929 D BluetoothHeadset: Proxy object connected
11-23 06:25:02.875   929   929 D BluetoothHeadset: Proxy object connected
11-23 06:25:02.875   929   946 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.878   929   946 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.883  3162  3174 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.883  3162  3162 D HeadsetProfile: Bluetooth service connected
11-23 06:25:02.883  3833  3853 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.895  5745  5755 D BluetoothHeadset: Proxy object connected
,11-23 06:25:02.896  5745  5745 D HeadsetProfile: Bluetooth service connected
,11-23 06:25:03.120   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:04.125   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:05.128   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 06:25:06.360  5809  5893 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 06:25:06.361  5809  5893 D BluetoothAdapterProperties: Setting state to 13
,11-23 06:25:06.361  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-23 06:25:06.363  5809  5893 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 06:25:06.364  5809  5893 I BluetoothAdapterState: Entering PendingCommandState
11-23 06:25:06.371  5809  5809 D BluetoothMapService: onReceive
11-23 06:25:06.372  5809  5809 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 06:25:06.372  5809  5809 D BluetoothMapService: STATE_TURNING_OFF
,11-23 06:25:06.373  5809  5809 D BluetoothMapService: MAP Service closeService in
11-23 06:25:06.374  5809  5809 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 06:25:06.374  5809  5809 D ObexServerSockets0: shutdown(block = true)
11-23 06:25:06.374  5809  5918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 06:25:06.376  5809  5897 D BluetoothAdapterProperties: Scan Mode:20
11-23 06:25:06.377  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 06:25:06.378  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:25:06.378  5689  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 06:25:06.378  5809  5809 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 06:25:06.379  5809  5919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 06:25:06.379  5689  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 06:25:06.380  5689  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 06:25:06.380  5809  5809 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 06:25:06.381  5809  5906 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 06:25:06.383  5745  5745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 06:25:06.384  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:25:06.388  5809  5809 I BtOppRfcommListener: stopping Accept Thread
,11-23 06:25:06.390  5809  5928 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 06:25:06.391  5809  5928 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 06:25:06.393  5809  5809 D HeadsetService: Received stop request...Stopping profile...
11-23 06:25:06.395  5745  5745 D DockEventReceiver: finishStartingService: stopping service
11-23 06:25:06.398   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 06:25:06.399  3162  3174 D BluetoothHeadset: Proxy object disconnected
11-23 06:25:06.399  3162  3162 D HeadsetProfile: Bluetooth service disconnected
,11-23 06:25:06.400  3833  4047 D BluetoothHeadset: Proxy object disconnected
,11-23 06:25:06.400  5809  5809 D A2dpService: Received stop request...Stopping profile...
11-23 06:25:06.401  5745  5759 D BluetoothHeadset: Proxy object disconnected
11-23 06:25:06.401  5809  5912 D A2dpStateMachine: Exit Disconnected: -1
11-23 06:25:06.402   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 06:25:06.402   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 06:25:06.402  3162  3162 D BluetoothA2dp: Proxy object disconnected
11-23 06:25:06.402   929   929 D BluetoothA2dp: Proxy object disconnected
11-23 06:25:06.403  5809  5809 D HidService: Received stop request...Stopping profile...
11-23 06:25:06.403  5809  5809 D HidService: Stopping Bluetooth HidService
,11-23 06:25:06.403  5745  5745 D HeadsetProfile: Bluetooth service disconnected
11-23 06:25:06.404  3162  3162 D BluetoothInputDevice: Proxy object disconnected
11-23 06:25:06.404  3162  3162 D HidProfile: Bluetooth service disconnected
11-23 06:25:06.405  5809  5809 D HealthService: Received stop request...Stopping profile...
11-23 06:25:06.405  5745  5745 D BluetoothA2dp: Proxy object disconnected
11-23 06:25:06.405  5745  5745 D BluetoothInputDevice: Proxy object disconnected
11-23 06:25:06.405  5745  5745 D HidProfile: Bluetooth service disconnected
11-23 06:25:06.407  5809  5809 D PanService: Received stop request...Stopping profile...
11-23 06:25:06.409  3162  3162 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 06:25:06.409  3162  3162 D PanProfile: Bluetooth service disconnected
11-23 06:25:06.409  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.409  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.409  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 06:25:06.409  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:06.409  5745  5745 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 06:25:06.409  5745  5745 D PanProfile: Bluetooth service disconnected
11-23 06:25:06.412  5809  5809 D BluetoothMapService: Received stop request...Stopping profile...
11-23 06:25:06.412  5809  5809 D BluetoothMapService: stop()
11-23 06:25:06.412  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 06:25:06.413  5809  5809 D BluetoothMapAppObserver: deinitObservers()
11-23 06:25:06.413  5809  5809 D BluetoothMapAppObserver: removeReceiver()
11-23 06:25:06.414  3162  3162 D BluetoothMap: Proxy object disconnected
11-23 06:25:06.414  5745  5745 D BluetoothMap: Proxy object disconnected
11-23 06:25:06.414  3162  3162 D MapProfile: Bluetooth service disconnected
11-23 06:25:06.414  5745  5745 D MapProfile: Bluetooth service disconnected
,11-23 06:25:06.416  5809  5809 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 06:25:06.416  5809  5809 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 06:25:06.417  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.417  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.417  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:06.417  5809  5904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:25:06.417  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:06.417  5809  5904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 06:25:06.417  5809  5904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:25:06.417  5809  5809 D SapService: Received stop request...Stopping profile...
,11-23 06:25:06.417  5809  5809 V SapService: stop()
11-23 06:25:06.418  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 06:25:06.418  5809  5897 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-23 06:25:06.420  5809  5904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:25:06.420  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.420  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.420  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:06.420  5809  5904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:25:06.421  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:06.421  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 06:25:06.421  5809  5904 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 06:25:06.421  5809  5809 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 06:25:06.421  5809  5904 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 06:25:06.421  5809  5809 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 06:25:06.421  5809  5904 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 06:25:06.421  5809  5897 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 06:25:06.421  5809  5904 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 06:25:06.421  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.421  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.421  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:06.421  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 06:25:06.421  5809  5809 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 06:25:06.422  5809  5897 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 06:25:06.422  5809  5809 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 06:25:06.422  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.422  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.422  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:06.422  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:06.423  5809  5809 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 06:25:06.423  5809  5809 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-23 06:25:06.426  3162  3162 D BluetoothPbap: Proxy object disconnected
11-23 06:25:06.426  3162  3162 D PbapServerProfile: Bluetooth service disconnected
11-23 06:25:06.427  5745  5745 D BluetoothPbap: Proxy object disconnected
,11-23 06:25:06.427  5745  5745 D PbapServerProfile: Bluetooth service disconnected
,11-23 06:25:06.429  5809  5809 D BluetoothMapService: MAP Service closeService in
11-23 06:25:06.429  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.429  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.429  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:06.429  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:06.430  5809  5809 D BluetoothMapService: cleanup()
11-23 06:25:06.430  5809  5809 D BluetoothMapService: MAP Service closeService in
11-23 06:25:06.430  5809  5809 V BluetoothAdapterState: isTurningOff()=true
11-23 06:25:06.430  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.430  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:06.430  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:06.430  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 06:25:06.430  5809  5893 D BluetoothAdapterProperties: Setting state to 15
11-23 06:25:06.430  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-23 06:25:06.431   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 06:25:06.431  5809  5893 I BluetoothAdapterState: Entering BleOnState
11-23 06:25:06.432  3162  3173 D BluetoothPan: onBluetoothStateChange on: false
11-23 06:25:06.433  5745  5932 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:25:06.433   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:25:06.433  5745  5759 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-23 06:25:06.434  3162  3965 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 06:25:06.435  3162  4020 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 06:25:06.436   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:25:06.436  5745  5755 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 06:25:06.437  3162  3174 D BluetoothMap: onBluetoothStateChange: up=false
11-23 06:25:06.437   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:25:06.437  3162  3173 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 06:25:06.438  5745  5932 D BluetoothPan: onBluetoothStateChange on: false
11-23 06:25:06.439  5745  5759 D BluetoothMap: onBluetoothStateChange: up=false
,11-23 06:25:06.439  3162  3965 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:25:06.440  3833  3857 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 06:25:06.440  5745  5755 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 06:25:06.441  5809  5893 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 06:25:06.441  5809  5893 D BluetoothAdapterProperties: Setting state to 16
11-23 06:25:06.441  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 06:25:06.442  5809  5893 D BluetoothAdapterProperties: onBleDisable
,11-23 06:25:06.442  5809  5893 I BluetoothAdapterState: Entering PendingCommandState
11-23 06:25:06.443  5809  5894 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 06:25:06.445  5809  5904 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 06:25:06.445  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 06:25:06.445  5809  5904 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 06:25:06.445  5809  5897 D BluetoothAdapterProperties: Scan Mode:20
11-23 06:25:06.446  5745  5745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 06:25:06.448  5689  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:25:06.453  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 06:25:06.455  5745  5745 D DockEventReceiver: finishStartingService: stopping service
,11-23 06:25:06.653  5809  5897 I bt_hci  : shut_down
,11-23 06:25:06.659  5809  5901 D bt_hwcfg: hw_epilog_process
11-23 06:25:06.659  5809  5901 I bt_vendor: low_power_mode_cb
,11-23 06:25:06.662  5809  5901 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 06:25:06.662  5809  5901 I bt_vendor: epilog_cb
11-23 06:25:06.662  5809  5901 I bt_hci  : epilog_finished_callback
,11-23 06:25:06.665  5809  5897 I bt_hci_h4: hal_close
11-23 06:25:06.665  5809  5897 I bt_userial_vendor: device fd = 54 close
,11-23 06:25:06.780  5809  5894 D bt_stack_manager: event_shut_down_stack finished.
,11-23 06:25:06.781  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 06:25:06.786  5809  5893 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 06:25:06.787  5809  5809 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 06:25:06.788  5809  5809 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 06:25:06.789  5809  5809 D BtGatt.GattService: stop()
11-23 06:25:06.789  5809  5809 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 06:25:06.794  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:06.794  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:06.794  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 06:25:06.795  5809  5809 V BluetoothAdapterState: isBleTurningOff()=true
11-23 06:25:06.795  5809  5893 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 06:25:06.796  5809  5893 D BluetoothAdapterProperties: Setting state to 10
,11-23 06:25:06.796  5809  5893 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 06:25:06.798  5809  5893 I BluetoothAdapterState: Entering OffState
11-23 06:25:06.799   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 06:25:06.816  5809  5809 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 06:25:06.816  5809  5809 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 06:25:06.817  5809  5809 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 06:25:06.819  5809  5894 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 06:25:06.824  5809  5809 I art     : System.exit called, status: 0
,11-23 06:25:06.825  5809  5809 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 06:25:06.859   929  3948 I ActivityManager: Process com.android.bluetooth (pid 5809) has died
,11-23 06:25:10.131   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:11.135   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:11.366  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 06:25:11.366  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:25:11.373  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:11.374  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63ba241 removed from the list
11-23 06:25:11.374  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:11.376  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:11.376  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4129bd4 added. We now have 4 listener(s)
11-23 06:25:11.377  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:11.381  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:11.383  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4129bd4 removed from the list
,11-23 06:25:11.383  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 06:25:11.385  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 06:25:11.385  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15f217d added. We now have 4 listener(s)
11-23 06:25:11.385  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:25:12.138   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:13.141   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:14.145   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:15.147   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 06:25:16.399  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:25:16.436   929   946 I ActivityManager: Start proc 5937:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 06:25:16.524  5937  5937 D AdapterServiceConfig: Adding HeadsetService
,11-23 06:25:16.525  5937  5937 D AdapterServiceConfig: Adding A2dpService
11-23 06:25:16.525  5937  5937 D AdapterServiceConfig: Adding HidService
11-23 06:25:16.525  5937  5937 D AdapterServiceConfig: Adding HealthService
11-23 06:25:16.525  5937  5937 D AdapterServiceConfig: Adding PanService
11-23 06:25:16.526  5937  5937 D AdapterServiceConfig: Adding GattService
11-23 06:25:16.526  5937  5937 D AdapterServiceConfig: Adding BluetoothMapService
,11-23 06:25:16.526  5937  5937 D AdapterServiceConfig: Adding SapService
,11-23 06:25:16.540   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6cf0663:true
,11-23 06:25:16.541  5937  5937 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 06:25:16.544  5937  5937 I bt_bluedroid: init
,11-23 06:25:16.545  5937  5949 I BluetoothAdapterState: Entering OffState
,11-23 06:25:16.549  5937  5950 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 06:25:16.549  5937  5950 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 06:25:16.549  5937  5950 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 06:25:16.550  5937  5950 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 06:25:16.551  5937  5937 I bt_bluedroid: get_profile_interface socket
,11-23 06:25:16.553  5937  5953 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 06:25:16.554  5937  5937 I bt_bluedroid: get_profile_interface sdp
11-23 06:25:16.555  5937  5953 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 06:25:16.562  5937  5948 I bt_bluedroid: config_hci_snoop_log
,11-23 06:25:16.563   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 06:25:16.570  5937  5949 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 06:25:16.570  5937  5949 D BluetoothAdapterProperties: Setting state to 14
,11-23 06:25:16.570  5937  5949 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 06:25:16.572  5937  5949 D BluetoothBondStateMachine: make
,11-23 06:25:16.574  5937  5954 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 06:25:16.578  5937  5949 I BluetoothAdapterState: Entering PendingCommandState
,11-23 06:25:16.580  5937  5937 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 06:25:16.584  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:16.584  5937  5937 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 06:25:16.585  5937  5937 D BtGatt.GattService: Received start request. Starting profile...
11-23 06:25:16.585  5937  5937 D BtGatt.GattService: start()
,11-23 06:25:16.586  5937  5937 I bt_bluedroid: get_profile_interface gatt
,11-23 06:25:16.587  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:16.588  5937  5937 D BtGatt.AdvertiseManager: advertise manager created
,11-23 06:25:16.596  5937  5937 V BluetoothAdapterState: isTurningOff()=false
,11-23 06:25:16.596  5937  5937 V BluetoothAdapterState: isTurningOn()=false
11-23 06:25:16.596  5937  5937 V BluetoothAdapterState: isBleTurningOn()=true
11-23 06:25:16.596  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:16.597  5937  5949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 06:25:16.599  5937  5949 I bt_bluedroid: bt_bluedroid
,11-23 06:25:16.599  5937  5950 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 06:25:16.599  5937  5950 I bt_hci  : start_up
,11-23 06:25:16.606  5937  5950 I bt_vendor: alloc value 0xf424b871
,11-23 06:25:16.606  5937  5950 I bt_vendor: init
11-23 06:25:16.607  5937  5950 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 06:25:16.607  5937  5950 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 06:25:16.718  5958  5958 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 06:25:16.716  5937  5950 D bt_hci  : start_up starting async portion
11-23 06:25:16.717  5937  5957 I bt_hci  : event_finish_startup
11-23 06:25:16.717  5937  5957 I bt_hci_h4: hal_open
,11-23 06:25:16.717  5937  5957 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-23 06:25:16.722  5937  5957 I bt_userial_vendor: device fd = 54 open
,11-23 06:25:16.742  5937  5957 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 06:25:16.746  5937  5957 D bt_hwcfg: Chipset BCM4358A3
,11-23 06:25:16.746  5937  5957 D bt_hwcfg: Target name = [BCM4358A3]
11-23 06:25:16.746  5937  5957 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 06:25:17.537  5937  5957 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 06:25:17.537  5937  5957 D bt_hwcfg: Settlement delay -- 100 ms
11-23 06:25:17.537  5937  5957 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 06:25:17.675  5937  5957 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-23 06:25:17.675  5937  5957 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-23 06:25:17.677  5937  5957 I bt_hwcfg: vendor lib fwcfg completed
11-23 06:25:17.677  5937  5957 I bt_vendor: firmware callback
11-23 06:25:17.678  5937  5957 I bt_hci  : firmware_config_callback
,11-23 06:25:17.690  5937  5960 I bt_btu  : btu_task pending for preload complete event
,11-23 06:25:17.690  5937  5960 I bt_btu_task: Bluetooth chip preload is complete
11-23 06:25:17.690  5937  5960 I bt_btu  : btu_task received preload complete event
,11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_HCI
11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_A2D
,11-23 06:25:17.699  5937  5960 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-23 06:25:17.700  5937  5960 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 06:25:17.800  5937  5960 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41c9549
11-23 06:25:17.800  5937  5960 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41c9549 
,11-23 06:25:17.832  5937  5953 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 06:25:17.836  5937  5953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 06:25:17.837  5937  5953 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 06:25:17.840  5937  5953 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 06:25:17.844  5937  5953 D BluetoothAdapterProperties: Scan Mode:20
11-23 06:25:17.845  5937  5953 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 06:25:17.845  5937  5953 D bt_hci  : do_postload posting postload work item
11-23 06:25:17.845  5937  5957 I bt_hci  : event_postload
11-23 06:25:17.845  5937  5957 I bt_vendor: sco_config_cb
11-23 06:25:17.845  5937  5957 I bt_hci  : sco_config_callback postload finished.
11-23 06:25:17.848  5937  5953 D bt_bte_conf: Device ID record 1 : primary
11-23 06:25:17.848  5937  5953 D bt_bte_conf:   vendorId            = 000f
11-23 06:25:17.848  5937  5953 D bt_bte_conf:   vendorIdSource      = 0001
11-23 06:25:17.848  5937  5953 D bt_bte_conf:   product             = 1200
,11-23 06:25:17.848  5937  5953 D bt_bte_conf:   version             = 1436
11-23 06:25:17.849  5937  5953 D bt_bte_conf:   clientExecutableURL = 
11-23 06:25:17.849  5937  5953 D bt_bte_conf:   serviceDescription  = 
11-23 06:25:17.849  5937  5953 D bt_bte_conf:   documentationURL    = 
11-23 06:25:17.849  5937  5953 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 06:25:17.849  5937  5950 D bt_stack_manager: event_start_up_stack finished
11-23 06:25:17.850  5937  5949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 06:25:17.851  5937  5949 D BluetoothAdapterProperties: Setting state to 15
11-23 06:25:17.851  5937  5949 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 06:25:17.852  5937  5949 I BluetoothAdapterState: Entering BleOnState
,11-23 06:25:17.853  5937  5957 I bt_vendor: low_power_mode_cb
,11-23 06:25:17.861  5937  5949 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 06:25:17.861  5937  5949 D BluetoothAdapterProperties: Setting state to 11
11-23 06:25:17.861  5937  5949 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 06:25:17.873  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:17.873  5937  5937 D HeadsetService: Received start request. Starting profile...
11-23 06:25:17.876  5937  5937 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 06:25:17.876  5937  5937 D HeadsetStateMachine: make
,11-23 06:25:17.885  5937  5949 I BluetoothAdapterState: Entering PendingCommandState
,11-23 06:25:17.886  5937  5937 D HeadsetStateMachine: max_hf_connections = 1
,11-23 06:25:17.887  5937  5937 I bt_bluedroid: get_profile_interface handsfree
11-23 06:25:17.887  5937  5953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 06:25:17.887  5937  5953 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 06:25:17.891  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:17.892  5937  5937 D A2dpService: Received start request. Starting profile...
,11-23 06:25:17.893  5937  5937 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 06:25:17.893  5937  5937 I bt_bluedroid: get_profile_interface avrcp
11-23 06:25:17.894  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 06:25:17.900  5937  5937 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 06:25:17.900  5937  5937 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 06:25:17.900  5937  5937 D A2dpStateMachine: make
,11-23 06:25:17.902  5937  5937 I bt_bluedroid: get_profile_interface a2dp
,11-23 06:25:17.903  5937  5953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 06:25:17.904  5937  5967 D A2dpStateMachine: Enter Disconnected: -2
,11-23 06:25:17.904  5937  5937 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 06:25:17.906  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:17.906  5937  5937 D HidService: Received start request. Starting profile...
11-23 06:25:17.907  5937  5937 I bt_bluedroid: get_profile_interface hidhost
11-23 06:25:17.907  5937  5937 D HidService: setHidService(): set to: null
11-23 06:25:17.907  5937  5953 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41aa56d
11-23 06:25:17.907  5937  5953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-23 06:25:17.907  5937  5937 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 06:25:17.908  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:17.909  5937  5937 D HealthService: Received start request. Starting profile...
,11-23 06:25:17.912  5937  5937 I bt_bluedroid: get_profile_interface health
,11-23 06:25:17.913  5937  5937 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 06:25:17.913  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:17.914  5937  5937 D PanService: Received start request. Starting profile...
11-23 06:25:17.915  5937  5937 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 06:25:17.915  5937  5937 I bt_bluedroid: get_profile_interface pan
11-23 06:25:17.916  5937  5953 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 06:25:17.917  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:17.918  5937  5937 D BluetoothMapService: Received start request. Starting profile...
11-23 06:25:17.918  5937  5937 D BluetoothMapService: start()
,11-23 06:25:17.921  5937  5937 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 06:25:17.922  5937  5937 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 06:25:17.922  5937  5937 D BluetoothMapAppObserver: createReceiver()
,11-23 06:25:17.923  5937  5937 D BluetoothMapAppObserver: initObservers()
11-23 06:25:17.924  5937  5937 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 06:25:17.933  5937  5937 V SapService: SapBinder()
,11-23 06:25:17.933  5937  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
11-23 06:25:17.934  5937  5937 D SapService: Received start request. Starting profile...
11-23 06:25:17.934  5937  5937 V SapService: start()
,11-23 06:25:17.936  5937  5937 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:17.936  5937  5937 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:17.936  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.936  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:17.936  5937  5965 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isTurningOff()=false
,11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isTurningOn()=true
,11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:17.937  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.938  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:17.939  5937  5937 V BluetoothAdapterState: isTurningOff()=false
11-23 06:25:17.939  5937  5937 V BluetoothAdapterState: isTurningOn()=true
11-23 06:25:17.939  5937  5937 V BluetoothAdapterState: isBleTurningOn()=false
11-23 06:25:17.939  5937  5937 V BluetoothAdapterState: isBleTurningOff()=false
11-23 06:25:17.940  5937  5949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-23 06:25:17.940  5937  5949 D BluetoothAdapterProperties: ScanMode =  20
11-23 06:25:17.940  5937  5949 D BluetoothAdapterProperties: State =  11
11-23 06:25:17.940  5937  5949 D BluetoothAdapterProperties: Setting state to 12
11-23 06:25:17.940  5937  5949 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 06:25:17.940   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 06:25:17.940  5937  5949 I BluetoothAdapterState: Entering OnState
11-23 06:25:17.943  3162  3173 D BluetoothPan: onBluetoothStateChange on: true
11-23 06:25:17.944  5937  5953 D BluetoothAdapterProperties: Scan Mode:21
11-23 06:25:17.944  5937  5953 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 06:25:17.944   929   929 D BluetoothA2dp: Proxy object connected
11-23 06:25:17.947  5745  5759 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:17.947   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:17.948  5745  5755 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 06:25:17.948  3162  3162 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 06:25:17.948  3162  3162 D PanProfile: Bluetooth service connected
,11-23 06:25:17.952  3162  3965 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 06:25:17.952  5937  5937 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 06:25:17.953  5937  5937 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-23 06:25:17.954  5937  5937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 06:25:17.956  5937  5937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 06:25:17.957  3162  3173 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 06:25:17.957  3162  3162 D BluetoothA2dp: Proxy object connected
,11-23 06:25:17.958  5937  5937 D ObexServerSockets: Succeed to create listening sockets 
,11-23 06:25:17.958  5937  5937 D ObexServerSockets0: startAccept()
11-23 06:25:17.958  5937  5937 D ObexServerSockets0: prepareForNewConnect()
11-23 06:25:17.961  5937  5937 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 06:25:17.961  5937  5937 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 06:25:17.961  5937  5972 D ObexServerSockets0: Accepting socket connection...
11-23 06:25:17.961   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:17.961  5745  5932 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 06:25:17.962  5745  5745 D BluetoothInputDevice: Proxy object connected
,11-23 06:25:17.962  5745  5745 D HidProfile: Bluetooth service connected
11-23 06:25:17.962  3162  3162 D BluetoothInputDevice: Proxy object connected
11-23 06:25:17.962  3162  3162 D HidProfile: Bluetooth service connected
11-23 06:25:17.963  5937  5973 D ObexServerSockets0: Accepting socket connection...
11-23 06:25:17.965  3162  3965 D BluetoothMap: onBluetoothStateChange: up=true
11-23 06:25:17.967   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 06:25:17.967  3162  4020 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 06:25:17.968  3162  3162 D BluetoothMap: Proxy object connected
11-23 06:25:17.968  3162  3162 D MapProfile: Bluetooth service connected
11-23 06:25:17.968  3162  3162 D BluetoothMap: getConnectedDevices()
11-23 06:25:17.969  5745  5759 D BluetoothPan: onBluetoothStateChange on: true
,11-23 06:25:17.971  5745  5932 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 06:25:17.974  5745  5745 D BluetoothA2dp: Proxy object connected
11-23 06:25:17.975  3162  3965 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:17.975  3833  3853 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 06:25:17.976  5745  5759 D BluetoothPbap: onBluetoothStateChange: up=true
,11-23 06:25:17.979   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 06:25:17.979  5937  5937 D BluetoothMapService: onReceive
11-23 06:25:17.979  5937  5937 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 06:25:17.979  5937  5937 D BluetoothMapService: STATE_ON
11-23 06:25:17.980  5745  5745 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 06:25:17.980  5745  5745 D PanProfile: Bluetooth service connected
11-23 06:25:17.980  5745  5745 D BluetoothMap: Proxy object connected
11-23 06:25:17.980  5745  5745 D MapProfile: Bluetooth service connected
11-23 06:25:17.980  5745  5745 D BluetoothMap: getConnectedDevices()
11-23 06:25:17.982  5937  5976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 06:25:17.984  5937  5976 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 06:25:17.984  5937  5976 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 06:25:17.988  5745  5745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 06:25:17.994  5745  5745 D DockEventReceiver: finishStartingService: stopping service
,11-23 06:25:17.999  3623  3623 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 06:25:18.007  3162  3162 D BluetoothPbap: Proxy object connected
11-23 06:25:18.007  3162  3162 D PbapServerProfile: Bluetooth service connected
,11-23 06:25:18.009  5745  5745 D BluetoothPbap: Proxy object connected
11-23 06:25:18.009  5745  5745 D PbapServerProfile: Bluetooth service connected
,11-23 06:25:18.012  5937  5937 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 06:25:18.012  5937  5937 D ObexServerSockets0: prepareForNewConnect()
,11-23 06:25:18.023  5937  5981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 06:25:18.035  5937  5985 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 06:25:18.037  5937  5985 I BtOppRfcommListener: Accept thread started.
,11-23 06:25:18.049   929   929 D BluetoothHeadset: Proxy object connected
,11-23 06:25:18.049  3162  3173 D BluetoothHeadset: Proxy object connected
11-23 06:25:18.050  3162  3162 D HeadsetProfile: Bluetooth service connected
11-23 06:25:18.050  3833  4047 D BluetoothHeadset: Proxy object connected
,11-23 06:25:18.050  5745  5759 D BluetoothHeadset: Proxy object connected
11-23 06:25:18.050   929   929 D BluetoothHeadset: Proxy object connected
11-23 06:25:18.050   929   929 D BluetoothHeadset: Proxy object connected
11-23 06:25:18.051  5745  5745 D HeadsetProfile: Bluetooth service connected
,11-23 06:25:18.061   929   946 D BluetoothHeadset: Proxy object connected
,11-23 06:25:18.067   929   946 D BluetoothHeadset: Proxy object connected
,11-23 06:25:18.076  3162  3965 D BluetoothHeadset: Proxy object connected
,11-23 06:25:18.076  3162  3162 D HeadsetProfile: Bluetooth service connected
11-23 06:25:18.076  3833  3857 D BluetoothHeadset: Proxy object connected
,11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 06:25:21.420  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 06:25:21.428  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 06:25:21.428  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:21.428  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15f217d removed from the list
11-23 06:25:21.428  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 06:25:21.430  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 06:25:21.431  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5638872 added. We now have 4 listener(s)
11-23 06:25:21.431  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:25:21.434   929  3985 D WifiService: setWifiEnabled: false pid=5689, uid=10077
11-23 06:25:21.434   929  3985 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 06:25:25.151   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:26.154   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:26.447  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 06:25:26.448   929   940 D WifiService: setWifiEnabled: true pid=5689, uid=10077
11-23 06:25:26.448   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 06:25:26.456   506   921 D SoftapController: Softap fwReload - Ok
,11-23 06:25:26.463   506   921 D CommandListener: Setting iface cfg
,11-23 06:25:26.463   506   921 D CommandListener: Trying to bring down wlan0
,11-23 06:25:26.466   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-23 06:25:26.473   929  3017 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 06:25:27.156   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:27.238   929  3017 D wifi    : set interface wlan0 flags (UP)
,11-23 06:25:27.240   929  3017 I WifiHAL : Initializing wifi
,11-23 06:25:27.240   929  3017 I WifiHAL : Creating socket
,11-23 06:25:27.248   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 06:25:27.251   929  3017 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 06:25:27.251   929  3017 D wifi    : Did set static halHandle = 0x7f734c3b80
11-23 06:25:27.251   929  3017 D wifi    : halHandle = 0x7f734c3b80, mVM = 0x7f8fb0d140, mCls = 0x20194e
11-23 06:25:27.252   929  3017 D wifi    : array field set
11-23 06:25:27.252   929  3017 I WifiNative-HAL: interface[0] = wlan0
,11-23 06:25:27.254   929  5990 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547395222400
11-23 06:25:27.254   929  5990 D wifi    : waitForHalEvents called, vm = 0x7f8fb0d140, obj = 0x20194e, env = 0x7f74358780
,11-23 06:25:27.306  5991  5991 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 06:25:27.323  5991  5991 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 06:25:27.346  5991  5991 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 06:25:27.346  5991  5991 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 06:25:27.356   929  3017 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 06:25:27.371   929  3017 D WifiConfigStore: Loading config and enabling all networks 
,11-23 06:25:27.382   929  3017 D WifiConfigStore: loaded 0 passpoint configs
,11-23 06:25:27.382   929  3017 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-23 06:25:27.383   929  3017 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 06:25:27.383   929  3017 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 06:25:27.384   929  3017 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 06:25:27.384   929  3017 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 06:25:27.385   929  3017 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 06:25:27.385   929  3017 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 06:25:27.408   929  3017 D WifiNative-HAL: Setting external_sim to 1
,11-23 06:25:27.409  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 06:25:27.409   929  3017 D wifi    : setting dfs flag to true, 0x7f76395cc0
11-23 06:25:27.410   929  3017 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 06:25:27.410   929  3017 D wifi    : setting scan oui 0x7f76395cc0
11-23 06:25:27.410   929  3017 D WifiHAL : Sending mac address OUI
,11-23 06:25:27.415   929  3017 E native  : do suspend false
,11-23 06:25:27.443   929  3017 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 06:25:27.443   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 06:25:27.443   929   929 D RttService: SCAN_AVAILABLE : 3
11-23 06:25:27.443   929  3127 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 06:25:27.444   506   921 D CommandListener: Setting iface cfg
,11-23 06:25:27.455   929  3016 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '145 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 145 Failed to set address (No such device)'
11-23 06:25:27.455   929  3016 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 06:25:27.460   929  3016 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 06:25:27.472   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=256596 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-23 06:25:27.472   929  3016 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-23 06:25:28.163   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:29.166   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:30.169   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 06:25:30.444  5991  5991 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 06:25:30.450  5991  5991 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 06:25:30.479  5991  5991 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 06:25:30.567   929  3017 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 06:25:30.570   929  3017 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 06:25:30.570   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:25:30.588   929  3017 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 06:25:30.631   929  3017 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 06:25:30.957  5991  5991 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 06:25:31.021  5991  5991 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 06:25:31.022  5991  5991 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 06:25:31.036   929  3017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 06:25:31.037   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 06:25:31.037   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 06:25:31.055   929  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 06:25:31.068   506   921 D CommandListener: Setting iface cfg
,11-23 06:25:31.074   929  3017 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 06:25:31.087   929  5996 D DhcpClient: Receive thread started
,11-23 06:25:31.089   929  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 06:25:31.090   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 06:25:31.090   929  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 06:25:31.193   929  3017 E native  : do suspend false
,11-23 06:25:31.218   929  5995 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 06:25:31.236   929  5996 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172581, domain null
,11-23 06:25:31.237   929  5995 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172581 seconds
,11-23 06:25:31.240   929  5995 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-23 06:25:31.271   929  5996 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 06:25:31.273   929  5995 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 06:25:31.277   506   921 D CommandListener: Setting iface cfg
,11-23 06:25:31.283   929  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 06:25:31.287   929  5995 D DhcpClient: Scheduling renewal in 86399s
,11-23 06:25:31.307   929  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 06:25:31.309   929  3017 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 06:25:31.311   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-23 06:25:31.314   929  3019 D ConnectivityService: Adding iface wlan0 to network 102
,11-23 06:25:31.324   929  3017 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 06:25:31.372   929  3019 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 06:25:31.372   929  3019 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-23 06:25:31.376   929  3019 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 06:25:31.381   929  3019 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 06:25:31.384   929  3019 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 06:25:31.394   929  3019 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:25:31.400   929  3019 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 06:25:31.400   929  3019 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 06:25:31.400   929  3019 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 06:25:31.400   929  3019 D ConnectivityService:    accepting network in place of null
11-23 06:25:31.400   929  3017 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 06:25:31.400   929  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 06:25:31.401   929  3019 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 06:25:31.425   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 06:25:31.446   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=260571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:25:31.449   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 06:25:31.454   929  3019 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-23 06:25:31.454   929  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 06:25:31.454  3805  3945 W QCNEJ   : |CORE| network available: 102
11-23 06:25:31.455   929  3019 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-23 06:25:31.456   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 06:25:31.458  3805  3945 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 06:25:31.459  3805  3945 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 06:25:31.459  3805  3945 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 06:25:31.464  5689  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 06:25:31.466  5689  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 06:25:31.467  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 06:25:31.467  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5638872 removed from the list
11-23 06:25:31.467  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:31.470  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-23 06:25:31.471  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-23 06:25:31.472  3949  3949 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-23 06:25:31.473  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2700227 Bundle[{}]
11-23 06:25:31.474  5689  5735 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 06:25:31.474  5689  5735 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 06:25:31.475  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 06:25:31.475  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 06:25:31.476  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 06:25:31.476  3998  3998 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 06:25:31.477  5689  5735 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-23 06:25:31.480  5100  5127 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 06:25:31.480  5100  5127 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 06:25:31.480  5100  5127 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 06:25:31.480  5100  5127 E SarControlService: no key has been found,reset the power
11-23 06:25:31.480  5100  5140 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 06:25:31.481  5100  5140 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 06:25:31.481  5100  5140 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 06:25:31.481  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 06:25:31.481  5128  5128 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 06:25:31.482  5689  5735 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-23 06:25:31.482  5689  5735 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-23 06:25:31.482  5689  5735 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-23 06:25:31.483  5100  5140 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 06:25:31.483  5100  5140 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 06:25:31.483  5100  5140 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 06:25:31.484  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 06:25:31.484  5128  5128 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 06:25:31.485  3998  3998 D SystemUpdateService: onCreate
11-23 06:25:31.485  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.486  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92004c3 added. We now have 3 listener(s)
11-23 06:25:31.488  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 06:25:31.488  5128  5142 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ec03000000000000ffffffff]
11-23 06:25:31.488  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.488  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.488  5128  5142 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 06:25:31.489  5128  5142 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 06:25:31.489  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.489  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e7a140 added. We now have 4 listener(s)
11-23 06:25:31.489  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.489  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 06:25:31.490  5128  5142 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7f473c2 HexData = [00000000ed03000000000000ffffffff]
11-23 06:25:31.490  5128  5142 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 06:25:31.490  5128  5142 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-23 06:25:31.491  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.491  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e415879 added. We now have 4 listener(s)
11-23 06:25:31.491  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 06:25:31.491  5100  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 06:25:31.491  5128  5128 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 06:25:31.491  5100  5112 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 06:25:31.492  3998  3998 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-23 06:25:31.492  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.492  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.492  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.493  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.493  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15db9be added. We now have 5 listener(s)
11-23 06:25:31.493  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.493  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:25:31.493  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.493  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:25:31.493  56,89  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.493  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.494  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.494  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92004c3 removed from the list
11-23 06:25:31.494  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.494  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e7a140 removed from the list
11-23 06:25:31.494  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:31.494  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.494  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.495  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.495  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.496  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.496  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.496  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.496  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.496  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e7a140 not in the list
11-23 06:25:31.496  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.496  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.498  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.498  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.499  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.499  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.499  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.499  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.499  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15db9be removed from the list
11-23 06:25:31.499  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.499  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.499  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.499  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e415879 removed from the list
11-23 06:25:31.500  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.500  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a742a1f added. We now have 3 listener(s)
,11-23 06:25:31.501  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.501  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.502  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 06:25:31.502  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.502  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b45916c added. We now have 4 listener(s)
11-23 06:25:31.502  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 06:25:31.503  3998  3998 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 06:25:31.503  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 06:25:31.504  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.504  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4760335 added. We now have 4 listener(s)
,11-23 06:25:31.506  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.506  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 06:25:31.506  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.506  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.506  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b37b3ca added. We now have 5 listener(s)
11-23 06:25:31.506  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.506  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:31.506  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 06:25:31.506  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 06:25:31.506  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:25:31.506  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 06:25:31.508  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 06:25:31.511  3998  6006 I SystemUpdateService: active receiver: enabled
11-23 06:25:31.512  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 06:25:31.512  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 06:25:31.512  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 06:25:31.515  3998  5462 I iu.UploadsManager: num queued entries: 0
,11-23 06:25:31.516  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.516  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 06:25:31.516  3998  3998 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 06:25:31.517  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 06:25:31.517  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 06:25:31.517  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 06:25:31.518  3998  3998 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 06:25:31.522  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.522  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 06:25:31.523  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 06:25:31.523  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 06:25:31.523  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 06:25:31.523  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.522  5823  5823 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 06:25:31.524  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.525  5937  5948 D BtGatt.GattService: registerClient() - UUID=9d297d9a-bed6-4874-99ac-3a0a1930002c
11-23 06:25:31.526  5937  5953 D BtGatt.GattService: onClientRegistered() - UUID=9d297d9a-bed6-4874-99ac-3a0a1930002c, clientIf=5
11-23 06:25:31.527  5689  5700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 06:25:31.527  5937  5947 D BtGatt.GattService: start scan with filters
11-23 06:25:31.528  5823  5823 D SprintDMHelper: simOperator: 
11-23 06:25:31.528  5823  5823 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 06:25:31.531  5937  5956 D BtGatt.ScanManager: handling starting scan
11-23 06:25:31.532  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 06:25:31.532  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.532  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 06:25:31.532  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.532  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 06:25:31.532  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 06:25:31.532  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.532  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 06:25:31.532  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 06:25:31.533  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.533  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.533  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 06:25:31.533  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.533  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 06:25:31.533  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.534  5937  5956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@300ec4b
,11-23 06:25:31.536  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.536  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:25:31.536  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.536  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.536  5689  5735 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 06:25:31.536  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.536  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.536  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 06:25:31.536  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.536  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:25:31.536  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.536  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 06:25:31.539  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 06:25:31.539  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.539  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.539  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 06:25:31.539  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.539  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 06:25:31.539  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.515  3998  5462 I iu.UploadsManager: num updated entries: 0
11-23 06:25:31.540  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.540  5937  5948 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 06:25:31.540  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 06:25:31.540  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.541  3998  5462 I iu.SyncManager: NEXT; no task
11-23 06:25:31.541  5937  5977 D BtGatt.GattService: stopScan() - queue size =1
11-23 06:25:31.541  5937  5974 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 06:25:31.541  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 06:25:31.541  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.541  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.542  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-23 06:25:31.542  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 06:25:31.542  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:25:31.543  5937  5953 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 06:25:31.543  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.543  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.543  5937  5956 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 06:25:31.543  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.543  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:25:31.543  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.543  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.544  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:25:31.544  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:25:31.545  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 06:25:31.545  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.545  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 06:25:31.545  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 06:25:31.545  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.545  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.545  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.546  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:25:31.546  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 06:25:31.546  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.546  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.546  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.546  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:25:31.546  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.546  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.546  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.546  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a742a1f removed from the list
11-23 06:25:31.546  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.546  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b45916c removed from the list
11-23 06:25:31.546  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:31.546  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.546  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.547  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.547  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.547  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.548  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.548  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.548  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.548  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.548  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.548  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.548  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b45916c not in the list
11-23 06:25:31.548  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.548  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.550  5937  5953 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 06:25:31.550  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.550  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.550  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.550  5937  5956 D BtGatt.ScanManager: Starting BLE batch scan
11-23 06:25:31.550  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.551  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.551  5937  5956 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 06:25:31.551  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.551  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.551  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b37b3ca removed from the list
11-23 06:25:31.551  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.551  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.551  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.551  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4760335 removed from the list
11-23 06:25:31.551  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.551  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b3e17 added. We now have 3 listener(s)
11-23 06:25:31.553  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.553  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.553  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.553  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.553  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fea204 added. We now have 4 listener(s)
11-23 06:25:31.553  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.553   929  5993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:804::200e
,11-23 06:25:31.554  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 06:25:31.554  3998  6006 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 06:25:31.559  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.559  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce063ed added. We now have 4 listener(s)
,11-23 06:25:31.560  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.560  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.560  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.560  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 06:25:31.560  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4af222 added. We now have 5 listener(s)
11-23 06:25:31.560  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.560  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:31.561  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:31.561  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 06:25:31.561  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 06:25:31.561  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:25:31.561  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 06:25:31.562  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 06:25:31.562  5937  5953 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 06:25:31.562  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:25:31.565  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 06:25:31.565  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 06:25:31.565  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 06:25:31.568  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.568  5937  5953 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 06:25:31.568  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.568  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 06:25:31.569  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 06:25:31.569  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 06:25:31.569  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 06:25:31.570  3998  6006 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-23 06:25:31.570  3998  6006 I SystemUpdateService: now status is 0 (complete)
11-23 06:25:31.570  3998  6006 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 06:25:31.570  3998  6006 I SystemUpdateService: file has been verified
11-23 06:25:31.570  3998  6006 I SystemUpdateService: OTA package size = 21989297
11-23 06:25:31.570  5937  5956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:25:31.572  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.572  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 06:25:31.572  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-23 06:25:31.572  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 06:25:31.573  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 06:25:31.573  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.574  5689  5735 D BluetoothAdapter: STATE_ON
,11-23 06:25:31.575  5937  5953 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:25:31.575  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:25:31.575  5937  5953 E BtGatt.ContextMap: Context not found for ID 5
,11-23 06:25:31.576  5937  5974 D BtGatt.GattService: registerClient() - UUID=203567a9-4453-41b5-9ddf-6b4d99ff4026
11-23 06:25:31.577  5937  5953 D BtGatt.GattService: onClientRegistered() - UUID=203567a9-4453-41b5-9ddf-6b4d99ff4026, clientIf=5
11-23 06:25:31.577  3998  6006 I SystemUpdateService: showing system update notification
11-23 06:25:31.577  5689  5700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 06:25:31.577  5937  5975 D BtGatt.GattService: start scan with filters
,11-23 06:25:31.582  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 06:25:31.582  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.582  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 06:25:31.582  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.582  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 06:25:31.582  5937  5953 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 06:25:31.583  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 06:25:31.583  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.583  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.583  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 06:25:31.583  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 06:25:31.583  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.583  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.583  5937  5956 D BtGatt.ScanManager: stopping BLe Batch
11-23 06:25:31.583  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.583  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.583  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 06:25:31.583  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.585  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.585  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:25:31.585  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.585  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.585  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:31.585  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.585  5689  5735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 06:25:31.586  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:25:31.586  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.586  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:25:31.586  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.586  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.586  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 06:25:31.586  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.586  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.586  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b3e17 removed from the list
11-23 06:25:31.586  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.586  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fea204 removed from the list
11-23 06:25:31.586  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:31.586  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.586  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:25:31.586  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.586  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.586  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 06:25:31.586  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.587  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:25:31.587  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.587  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.587  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.587  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.587  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.588  5937  5953 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.588  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.588  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.588  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.588  5937  5956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:25:31.588  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.588  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fea204 not in the list
11-23 06:25:31.588  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.588  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.589  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.589  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 06:25:31.589  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.590  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.590  5937  5975 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 06:25:31.590  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 06:25:31.590  3998  3998 D SystemUpdateService: onDestroy
11-23 06:25:31.591  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.593  5937  5948 D BtGatt.GattService: stopScan() - queue size =0
11-23 06:25:31.594  5937  5953 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:25:31.594  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.596  5937  5977 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 06:25:31.596  5937  5956 D BtGatt.ScanManager: handling starting scan
,11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.596  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-23 06:25:31.596  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 06:25:31.597  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:25:31.597  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.597  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.598  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:25:31.598  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.598  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.598  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 06:25:31.598  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 06:25:31.598  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.598  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4af222 removed from the list
11-23 06:25:31.598  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.598  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.598  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.598  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce063ed removed from the list
11-23 06:25:31.598  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:25:31.598  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.599  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@101d90f added. We now have 3 listener(s)
11-23 06:25:31.599  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 06:25:31.599  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:25:31.599  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.599  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 06:25:31.599  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.599  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.600  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.600  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e862d9c added. We now have 4 listener(s)
11-23 06:25:31.600  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.600  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 06:25:31.602  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 06:25:31.603  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.603  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.603  5937  5953 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 06:25:31.603  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.603  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.603  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af23a5 added. We now have 4 listener(s)
11-23 06:25:31.604  5937  5956 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 06:25:31.604  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.604  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.604  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 06:25:31.604  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.604  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50ca37a added. We now have 5 listener(s)
11-23 06:25:31.604  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.605  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:31.605  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 06:25:31.605  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 06:25:31.605  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 06:25:31.605  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 06:25:31.606  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 06:25:31.607  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 06:25:31.607  5689  5735 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 06:25:31.608  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 06:25:31.609  5937  5953 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 06:25:31.609  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.609  5937  5956 D BtGatt.ScanManager: Starting BLE batch scan
11-23 06:25:31.609  5937  5956 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 06:25:31.610  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.610  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 06:25:31.610  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 06:25:31.611  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 06:25:31.611  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 06:25:31.613  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.613  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 06:25:31.613  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 06:25:31.613  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 06:25:31.613  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 06:25:31.613  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.614  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.615  5937  5977 D BtGatt.GattService: registerClient() - UUID=c995c4b7-b6f6-4227-951c-5d6f15b8e87b
11-23 06:25:31.615  5937  5953 D BtGatt.GattService: onClientRegistered() - UUID=c995c4b7-b6f6-4227-951c-5d6f15b8e87b, clientIf=5
,11-23 06:25:31.616  5689  5700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 06:25:31.616  5937  5948 D BtGatt.GattService: start scan with filters
11-23 06:25:31.618  5937  5953 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-23 06:25:31.618  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:25:31.621  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 06:25:31.621  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.621  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 06:25:31.621  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.621  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 06:25:31.621  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 06:25:31.621  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 06:25:31.621  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-23 06:25:31.621  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 06:25:31.621  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 06:25:31.621  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 06:25:31.621  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.621  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.622  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 06:25:31.622  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.623  5937  5953 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 06:25:31.623  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.623  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.623  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:25:31.623  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 06:25:31.623  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.624  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.625  5937  5956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:25:31.626  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.626  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.626  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.626  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 06:25:31.627  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:25:31.627  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.627  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:25:31.627  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 06:25:31.627  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.627  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:25:31.627  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.627  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.627  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@101d90f removed from the list
11-23 06:25:31.627  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.627  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e862d9c removed from the list
11-23 06:25:31.627  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:31.627  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.627  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:25:31.628  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.628  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-23 06:25:31.628  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 06:25:31.628  5689  5735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 06:25:31.628  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 06:25:31.628  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.629  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.629  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.629  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e862d9c not in the list
11-23 06:25:31.629  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.629  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 06:25:31.629  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.630  5937  5953 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:25:31.630  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.630  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.631  5937  5948 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-23 06:25:31.631  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 06:25:31.631  5689  5735 D BluetoothAdapter: STATE_ON
11-23 06:25:31.632  5937  5975 D BtGatt.GattService: stopScan() - queue size =0
11-23 06:25:31.633  5937  5974 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 06:25:31.633  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.634  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 06:25:31.634  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 06:25:31.635  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 06:25:31.635  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.637  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.637  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:25:31.637  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.637  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.637  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.637  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.637  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.637  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:25:31.637  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50ca37a removed from the list
11-23 06:25:31.637  5689  5,735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.637  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.637  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.637  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 06:25:31.637  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3af23a5 removed from the list
11-23 06:25:31.637  5937  5953 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 06:25:31.637  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.637  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.637  5689  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 06:25:31.638  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.638  5937  5956 D BtGatt.ScanManager: stopping BLe Batch
11-23 06:25:31.638  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 06:25:31.638  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 06:25:31.638  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.638  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.638  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d61db07 added. We now have 3 listener(s)
11-23 06:25:31.639  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.639  5689  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.639  5689  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 06:25:31.639  5689  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.639  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.640  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.640  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.640  5689  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 06:25:31.640  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.640  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConne,ctor: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.640  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.640  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.640  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d09434 added. We now have 4 listener(s)
11-23 06:25:31.641  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.641  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 06:25:31.643  5937  5953 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 06:25:31.643  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.643  5937  5956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:25:31.643  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 06:25:31.643  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72f225d added. We now have 4 listener(s)
11-23 06:25:31.645  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 06:25:31.646  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 06:25:31.646  5689  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 06:25:31.646  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 06:25:31.646  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7827d2 added. We now have 5 listener(s)
11-23 06:25:31.646  5689  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 06:25:31.647  5689  5735 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 06:25:31.647  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.647  5689  5735 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 06:25:31.647  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.647  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.647  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.647  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d61db07 removed from the list
11-23 06:25:31.647  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.647  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d09434 removed from the list
11-23 06:25:31.647  5689  5735 D io.jxcore.node.ConnectivityMonitor: stop
11-23 06:25:31.647  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.647  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.648  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.648  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.648  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.648  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.648  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.648  5937  5953 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:25:31.648  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.648  5689  5735 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d09434 not in the list
11-23 06:25:31.648  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.648  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.648  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.649  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.649  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.649  5689  5735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 06:25:31.649  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 06:25:31.649  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 06:25:31.649  5689  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 06:25:31.649  5689  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7827d2 removed from the list
11-23 06:25:31.649  5689  5735 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 06:25:31.649  5689  5735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 06:25:31.649  5689  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 06:25:31.649  5689  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72f225d removed from the list
11-23 06:25:31.650  5937  5956 D BtGatt.ScanManager: handling starting scan
11-23 06:25:31.650  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 06:25:31.650  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 06:25:31.650  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 06:25:31.650  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:31.650  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 06:25:31.650  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:31.654  5937  5953 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 06:25:31.654  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.655  5937  5956 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 06:25:31.660  5937  5953 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 06:25:31.660  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.661  5937  5956 D BtGatt.ScanManager: Starting BLE batch scan
11-23 06:25:31.661  5937  5956 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 06:25:31.670  5937  5953 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 06:25:31.670  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:25:31.675  5937  5953 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 06:25:31.675  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.677  5937  5956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:25:31.682  5937  5953 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:25:31.682  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.682  5937  5953 E BtGatt.ContextMap: Context not found for ID 5
11-23 06:25:31.688  5937  5953 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 06:25:31.688  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.688  5937  5956 D BtGatt.ScanManager: stopping BLe Batch
11-23 06:25:31.694  5937  5953 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 06:25:31.694  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 06:25:31.694  5937  5956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 06:25:31.699  5937  5953 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 06:25:31.699  5937  5953 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 06:25:32.016   929  5993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 11:25:31 GMT], X-Android-Received-Millis=[1479900332014], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479900331707]}
,11-23 06:25:32.020   929  3019 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 06:25:32.020   929  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 06:25:32.021   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:25:32.025   929  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 06:25:32.047  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 06:25:32.076  5069  6011 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 06:25:32.100  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 06:25:32.140  5689  5689 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 06:25:32.457   929  3019 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 06:25:33.818  5689  6018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 06:25:33.818  5689  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:34.117   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:25:34.631  5689  6018 W !!      : call onHalfStreamCopied
,11-23 06:25:34.632  5689  6018 I testCopyDataAndClose: closing input stream
,11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 06:25:35.423  5689  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 06:25:37.157   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:25:39.171  5689  6019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:39.171  5689  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:39.403   929  3019 D ConnectivityService: handlePromptUnvalidated 102
,11-23 06:25:40.184   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:25:41.173  5689  5735 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-23 06:25:41.173  5689  5735 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 06:25:41.174  5689  5735 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-23 06:25:41.175  5689  6019 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-23 06:25:41.176  5689  6019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:41.176  5689  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-23 06:25:41.365  5689  6020 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 06:25:41.365  5689  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:42.475   929  3017 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-23 06:25:42.981  5689  6020 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 06:25:42.981  5689  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 06:25:42.982  5689  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 06:25:45.171   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:46.173   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:46.725  5689  6021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:46.725  5689  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 06:25:46.726  5689  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 06:25:46.727  5689  6021 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 06:25:46.727  5689  6021 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 06:25:46.727  5689  6021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:46.727  5689  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 06:25:46.730  5689  5735 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-23 06:25:46.733  5689  6022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:46.733  5689  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 06:25:46.734  5689  6022 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-23 06:25:46.734  5689  6022 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:46.734  5689  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 06:25:46.734  5689  6022 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-23 06:25:46.734  5689  6022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-23 06:25:46.734  5689  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 06:25:46.740  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 06:25:46.740  5689  5735 I jxcore-log: 
,11-23 06:25:46.741  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 06:25:46.741  5689  5735 I jxcore-log: 
11-23 06:25:46.741  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 06:25:46.741  5689  5735 I jxcore-log: 
11-23 06:25:46.741  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 06:25:46.741  5689  5735 I jxcore-log: 
11-23 06:25:46.742  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'Total duration:  90918'
11-23 06:25:46.742  5689  5735 I jxcore-log: 
,11-23 06:25:46.744  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 06:25:46.744  5689  5735 I jxcore-log: 
,11-23 06:25:46.749  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 06:25:46.749  5689  5735 I jxcore-log: 
,11-23 06:25:46.750  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 06:25:46.750  5689  5735 I jxcore-log: 
11-23 06:25:46.750  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 06:25:46.750  5689  5735 I jxcore-log: 
11-23 06:25:46.751  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 06:25:46.751  5689  5735 I jxcore-log: 
11-23 06:25:46.751  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.751  5689  5735 I jxcore-log: 
11-23 06:25:46.752  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 06:25:46.752  5689  5735 I jxcore-log: 
,11-23 06:25:46.752  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.752  5689  5735 I jxcore-log: 
11-23 06:25:46.752  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 06:25:46.752  5689  5735 I jxcore-log: 
,11-23 06:25:46.753  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 06:25:46.753  5689  5735 I jxcore-log: 
11-23 06:25:46.753  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 06:25:46.753  5689  5735 I jxcore-log: 
11-23 06:25:46.753  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 06:25:46.753  5689  5735 I jxcore-log: 
11-23 06:25:46.753  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.753  5689  5735 I jxcore-log: 
11-23 06:25:46.753  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 06:25:46.753  5689  5735 I jxcore-log: 
11-23 06:25:46.754  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.754  5689  5735 I jxcore-log: 
,11-23 06:25:46.754  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 06:25:46.754  5689  5735 I jxcore-log: 
11-23 06:25:46.754  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.754  5689  5735 I jxcore-log: 
11-23 06:25:46.754  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 06:25:46.754  5689  5735 I jxcore-log: 
11-23 06:25:46.754  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-23 06:25:46.754  5689  5735 I jxcore-log: 
11-23 06:25:46.755  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 06:25:46.755  5689  5735 I jxcore-log: 
,11-23 06:25:46.755  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 06:25:46.755  5689  5735 I jxcore-log: 
11-23 06:25:46.755  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 06:25:46.755  5689  5735 I jxcore-log: 
11-23 06:25:46.756  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 06:25:46.756  5689  5735 I jxcore-log: 
11-23 06:25:46.756  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 06:25:46.756  5689  5735 I jxcore-log: 
,11-23 06:25:46.756  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 06:25:46.756  5689  5735 I jxcore-log: 
,11-23 06:25:46.758  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 06:25:46.758  5689  5735 I jxcore-log: 
11-23 06:25:46.758  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 06:25:46.758  5689  5735 I jxcore-log: 
,11-23 06:25:46.758  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 06:25:46.758  5689  5735 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-23 06:25:46.758  5689  5735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 06:25:46.759  5689  5735 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 06:25:46.759  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 06:25:46.759  5689  5735 I jxcore-log: 
11-23 06:25:46.759  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.759  5689  5735 I jxcore-log: 
,11-23 06:25:46.759  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 06:25:46.759  5689  5735 I jxcore-log: 
11-23 06:25:46.759  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.759  5689  5735 I jxcore-log: 
11-23 06:25:46.760  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 06:25:46.760  5689  5735 I jxcore-log: 
11-23 06:25:46.760  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 06:25:46.760  5689  5735 I jxcore-log: 
,11-23 06:25:46.765  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 06:25:46.765  5689  5735 I jxcore-log: 
11-23 06:25:46.765  5689  5735 I jxcore-log: 2016-11-23 11:25:46 - WARN testUtils: 'myNameCallback not set!'
11-23 06:25:46.765  5689  5735 I jxcore-log: 
,11-23 06:25:46.770  5689  5689 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 06:25:47.174   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:48.175   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:48.735  5689  5735 I jxcore-log: 2016-11-23 11:25:48 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 06:25:48.735  5689  5735 I jxcore-log: 
,11-23 06:25:48.737  5689  5735 I jxcore-log: 2016-11-23 11:25:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 06:25:48.737  5689  5735 I jxcore-log: 
,11-23 06:25:49.085  5689  5735 I jxcore-log: 2016-11-23 11:25:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 06:25:49.085  5689  5735 I jxcore-log: 
,11-23 06:25:49.095  5689  5735 I jxcore-log: 2016-11-23 11:25:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 06:25:49.095  5689  5735 I jxcore-log: 
,11-23 06:25:49.177   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:25:50.178   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 06:25:50.182  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 06:25:50.182  5689  5735 I jxcore-log: 
,11-23 06:25:50.369  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 06:25:50.369  5689  5735 I jxcore-log: 
,11-23 06:25:50.374  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 06:25:50.374  5689  5735 I jxcore-log: 
,11-23 06:25:50.379  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 06:25:50.379  5689  5735 I jxcore-log: 
,11-23 06:25:50.856  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 06:25:50.856  5689  5735 I jxcore-log: 
,11-23 06:25:50.900  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 06:25:50.900  5689  5735 I jxcore-log: 
,11-23 06:25:50.914  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 06:25:50.914  5689  5735 I jxcore-log: 
,11-23 06:25:50.918  5689  5735 I jxcore-log: 2016-11-23 11:25:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 06:25:50.918  5689  5735 I jxcore-log: 
,11-23 06:25:51.185  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 06:25:51.185  5689  5735 I jxcore-log: 
,11-23 06:25:51.310  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 06:25:51.310  5689  5735 I jxcore-log: 
,11-23 06:25:51.674  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 06:25:51.674  5689  5735 I jxcore-log: 
,11-23 06:25:51.682  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 06:25:51.682  5689  5735 I jxcore-log: 
,11-23 06:25:51.686  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 06:25:51.686  5689  5735 I jxcore-log: 
,11-23 06:25:51.691  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 06:25:51.691  5689  5735 I jxcore-log: 
,11-23 06:25:51.697  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 06:25:51.697  5689  5735 I jxcore-log: 
,11-23 06:25:51.726  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 06:25:51.726  5689  5735 I jxcore-log: 
,11-23 06:25:51.760  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 06:25:51.760  5689  5735 I jxcore-log: 
,11-23 06:25:51.766  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 06:25:51.766  5689  5735 I jxcore-log: 
,11-23 06:25:51.771  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 06:25:51.771  5689  5735 I jxcore-log: 
,11-23 06:25:51.785  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 06:25:51.785  5689  5735 I jxcore-log: 
,11-23 06:25:51.799  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 06:25:51.799  5689  5735 I jxcore-log: 
,11-23 06:25:51.804  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 06:25:51.804  5689  5735 I jxcore-log: 
,11-23 06:25:51.809  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 06:25:51.809  5689  5735 I jxcore-log: 
,11-23 06:25:51.821  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 06:25:51.821  5689  5735 I jxcore-log: 
,11-23 06:25:51.836  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 06:25:51.836  5689  5735 I jxcore-log: 
,11-23 06:25:51.849  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 06:25:51.849  5689  5735 I jxcore-log: 
,11-23 06:25:51.858  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 06:25:51.858  5689  5735 I jxcore-log: 
,11-23 06:25:51.870  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 06:25:51.870  5689  5735 I jxcore-log: 
,11-23 06:25:51.879  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 06:25:51.879  5689  5735 I jxcore-log: 
,11-23 06:25:51.891  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 06:25:51.891  5689  5735 I jxcore-log: 
,11-23 06:25:51.899  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 06:25:51.899  5689  5735 I jxcore-log: 
,11-23 06:25:51.905  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 06:25:51.905  5689  5735 I jxcore-log: 
,11-23 06:25:51.924  5689  5735 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 06:25:51.925  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 06:25:51.925  5689  5735 I jxcore-log: 
,11-23 06:25:51.956  5689  5735 I jxcore-log: 2016-11-23 11:25:51 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 06:25:51.956  5689  5735 I jxcore-log: 
,11-23 06:25:52.245  5689  5735 I jxcore-log: 2016-11-23 11:25:52 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 06:25:52.245  5689  5735 I jxcore-log: 
,11-23 06:26:07.411   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:26:10.179   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:10.447   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:26:11.181   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:11.369   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:26:12.182   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:13.113   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:26:13.184   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:14.185   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:15.186   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 06:26:16.508   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:26:22.260   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:26:22.581   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:26:38.286   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:26:40.187   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 06:26:40.188   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 06:26:47.407   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=336530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:26:51.376   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:26:55.189   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:56.191   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:57.193   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:58.194   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:26:59.195   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:00.196   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 06:27:03.354   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=352477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:27:05.197   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:06.199   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:07.200   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:08.202   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:09.203   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:10.204   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 06:27:11.377   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:27:12.486   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=361610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:27:20.207   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:21.208   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:22.209   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:23.211   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:24.212   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:25.213   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 06:27:28.580   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:27:37.673   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:27:40.214   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:41.216   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:42.217   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:43.218   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:44.220   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:27:45.221   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 06:27:51.382   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:27:53.913   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=403037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:28:03.033   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=412157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:28:05.223   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:06.224   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:07.225   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:08.226   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:09.227   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:10.228   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 06:28:11.385   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:28:18.980   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=428104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:28:28.073   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=437197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:28:31.388   929  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 06:28:35.229   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 06:28:35.230   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 06:28:43.993   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=453117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 06:28:53.113   929  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=462237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 06:28:55.231   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:55.276  5991  5991 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 06:28:56.232   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:57.234   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:58.235   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:59.236   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:28:59.895   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:29:00.237   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 06:29:02.934   929  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 06:29:04.877  5689  5735 I jxcore-log: 2016-11-23 11:29:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 06:29:04.877  5689  5735 I jxcore-log: 
,11-23 06:29:05.105  5689  5735 I jxcore-log: 2016-11-23 11:29:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 06:29:05.105  5689  5735 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 06:29:05.105  5689  5735 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 06:29:05.105  5689  5735 I jxcore-log: emit@events.js:82:1
11-23 06:29:05.105  5689  5735 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 06:29:05.105  5689  5735 I jxcore-log: emit@events.js:82:1''
11-23 06:29:05.105  5689  5735 I jxcore-log: 
,11-23 06:29:05.107  5689  5735 I jxcore-log: 2016-11-23 11:29:05 - DEBUG CoordinatedClient: 'test client failed'
11-23 06:29:05.107  5689  5735 I jxcore-log: 
,11-23 06:29:05.120  5689  5735 I jxcore-log: 2016-11-23 11:29:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 06:29:05.120  5689  5735 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 06:29:05.120  5689  5735 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 06:29:05.120  5689  5735 I jxcore-log: emit@events.js:82:1
11-23 06:29:05.120  5689  5735 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 06:29:05.120  5689  5735 I jxcore-log: emit@events.js:82:1''
11-23 06:29:05.120  5689  5735 I jxcore-log: 
,11-23 06:29:05.121  5689  5735 I jxcore-log: 2016-11-23 11:29:05 - DEBUG CoordinatedClient: 'test client failed'
11-23 06:29:05.121  5689  5735 I jxcore-log: 
,11-23 06:29:05.127  5689  5735 I jxcore-log: 2016-11-23 11:29:05 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 06:29:05.127  5689  5735 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 06:29:05.127  5689  5735 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 06:29:05.127  5689  5735 I jxcore-log: emit@events.js:82:1
11-23 06:29:05.127  5689  5735 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 06:29:05.127  5689  5735 I jxcore-log: emit@events.js:82:1''
11-23 06:29:05.127  5689  5735 I jxcore-log: 
,11-23 06:29:05.130  5689  5735 I jxcore-log: 2016-11-23 11:29:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 06:29:05.130  5689  5735 I jxcore-log: 
,11-23 06:29:05.237   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:29:05.810  6032  6032 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 06:29:05.843  6032  6032 D AndroidRuntime: CheckJNI is OFF
,11-23 06:29:05.867  6032  6032 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 06:29:05.898  6032  6032 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 06:29:05.913  6032  6032 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 06:29:05.922   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-23 06:29:05.923   929   942 I ActivityManager: Killing 5689:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 06:29:06.038   929  3984 D GraphicsStats: Buffer count: 2
,11-23 06:29:06.039   929  3018 D WifiService: Client connection lost with reason: 4
11-23 06:29:06.038   929  3976 I WindowState: WIN DEATH: Window{799f7a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 06:29:06.059   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-23 06:29:06.061   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-23 06:29:06.062   929   942 E ActivityManager: Failure starting process com.test.thalitest
11-23 06:29:06.062   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-23 06:29:06.062   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:29:06.062   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:29:06.062   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 06:29:06.062   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-23 06:29:06.063   929   953 I art     : Starting a blocking GC Explicit
11-23 06:29:06.063   929   942 I ActivityManager:   Force finishing activity ActivityRecord{7c8f89a u0 com.test.thalitest/.MainActivity t10}
,11-23 06:29:06.069   929  3637 W ActivityManager: Spurious death for ProcessRecord{bf2c7d1 0:com.test.thalitest/u0a77}, curProc for 5689: null
,11-23 06:29:06.077   929   947 W WindowManager: Attempted to add application window with unknown token Token{d6cf5cb ActivityRecord{7c8f89a u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-23 06:29:06.078   929   947 W WindowManager: Token{d6cf5cb ActivityRecord{7c8f89a u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{d6cf5cb ActivityRecord{7c8f89a u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-23 06:29:06.078   929   947 W WindowManager: view not successfully added to wm, removing view
11-23 06:29:06.078   929   947 W WindowManager: Exception when adding starting window
11-23 06:29:06.078   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a790d10 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-23 06:29:06.078   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-23 06:29:06.078   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-23 06:29:06.078   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-23 06:29:06.078   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-23 06:29:06.078   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-23 06:29:06.078   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:29:06.078   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:29:06.078   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 06:29:06.078   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-23 06:29:06.157   929   953 I art     : Explicit concurrent mark sweep GC freed 104296(7MB) AllocSpace objects, 60(1820KB) LOS objects, 33% free, 29MB/43MB, paused 1.627ms total 94.425ms
,11-23 06:29:06.181   929   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 06:29:06.185  6032  6032 I art     : System.exit called, status: 0
11-23 06:29:06.185  6032  6032 I AndroidRuntime: VM exiting with result code 0.
,11-23 06:29:06.208   929   953 I ActivityManager: Start proc 6042:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-23 06:29:06.209   929   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 06:29:06.217   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-23 06:29:06.221  5937  5937 D BluetoothMapAppObserver: onReceive
11-23 06:29:06.221  5937  5937 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 06:29:06.223  3713  3713 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 06:29:06.226  4183  4247 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-23 06:29:06.230   929  2983 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 06:29:06.238   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 06:29:06.249  3713  6054 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 06:29:06.254  3444  6056 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 06:29:06.258  3713  6054 I Decoder : createOrResetDecoder
,11-23 06:29:06.282  5663  5663 W kworker/3:3: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 06:29:06.285  5663  5663 W kworker/3:3: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 06:29:06.298  3833  3833 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 06:29:06.298  5663  5663 W kworker/3:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 06:29:06.314  3623  3623 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-23 06:29:06.315  3623  3623 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-23 06:29:06.316  3623  3623 E AndroidRuntime: FATAL EXCEPTION: main
11-23 06:29:06.316  3623  3623 E AndroidRuntime: Process: com.google.process.gapps, PID: 3623
11-23 06:29:06.316  3623  3623 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-23 06:29:06.316  3623  3623 E AndroidRuntime: 	... 8 more
,11-23 06:29:06.328   929  6061 E DropBoxManagerService: Can't write: system_app_crash
11-23 06:29:06.328   929  6061 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 06:29:06.328   929  6061 E DropBoxManagerService: 	... 5 more
,11-23 06:29:06.334   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 06:29:06.335  3623  3623 I Process : Sending signal. PID: 3623 SIG: 9
,11-23 06:29:06.337   929   942 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
,11-23 06:29:06.338   929   942 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
11-23 06:29:06.338   929   942 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 06:29:06.338   929   942 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-23 06:29:06.353  3444  3467 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj5B00919E0) - 
,11-23 06:29:06.369   929  3018 D WifiService: Client connection lost with reason: 4
,11-23 06:29:06.376   929   942 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,11-23 06:29:06.376   929   942 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
11-23 06:29:06.376   929   942 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 20999ms
11-23 06:29:06.378  3444  6056 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-23 06:29:06.378  3444  6056 I Process : Sending signal. PID: 3444 SIG: 9
,11-23 06:29:06.388   929   942 I ActivityManager: Start proc 6062:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,11-23 06:29:06.391   929  3242 W ActivityManager: Spurious death for ProcessRecord{2bd80df 6062:com.google.process.gapps/u0a12}, curProc for 3623: null
,11-23 06:29:06.392   382   481 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown
11-23 06:29:06.392   382   481 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
,11-23 06:29:06.427   929  3638 I ActivityManager: Process android.process.acore (pid 3444) has died
,11-23 06:29:06.427   929  3638 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30948ms
,11-23 06:29:06.702   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
