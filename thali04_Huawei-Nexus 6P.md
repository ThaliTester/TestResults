#### Test 85202518d195ad1_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-16 11:50:10.545   927  5109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=316211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:50:12.582  5348  5348 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 11:50:12.588  5348  5348 D AndroidRuntime: CheckJNI is OFF
09-16 11:50:12.618  5348  5348 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 11:50:12.655  5348  5348 I Radio-JNI: register_android_hardware_Radio DONE
09-16 11:50:12.672  5348  5348 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-16 11:50:12.676   927  3545 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 11:50:12.721   927  3545 I ActivityManager: Start proc 5357:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 11:50:12.728  5348  5348 D AndroidRuntime: Shutting down VM
,09-16 11:50:13.062   927  3147 I WindowManager: Screenshot max retries 4 of Token{a829429 ActivityRecord{f9ebdb0 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{8c092c8 u0 Starting com.test.thalitest} drawState=4
,09-16 11:50:13.133  5357  5357 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-16 11:50:13.166  5357  5357 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-16 11:50:13.188  5357  5357 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 8836-8854)
,09-16 11:50:13.188  5357  5357 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 11:50:13.207  5357  5357 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e6d90e0}
,09-16 11:50:13.208  5357  5357 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-16 11:50:13.208  5357  5357 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-16 11:50:13.213  5357  5357 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-16 11:50:13.214  5357  5357 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-16 11:50:13.247  5357  5357 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-16 11:50:13.265  5357  5357 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-16 11:50:13.265  5357  5357 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 11:50:13.265  5357  5357 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 11:50:13.265  5357  5357 I Adreno  : Build Date                       : 12/06/15
09-16 11:50:13.265  5357  5357 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 11:50:13.265  5357  5357 I Adreno  : Local Branch                     : mybranch17112971
09-16 11:50:13.265  5357  5357 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 11:50:13.265  5357  5357 I Adreno  : Remote Branch                    : NONE
09-16 11:50:13.265  5357  5357 I Adreno  : Reconstruct Branch               : NOTHING
,09-16 11:50:13.308   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f70603f:true
,09-16 11:50:13.330  3980  3980 W Binder_5: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14992]" dev="sockfs" ino=14992 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 11:50:13.334  3980  3980 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14992]" dev="sockfs" ino=14992 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 11:50:13.346  5357  5357 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-16 11:50:13.354  5357  5357 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-16 11:50:13.377  3980  3980 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32131]" dev="sockfs" ino=32131 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 11:50:13.380  5357  5394 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 11:50:13.377  3980  3980 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32131]" dev="sockfs" ino=32131 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 11:50:13.380  3420  3420 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[23549]" dev="sockfs" ino=23549 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-16 11:50:13.380  3420  3420 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23549]" dev="sockfs" ino=23549 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 11:50:13.386  5357  5381 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-16 11:50:13.404  5357  5394 I OpenGLRenderer: Initialized EGL, version 1.4
,09-16 11:50:13.462   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +398ms (total +771ms)
,09-16 11:50:13.504  5357  5357 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5357
,09-16 11:50:13.580  5357  5357 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 11:50:13.709  5357  5396 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -577242832
,09-16 11:50:13.723  5357  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 11:50:13.723  5357  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 11:50:13.723  5357  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 11:50:13.723  5357  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 11:50:13.723  5357  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-16 11:50:13.723  5357  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91b8e91 added. We now have 1 listener(s)
,09-16 11:50:13.726  5357  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-16 11:50:13.726  5357  5396 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 11:50:13.727  5357  5396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-16 11:50:13.727  5357  5396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 11:50:13.729  5357  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff7064 added. We now have 1 listener(s)
09-16 11:50:13.729  5357  5396 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:50:13.734   927  2965 D WifiService: New client listening to asynchronous messages
,09-16 11:50:13.734  5357  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 11:50:13.734  5357  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 11:50:13.734  5357  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 11:50:13.735  5357  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 11:50:13.735  5357  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-16 11:50:13.736  5357  5396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:50:13.736  5357  5396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-16 11:50:13.741  5357  5396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:13.741  5357  5396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:13.741  5357  5396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-16 11:50:13.742  5357  5396 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 11:50:13.743  5357  5396 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 11:50:13.744  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:13.746  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:13.759  5357  5357 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 11:50:14.044  5357  5403 W jxcore-log: Initializing JXcore engine
09-16 11:50:14.045  5357  5403 W jxcore-log: JXcore engine is ready
,09-16 11:50:14.067  5403  5403 W Thread-53: type=1400 audit(0.0:105): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12389 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-16 11:50:14.067  5403  5403 W Thread-53: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[15432]" dev="sockfs" ino=15432 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-16 11:50:14.067  5403  5403 W Thread-53: type=1400 audit(0.0:107): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 11:50:14.067  5403  5403 W Thread-53: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32105]" dev="sockfs" ino=32105 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 11:50:14.080  5357  5403 W jxcore-log: Starting JXcore engine
,09-16 11:50:14.138  5357  5403 W jxcore-log: Platform android
09-16 11:50:14.138  5357  5403 W jxcore-log: 
,09-16 11:50:14.139  5357  5403 W jxcore-log: Process ARCH arm
09-16 11:50:14.139  5357  5403 W jxcore-log: 
,09-16 11:50:14.240  5357  5403 I jxcore-log: JXcore Cordova bridge is ready!
09-16 11:50:14.240  5357  5403 I jxcore-log: 
09-16 11:50:14.240  5357  5403 W jxcore-log: JXcore engine is started
,09-16 11:50:14.253  5357  5396 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 11:50:14.259  5357  5357 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 11:50:15.719   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:50:23.736  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 11:50:23.736  5357  5403 I jxcore-log: 
,09-16 11:50:23.739  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 11:50:23.739  5357  5403 I jxcore-log: 
,09-16 11:50:23.742  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:23.742  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:50:23.742  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:23.742  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:50:23.744  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 11:50:23.744  5357  5403 I jxcore-log: 
,09-16 11:50:23.745  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 11:50:23.745  5357  5403 I jxcore-log: 
,09-16 11:50:23.815   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:50:23.816   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:50:23.990  5357  5403 I jxcore-log: Running unit tests
09-16 11:50:23.990  5357  5403 I jxcore-log: 
,09-16 11:50:23.991  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 11:50:23.991  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e0f676 added. We now have 2 listener(s)
,09-16 11:50:23.991  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:50:23.992  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 11:50:23.992  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 11:50:23.992  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:50:23.992  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5251477 added. We now have 2 listener(s)
,09-16 11:50:23.992  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:50:23.992  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 11:50:23.994  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:50:23.995  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:23.995  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:50:23.995  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:23.996  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:50:23.996  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:50:23.997  5357  5403 D executeNativeTests: Running unit tests
,09-16 11:50:24.001  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:24.005  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:24.034  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 11:50:24.034  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd added. We now have 3 listener(s)
09-16 11:50:24.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:50:24.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 11:50:24.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 11:50:24.035  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:50:24.035  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 added. We now have 3 listener(s)
09-16 11:50:24.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:50:24.035  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 11:50:24.036  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:50:24.037  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:24.037  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:24.037  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:24.037  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:24.038  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:50:24.039  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:50:24.039  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:24.039  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-16 11:50:24.039  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:24.040  5357  5403 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 11:50:24.040  5357  5403 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 11:50:24.040  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 11:50:24.040  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:24.040  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:24.040  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:24.040  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:24.041  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:24.041  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:24.041  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:24.041  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:24.041  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.041  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:50:24.041  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 11:50:24.041  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd removed from the list
09-16 11:50:24.041  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:24.041  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 removed from the list
09-16 11:50:24.046  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:24.046  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:24.046  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.047  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.047  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.047  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:24.047  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:24.047  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:24.047  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:24.048  5357  5403 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 11:50:24.048  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:24.048  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:24.048  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:24.048  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:24.048  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.048  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.048  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:24.048  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:24.048  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:24.048  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:24.048  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.048  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.048  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.048  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.049  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:24.049  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:24.049  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:24.049  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 11:50:24.051  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 11:50:24.052  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:24.052  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:24.052  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:24.052  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:24.052  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.052  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.052  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:24.052  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:24.052  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:24.052  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:24.052  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.052  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.052  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:24.052  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:24.052  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:24.053  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:24.053  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:24.053  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:24.053  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 11:50:24.054  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:50:24.055  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:24.055  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:24.055  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:24.055  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:24.056  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:50:24.056  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:50:24.056  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:50:24.056  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:50:24.056  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:50:24.056  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:50:24.057  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-16 11:50:24.058  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-16 11:50:24.058  5357  5403 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-16 11:50:24.058  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
09-16 11:50:24.063  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:24.065  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:24.065  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-16 11:50:24.567  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:50:29.059  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:29.060  5357  5403 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-16 11:50:29.062  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:29.062  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:29.062  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 11:50:29.062  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:29.063  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 11:50:29.063  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 11:50:29.063  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:50:29.063  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:50:29.063  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:50:29.064  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:50:29.065  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:50:29.065  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:50:29.066  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:29.066  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:50:29.066  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:50:29.066  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:50:29.066  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:29.066  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:50:29.066  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:29.066  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:29.066  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:29.066  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:50:29.067  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:29.067  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:29.067  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:29.068  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:29.068  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:50:29.068  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:29.068  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:29.069  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 11:50:29.071  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:50:29.075  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:29.075  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:29.076  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:29.076  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:29.076  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:50:29.077  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:50:29.077  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:50:29.077  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 11:50:29.077  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:50:29.077  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:50:29.079  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-16 11:50:29.080  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-16 11:50:29.080  5357  5403 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-16 11:50:29.080  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
09-16 11:50:29.081  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:29.083  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:29.083  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-16 11:50:29.585  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:50:34.081  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:50:34.081  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:50:34.081  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:50:34.081  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:50:34.081  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 11:50:34.081  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 11:50:34.081  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 11:50:34.081  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 11:50:34.082  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:50:34.082  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:50:34.082  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 11:50:34.083  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:50:34.084  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:50:34.084  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:50:34.084  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:50:34.586  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:50:34.586  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:50:34.586  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:50:35.723   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:50:38.291   927  5109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 11:50:38.817   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:39.085  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:50:39.085  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.086  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.086  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:50:39.086  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:50:39.086  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:50:39.087  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.087  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.088  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.088  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:50:39.088  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.090  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.090  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:39.091  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:50:39.091  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.091  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.092  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.094  5357  5403 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-16 11:50:39.096  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:39.096  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:50:39.097  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.097  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.097  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.097  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.098  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.098  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.098  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
,09-16 11:50:39.098  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.098  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.098  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.099  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.099  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.100  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.100  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:50:39.100  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.100  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.102  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 11:50:39.102  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:39.103  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.103  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.103  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.105  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:50:39.105  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.105  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.105  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.105  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.105  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.105  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.105  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.105  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.105  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:39.106  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.106  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.106  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.106  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.107  5357  5403 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 11:50:39.107  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:50:39.107  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.108  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.108  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.108  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.108  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.108  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.108  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.108  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.108  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.108  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.108  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.108  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.108  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.109  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.109  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.109  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.109  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.110  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 11:50:39.110  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:39.111  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:50:39.111  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.111  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.111  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.111  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.111  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.111  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.111  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.111  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.111  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.111  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.111  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.112  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.113  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.113  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:50:39.113  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.113  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.114  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:50:39.115  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:39.115  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:39.115  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 11:50:39.115  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:39.115  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:39.115  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:50:39.115  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:39.115  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:39.115  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:39.115  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.115  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.115  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.116  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.116  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.116  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.117  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.117  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.117  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.117  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.117  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.117  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.117  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.118  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.118  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.118  5357  5403 I o,rg.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.118  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.119  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:50:39.119  5357  5403 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 11:50:39.119  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 11:50:39.122  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:50:39.122  5357  5403 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 11:50:39.122  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 11:50:39.123  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 11:50:39.124  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 11:50:39.124  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 11:50:39.125  5357  5403 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 11:50:39.125  5357  5403 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 11:50:39.125  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-16 11:50:39.125  5357  5403 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 11:50:39.125  5357  5403 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 11:50:39.125  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:50:39.125  5357  5403 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 11:50:39.125  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-16 11:50:39.126  5357  5403 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-16 11:50:39.127  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-16 11:50:39.127  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 11:50:39.127  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 11:50:39.128  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 11:50:39.128  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 11:50:39.128  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 11:50:39.128  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 11:50:39.129  5357  5403 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-16 11:50:39.129  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:39.130  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.130  5357  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 117)
09-16 11:50:39.130  5357  5405 E BluetoothDevice: Bluetooth is not enabled
09-16 11:50:39.130  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.130  5357  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 117)
09-16 11:50:39.130  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.130  5357  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 117)
09-16 11:50:39.130  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.130  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.130  5357  5405 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 117)
09-16 11:50:39.130  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-16 11:50:39.131  5357  5357 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-16 11:,50:39.131  5357  5357 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-16 11:50:39.132  5357  5357 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 11:50:39.132  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.132  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.132  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.132  5357  5357 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:39.132  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.132  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.132  5357  5357 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:39.132  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.132  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.132  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.132  5357  5406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 117
09-16 11:50:39.132  5357  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 117
09-16 11:50:39.132  5357  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 117)
,09-16 11:50:39.133  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.133  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.133  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.133  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.134  5357  5403 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 11:50:39.134  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:39.134  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.135  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:50:39.135  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.135  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.135  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.135  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.135  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.135  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.135  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.135  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.135  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.135  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.135  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.136  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.136  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.136  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.136  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.137  5357  5403 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 11:50:39.137  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:50:39.137  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.137  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.137  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.137  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.137  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.137  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.137  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.137  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.137  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.137  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.137  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.138  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.138  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.138  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.138  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:50:39.138  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.138  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.139  5357  5403 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 11:50:39.139  5357  5403 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 11:50:39.139  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 11:50:39.139  5357  5403 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 11:50:39.139  5357  5403 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 11:50:39.139  5357  5403 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 11:50:39.139  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 11:50:39.139  5357  5403 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 11:50:39.140  5357  5403 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 11:50:39.140  5357  5403 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 11:50:39.140  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 11:50:39.140  5357  5403 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 11:50:39.140  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:50:39.140  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:39.140  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:39.140  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.140  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.140  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.140  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.140  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.140  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.140  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.140  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.141  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.141  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.141  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.141  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:39.141  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:39.141  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.141  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.142  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:39.142  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:50:39.142  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:39.142  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:39.142  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:39.142  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:39.142  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:39.142  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:39.142  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:39.818   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:40.819   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:41.820   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:42.821   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:43.822   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 11:50:44.143  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:50:44.143  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.144  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:50:44.144  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.144  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:44.144  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.144  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:44.144  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:44.145  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:44.145  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:50:44.145  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.145  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.145  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.145  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.146  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.146  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:50:44.146  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.146  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.146  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.146  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.148  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:44.148  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:44.148  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:50:44.148  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.152  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 11:50:44.153  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:50:44.153  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-16 11:50:44.153  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-16 11:50:44.154  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:50:44.154  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-16 11:50:44.155  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:44.155  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 11:50:44.155  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:44.156  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-16 11:50:44.156  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.156  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:50:44.156  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 11:50:44.156  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:50:44.156  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:50:44.156  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 11:50:44.157  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.157  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.159  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:50:44.160  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.160  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:50:44.160  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:44.160  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:50:44.160  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:44.160  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:50:44.160  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:44.161  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:44.161  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.161  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:44.161  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.161  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.161  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.162  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:44.162  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.162  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.162  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.163  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:50:44.165  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:50:44.165  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:50:44.166  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.166  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.167  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 11:50:44.168  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:44.168  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 11:50:44.168  5357  5403 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-16 11:50:44.168  5357  5403 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 11:50:44.169  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 11:50:44.169  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:44.169  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 11:50:44.169  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:44.169  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:44.170  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:44.170  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:44.171  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.171  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.171  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.171  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:50:44.172  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.172  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:44.172  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.172  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.172  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.172  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.173  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:44.173  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:44.173  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.173  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.176  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:44.176  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:44.176  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:44.176  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:44.176  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.177  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.177  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.177  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.177  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.177  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:44.177  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.177  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.177  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.177  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.178  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:44.178  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:44.178  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.178  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-,16 11:50:44.179  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:50:44.179  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:50:44.179  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:50:44.179  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:50:44.179  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.179  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.179  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@133e7bd not in the list
09-16 11:50:44.180  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.180  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.180  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:44.180  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.180  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.180  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:44.180  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:44.181  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:50:44.181  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:50:44.181  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:50:44.181  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce371b2 not in the list
09-16 11:50:44.182  5357  5403 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 11:50:44.183  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 11:50:44.183  5357  5403 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 11:50:44.183  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 11:50:44.183  5357  5403 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 11:50:44.183  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 11:50:44.185  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 11:50:44.186  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-16 11:50:44.186  5357  5403 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 11:50:44.187  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connectio,n(s) left
09-16 11:50:44.187  5357  5403 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 11:50:44.187  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 11:50:44.187  5357  5403 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-16 11:50:44.187  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 11:50:44.188  5357  5403 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-16 11:50:44.188  5357  5403 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-16 11:50:44.188  5357  5403 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 11:50:44.188  5357  5403 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-16 11:50:44.189  5357  5403 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-16 11:50:44.189  5357  5403 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-16 11:50:44.190  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:50:44.190  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f430ac added. We now have 3 listener(s)
09-16 11:50:44.190  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:50:44.192   927   937 D WifiService: setWifiEnabled: true pid=5357, uid=10077
09-16 11:50:44.192   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-16 11:50:44.210   927   944 I ActivityManager: Start proc 5408:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 11:50:44.287  5408  5408 D AdapterServiceConfig: Adding HeadsetService
,09-16 11:50:44.288  5408  5408 D AdapterServiceConfig: Adding A2dpService
09-16 11:50:44.288  5408  5408 D AdapterServiceConfig: Adding HidService
09-16 11:50:44.288  5408  5408 D AdapterServiceConfig: Adding HealthService
09-16 11:50:44.288  5408  5408 D AdapterServiceConfig: Adding PanService
09-16 11:50:44.288  5408  5408 D AdapterServiceConfig: Adding GattService
09-16 11:50:44.288  5408  5408 D AdapterServiceConfig: Adding BluetoothMapService
09-16 11:50:44.289  5408  5408 D AdapterServiceConfig: Adding SapService
,09-16 11:50:44.309   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0be3a5:true
,09-16 11:50:44.310  5408  5408 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 11:50:44.312  5408  5408 I bt_bluedroid: init
,09-16 11:50:44.312  5408  5420 I BluetoothAdapterState: Entering OffState
,09-16 11:50:44.315  5408  5421 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 11:50:44.318  5408  5421 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-16 11:50:44.318  5408  5421 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 11:50:44.318  5408  5421 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-16 11:50:44.319  5408  5408 I bt_bluedroid: get_profile_interface socket
,09-16 11:50:44.321  5408  5424 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 11:50:44.322  5408  5424 D BluetoothAdapterProperties: Name is: Nexus 6P
09-16 11:50:44.322  5408  5408 I bt_bluedroid: get_profile_interface sdp
,09-16 11:50:44.327  5408  5419 I bt_bluedroid: config_hci_snoop_log
,09-16 11:50:44.328   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-16 11:50:44.331  5408  5420 D BluetoothAdapterState: Current state: OFF, message: 0
09-16 11:50:44.331  5408  5420 D BluetoothAdapterProperties: Setting state to 14
,09-16 11:50:44.331  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 11:50:44.333  5408  5420 D BluetoothBondStateMachine: make
,09-16 11:50:44.335  5408  5425 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:50:44.338  5408  5420 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:50:44.339  5408  5408 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 11:50:44.341  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:50:44.342  5408  5408 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 11:50:44.342  5408  5408 D BtGatt.GattService: Received start request. Starting profile...
09-16 11:50:44.342  5408  5408 D BtGatt.GattService: start()
09-16 11:50:44.342  5408  5408 I bt_bluedroid: get_profile_interface gatt
09-16 11:50:44.343  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:50:44.343  5408  5408 D BtGatt.AdvertiseManager: advertise manager created
,09-16 11:50:44.348  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:44.348  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:44.348  5408  5408 V BluetoothAdapterState: isBleTurningOn()=true
09-16 11:50:44.348  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:44.349  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 11:50:44.350  5408  5420 I bt_bluedroid: bt_bluedroid
,09-16 11:50:44.350  5408  5421 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 11:50:44.351  5408  5421 I bt_hci  : start_up
,09-16 11:50:44.357  5408  5421 I bt_vendor: alloc value 0xf41eb871
,09-16 11:50:44.357  5408  5421 I bt_vendor: init
09-16 11:50:44.362  5408  5421 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 11:50:44.362  5408  5421 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 11:50:44.472  5408  5421 D bt_hci  : start_up starting async portion
,09-16 11:50:44.472  5408  5428 I bt_hci  : event_finish_startup
09-16 11:50:44.473  5408  5428 I bt_hci_h4: hal_open
09-16 11:50:44.473  5408  5428 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 11:50:44.470  5429  5429 W irq/448-msm_hs_: type=1400 audit(0.0:109): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 11:50:44.476  5408  5428 I bt_userial_vendor: device fd = 54 open
,09-16 11:50:44.491  5408  5428 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 11:50:44.494  5408  5428 D bt_hwcfg: Chipset BCM4358A3
,09-16 11:50:44.494  5408  5428 D bt_hwcfg: Target name = [BCM4358A3]
09-16 11:50:44.494  5408  5428 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 11:50:44.661  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:50:45.008  5408  5428 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-16 11:50:45.008  5408  5428 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 11:50:45.008  5408  5428 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 11:50:45.133  5408  5428 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 11:50:45.133  5408  5428 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 11:50:45.135  5408  5428 I bt_hwcfg: vendor lib fwcfg completed
09-16 11:50:45.135  5408  5428 I bt_vendor: firmware callback
09-16 11:50:45.135  5408  5428 I bt_hci  : firmware_config_callback
,09-16 11:50:45.144  5408  5431 I bt_btu  : btu_task pending for preload complete event
,09-16 11:50:45.145  5408  5431 I bt_btu_task: Bluetooth chip preload is complete
09-16 11:50:45.146  5408  5431 I bt_btu  : btu_task received preload complete event
,09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 11:50:45.152  5408  5431 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 11:50:45.153  5408  5431 I         : BTE_InitTraceLevels -- TRC_GAP
,09-16 11:50:45.153  5408  5431 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 11:50:45.153  5408  5431 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 11:50:45.153  5408  5431 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 11:50:45.154  5408  5431 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 11:50:45.154  5408  5431 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 11:50:45.154  5408  5431 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 11:50:45.253  5408  5431 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
09-16 11:50:45.254  5408  5431 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,09-16 11:50:45.281  5408  5424 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 11:50:45.283  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 11:50:45.284  5408  5424 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 11:50:45.286  5408  5424 D BluetoothAdapterProperties: Name is: Nexus 6P
09-16 11:50:45.288  5408  5424 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:50:45.289  5408  5424 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 11:50:45.289  5408  5424 D bt_hci  : do_postload posting postload work item
09-16 11:50:45.289  5408  5428 I bt_hci  : event_postload
09-16 11:50:45.289  5408  5428 I bt_vendor: sco_config_cb
09-16 11:50:45.289  5408  5428 I bt_hci  : sco_config_callback postload finished.
,09-16 11:50:45.295  5408  5424 D bt_bte_conf: Device ID record 1 : primary
,09-16 11:50:45.295  5408  5424 D bt_bte_conf:   vendorId            = 000f
09-16 11:50:45.295  5408  5424 D bt_bte_conf:   vendorIdSource      = 0001
,09-16 11:50:45.295  5408  5424 D bt_bte_conf:   product             = 1200
09-16 11:50:45.295  5408  5424 D bt_bte_conf:   version             = 1436
09-16 11:50:45.295  5408  5424 D bt_bte_conf:   clientExecutableURL = 
09-16 11:50:45.295  5408  5424 D bt_bte_conf:   serviceDescription  = 
09-16 11:50:45.295  5408  5424 D bt_bte_conf:   documentationURL    = 
09-16 11:50:45.295  5408  5424 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 11:50:45.296  5408  5421 D bt_stack_manager: event_start_up_stack finished
09-16 11:50:45.296  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:45.296  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-16 11:50:45.297  5408  5420 D BluetoothAdapterProperties: Setting state to 15
09-16 11:50:45.297  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 11:50:45.301  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:45.302  5408  5420 I BluetoothAdapterState: Entering BleOnState
,09-16 11:50:45.304  5408  5420 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 11:50:45.305  5408  5420 D BluetoothAdapterProperties: Setting state to 11
09-16 11:50:45.305  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-16 11:50:45.306  5408  5428 I bt_vendor: low_power_mode_cb
09-16 11:50:45.310  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:50:45.311  5408  5408 D HeadsetService: Received start request. Starting profile...
09-16 11:50:45.314  5408  5408 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 11:50:45.314  5408  5408 D HeadsetStateMachine: make
,09-16 11:50:45.324  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:45.327  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:45.330   927   940 I ActivityManager: Start proc 5438:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-16 11:50:45.333  5408  5408 D HeadsetStateMachine: max_hf_connections = 1
09-16 11:50:45.333  5408  5408 I bt_bluedroid: get_profile_interface handsfree
09-16 11:50:45.333  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 11:50:45.333  5408  5424 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-16 11:50:45.335  5408  5420 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:50:45.336  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:50:45.337   927   927 D BluetoothA2dp: Proxy object connected
,09-16 11:50:45.337  5408  5408 D A2dpService: Received start request. Starting profile...
09-16 11:50:45.338  5408  5408 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 11:50:45.338  5408  5408 I bt_bluedroid: get_profile_interface avrcp
,09-16 11:50:45.344  5408  5408 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 11:50:45.344  5408  5408 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 11:50:45.344  5408  5408 D A2dpStateMachine: make
,09-16 11:50:45.346  5408  5408 I bt_bluedroid: get_profile_interface a2dp
09-16 11:50:45.346  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-16 11:50:45.348  5408  5408 I BluetoothHidServiceJni: classInitNative: succeeds
,09-16 11:50:45.348  5408  5451 D A2dpStateMachine: Enter Disconnected: -2
,09-16 11:50:45.348  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:50:45.350  3106  3106 D BluetoothInputDevice: Proxy object connected
09-16 11:50:45.351  3106  3106 D HidProfile: Bluetooth service connected
09-16 11:50:45.351  5408  5408 D HidService: Received start request. Starting profile...
09-16 11:50:45.351  5408  5408 I bt_bluedroid: get_profile_interface hidhost
09-16 11:50:45.352  5408  5424 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
09-16 11:50:45.352  5408  5408 D HidService: setHidService(): set to: null
09-16 11:50:45.352  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-16 11:50:45.352  5408  5408 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-16 11:50:45.354  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:50:45.355  5408  5408 D HealthService: Received start request. Starting profile...
09-16 11:50:45.358  5408  5408 I bt_bluedroid: get_profile_interface health
09-16 11:50:45.359  5408  5408 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-16 11:50:45.360  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:50:45.361  5408  5408 D PanService: Received start request. Starting profile...
,09-16 11:50:45.361  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:50:45.361  5408  5408 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 11:50:45.361  5408  5408 I bt_bluedroid: get_profile_interface pan
09-16 11:50:45.361  3106  3106 D PanProfile: Bluetooth service connected
09-16 11:50:45.361  5408  5424 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-16 11:50:45.364  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:50:45.365  5408  5408 D BluetoothMapService: Received start request. Starting profile...
,09-16 11:50:45.365  5408  5408 D BluetoothMapService: start()
09-16 11:50:45.367  3106  3106 D BluetoothMap: Proxy object connected
09-16 11:50:45.367  3106  3106 D MapProfile: Bluetooth service connected
09-16 11:50:45.367  3106  3106 D BluetoothMap: getConnectedDevices()
09-16 11:50:45.368  5408  5408 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-16 11:50:45.368  3106  3106 D BluetoothMap: Bluetooth is Not enabled
09-16 11:50:45.368  5408  5408 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 11:50:45.368  5408  5408 D BluetoothMapAppObserver: createReceiver()
,09-16 11:50:45.370  5408  5408 D BluetoothMapAppObserver: initObservers()
09-16 11:50:45.370  5408  5408 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 11:50:45.374  5408  5408 V SapService: SapBinder()
,09-16 11:50:45.374  5408  5408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:50:45.375  5408  5408 D SapService: Received start request. Starting profile...
09-16 11:50:45.375  5408  5408 V SapService: start()
09-16 11:50:45.376  5438  5438 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-16 11:50:45.377  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:45.378  5408  5436 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:45.378  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.379  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:45.380  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:45.380  5408  5408 V BluetoothAdapterState: isTurningOn()=true
09-16 11:50:45.380  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:45.380  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:50:45.380  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-16 11:50:45.380  5408  5420 D BluetoothAdapterProperties: ScanMode =  20
09-16 11:50:45.380  5408  5420 D BluetoothAdapterProperties: State =  11
09-16 11:50:45.381  5408  5420 D BluetoothAdapterProperties: Setting state to 12
09-16 11:50:45.381  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 11:50:45.381  5408  5420 I BluetoothAdapterState: Entering OnState
09-16 11:50:45.381  3106  3134 D BluetoothPan: onBluetoothStateChange on: true
09-16 11:50:45.382  5408  5424 D BluetoothAdapterProperties: Scan Mode:21
09-16 11:50:45.382  5408  5424 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 11:50:45.382  3106  3129 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 11:50:45.384   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:50:45.385  5357  5357 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 11:50:45.385   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:50:45.385  3525  3549 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 11:50:45.388  3106  3707 D BluetoothMap: onBluetoothStateChange: up=true
,09-16 11:50:45.389   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:50:45.389  3106  3134 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 11:50:45.389   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:50:45.389  5357  5357 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-16 11:50:45.390  5408  5408 D BluetoothMapService: onReceive
09-16 11:50:45.390  5408  5408 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:50:45.391  5408  5408 D BluetoothMapService: STATE_ON
,09-16 11:50:45.395  5408  5408 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 11:50:45.395  5408  5408 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 11:50:45.396  5357  5357 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-16 11:50:45.397   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:45.401  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:50:45.403  3106  3366 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-16 11:50:45.403  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:45.405  5408  5456 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:50:45.405  5408  5408 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:50:45.407  3106  3366 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-16 11:50:45.407  3106  3106 D BluetoothA2dp: Proxy object connected
09-16 11:50:45.407  5408  5456 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 11:50:45.407  5408  5456 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 11:50:45.408  5408  5408 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:45.409  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:50:45.410  5408  5408 D ObexServerSockets: Succeed to create listening sockets 
09-16 11:50:45.410  5408  5408 D ObexServerSockets0: startAccept()
09-16 11:50:45.410  5408  5408 D ObexServerSockets0: prepareForNewConnect()
09-16 11:50:45.411  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:45.411  5408  5408 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 11:50:45.411  5408  5408 D BluetoothSdpJni: SDP Create record success - handle: 1
09-16 11:50:45.412  5408  5459 D ObexServerSockets0: Accepting socket connection...
09-16 11:50:45.412  5408  5460 D ObexServerSockets0: Accepting socket connection...
09-16 11:50:45.413  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:45.413  5408  5408 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 11:50:45.413  5408  5408 D ObexServerSockets0: prepareForNewConnect()
,09-16 11:50:45.414  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:45.423   927   937 I ActivityManager: Killing 4804:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-16 11:50:45.454  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:50:45.466   927  3545 I ActivityManager: Start proc 5461:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 11:50:45.485   927   944 D BluetoothHeadset: Proxy object connected
,09-16 11:50:45.487  3525  3551 D BluetoothHeadset: Proxy object connected
,09-16 11:50:45.488   927   944 D BluetoothHeadset: Proxy object connected
,09-16 11:50:45.489   927   944 D BluetoothHeadset: Proxy object connected
,09-16 11:50:45.497  5461  5461 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 11:50:45.510  3106  3707 D BluetoothHeadset: Proxy object connected
,09-16 11:50:45.511  3106  3106 D HeadsetProfile: Bluetooth service connected
,09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.k.d(PG:583)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.677  5461  5461 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:50:45.677  5461  5461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:50:45.683  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:50:45.691  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 11:50:45.691   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6ca371:true
09-16 11:50:45.698  3106  3106 D BluetoothPbap: Proxy object connected
09-16 11:50:45.698  3106  3106 D PbapServerProfile: Bluetooth service connected
09-16 11:50:45.706  5438  5438 D LocalBluetoothProfileManager: Adding local A2DP profile
09-16 11:50:45.707  5408  5488 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:50:45.720  5408  5493 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:50:45.722  5408  5493 I BtOppRfcommListener: Accept thread started.
09-16 11:50:45.723  5438  5438 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-16 11:50:45.738  5438  5438 D LocalBluetoothProfileManager: Adding local MAP profile
09-16 11:50:45.739  5438  5438 D BluetoothMap: Create BluetoothMap proxy object
09-16 11:50:45.756  5438  5438 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 11:50:45.762  5438  5438 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:50:45.763  5438  5438 D BluetoothA2dp: Proxy object connected
,09-16 11:50:45.767  5438  5438 D BluetoothInputDevice: Proxy object connected
,09-16 11:50:45.767  5438  5438 D HidProfile: Bluetooth service connected
,09-16 11:50:45.774  5438  5438 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:50:45.775  5438  5438 D PanProfile: Bluetooth service connected
09-16 11:50:45.775  5438  5438 D BluetoothMap: Proxy object connected
,09-16 11:50:45.775  5438  5438 D MapProfile: Bluetooth service connected
09-16 11:50:45.775  5438  5438 D BluetoothMap: getConnectedDevices()
,09-16 11:50:45.777  5438  5438 D BluetoothPbap: Proxy object connected
09-16 11:50:45.778  5438  5438 D PbapServerProfile: Bluetooth service connected
,09-16 11:50:45.779   927  3420 I ActivityManager: Killing 4227:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-16 11:50:45.826  5438  5450 D BluetoothHeadset: Proxy object connected
09-16 11:50:45.827  5438  5438 D HeadsetProfile: Bluetooth service connected
,09-16 11:50:45.894  5461  5497 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-16 11:50:45.973  5461  5483 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 11:50:45.982   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49e4fb7:true
,09-16 11:50:46.368  3613  5504 V NQFileLogger: [150] e.a: about to write to file
,09-16 11:50:46.372  3613  5504 V ProcessReports: [150] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,09-16 11:50:47.085   389   389 I MSM-irqbalance: Discovered a new IRQ: 146
,09-16 11:50:47.088   389   389 I MSM-irqbalance: Discovered a new IRQ: 271
,09-16 11:50:48.823   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:49.200  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:50:49.200  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd55175 added. We now have 4 listener(s)
09-16 11:50:49.200  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:50:49.213  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:50:49.213  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd55175 removed from the list
,09-16 11:50:49.213  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:49.214  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:50:49.214  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:49.216  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:50:49.216  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b23850a added. We now have 4 listener(s)
,09-16 11:50:49.216  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:50:49.221  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:50:49.222  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b23850a removed from the list
09-16 11:50:49.222  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:50:49.222  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:50:49.222  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:50:49.224  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:50:49.224  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64e17b added. We now have 4 listener(s)
09-16 11:50:49.224  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:50:49.229   927  3147 D WifiService: setWifiEnabled: false pid=5357, uid=10077
,09-16 11:50:49.229   927  3147 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 11:50:49.233   927  2964 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 11:50:49.233   927  2964 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 11:50:49.234   927  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 11:50:49.234   927  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 11:50:49.238  5408  5420 D BluetoothAdapterState: Current state: ON, message: 23
09-16 11:50:49.238  5408  5420 D BluetoothAdapterProperties: Setting state to 13
09-16 11:50:49.238  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 11:50:49.240  5408  5420 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 11:50:49.241  5408  5420 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:50:49.246  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:50:49.251  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.251   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-16 11:50:49.251   927  5110 D DhcpClient: Clearing IP address
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:49.251  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:49.252  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.252  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:49.252  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:50:49.253  5408  5424 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:50:49.253  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-16 11:50:49.256  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.257  5408  5408 D BluetoothMapService: onReceive
09-16 11:50:49.258  5408  5408 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:50:49.258  5408  5408 D BluetoothMapService: STATE_TURNING_OFF
,09-16 11:50:49.258  5408  5408 D BluetoothMapService: MAP Service closeService in
09-16 11:50:49.258  5408  5408 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 11:50:49.258  5408  5408 D ObexServerSockets0: shutdown(block = true)
09-16 11:50:49.258   507   920 D CommandListener: Setting iface cfg
09-16 11:50:49.259  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.260  5408  5408 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 11:50:49.260  5408  5408 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 11:50:49.261  5408  5460 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 11:50:49.262  5408  5459 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 11:50:49.262  5408  5433 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 11:50:49.263  5408  5408 I BtOppRfcommListener: stopping Accept Thread
09-16 11:50:49.264  5408  5493 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-16 11:50:49.264  5408  5493 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 11:50:49.265   927  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 11:50:49.265   927  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-16 11:50:49.267  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:50:49.267  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:49.269  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:50:49.269  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.269  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:50:49.271   927  5111 D DhcpClient: Receive thread stopped
,09-16 11:50:49.274  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.274  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:50:49.274  5408  5408 D HeadsetService: Received stop request...Stopping profile...
09-16 11:50:49.275  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.275  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:50:49.276   533   533 E Parcel  : Reading a NULL string not supported here.
,09-16 11:50:49.278  3613  5163 V NativeCrypto: Read error: ssl=0x7f88142e00: I/O error during system call, Connection timed out
,09-16 11:50:49.279   927  2966 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-16 11:50:49.279   927   927 D RttService: SCAN_AVAILABLE : 1
09-16 11:50:49.279   927  3071 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:50:49.281  3483  3655 W QCNEJ   : |CORE| network lost: 100
,09-16 11:50:49.281  3525  3551 D BluetoothHeadset: Proxy object disconnected
09-16 11:50:49.281  3483  3655 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 11:50:49.282  3106  3129 D BluetoothHeadset: Proxy object disconnected
09-16 11:50:49.282  5408  5408 D A2dpService: Received stop request...Stopping profile...
09-16 11:50:49.282  5408  5451 D A2dpStateMachine: Exit Disconnected: -1
09-16 11:50:49.282  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.282  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:50:49.283  5438  5449 D BluetoothHeadset: Proxy object disconnected
09-16 11:50:49.283   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 11:50:49.283   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 11:50:49.283   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 11:50:49.283  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.283  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:49.283   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 11:50:49.284  5408  5408 D HidService: Received stop request...Stopping profile...
09-16 11:50:49.284  3613  5163 V NativeCrypto: SSL shutdown failed: ssl=0x7f88142e00: I/O error during system call, Broken pipe
,09-16 11:50:49.285  5408  5408 D HidService: Stopping Bluetooth HidService
,09-16 11:50:49.287  3106  3106 D HeadsetProfile: Bluetooth service disconnected
09-16 11:50:49.288  5408  5408 D HealthService: Received stop request...Stopping profile...
09-16 11:50:49.289  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.289  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:49.289  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.289  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:49.291  5408  5408 D PanService: Received stop request...Stopping profile...
09-16 11:50:49.292  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.292  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:49.293  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.293  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.293  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.293  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:49.295  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50,:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.295  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:50:49.297  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:50:49.297  3106  3106 D BluetoothA2dp: Proxy object disconnected
09-16 11:50:49.297   927  2964 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 11:50:49.297  3106  3106 D BluetoothInputDevice: Proxy object disconnected
09-16 11:50:49.298  3106  3106 D HidProfile: Bluetooth service disconnected
09-16 11:50:49.299  3106  3106 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:50:49.299  3106  3106 D PanProfile: Bluetooth service disconnected
09-16 11:50:49.299  5408  5408 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 11:50:49.300  5408  5408 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 11:50:49.300  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 11:50:49.300  5408  5431 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:50:49.300  5408  5431 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:50:49.300  5408  5431 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:50:49.300  5438  5438 D DockEventReceiver: finishStartingService: stopping service
09-16 11:50:49.301  5408  5408 D BluetoothMapService: Received stop request...Stopping profile...
09-16 11:50:49.301  5408  5408 D BluetoothMapService: stop()
09-16 11:50:49.301  5408  5424 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 11:50:49.301  5408  5408 D BluetoothMapAppObserver: deinitObservers()
09-16 11:50:49.301  5408  5408 D BluetoothMapAppObserver: removeReceiver()
09-16 11:50:49.302  5438  5438 D HeadsetProfile: Bluetooth service disconnected
09-16 11:50:49.302  5438  5438 D BluetoothA2dp: Proxy object disconnected
09-16 11:50:49.302  5438  5438 D BluetoothInputDevice: Proxy object disconnected
09-16 11:50:49.302  5438  5438 D HidProfile: Bluetooth service disconnected
09-16 11:50:49.303  5438  5438 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:50:49.303  5438  5438 D PanProfile: Bluetooth service disconnected
,09-16 11:50:49.303  5438  5438 D BluetoothMap: Proxy object disconnected
09-16 11:50:49.303  5438  5438 D MapProfile: Bluetooth service disconnected
09-16 11:50:49.304  5408  5408 D SapService: Received stop request...Stopping profile...
09-16 11:50:49.304  5408  5408 V SapService: stop()
09-16 11:50:49.305  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.305  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.305  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.305  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:50:49.307  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 11:50:49.307  5408  5431 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:50:49.307  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.307  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.307  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.307  5408  5431 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:50:49.307  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:49.307  5408  5431 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 11:50:49.307  5408  5431 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-16 11:50:49.307  5408  5431 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 11:50:49.307  5408  5431 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 11:50:49.307  5408  5408 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 11:50:49.307  5408  5408 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 11:50:49.308  5408  5424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 11:50:49.308  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.308  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.308  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.308  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:49.308  5408  5408 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 11:50:49.308  5408  5408 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 11:50:49.309   927  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 11:50:49.309  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.309  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.310  5408  5424 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 11:50:49.310  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:50:49.310  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:49.311  5408  5408 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 11:50:49.311  5408  5408 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 11:50:49.312  3106  3106 D BluetoothMap: Proxy object disconnected
09-16 11:50:49.312  3106  3106 D MapProfile: Bluetooth service disconnected
09-16 11:50:49.312  3106  3106 D BluetoothPbap: Proxy object disconnected
09-16 11:50:49.312  3106  3106 D PbapServerProfile: Bluetooth service disconnected
09-16 11:50:49.313  5438  5438 D BluetoothPbap: Proxy object disconnected
09-16 11:50:49.313  5438  5438 D PbapServerProfile: Bluetooth service disconnected
09-16 11:50:49.313  5408  5408 D BluetoothMapService: MAP Service closeService in
09-16 11:50:49.313  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.313  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.313  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.313  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:49.314  5408  5408 D BluetoothMapService: cleanup()
09-16 11:50:49.314  5408  5408 D BluetoothMapService: MAP Service closeService in
,09-16 11:50:49.314  5408  5408 V BluetoothAdapterState: isTurningOff()=true
09-16 11:50:49.314  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.314  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.314  5408  5408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:50:49.314  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-16 11:50:49.314  5408  5420 D BluetoothAdapterProperties: Setting state to 15
09-16 11:50:49.314  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 11:50:49.315  5408  5420 I BluetoothAdapterState: Entering BleOnState
09-16 11:50:49.316  5438  5450 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 11:50:49.316   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 11:50:49.317  5438  5449 D BluetoothMap: onBluetoothStateChange: up=false
09-16 11:50:49.318  3106  3707 D BluetoothPan: onBluetoothStateChange on: false
09-16 11:50:49.318  5438  5450 D BluetoothPan: onBluetoothStateChange on: false
09-16 11:50:49.319  3106  3134 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:50:49.320  3106  3129 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 11:50:49.321   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:50:49.321  3106  3707 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 11:50:49.321   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:50:49.322  3525  3917 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:50:49.322  3106  3134 D BluetoothMap: onBluetoothStateChange: up=false
09-16 11:50:49.323   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:50:49.323  3106  3129 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 11:50:49.323   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:50:49.324  5438  5449 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 11:50:49.324  5438  5450 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 11:50:49.324  5438  5449 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 11:50:49.325  5408  5420 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 11:50:49.325  5408  5420 D BluetoothAdapterProperties: Setting state to 16
09-16 11:50:49.325  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 11:50:49.326  5408  5420 D BluetoothAdapterProperties: onBleDisable
09-16 11:50:49.326  5408  5420 I BluetoothAdapterState: Entering PendingCommandState
09-16 11:50:49.327  5408  5421 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 11:50:49.327  5408  5431 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 11:50:49.327  5408  5431 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:50:49.328  5408  5424 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:50:49.328  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:49.330  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.331  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:50:49.332  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.334  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.335  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.336  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.337  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:50:49.340  5438  5438 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:50:49.348   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 11:50:49.349   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-16 11:50:49.349   507   920 D TetherController: Setting IP forward enable = 0
,09-16 11:50:49.351   927  2966 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-16 11:50:49.351   927  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 11:50:49.355  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.355   927  2964 D DhcpClient: doQuit
09-16 11:50:49.355   927  2964 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 11:50:49.355   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 11:50:49.356   927  5110 D DhcpClient: onQuitting
09-16 11:50:49.356  3624  3624 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 11:50:49.356  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:49.358  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.358  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:50:49.359  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.359  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:49.361  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.361  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:49.361  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.361  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:49.363  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:49.363  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:49.364  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:49.364  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:50:49.365  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.366  4763  4763 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-16 11:50:49.368  4829  4851 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-16 11:50:49.368  4829  4851 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-16 11:50:49.368  4829  4851 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 11:50:49.368  4829  4851 E SarControlService: no key has been found,reset the power
09-16 11:50:49.369  4829  4871 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 11:50:49.369  4829  4871 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 11:50:49.369  4829  4871 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-16 11:50:49.369  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 11:50:49.369  4859  4859 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 11:50:49.370  4829  4871 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 11:50:49.371  4829  4871 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 11:50:49.372  4829  4871 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 11:50:49.373  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 11:50:49.373  4859  4859 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 11:50:49.376  4859  4873 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ae3c712 HexData = [00000000ea03000000000000ffffffff]
09-16 11:50:49.376  4859  4873 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 11:50:49.376  4859  4873 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-16 11:50:49.376  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 11:50:49.376  4829  4839 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 11:50:49.378  3624  3624 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-16 11:50:49.380  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-16 11:50:49.383  4859  4873 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ae3c712 HexData = [00000000eb03000000000000ffffffff]
09-16 11:50:49.383  4859  4873 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 11:50:49.383  4859  4873 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-16 11:50:49.384  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-16 11:50:49.384  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 11:50:49.384  4829  4840 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 11:50:49.385  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 11:50:49.387  3624  3624 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 11:50:49.388  3893  5134 I iu.UploadsManager: num queued entries: 0
09-16 11:50:49.388  3893  5134 I iu.UploadsManager: num updated entries: 0
09-16 11:50:49.389  5137  5137 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 11:50:49.389  3893  5134 I iu.SyncManager: NEXT; no task
,09-16 11:50:49.394  5137  5137 D SprintDMHelper: simOperator: 
09-16 11:50:49.394  5137  5137 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 11:50:49.404  4287  5529 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 11:50:49.415   507   920 E Netd    : netlink response contains error (No such file or directory)
,09-16 11:50:49.415   507   920 D TetherController: Setting IP forward enable = 0
,09-16 11:50:49.418  3624  3624 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 11:50:49.418   927   938 I ActivityManager: Start proc 5531:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-16 11:50:49.427  3624  3624 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 11:50:49.441   927  2964 D wifi    : In wifi stop Hal
,09-16 11:50:49.441   927  2964 D wifi    : halHandle = 0x7f6d37bf20, mVM = 0x7f899cd140, mCls = 0x100b0a
09-16 11:50:49.441  4287  4287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 11:50:49.441   927  3617 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 11:50:49.441   927  3617 D WifiHAL : Got a signal to exit!!!
09-16 11:50:49.441   927  3617 I WifiHAL : Exit wifi_event_loop
09-16 11:50:49.442   927  2964 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-16 11:50:49.442   927  2964 E WifiHAL : Event processing terminated
09-16 11:50:49.442   927  2964 D wifi    : In wifi cleaned up handler
,09-16 11:50:49.442   927  2964 I WifiHAL : Internal cleanup completed
09-16 11:50:49.443  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:49.445  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.446  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:49.446  3449  4027 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 11:50:49.454  5531  5531 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-16 11:50:49.466   927  3617 D wifi    : set interface wlan0 flags (DOWN)
,09-16 11:50:49.466   927  2964 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 11:50:49.533  5408  5424 I bt_hci  : shut_down
,09-16 11:50:49.538  5408  5428 D bt_hwcfg: hw_epilog_process
,09-16 11:50:49.538  5408  5428 I bt_vendor: low_power_mode_cb
,09-16 11:50:49.540  5408  5428 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-16 11:50:49.540  5408  5428 I bt_vendor: epilog_cb
09-16 11:50:49.540  5408  5428 I bt_hci  : epilog_finished_callback
,09-16 11:50:49.542  5408  5424 I bt_hci_h4: hal_close
,09-16 11:50:49.542  5408  5424 I bt_userial_vendor: device fd = 54 close
,09-16 11:50:49.652  5408  5421 D bt_stack_manager: event_shut_down_stack finished.
,09-16 11:50:49.652  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 11:50:49.654  5408  5408 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 11:50:49.654  5408  5420 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 11:50:49.655  5408  5408 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 11:50:49.655  5408  5408 D BtGatt.GattService: stop()
,09-16 11:50:49.655  5408  5408 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 11:50:49.657  5408  5408 V BluetoothAdapterState: isTurningOff()=false
09-16 11:50:49.657  5408  5408 V BluetoothAdapterState: isTurningOn()=false
09-16 11:50:49.657  5408  5408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:50:49.657  5408  5408 V BluetoothAdapterState: isBleTurningOff()=true
09-16 11:50:49.658  5408  5420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 11:50:49.658  5408  5420 D BluetoothAdapterProperties: Setting state to 10
09-16 11:50:49.658  5408  5420 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 11:50:49.658  5408  5420 I BluetoothAdapterState: Entering OffState
,09-16 11:50:49.659   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 11:50:49.667  5408  5408 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 11:50:49.667  5408  5408 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-16 11:50:49.667  5408  5408 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 11:50:49.669   927   944 D Tethering: InitialState.processMessage what=4
09-16 11:50:49.669  5408  5421 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-16 11:50:49.672   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 11:50:49.677  5408  5408 I art     : System.exit called, status: 0
09-16 11:50:49.677  5408  5408 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 11:50:49.703   927  3427 I ActivityManager: Process com.android.bluetooth (pid 5408) has died
,09-16 11:50:49.824   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:50.825   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:51.357   927  3919 I ActivityManager: Killing 4517:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-16 11:50:51.825   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:52.827   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:50:53.827   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:50:54.255   927   937 D WifiService: setWifiEnabled: true pid=5357, uid=10077
,09-16 11:50:54.255   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 11:50:54.264   507   920 D SoftapController: Softap fwReload - Ok
,09-16 11:50:54.268   507   920 D CommandListener: Setting iface cfg
,09-16 11:50:54.268   507   920 D CommandListener: Trying to bring down wlan0
,09-16 11:50:54.270   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:50:54.274   927  2964 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 11:50:54.859   927  2964 D wifi    : set interface wlan0 flags (UP)
09-16 11:50:54.862   927  2964 I WifiHAL : Initializing wifi
09-16 11:50:54.862   927  2964 I WifiHAL : Creating socket
,09-16 11:50:54.869   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 11:50:54.870   927  2964 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-16 11:50:54.870   927  2964 D wifi    : Did set static halHandle = 0x7f6d37bf20
,09-16 11:50:54.871   927  2964 D wifi    : halHandle = 0x7f6d37bf20, mVM = 0x7f899cd140, mCls = 0x1017fa
,09-16 11:50:54.871   927  2964 D wifi    : array field set
09-16 11:50:54.871   927  2964 I WifiNative-HAL: interface[0] = wlan0
,09-16 11:50:54.874   927  5550 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547293216544
,09-16 11:50:54.874   927  5550 D wifi    : waitForHalEvents called, vm = 0x7f899cd140, obj = 0x1017fa, env = 0x7f69e196c0
09-16 11:50:54.877   927  2964 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 11:50:54.878   927  2964 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-16 11:50:54.880  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:54.881  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:54.882  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:50:54.954  5551  5551 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 11:50:54.975  5551  5551 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 11:50:54.986  5551  5551 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-16 11:50:54.986  5551  5551 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 11:50:55.892  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:55.892  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:50:55.892  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:55.893  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:55.893   927  2964 D WifiConfigStore: Loading config and enabling all networks 
,09-16 11:50:55.896  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:55.896  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:55.896  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:55.897  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:55.899  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:55.899  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:55.899  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:55.899  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:50:55.911   927  2964 D WifiConfigStore: loaded 0 passpoint configs
09-16 11:50:55.912   927  2964 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 11:50:55.912   927  2964 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 11:50:55.914   927  2964 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 11:50:55.915   927  2964 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 11:50:55.915   927  2964 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 11:50:55.915   927  2964 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 11:50:55.915   927  2964 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 11:50:55.920   927  2964 D WifiNative-HAL: Setting external_sim to 1
,09-16 11:50:55.920  4287  4287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 11:50:55.920   927  2964 D wifi    : setting dfs flag to true, 0x7f6e3feee0
09-16 11:50:55.921   927  2964 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 11:50:55.921   927  2964 D wifi    : setting scan oui 0x7f6e3feee0
09-16 11:50:55.921   927  2964 D WifiHAL : Sending mac address OUI
,09-16 11:50:55.926   927  2964 E native  : do suspend false
,09-16 11:50:55.933   927  2964 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-16 11:50:55.933   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-16 11:50:55.934   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 11:50:55.934   927  3071 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 11:50:55.935   507   920 D CommandListener: Setting iface cfg
,09-16 11:50:55.939   927  2963 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-16 11:50:55.939   927  2963 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 11:50:55.948   927  2963 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 11:50:55.953   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=361619 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-16 11:50:55.953   927  2963 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 11:50:59.175  5551  5551 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 11:50:59.184  5551  5551 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 11:50:59.189  5551  5551 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 11:50:59.195  5551  5551 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 11:50:59.200  5551  5551 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 11:50:59.222   927  2964 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 11:50:59.223   927  2964 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-16 11:50:59.223   927  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 11:50:59.232   927  2964 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 11:50:59.262   927  3421 D WifiService: setWifiEnabled: false pid=5357, uid=10077
,09-16 11:50:59.262   927  3421 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 11:50:59.266   927  2964 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 11:50:59.268  5551  5551 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 11:50:59.281   927   927 D RttService: SCAN_AVAILABLE : 1
09-16 11:50:59.281   927  3071 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 11:50:59.291   927  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 11:50:59.291   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:50:59.296   927  2964 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 11:50:59.297  5551  5551 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-16 11:50:59.305  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:59.306  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:59.306  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:59.306  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:50:59.307  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:59.307  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:59.307  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:59.307  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:50:59.308  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:50:59.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:50:59.308  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:50:59.308  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:50:59.312  5551  5551 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-16 11:50:59.315  5551  5551 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,09-16 11:50:59.321  5551  5551 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 11:50:59.324  5551  5551 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 11:50:59.427  4287  4287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 11:50:59.427   927  2964 D wifi    : In wifi stop Hal
09-16 11:50:59.428   927  2964 D wifi    : halHandle = 0x7f6d37bf20, mVM = 0x7f899cd140, mCls = 0x1017fa
09-16 11:50:59.428   927  5550 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 11:50:59.428   927  5550 D WifiHAL : Got a signal to exit!!!
,09-16 11:50:59.428   927  5550 I WifiHAL : Exit wifi_event_loop
09-16 11:50:59.432  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:59.433   927  2964 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-16 11:50:59.433   927  2964 E WifiHAL : Event processing terminated
09-16 11:50:59.434   927  2964 D wifi    : In wifi cleaned up handler
,09-16 11:50:59.434   927  2964 I WifiHAL : Internal cleanup completed
09-16 11:50:59.435  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:59.437  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:50:59.441  3449  4027 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 11:50:59.472   927  5550 D wifi    : set interface wlan0 flags (DOWN)
,09-16 11:50:59.472   927  2964 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 11:50:59.679   927   944 D Tethering: InitialState.processMessage what=4
,09-16 11:50:59.686   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 11:51:03.828   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:04.308   927   944 I ActivityManager: Start proc 5555:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 11:51:04.406  5555  5555 D AdapterServiceConfig: Adding HeadsetService
09-16 11:51:04.406  5555  5555 D AdapterServiceConfig: Adding A2dpService
,09-16 11:51:04.407  5555  5555 D AdapterServiceConfig: Adding HidService
09-16 11:51:04.407  5555  5555 D AdapterServiceConfig: Adding HealthService
,09-16 11:51:04.407  5555  5555 D AdapterServiceConfig: Adding PanService
09-16 11:51:04.407  5555  5555 D AdapterServiceConfig: Adding GattService
09-16 11:51:04.407  5555  5555 D AdapterServiceConfig: Adding BluetoothMapService
09-16 11:51:04.407  5555  5555 D AdapterServiceConfig: Adding SapService
,09-16 11:51:04.418   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f8afa2:true
09-16 11:51:04.418  5555  5555 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 11:51:04.421  5555  5555 I bt_bluedroid: init
,09-16 11:51:04.422  5555  5567 I BluetoothAdapterState: Entering OffState
,09-16 11:51:04.424  5555  5568 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 11:51:04.424  5555  5568 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 11:51:04.425  5555  5568 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 11:51:04.425  5555  5568 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-16 11:51:04.425  5555  5555 I bt_bluedroid: get_profile_interface socket
,09-16 11:51:04.427  5555  5571 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 11:51:04.427  5555  5555 I bt_bluedroid: get_profile_interface sdp
09-16 11:51:04.428  5555  5571 D BluetoothAdapterProperties: Name is: Nexus 6P
09-16 11:51:04.432  5555  5566 I bt_bluedroid: config_hci_snoop_log
,09-16 11:51:04.433   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 11:51:04.438  5555  5567 D BluetoothAdapterState: Current state: OFF, message: 0
09-16 11:51:04.438  5555  5567 D BluetoothAdapterProperties: Setting state to 14
09-16 11:51:04.438  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 11:51:04.439  5555  5567 D BluetoothBondStateMachine: make
,09-16 11:51:04.441  5555  5572 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:51:04.443  5555  5567 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:51:04.444  5555  5555 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-16 11:51:04.446  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:04.447  5555  5555 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 11:51:04.447  5555  5555 D BtGatt.GattService: Received start request. Starting profile...
09-16 11:51:04.448  5555  5555 D BtGatt.GattService: start()
09-16 11:51:04.448  5555  5555 I bt_bluedroid: get_profile_interface gatt
,09-16 11:51:04.449  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:04.449  5555  5555 D BtGatt.AdvertiseManager: advertise manager created
,09-16 11:51:04.453  5555  5555 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:51:04.453  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:04.453  5555  5555 V BluetoothAdapterState: isBleTurningOn()=true
09-16 11:51:04.453  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:04.454  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 11:51:04.455  5555  5567 I bt_bluedroid: bt_bluedroid
09-16 11:51:04.455  5555  5568 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 11:51:04.456  5555  5568 I bt_hci  : start_up
,09-16 11:51:04.460  5555  5568 I bt_vendor: alloc value 0xf41eb871
,09-16 11:51:04.460  5555  5568 I bt_vendor: init
09-16 11:51:04.460  5555  5568 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 11:51:04.460  5555  5568 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 11:51:04.576  5555  5568 D bt_hci  : start_up starting async portion
09-16 11:51:04.577  5555  5575 I bt_hci  : event_finish_startup
,09-16 11:51:04.577  5555  5575 I bt_hci_h4: hal_open
09-16 11:51:04.577  5555  5575 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 11:51:04.581  5555  5575 I bt_userial_vendor: device fd = 54 open
,09-16 11:51:04.574  5576  5576 W irq/448-msm_hs_: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 11:51:04.598  5555  5575 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 11:51:04.601  5555  5575 D bt_hwcfg: Chipset BCM4358A3
,09-16 11:51:04.601  5555  5575 D bt_hwcfg: Target name = [BCM4358A3]
,09-16 11:51:04.602  5555  5575 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 11:51:04.830   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:05.116  5555  5575 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 11:51:05.117  5555  5575 D bt_hwcfg: Settlement delay -- 100 ms
09-16 11:51:05.117  5555  5575 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 11:51:05.254  5555  5575 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 11:51:05.254  5555  5575 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 11:51:05.256  5555  5575 I bt_hwcfg: vendor lib fwcfg completed
,09-16 11:51:05.256  5555  5575 I bt_vendor: firmware callback
09-16 11:51:05.256  5555  5575 I bt_hci  : firmware_config_callback
,09-16 11:51:05.266  5555  5578 I bt_btu  : btu_task pending for preload complete event
,09-16 11:51:05.267  5555  5578 I bt_btu_task: Bluetooth chip preload is complete
09-16 11:51:05.267  5555  5578 I bt_btu  : btu_task received preload complete event
,09-16 11:51:05.274  5555  5578 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 11:51:05.274  5555  5578 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-16 11:51:05.274  5555  5578 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 11:51:05.274  5555  5578 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-16 11:51:05.274  5555  5578 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_BTM
,09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 11:51:05.275  5555  5578 I         : BTE_InitTraceLevels -- TRC_SMP
,09-16 11:51:05.276  5555  5578 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-16 11:51:05.276  5555  5578 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 11:51:05.364  5555  5578 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
,09-16 11:51:05.364  5555  5578 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,09-16 11:51:05.379  5555  5571 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 11:51:05.380  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 11:51:05.381  5555  5571 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 11:51:05.383  5555  5571 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 11:51:05.386  5555  5571 D BluetoothAdapterProperties: Scan Mode:20
,09-16 11:51:05.387  5555  5571 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-16 11:51:05.387  5555  5571 D bt_hci  : do_postload posting postload work item
,09-16 11:51:05.387  5555  5575 I bt_hci  : event_postload
09-16 11:51:05.387  5555  5575 I bt_vendor: sco_config_cb
09-16 11:51:05.387  5555  5575 I bt_hci  : sco_config_callback postload finished.
09-16 11:51:05.389  5555  5571 D bt_bte_conf: Device ID record 1 : primary
09-16 11:51:05.390  5555  5571 D bt_bte_conf:   vendorId            = 000f
09-16 11:51:05.390  5555  5571 D bt_bte_conf:   vendorIdSource      = 0001
09-16 11:51:05.390  5555  5571 D bt_bte_conf:   product             = 1200
09-16 11:51:05.390  5555  5571 D bt_bte_conf:   version             = 1436
,09-16 11:51:05.390  5555  5571 D bt_bte_conf:   clientExecutableURL = 
09-16 11:51:05.390  5555  5571 D bt_bte_conf:   serviceDescription  = 
09-16 11:51:05.390  5555  5571 D bt_bte_conf:   documentationURL    = 
09-16 11:51:05.390  5555  5571 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 11:51:05.390  5555  5568 D bt_stack_manager: event_start_up_stack finished
09-16 11:51:05.391  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 11:51:05.391  5555  5567 D BluetoothAdapterProperties: Setting state to 15
09-16 11:51:05.391  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 11:51:05.392  5555  5567 I BluetoothAdapterState: Entering BleOnState
,09-16 11:51:05.396  5555  5575 I bt_vendor: low_power_mode_cb
,09-16 11:51:05.397  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:05.398  5555  5567 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-16 11:51:05.398  5555  5567 D BluetoothAdapterProperties: Setting state to 11
09-16 11:51:05.398  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 11:51:05.399  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:05.401  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:05.403  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:05.404  5555  5555 D HeadsetService: Received start request. Starting profile...
,09-16 11:51:05.406  5555  5555 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 11:51:05.407  5555  5555 D HeadsetStateMachine: make
,09-16 11:51:05.412  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:05.415  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:05.417  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:05.418  5555  5567 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:51:05.421  5555  5555 D HeadsetStateMachine: max_hf_connections = 1
,09-16 11:51:05.421  5555  5555 I bt_bluedroid: get_profile_interface handsfree
09-16 11:51:05.421  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 11:51:05.421  5555  5571 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-16 11:51:05.424  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:05.425  5555  5555 D A2dpService: Received start request. Starting profile...
,09-16 11:51:05.426  5555  5555 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 11:51:05.427  5555  5555 I bt_bluedroid: get_profile_interface avrcp
,09-16 11:51:05.432  5555  5555 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 11:51:05.432  5555  5555 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 11:51:05.432  5555  5555 D A2dpStateMachine: make
,09-16 11:51:05.433  5555  5555 I bt_bluedroid: get_profile_interface a2dp
09-16 11:51:05.434  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-16 11:51:05.435  5555  5586 D A2dpStateMachine: Enter Disconnected: -2
09-16 11:51:05.435  5555  5555 I BluetoothHidServiceJni: classInitNative: succeeds
09-16 11:51:05.436  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:05.436  5555  5555 D HidService: Received start request. Starting profile...
09-16 11:51:05.437  5555  5555 I bt_bluedroid: get_profile_interface hidhost
09-16 11:51:05.437  5555  5555 D HidService: setHidService(): set to: null
09-16 11:51:05.437  5555  5571 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
09-16 11:51:05.437  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-16 11:51:05.438  5555  5555 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-16 11:51:05.439  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:05.440  5555  5555 D HealthService: Received start request. Starting profile...
09-16 11:51:05.440  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:51:05.441  5555  5555 I bt_bluedroid: get_profile_interface health
,09-16 11:51:05.442  5555  5555 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-16 11:51:05.443  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:05.443  5555  5555 D PanService: Received start request. Starting profile...
09-16 11:51:05.443  5555  5555 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 11:51:05.443  5555  5555 I bt_bluedroid: get_profile_interface pan
,09-16 11:51:05.444  5555  5571 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-16 11:51:05.447  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:05.448  5555  5555 D BluetoothMapService: Received start request. Starting profile...
,09-16 11:51:05.448  5555  5555 D BluetoothMapService: start()
09-16 11:51:05.450  5555  5555 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 11:51:05.451  5555  5555 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-16 11:51:05.451  5555  5555 D BluetoothMapAppObserver: createReceiver()
,09-16 11:51:05.453  5555  5555 D BluetoothMapAppObserver: initObservers()
,09-16 11:51:05.453  5555  5555 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 11:51:05.459  5555  5555 V SapService: SapBinder()
,09-16 11:51:05.459  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:05.459  5555  5555 D SapService: Received start request. Starting profile...
09-16 11:51:05.459  5555  5555 V SapService: start()
,09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:05.461  5555  5584 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:05.461  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:05.462  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:05.463  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:05.463  5555  5555 V BluetoothAdapterState: isTurningOn()=true
,09-16 11:51:05.463  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:05.463  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 11:51:05.465  5555  5555 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:51:05.465  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:05.465  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:05.465  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:05.466  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 11:51:05.466  5555  5567 D BluetoothAdapterProperties: ScanMode =  20
09-16 11:51:05.466  5555  5567 D BluetoothAdapterProperties: State =  11
09-16 11:51:05.468  5555  5571 D BluetoothAdapterProperties: Scan Mode:21
09-16 11:51:05.468  5555  5567 D BluetoothAdapterProperties: Setting state to 12
09-16 11:51:05.468  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 11:51:05.468  5555  5571 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 11:51:05.468  5438  5450 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 11:51:05.470  5555  5567 I BluetoothAdapterState: Entering OnState
09-16 11:51:05.470  5438  5449 D BluetoothMap: onBluetoothStateChange: up=true
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:05.471  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:51:05.472  3106  3134 D BluetoothPan: onBluetoothStateChange on: true
09-16 11:51:05.474  5438  5449 D BluetoothPan: onBluetoothStateChange on: true
09-16 11:51:05.474  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:05.475  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:51:05.475  3106  3106 D PanProfile: Bluetooth service connected
09-16 11:51:05.476  3106  3707 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:05.477  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:51:05.477  3106  3134 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 11:51:05.478  3106  3106 D BluetoothA2dp: Proxy object connected
09-16 11:51:05.479   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:05.479  5555  5555 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 11:51:05.479  3106  3129 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:05.479   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:51:05.479  5555  5555 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 11:51:05.479  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:05.480  3525  3776 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:05.480   927   927 D BluetoothA2dp: Proxy object connected
09-16 11:51:05.480  5438  5438 D BluetoothMap: Proxy object connected
09-16 11:51:05.480  5438  5438 D MapProfile: Bluetooth service connected
,09-16 11:51:05.480  5438  5438 D BluetoothMap: getConnectedDevices()
09-16 11:51:05.481  5555  5555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:51:05.481  3106  3707 D BluetoothMap: onBluetoothStateChange: up=true
,09-16 11:51:05.483   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:05.483  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:51:05.483  5555  5555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:51:05.483  3106  3106 D BluetoothMap: Proxy object connected
09-16 11:51:05.483  3106  3106 D MapProfile: Bluetooth service connected
09-16 11:51:05.483  3106  3106 D BluetoothMap: getConnectedDevices()
09-16 11:51:05.483  3106  3129 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 11:51:05.485   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:05.485  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:05.485  5438  5450 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:51:05.485  5438  5438 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 11:51:05.485  5438  5438 D PanProfile: Bluetooth service connected
09-16 11:51:05.486  5555  5555 D ObexServerSockets: Succeed to create listening sockets 
09-16 11:51:05.486  5555  5555 D ObexServerSockets0: startAccept()
09-16 11:51:05.486  5555  5555 D ObexServerSockets0: prepareForNewConnect()
09-16 11:51:05.488  5555  5555 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 11:51:05.488  5555  5555 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 11:51:05.489  5555  5593 D ObexServerSockets0: Accepting socket connection...
09-16 11:51:05.489  5555  5594 D ObexServerSockets0: Accepting socket connection...
09-16 11:51:05.490  3106  3106 D BluetoothInputDevice: Proxy object connected
09-16 11:51:05.490  5438  5592 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:05.490  3106  3106 D HidProfile: Bluetooth service connected
09-16 11:51:05.491  5438  5449 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 11:51:05.493  5438  5438 D BluetoothA2dp: Proxy object connected
09-16 11:51:05.494   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 11:51:05.494  5555  5555 D BluetoothMapService: onReceive
,09-16 11:51:05.494  5555  5555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:51:05.495  5555  5555 D BluetoothMapService: STATE_ON
09-16 11:51:05.496  5438  5438 D BluetoothInputDevice: Proxy object connected
09-16 11:51:05.496  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:05.496  5438  5438 D HidProfile: Bluetooth service connected
,09-16 11:51:05.497  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:05.498  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:05.499  5555  5596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:51:05.501  5555  5596 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-16 11:51:05.501  5555  5596 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 11:51:05.504  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 11:51:05.510  5438  5438 D DockEventReceiver: finishStartingService: stopping service
09-16 11:51:05.510  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:51:05.516  5438  5438 D BluetoothPbap: Proxy object connected
,09-16 11:51:05.516  5438  5438 D PbapServerProfile: Bluetooth service connected
,09-16 11:51:05.521  5555  5555 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 11:51:05.521  5555  5555 D ObexServerSockets0: prepareForNewConnect()
09-16 11:51:05.522  3106  3106 D BluetoothPbap: Proxy object connected
09-16 11:51:05.522  3106  3106 D PbapServerProfile: Bluetooth service connected
,09-16 11:51:05.525  5555  5600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:51:05.538  5555  5604 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:51:05.539  5555  5604 I BtOppRfcommListener: Accept thread started.
,09-16 11:51:05.580  3525  3549 D BluetoothHeadset: Proxy object connected
,09-16 11:51:05.583  3106  3129 D BluetoothHeadset: Proxy object connected
,09-16 11:51:05.583  3106  3106 D HeadsetProfile: Bluetooth service connected
,09-16 11:51:05.583  5438  5592 D BluetoothHeadset: Proxy object connected
,09-16 11:51:05.584  3106  3707 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.584   927   927 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.584   927   927 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.584   927   927 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.584  3525  3551 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.584   927   944 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.584   927   944 D BluetoothHeadset: Proxy object connected
09-16 11:51:05.585  3106  3106 D HeadsetProfile: Bluetooth service connected
09-16 11:51:05.587  5438  5438 D HeadsetProfile: Bluetooth service connected
,09-16 11:51:05.591  5438  5450 D BluetoothHeadset: Proxy object connected
,09-16 11:51:05.591  5438  5438 D HeadsetProfile: Bluetooth service connected
,09-16 11:51:05.831   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:06.832   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:07.833   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:08.834   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:51:09.292  5555  5567 D BluetoothAdapterState: Current state: ON, message: 23
,09-16 11:51:09.292  5555  5567 D BluetoothAdapterProperties: Setting state to 13
09-16 11:51:09.292  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 11:51:09.294  5555  5567 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 11:51:09.295  5555  5567 I BluetoothAdapterState: Entering PendingCommandState
09-16 11:51:09.299  5555  5555 D BluetoothMapService: onReceive
09-16 11:51:09.300  5555  5555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:51:09.300  5555  5555 D BluetoothMapService: STATE_TURNING_OFF
,09-16 11:51:09.301  5555  5555 D BluetoothMapService: MAP Service closeService in
09-16 11:51:09.301  5555  5555 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 11:51:09.301  5555  5555 D ObexServerSockets0: shutdown(block = true)
09-16 11:51:09.303  5555  5593 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 11:51:09.303  5555  5555 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 11:51:09.305  5555  5555 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 11:51:09.306  5555  5580 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-16 11:51:09.308  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:09.308  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:51:09.308  5555  5594 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-16 11:51:09.311  5555  5571 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:51:09.311  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:51:09.311  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:51:09.311  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 11:51:09.311  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:09.312  5555  5555 I BtOppRfcommListener: stopping Accept Thread
09-16 11:51:09.312  5555  5604 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-16 11:51:09.313  5555  5604 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 11:51:09.317  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:09.317  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:51:09.318  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:51:09.318  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:09.321  5555  5555 D HeadsetService: Received stop request...Stopping profile...
,09-16 11:51:09.323  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:09.323  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:51:09.324  3525  3917 D BluetoothHeadset: Proxy object disconnected
09-16 11:51:09.324  3106  3129 D BluetoothHeadset: Proxy object disconnected
09-16 11:51:09.325  5357  5357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 11:51:09.325  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:09.325  5438  5449 D BluetoothHeadset: Proxy object disconnected
09-16 11:51:09.326   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 11:51:09.326   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 11:51:09.326   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 11:51:09.327  5438  5438 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:51:09.328  5438  5438 D HeadsetProfile: Bluetooth service disconnected
09-16 11:51:09.328  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.331  5555  5555 V BluetoothAdapterState: isTurningOff()=true
09-16 11:51:09.331  5555  5555 V BluetoothAdapterState: isTurningOn()=false
,09-16 11:51:09.331  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.331  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:09.331  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.334  5555  5555 D A2dpService: Received stop request...Stopping profile...
,09-16 11:51:09.334  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:51:09.335  5555  5586 D A2dpStateMachine: Exit Disconnected: -1
09-16 11:51:09.335  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.336   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 11:51:09.339  5555  5555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 11:51:09.339  5555  5555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 11:51:09.340  5555  5578 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-16 11:51:09.340  5555  5578 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:51:09.340  5555  5578 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:51:09.340  5555  5555 D HidService: Received stop request...Stopping profile...
09-16 11:51:09.340  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 11:51:09.340  5555  5555 D HidService: Stopping Bluetooth HidService
,09-16 11:51:09.340  5555  5571 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-16 11:51:09.342  5438  5438 D BluetoothA2dp: Proxy object disconnected
09-16 11:51:09.343  3106  3106 D HeadsetProfile: Bluetooth service disconnected
09-16 11:51:09.343  3106  3106 D BluetoothA2dp: Proxy object disconnected
09-16 11:51:09.343  5438  5438 D BluetoothInputDevice: Proxy object disconnected
09-16 11:51:09.343  5438  5438 D HidProfile: Bluetooth service disconnected
09-16 11:51:09.343  3106  3106 D BluetoothInputDevice: Proxy object disconnected
09-16 11:51:09.343  3106  3106 D HidProfile: Bluetooth service disconnected
09-16 11:51:09.345  3106  3106 D BluetoothPbap: Proxy object disconnected
09-16 11:51:09.345  3106  3106 D PbapServerProfile: Bluetooth service disconnected
09-16 11:51:09.345  5438  5438 D BluetoothPbap: Proxy object disconnected
,09-16 11:51:09.345  5438  5438 D PbapServerProfile: Bluetooth service disconnected
,09-16 11:51:09.348  5555  5555 D HealthService: Received stop request...Stopping profile...
09-16 11:51:09.349  5555  5555 D PanService: Received stop request...Stopping profile...
,09-16 11:51:09.350  3106  3106 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:51:09.350  3106  3106 D PanProfile: Bluetooth service disconnected
09-16 11:51:09.351  5438  5438 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 11:51:09.351  5438  5438 D PanProfile: Bluetooth service disconnected
09-16 11:51:09.352  5555  5555 D BluetoothMapService: Received stop request...Stopping profile...
09-16 11:51:09.352  5555  5555 D BluetoothMapService: stop()
09-16 11:51:09.353  5555  5555 D BluetoothMapAppObserver: deinitObservers()
09-16 11:51:09.353  5555  5555 D BluetoothMapAppObserver: removeReceiver()
,09-16 11:51:09.355  5555  5555 V BluetoothAdapterState: isTurningOff()=true
09-16 11:51:09.355  5555  5555 V BluetoothAdapterState: isTurningOn()=false
,09-16 11:51:09.355  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:51:09.355  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.355  3106  3106 D BluetoothMap: Proxy object disconnected
09-16 11:51:09.355  3106  3106 D MapProfile: Bluetooth service disconnected
09-16 11:51:09.355  5438  5438 D BluetoothMap: Proxy object disconnected
09-16 11:51:09.356  5438  5438 D MapProfile: Bluetooth service disconnected
09-16 11:51:09.356  5555  5578 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:51:09.356  5555  5578 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:51:09.357  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 11:51:09.357  5555  5578 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 11:51:09.357  5555  5578 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 11:51:09.357  5555  5578 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 11:51:09.357  5555  5578 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-16 11:51:09.358  5555  5555 D SapService: Received stop request...Stopping profile...
09-16 11:51:09.359  5555  5555 V SapService: stop()
,09-16 11:51:09.360  5555  5555 V BluetoothAdapterState: isTurningOff()=true
09-16 11:51:09.360  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:09.360  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:09.360  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.360  5555  5555 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 11:51:09.360  5555  5555 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 11:51:09.360  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 11:51:09.361  5555  5555 V BluetoothAdapterState: isTurningOff()=true
09-16 11:51:09.361  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:09.361  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:51:09.361  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.361  5555  5555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 11:51:09.361  5555  5571 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 11:51:09.361  5555  5555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 11:51:09.361  5555  5555 V BluetoothAdapterState: isTurningOff()=true
09-16 11:51:09.361  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:09.362  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 11:51:09.362  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.362  5555  5555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 11:51:09.362  5555  5555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 11:51:09.363  5555  5555 D BluetoothMapService: MAP Service closeService in
09-16 11:51:09.363  5555  5555 V BluetoothAdapterState: isTurningOff()=true
09-16 11:51:09.363  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:09.363  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:09.363  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.363  5555  5555 D BluetoothMapService: cleanup()
09-16 11:51:09.363  5555  5555 D BluetoothMapService: MAP Service closeService in
09-16 11:51:09.363  5555  5555 V BluetoothAdapterState: isTurningOff()=true
,09-16 11:51:09.364  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:09.364  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:09.364  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:09.364  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 11:51:09.364  5555  5567 D BluetoothAdapterProperties: Setting state to 15
09-16 11:51:09.364  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-16 11:51:09.365  5555  5567 I BluetoothAdapterState: Entering BleOnState
09-16 11:51:09.365  5438  5449 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 11:51:09.366  5438  5592 D BluetoothMap: onBluetoothStateChange: up=false
09-16 11:51:09.367  3106  3707 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:51:09.367  5438  5450 D BluetoothPan: onBluetoothStateChange on: false
,09-16 11:51:09.368  3106  3129 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:51:09.369  3106  3134 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 11:51:09.370   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:51:09.371  3106  3129 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:51:09.372   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 11:51:09.372  3525  3776 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:51:09.372  3106  3707 D BluetoothMap: onBluetoothStateChange: up=false
09-16 11:51:09.372   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:51:09.373  3106  3134 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 11:51:09.373   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:51:09.374  5438  5449 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 11:51:09.374  5438  5592 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 11:51:09.374  5438  5450 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 11:51:09.375  5555  5567 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 11:51:09.375  5555  5567 D BluetoothAdapterProperties: Setting state to 16
,09-16 11:51:09.375  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 11:51:09.376  5555  5567 D BluetoothAdapterProperties: onBleDisable
09-16 11:51:09.376  5555  5567 I BluetoothAdapterState: Entering PendingCommandState
09-16 11:51:09.377  5555  5568 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 11:51:09.378  5555  5578 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 11:51:09.378  5555  5578 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 11:51:09.378  5555  5571 D BluetoothAdapterProperties: Scan Mode:20
09-16 11:51:09.380  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 11:51:09.382  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.383  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.385  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.388  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:09.390  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.391  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 11:51:09.392  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:09.393  5438  5438 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:51:09.594  5555  5571 I bt_hci  : shut_down
,09-16 11:51:09.599  5555  5575 D bt_hwcfg: hw_epilog_process
,09-16 11:51:09.599  5555  5575 I bt_vendor: low_power_mode_cb
,09-16 11:51:09.602  5555  5575 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-16 11:51:09.602  5555  5575 I bt_vendor: epilog_cb
09-16 11:51:09.602  5555  5575 I bt_hci  : epilog_finished_callback
,09-16 11:51:09.606  5555  5571 I bt_hci_h4: hal_close
,09-16 11:51:09.607  5555  5571 I bt_userial_vendor: device fd = 54 close
,09-16 11:51:09.716  5555  5568 D bt_stack_manager: event_shut_down_stack finished.
09-16 11:51:09.716  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 11:51:09.719  5555  5567 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 11:51:09.719  5555  5555 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 11:51:09.720  5555  5555 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 11:51:09.720  5555  5555 D BtGatt.GattService: stop()
,09-16 11:51:09.720  5555  5555 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 11:51:09.722  5555  5555 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:51:09.722  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:09.722  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:09.722  5555  5555 V BluetoothAdapterState: isBleTurningOff()=true
09-16 11:51:09.723  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-16 11:51:09.723  5555  5567 D BluetoothAdapterProperties: Setting state to 10
,09-16 11:51:09.723  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 11:51:09.724  5555  5567 I BluetoothAdapterState: Entering OffState
,09-16 11:51:09.725   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 11:51:09.734  5555  5555 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 11:51:09.735  5555  5555 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 11:51:09.735  5555  5555 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 11:51:09.737  5555  5568 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 11:51:09.742  5555  5555 I art     : System.exit called, status: 0
,09-16 11:51:09.742  5555  5555 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 11:51:09.772   927  3427 I ActivityManager: Process com.android.bluetooth (pid 5555) has died
,09-16 11:51:14.288  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:14.289  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:14.294  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:51:14.294  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64e17b removed from the list
,09-16 11:51:14.294  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:51:14.294  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:14.294  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:14.297  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:51:14.297  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b68ff1 added. We now have 4 listener(s)
09-16 11:51:14.297  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:51:14.299  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:14.299  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b68ff1 removed from the list
09-16 11:51:14.299  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:14.300  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:14.300  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:14.302  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:14.302  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfce7d6 added. We now have 4 listener(s)
09-16 11:51:14.302  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:51:19.313  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:19.349   927   944 I ActivityManager: Start proc 5612:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 11:51:19.435  5612  5612 D AdapterServiceConfig: Adding HeadsetService
,09-16 11:51:19.436  5612  5612 D AdapterServiceConfig: Adding A2dpService
09-16 11:51:19.436  5612  5612 D AdapterServiceConfig: Adding HidService
09-16 11:51:19.436  5612  5612 D AdapterServiceConfig: Adding HealthService
09-16 11:51:19.436  5612  5612 D AdapterServiceConfig: Adding PanService
,09-16 11:51:19.437  5612  5612 D AdapterServiceConfig: Adding GattService
,09-16 11:51:19.437  5612  5612 D AdapterServiceConfig: Adding BluetoothMapService
09-16 11:51:19.438  5612  5612 D AdapterServiceConfig: Adding SapService
,09-16 11:51:19.448   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a4544f:true
,09-16 11:51:19.448  5612  5612 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 11:51:19.451  5612  5612 I bt_bluedroid: init
,09-16 11:51:19.452  5612  5624 I BluetoothAdapterState: Entering OffState
,09-16 11:51:19.454  5612  5625 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 11:51:19.454  5612  5625 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 11:51:19.454  5612  5625 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-16 11:51:19.454  5612  5625 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-16 11:51:19.455  5612  5612 I bt_bluedroid: get_profile_interface socket
,09-16 11:51:19.457  5612  5628 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 11:51:19.457  5612  5612 I bt_bluedroid: get_profile_interface sdp
09-16 11:51:19.458  5612  5628 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 11:51:19.462  5612  5623 I bt_bluedroid: config_hci_snoop_log
09-16 11:51:19.463   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 11:51:19.467  5612  5624 D BluetoothAdapterState: Current state: OFF, message: 0
09-16 11:51:19.467  5612  5624 D BluetoothAdapterProperties: Setting state to 14
09-16 11:51:19.467  5612  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 11:51:19.468  5612  5624 D BluetoothBondStateMachine: make
,09-16 11:51:19.471  5612  5629 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:51:19.474  5612  5624 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:51:19.475  5612  5612 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 11:51:19.477  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:19.478  5612  5612 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 11:51:19.479  5612  5612 D BtGatt.GattService: Received start request. Starting profile...
09-16 11:51:19.479  5612  5612 D BtGatt.GattService: start()
09-16 11:51:19.479  5612  5612 I bt_bluedroid: get_profile_interface gatt
09-16 11:51:19.480  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:19.480  5612  5612 D BtGatt.AdvertiseManager: advertise manager created
,09-16 11:51:19.486  5612  5612 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:51:19.486  5612  5612 V BluetoothAdapterState: isTurningOn()=false
09-16 11:51:19.486  5612  5612 V BluetoothAdapterState: isBleTurningOn()=true
09-16 11:51:19.486  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:19.486  5612  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 11:51:19.488  5612  5624 I bt_bluedroid: bt_bluedroid
09-16 11:51:19.488  5612  5625 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 11:51:19.489  5612  5625 I bt_hci  : start_up
,09-16 11:51:19.494  5612  5625 I bt_vendor: alloc value 0xf41eb871
,09-16 11:51:19.494  5612  5625 I bt_vendor: init
09-16 11:51:19.494  5612  5625 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 11:51:19.494  5612  5625 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 11:51:19.604  5612  5625 D bt_hci  : start_up starting async portion
,09-16 11:51:19.605  5612  5632 I bt_hci  : event_finish_startup
09-16 11:51:19.605  5612  5632 I bt_hci_h4: hal_open
09-16 11:51:19.605  5612  5632 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 11:51:19.600  5633  5633 W irq/448-msm_hs_: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 11:51:19.608  5612  5632 I bt_userial_vendor: device fd = 54 open
,09-16 11:51:19.622  5612  5632 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 11:51:19.625  5612  5632 D bt_hwcfg: Chipset BCM4358A3
,09-16 11:51:19.625  5612  5632 D bt_hwcfg: Target name = [BCM4358A3]
09-16 11:51:19.625  5612  5632 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 11:51:20.146  5612  5632 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 11:51:20.146  5612  5632 D bt_hwcfg: Settlement delay -- 100 ms
09-16 11:51:20.146  5612  5632 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 11:51:20.280  5612  5632 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 11:51:20.281  5612  5632 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 11:51:20.282  5612  5632 I bt_hwcfg: vendor lib fwcfg completed
09-16 11:51:20.282  5612  5632 I bt_vendor: firmware callback
,09-16 11:51:20.282  5612  5632 I bt_hci  : firmware_config_callback
,09-16 11:51:20.293  5612  5635 I bt_btu  : btu_task pending for preload complete event
,09-16 11:51:20.293  5612  5635 I bt_btu_task: Bluetooth chip preload is complete
,09-16 11:51:20.294  5612  5635 I bt_btu  : btu_task received preload complete event
,09-16 11:51:20.302  5612  5635 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 11:51:20.302  5612  5635 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 11:51:20.302  5612  5635 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 11:51:20.302  5612  5635 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 11:51:20.302  5612  5635 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_GAP
,09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 11:51:20.303  5612  5635 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 11:51:20.304  5612  5635 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-16 11:51:20.304  5612  5635 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 11:51:20.401  5612  5635 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
,09-16 11:51:20.401  5612  5635 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,09-16 11:51:20.421  5612  5628 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 11:51:20.423  5612  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 11:51:20.424  5612  5628 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 11:51:20.426  5612  5628 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 11:51:20.429  5612  5628 D BluetoothAdapterProperties: Scan Mode:20
,09-16 11:51:20.429  5612  5628 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 11:51:20.429  5612  5628 D bt_hci  : do_postload posting postload work item
09-16 11:51:20.430  5612  5632 I bt_hci  : event_postload
09-16 11:51:20.430  5612  5632 I bt_vendor: sco_config_cb
09-16 11:51:20.430  5612  5632 I bt_hci  : sco_config_callback postload finished.
,09-16 11:51:20.435  5612  5628 D bt_bte_conf: Device ID record 1 : primary
09-16 11:51:20.435  5612  5628 D bt_bte_conf:   vendorId            = 000f
09-16 11:51:20.434  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:20.435  5612  5628 D bt_bte_conf:   vendorIdSource      = 0001
09-16 11:51:20.435  5612  5628 D bt_bte_conf:   product             = 1200
09-16 11:51:20.435  5612  5628 D bt_bte_conf:   version             = 1436
09-16 11:51:20.435  5612  5628 D bt_bte_conf:   clientExecutableURL = 
09-16 11:51:20.435  5612  5628 D bt_bte_conf:   serviceDescription  = 
,09-16 11:51:20.435  5612  5628 D bt_bte_conf:   documentationURL    = 
09-16 11:51:20.435  5612  5628 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-16 11:51:20.436  5612  5625 D bt_stack_manager: event_start_up_stack finished
,09-16 11:51:20.438  5612  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 11:51:20.439  5612  5624 D BluetoothAdapterProperties: Setting state to 15
,09-16 11:51:20.439  5612  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 11:51:20.440  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:20.440  5612  5624 I BluetoothAdapterState: Entering BleOnState
,09-16 11:51:20.443  5612  5632 I bt_vendor: low_power_mode_cb
09-16 11:51:20.443  5612  5624 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-16 11:51:20.444  5612  5624 D BluetoothAdapterProperties: Setting state to 11
09-16 11:51:20.444  5612  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 11:51:20.452  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:20.452  5612  5612 D HeadsetService: Received start request. Starting profile...
09-16 11:51:20.454  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:20.456  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:20.458  5612  5612 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 11:51:20.458  5612  5612 D HeadsetStateMachine: make
,09-16 11:51:20.470  5612  5624 I BluetoothAdapterState: Entering PendingCommandState
,09-16 11:51:20.471  5612  5612 D HeadsetStateMachine: max_hf_connections = 1
,09-16 11:51:20.471  5612  5612 I bt_bluedroid: get_profile_interface handsfree
09-16 11:51:20.471  5612  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 11:51:20.471  5612  5628 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-16 11:51:20.474  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:20.475  5612  5612 D A2dpService: Received start request. Starting profile...
09-16 11:51:20.476  5612  5612 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 11:51:20.476  5612  5612 I bt_bluedroid: get_profile_interface avrcp
,09-16 11:51:20.482  5612  5612 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-16 11:51:20.482  5612  5612 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 11:51:20.482  5612  5612 D A2dpStateMachine: make
,09-16 11:51:20.483  5612  5612 I bt_bluedroid: get_profile_interface a2dp
,09-16 11:51:20.484  5612  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-16 11:51:20.485  5612  5643 D A2dpStateMachine: Enter Disconnected: -2
,09-16 11:51:20.487  5612  5612 I BluetoothHidServiceJni: classInitNative: succeeds
09-16 11:51:20.488  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:20.488  5612  5612 D HidService: Received start request. Starting profile...
09-16 11:51:20.488  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 11:51:20.488  5612  5612 I bt_bluedroid: get_profile_interface hidhost
09-16 11:51:20.489  5612  5628 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
09-16 11:51:20.489  5612  5612 D HidService: setHidService(): set to: null
,09-16 11:51:20.489  5612  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 11:51:20.489  5612  5612 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-16 11:51:20.490  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:20.491  5612  5612 D HealthService: Received start request. Starting profile...
,09-16 11:51:20.492  5612  5612 I bt_bluedroid: get_profile_interface health
09-16 11:51:20.493  5612  5612 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-16 11:51:20.494  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:20.494  5612  5612 D PanService: Received start request. Starting profile...
09-16 11:51:20.495  5612  5612 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 11:51:20.495  5612  5612 I bt_bluedroid: get_profile_interface pan
09-16 11:51:20.495  5612  5628 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-16 11:51:20.497  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:20.497  5612  5612 D BluetoothMapService: Received start request. Starting profile...
,09-16 11:51:20.497  5612  5612 D BluetoothMapService: start()
,09-16 11:51:20.500  5612  5612 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 11:51:20.501  5612  5612 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 11:51:20.501  5612  5612 D BluetoothMapAppObserver: createReceiver()
09-16 11:51:20.502  5612  5612 D BluetoothMapAppObserver: initObservers()
09-16 11:51:20.502  5612  5612 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 11:51:20.509  5612  5612 V SapService: SapBinder()
09-16 11:51:20.509  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
,09-16 11:51:20.510  5612  5612 D SapService: Received start request. Starting profile...
,09-16 11:51:20.510  5612  5612 V SapService: start()
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.512  5612  5641 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isTurningOff()=false
,09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.512  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.513  5612  5612 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:20.513  5612  5612 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:20.513  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.513  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isTurningOn()=true
,09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.514  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.515  5612  5612 V BluetoothAdapterState: isTurningOff()=false
09-16 11:51:20.515  5612  5612 V BluetoothAdapterState: isTurningOn()=true
09-16 11:51:20.515  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
09-16 11:51:20.515  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
09-16 11:51:20.516  5612  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 11:51:20.516  5612  5624 D BluetoothAdapterProperties: ScanMode =  20
09-16 11:51:20.516  5612  5624 D BluetoothAdapterProperties: State =  11
,09-16 11:51:20.516  5612  5624 D BluetoothAdapterProperties: Setting state to 12
09-16 11:51:20.516  5612  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-16 11:51:20.517  5612  5624 I BluetoothAdapterState: Entering OnState
,09-16 11:51:20.517  5438  5592 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 11:51:20.517  5612  5628 D BluetoothAdapterProperties: Scan Mode:21
09-16 11:51:20.518  5612  5628 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 11:51:20.520  5438  5450 D BluetoothMap: onBluetoothStateChange: up=true
,09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:20.521  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:51:20.521  3106  3134 D BluetoothPan: onBluetoothStateChange on: true
09-16 11:51:20.523  5438  5438 D BluetoothMap: Proxy object connected
09-16 11:51:20.523  5438  5438 D MapProfile: Bluetooth service connected
09-16 11:51:20.523  5438  5438 D BluetoothMap: getConnectedDevices()
09-16 11:51:20.523  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:20.524  5438  5592 D BluetoothPan: onBluetoothStateChange on: true
09-16 11:51:20.524  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:51:20.524  3106  3106 D PanProfile: Bluetooth service connected
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:20.526  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 11:51:20.527  5612  5612 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 11:51:20.527  5612  5612 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 11:51:20.528  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:20.528  3106  3707 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:51:20.528  5612  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:51:20.530  3106  3134 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 11:51:20.530  5612  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:51:20.531   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:20.531  3106  3129 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:20.531  5612  5612 D ObexServerSockets: Succeed to create listening sockets 
09-16 11:51:20.531  5612  5612 D ObexServerSockets0: startAccept()
09-16 11:51:20.531  5612  5612 D ObexServerSockets0: prepareForNewConnect()
,09-16 11:51:20.531   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:51:20.532  3525  3776 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:20.533  3106  3707 D BluetoothMap: onBluetoothStateChange: up=true
09-16 11:51:20.533  5612  5612 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 11:51:20.533  5612  5612 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 11:51:20.534  3106  3106 D BluetoothMap: Proxy object connected
09-16 11:51:20.534   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:20.534  3106  3106 D MapProfile: Bluetooth service connected
09-16 11:51:20.534  3106  3106 D BluetoothMap: getConnectedDevices()
09-16 11:51:20.534   927   927 D BluetoothA2dp: Proxy object connected
09-16 11:51:20.534  3106  3134 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 11:51:20.535  5438  5438 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 11:51:20.535  5438  5438 D PanProfile: Bluetooth service connected
09-16 11:51:20.535  5612  5649 D ObexServerSockets0: Accepting socket connection...
09-16 11:51:20.536   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:20.537  5438  5449 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 11:51:20.537  3106  3106 D BluetoothA2dp: Proxy object connected
09-16 11:51:20.537  5612  5650 D ObexServerSockets0: Accepting socket connection...
09-16 11:51:20.539  3106  3106 D BluetoothInputDevice: Proxy object connected
09-16 11:51:20.539  3106  3106 D HidProfile: Bluetooth service connected
,09-16 11:51:20.539  5438  5592 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 11:51:20.540  5438  5450 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 11:51:20.542  5438  5438 D BluetoothA2dp: Proxy object connected
09-16 11:51:20.543   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 11:51:20.543  5612  5612 D BluetoothMapService: onReceive
09-16 11:51:20.543  5612  5612 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 11:51:20.543  5612  5612 D BluetoothMapService: STATE_ON
,09-16 11:51:20.545  5438  5438 D BluetoothInputDevice: Proxy object connected
,09-16 11:51:20.545  5438  5438 D HidProfile: Bluetooth service connected
09-16 11:51:20.545  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:20.547  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:20.547  5612  5651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:51:20.549  5612  5651 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 11:51:20.549  5612  5651 D BluetoothSdpJni: SDP Create record success - handle: 1
09-16 11:51:20.552  5438  5438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 11:51:20.558  3613  3613 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 11:51:20.558  5438  5438 D DockEventReceiver: finishStartingService: stopping service
,09-16 11:51:20.566  3106  3106 D BluetoothPbap: Proxy object connected
,09-16 11:51:20.566  3106  3106 D PbapServerProfile: Bluetooth service connected
,09-16 11:51:20.566  5612  5612 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 11:51:20.566  5612  5612 D ObexServerSockets0: prepareForNewConnect()
,09-16 11:51:20.570  5438  5438 D BluetoothPbap: Proxy object connected
09-16 11:51:20.570  5438  5438 D PbapServerProfile: Bluetooth service connected
,09-16 11:51:20.573  5612  5655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:51:20.590  5612  5659 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:51:20.592  5612  5659 I BtOppRfcommListener: Accept thread started.
,09-16 11:51:20.632  3525  3551 D BluetoothHeadset: Proxy object connected
,09-16 11:51:20.632  3525  3549 D BluetoothHeadset: Proxy object connected
,09-16 11:51:20.633  3106  3129 D BluetoothHeadset: Proxy object connected
,09-16 11:51:20.633  3106  3106 D HeadsetProfile: Bluetooth service connected
09-16 11:51:20.634  5438  5592 D BluetoothHeadset: Proxy object connected
09-16 11:51:20.634   927   927 D BluetoothHeadset: Proxy object connected
09-16 11:51:20.634   927   927 D BluetoothHeadset: Proxy object connected
09-16 11:51:20.634   927   927 D BluetoothHeadset: Proxy object connected
09-16 11:51:20.635   927   944 D BluetoothHeadset: Proxy object connected
09-16 11:51:20.636  5438  5438 D HeadsetProfile: Bluetooth service connected
09-16 11:51:20.637   927   944 D BluetoothHeadset: Proxy object connected
,09-16 11:51:20.640  5438  5449 D BluetoothHeadset: Proxy object connected
09-16 11:51:20.640  5438  5438 D HeadsetProfile: Bluetooth service connected
,09-16 11:51:23.835   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:24.330  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:51:24.336  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 11:51:24.337  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:24.337  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfce7d6 removed from the list
09-16 11:51:24.338  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:24.338  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:24.338  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:24.340  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:24.340  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd61a57 added. We now have 4 listener(s)
09-16 11:51:24.341  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:51:24.344   927   938 D WifiService: setWifiEnabled: false pid=5357, uid=10077
09-16 11:51:24.344   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 11:51:24.836   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:25.837   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:26.838   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:27.840   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:28.841   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:51:29.355  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:29.355   927  3545 D WifiService: setWifiEnabled: true pid=5357, uid=10077
09-16 11:51:29.356   927  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 11:51:29.367   507   920 D SoftapController: Softap fwReload - Ok
,09-16 11:51:29.372   507   920 D CommandListener: Setting iface cfg
,09-16 11:51:29.372   507   920 D CommandListener: Trying to bring down wlan0
,09-16 11:51:29.374   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-16 11:51:29.381   927  2964 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 11:51:30.045   927  2964 D wifi    : set interface wlan0 flags (UP)
09-16 11:51:30.049   927  2964 I WifiHAL : Initializing wifi
,09-16 11:51:30.049   927  2964 I WifiHAL : Creating socket
,09-16 11:51:30.056   927  2964 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 11:51:30.056   927  2964 D wifi    : Did set static halHandle = 0x7f6d37bf20
09-16 11:51:30.056   927  2964 D wifi    : halHandle = 0x7f6d37bf20, mVM = 0x7f899cd140, mCls = 0x1282
09-16 11:51:30.057   927  2964 D wifi    : array field set
09-16 11:51:30.057   927  2964 I WifiNative-HAL: interface[0] = wlan0
,09-16 11:51:30.059   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 11:51:30.062   927  5664 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547293216544
09-16 11:51:30.062   927  5664 D wifi    : waitForHalEvents called, vm = 0x7f899cd140, obj = 0x1282, env = 0x7f69e1a680
,09-16 11:51:30.108  5665  5665 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 11:51:30.129  5665  5665 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 11:51:30.140  5665  5665 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 11:51:30.140  5665  5665 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 11:51:30.161   927  2964 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 11:51:30.167  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:30.174   927  2964 D WifiConfigStore: Loading config and enabling all networks 
,09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:30.178  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:51:30.182  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 11:51:30.185  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 11:51:30.187  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 11:51:30.188  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:30.191   927  2964 D WifiConfigStore: loaded 0 passpoint configs
,09-16 11:51:30.192   927  2964 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 11:51:30.192   927  2964 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 11:51:30.193   927  2964 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 11:51:30.194   927  2964 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 11:51:30.195   927  2964 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 11:51:30.195   927  2964 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 11:51:30.195   927  2964 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 11:51:30.199   927  2964 D WifiNative-HAL: Setting external_sim to 1
,09-16 11:51:30.199  4287  4287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 11:51:30.199   927  2964 D wifi    : setting dfs flag to true, 0x7f6e3fe620
09-16 11:51:30.200   927  2964 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 11:51:30.200   927  2964 D wifi    : setting scan oui 0x7f6e3fe620
09-16 11:51:30.200   927  2964 D WifiHAL : Sending mac address OUI
,09-16 11:51:30.204   927  2964 E native  : do suspend false
,09-16 11:51:30.216   927  2964 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 11:51:30.216   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 11:51:30.216   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 11:51:30.216   927  3071 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 11:51:30.217   507   920 D CommandListener: Setting iface cfg
,09-16 11:51:30.223   927  2963 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,09-16 11:51:30.223   927  2963 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 11:51:30.232   927  2963 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 11:51:30.233   927  2963 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 11:51:30.238   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=395905 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-16 11:51:33.467   927  2964 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 11:51:33.468   927  2964 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-16 11:51:33.469   927  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 11:51:33.479   927  2964 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 11:51:33.513   927  2964 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 11:51:33.515  5665  5665 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 11:51:33.964  5665  5665 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 11:51:33.999  5665  5665 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 11:51:33.999  5665  5665 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 11:51:34.013   927  2964 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 11:51:34.014   927  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-16 11:51:34.014   927  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 11:51:34.034   927  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 11:51:34.046   507   920 D CommandListener: Setting iface cfg
,09-16 11:51:34.052   927  2964 D WifiStateMachine: Start Dhcp Watchdog 2
,09-16 11:51:34.060   927  5670 D DhcpClient: Receive thread started
,09-16 11:51:34.063   927  2964 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-16 11:51:34.063   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-16 11:51:34.063   927  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-16 11:51:34.144   927  2964 E native  : do suspend false
,09-16 11:51:34.155   927  5669 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 11:51:34.184   927  5670 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172442, domain null
,09-16 11:51:34.185   927  5669 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172442 seconds
,09-16 11:51:34.187   927  5669 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 11:51:34.219   927  5670 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 11:51:34.220   927  5669 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 11:51:34.223   507   920 D CommandListener: Setting iface cfg
,09-16 11:51:34.229   927  2964 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 11:51:34.232   927  5669 D DhcpClient: Scheduling renewal in 86399s
,09-16 11:51:34.240   927  2964 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 11:51:34.241   927  2964 D WifiConfigStore: No blacklist allowed without epno enabled
09-16 11:51:34.242   927  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-16 11:51:34.244   927  2964 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 11:51:34.251   927  2966 D ConnectivityService: Adding iface wlan0 to network 101
,09-16 11:51:34.299   927  2966 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-16 11:51:34.299   927  2966 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-16 11:51:34.305   927  2966 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-16 11:51:34.308   927  2966 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-16 11:51:34.309   927  2966 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-16 11:51:34.317   927  2966 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:51:34.322   927  2966 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-16 11:51:34.323   927  2966 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-16 11:51:34.323   927  2966 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-16 11:51:34.323   927  2964 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-16 11:51:34.323   927  2966 D ConnectivityService:    accepting network in place of null
09-16 11:51:34.323   927  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 11:51:34.325   927  2966 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 11:51:34.336   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=400003, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:51:34.353   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:34.372  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:51:34.374  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:51:34.375  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:51:34.375  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd61a57 removed from the list
,09-16 11:51:34.375  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:34.375  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:34.375  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:34.378  5357  5678 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-16 11:51:34.378  5357  5678 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-16 11:51:34.379   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 11:51:34.382   927  2966 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-16 11:51:34.382   927  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:51:34.383  3483  3655 W QCNEJ   : |CORE| network available: 101
09-16 11:51:34.385   927  2966 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-16 11:51:34.385   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 11:51:34.389  3483  3655 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 11:51:34.390  3483  3655 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-16 11:51:34.391  3483  3655 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:34.396  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:51:34.398  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:34.402  5357  5357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:51:34.404  5357  5357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:34.405  4829  4851 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 11:51:34.405  4829  4851 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 11:51:34.405  4829  4851 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-16 11:51:34.405  4829  4851 E SarControlService: no key has been found,reset the power
09-16 11:51:34.405  4829  4871 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 11:51:34.405  4829  4871 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 11:51:34.405  4829  4871 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 11:51:34.406  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 11:51:34.406  4859  4859 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-16 11:51:34.407  4763  4763 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-16 11:51:34.408   927  5667 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:400d:803::200e
09-16 11:51:34.408  4829  4871 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 11:51:34.409  4829  4871 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 11:51:34.409  4829  4871 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 11:51:34.409  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 11:51:34.409  4859  4859 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-16 11:51:34.415  4859  4873 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ae3c712 HexData = [00000000ec03000000000000ffffffff]
,09-16 11:51:34.415  4859  4873 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 11:51:34.416  4859  4873 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-16 11:51:34.416  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 11:51:34.416  4829  4839 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 11:51:34.417  4859  4873 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ae3c712 HexData = [00000000ed03000000000000ffffffff]
,09-16 11:51:34.421  4859  4873 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 11:51:34.421  4859  4873 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-16 11:51:34.422  4859  4859 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 11:51:34.422  4829  4840 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 11:51:34.425  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 11:51:34.431  3893  5134 I iu.UploadsManager: num queued entries: 0
,09-16 11:51:34.432  3893  5134 I iu.UploadsManager: num updated entries: 0
09-16 11:51:34.432  3893  5134 I iu.SyncManager: NEXT; no task
,09-16 11:51:34.436  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 11:51:34.437  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 11:51:34.439  5137  5137 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 11:51:34.443  5137  5137 D SprintDMHelper: simOperator: 
09-16 11:51:34.443  5137  5137 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 11:51:34.492   927  5667 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 15:51:34 GMT], X-Android-Received-Millis=[1474041094491], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474041094454]}
,09-16 11:51:34.492   927  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 11:51:34.492   927  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-16 11:51:34.492   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:51:34.494   927  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 11:51:34.572  4287  5684 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 11:51:35.383   927  2966 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-16 11:51:37.088   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:51:37.397  5357  5692 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-16 11:51:37.397  5357  5678 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-16 11:51:37.398  5357  5678 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-16 11:51:37.398  5357  5692 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-16 11:51:37.398  5357  5678 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 11:51:37.398  5357  5692 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:51:37.400  5357  5678 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:51:37.400  5357  5692 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:51:37.401  5357  5695 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 149, name: IncomingSocketThread/Sender)
,09-16 11:51:37.402  5357  5678 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-16 11:51:37.402  5357  5692 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-16 11:51:37.403  5357  5696 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 151, name: IncomingSocketThread/Receiver)
09-16 11:51:37.405  5357  5696 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 151, thread name: IncomingSocketThread/Receiver)
,09-16 11:51:37.405  5357  5696 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-16 11:51:37.405  5357  5696 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 151, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-16 11:51:37.407  5357  5694 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 148, name: OutgoingSocketThread/Sender)
,09-16 11:51:37.408  5357  5697 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 150, name: OutgoingSocketThread/Receiver)
09-16 11:51:37.409  5357  5697 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 150, thread name: OutgoingSocketThread/Receiver)
09-16 11:51:37.409  5357  5697 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-16 11:51:37.409  5357  5697 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 150, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-16 11:51:40.387  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-16 11:51:40.389  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-16 11:51:40.394  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d2f3f36 Bundle[{}]
,09-16 11:51:40.395  5357  5403 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 11:51:40.396  5357  5403 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-16 11:51:40.398  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-16 11:51:40.398  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-16 11:51:40.399  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-16 11:51:40.400  5357  5403 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-16 11:51:40.406  5357  5403 I System.out: Running OutgoingSocketThread
,09-16 11:51:40.408  5357  5698 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-16 11:51:40.408  5357  5698 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 11:51:42.328   927  2966 D ConnectivityService: handlePromptUnvalidated 101
,09-16 11:51:43.419  5357  5698 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-16 11:51:43.419  5357  5698 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-16 11:51:43.419  5357  5698 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:51:43.420  5357  5698 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:51:43.422  5357  5699 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-16 11:51:43.422  5357  5699 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-16 11:51:43.422  5357  5698 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-16 11:51:43.423  5357  5701 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Sender)
,09-16 11:51:43.424  5357  5702 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: OutgoingSocketThread/Receiver)
09-16 11:51:43.425  5357  5699 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:51:43.426  5357  5699 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 11:51:43.426  5357  5702 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: OutgoingSocketThread/Receiver)
09-16 11:51:43.426  5357  5702 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-16 11:51:43.426  5357  5702 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-16 11:51:43.428  5357  5699 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-16 11:51:43.430  5357  5703 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: IncomingSocketThread/Sender)
,09-16 11:51:43.432  5357  5704 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: IncomingSocketThread/Receiver)
09-16 11:51:43.433  5357  5704 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: IncomingSocketThread/Receiver)
,09-16 11:51:43.433  5357  5704 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-16 11:51:43.434  5357  5704 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-16 11:51:45.241   927  2964 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 21, 22 -> obsolete
,09-16 11:51:46.417  5357  5403 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 172)
,09-16 11:51:46.419  5357  5403 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-16 11:51:46.419  5357  5403 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
,09-16 11:51:46.424  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 11:51:46.425  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c79e944 added. We now have 3 listener(s)
,09-16 11:51:46.428  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:51:46.429  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 11:51:46.429  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:51:46.429  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:46.429  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3933a2d added. We now have 4 listener(s)
09-16 11:51:46.429  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:51:46.431  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 11:51:46.436  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:46.444  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:51:46.448  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:51:46.448  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:51:46.449  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:51:46.449  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:51:46.449  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:51:46.449  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:46.449  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:46.449  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:51:46.449  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 11:51:46.449  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c79e944 removed from the list
09-16 11:51:46.449  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:51:46.450  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3933a2d removed from the list
09-16 11:51:46.452  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:46.452  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:46.452  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:46.453  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:46.453  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:46.455  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:46.455  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:51:46.455  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:46.455  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3933a2d not in the list
09-16 11:51:46.455  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:46.455  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:46.457  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:51:46.457  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:46.457  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:46.457  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:46.457  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3933a2d not in the list
09-16 11:51:46.457  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:46.457  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:46.458  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:46.458  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c79e944 not in the list
09-16 11:51:46.458  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 11:51:46.459  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b804f3 added. We now have 3 listener(s)
09-16 11:51:46.461  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:51:46.461  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 11:51:46.461  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:51:46.461  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:46.461  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ce55b0 added. We now have 4 listener(s)
09-16 11:51:46.461  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:51:46.462  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 11:51:46.466  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:46.472  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:51:46.473  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:51:46.473  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 11:51:46.474  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:51:46.474  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:51:46.474  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:51:46.474  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:51:46.474  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:51:46.478  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:46.479  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:51:46.479  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:51:46.482  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:46.485  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 11:51:46.487  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:51:46.487  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 11:51:46.492  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 11:51:46.492  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:51:46.493  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 11:51:46.494  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:51:46.499  5612  5623 D BtGatt.GattService: registerClient() - UUID=bb71ab5c-4660-4690-9e18-470e4d10fbd7
,09-16 11:51:46.500  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=bb71ab5c-4660-4690-9e18-470e4d10fbd7, clientIf=5
09-16 11:51:46.501  5357  5368 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 11:51:46.502  5612  5640 D BtGatt.GattService: start scan with filters
,09-16 11:51:46.506  5612  5631 D BtGatt.ScanManager: handling starting scan
09-16 11:51:46.506  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:51:46.506  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 11:51:46.506  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 11:51:46.506  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 11:51:46.508  5612  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b29d75b
09-16 11:51:46.510  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:51:46.510  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:51:46.510  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:51:46.511  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 11:51:46.514  5357  5403 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 11:51:46.514  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:51:46.514  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:51:46.514  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:46.514  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 11:51:46.514  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:51:46.514  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:51:46.514  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 11:51:46.514  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:51:46.514  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 11:51:46.515  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 11:51:46.516  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:51:46.516  5612  5640 D BtGatt.GattService: stopScan() - queue size =1
,09-16 11:51:46.517  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:51:46.517  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:46.517  5612  5648 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 11:51:46.518  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 11:51:46.518  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 11:51:46.518  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:51:46.518  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 11:51:46.518  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:51:46.518  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:51:46.520  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:51:46.521  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:51:46.522  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:51:46.522  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:51:46.523  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 11:51:46.524  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:51:46.524  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:51:46.524  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:51:46.525  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 11:51:46.525  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:46.525  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:51:46.525  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:51:46.535  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 11:51:46.535  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:51:46.541  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 11:51:46.541  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:51:46.548  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 11:51:46.549  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:46.549  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
,09-16 11:51:46.554  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 11:51:46.554  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:46.555  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:51:46.560  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 11:51:46.560  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:51:47.026  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:51:47.026  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:51:47.027  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:51:48.842   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:49.525  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:51:49.525  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:51:49.525  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:51:49.525  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:51:49.526  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:49.526  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 11:51:49.526  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-16 11:51:49.526  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b804f3 removed from the list
09-16 11:51:49.526  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:49.527  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ce55b0 removed from the list
09-16 11:51:49.527  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 11:51:49.527  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:49.529  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:49.530  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:49.535  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 11:51:49.536  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:51:49.537  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:49.538  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ce55b0 not in the list
09-16 11:51:49.538  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:49.538  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:49.542  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:51:49.542  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:49.542  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:51:49.542  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ce55b0 not in the list
09-16 11:51:49.543  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:49.543  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:49.543  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:49.543  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b804f3 not in the list
09-16 11:51:49.545  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 11:51:49.545  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9e81e5 added. We now have 3 listener(s)
09-16 11:51:49.549  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 11:51:49.550  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 11:51:49.551  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:51:49.551  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:49.552  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f44ba added. We now have 4 listener(s)
09-16 11:51:49.552  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:51:49.554  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 11:51:49.561  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:49.566  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:51:49.569  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:51:49.569  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:51:49.570  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 11:51:49.571  5357  5403 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-16 11:51:49.571  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-16 11:51:49.572  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 11:51:49.572  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 11:51:49.572  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 11:51:49.572  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:51:49.574  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 11:51:49.576  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 11:51:49.576  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 11:51:49.576  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 11:51:49.576  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 11:51:49.576  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:51:49.576  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:51:49.580  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:49.577  5640  5640 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30557]" dev="sockfs" ino=30557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 11:51:49.577  5640  5640 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30557]" dev="sockfs" ino=30557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 11:51:49.583  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:51:49.583  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:51:49.583  5357  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 11:51:49.584  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:49.584  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 11:51:49.588  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 11:51:49.588  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 11:51:49.589  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:51:49.590  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 11:51:49.591  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:51:49.591  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-16 11:51:49.592  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-16 11:51:49.592  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:51:49.592  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 11:51:49.593  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:51:49.598  5612  5640 D BtGatt.GattService: registerClient() - UUID=5b4f90bc-dfea-4f3c-95f4-8d9d964e45cd
09-16 11:51:49.599  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=5b4f90bc-dfea-4f3c-95f4-8d9d964e45cd, clientIf=5
,09-16 11:51:49.599  5357  5367 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 11:51:49.602  5612  5630 D BtGatt.AdvertiseManager: message : 0
,09-16 11:51:49.604  5612  5630 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 11:51:49.615  5612  5628 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 11:51:49.621  5612  5628 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 11:51:49.622  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 11:51:49.622  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 11:51:49.624  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:51:49.625  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 11:51:49.625  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 11:51:49.626  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 11:51:49.626  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 11:51:49.626  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 11:51:49.626  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-16 11:51:49.629  5357  5357 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 11:51:49.629  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 11:51:49.630  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 11:51:49.630  5357  5403 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:51:49.842   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:50.130  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 11:51:50.844   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:51.845   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:52.197   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:51:52.631  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:51:52.632  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-16 11:51:52.632  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:51:52.632  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-16 11:51:52.632  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 11:51:52.632  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-16 11:51:52.633  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 11:51:52.633  5357  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 11:51:52.633  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 11:51:52.633  5357  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-16 11:51:52.634  5357  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 11:51:52.634  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:51:52.634  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:51:52.634  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 11:51:52.634  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:51:52.634  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 11:51:52.634  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:51:52.637  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:51:52.637  5357  5403 D BluetoothLeScanner: could not find callback wrapper
09-16 11:51:52.637  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 11:51:52.638  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 11:51:52.640  5612  5630 D BtGatt.AdvertiseManager: message : 1
09-16 11:51:52.643  5612  5630 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 11:51:52.656  5612  5628 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-16 11:51:52.656  5612  5628 D BtGatt.GattService: Client app is not null!
,09-16 11:51:52.657  5612  5648 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 11:51:52.658  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 11:51:52.658  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 11:51:52.658  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-16 11:51:52.658  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-16 11:51:52.658  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-16 11:51:52.661  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:51:52.661  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 11:51:52.661  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:51:52.662  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 11:51:52.665  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:51:52.665  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:51:52.665  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:52.665  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:51:52.665  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:51:52.665  5357  5357 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-16 11:51:52.665  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 11:51:52.666  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:51:52.666  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9e81e5 removed from the list
09-16 11:51:52.666  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 11:51:52.666  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f44ba removed from the list
09-16 11:51:52.666  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:52.666  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:52.667  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:52.667  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:52.669  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:52.669  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:51:52.669  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:52.669  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f44ba not in the list
,09-16 11:51:52.669  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:52.670  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:52.672  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:51:52.672  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:52.672  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:52.672  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f44ba not in the list
09-16 11:51:52.672  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:52.672  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:52.673  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:52.673  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9e81e5 not in the list
09-16 11:51:52.674  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 11:51:52.674  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83c4747 added. We now have 3 listener(s)
09-16 11:51:52.677  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:51:52.677  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 11:51:52.677  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:51:52.678  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:52.678  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74c2b74 added. We now have 4 listener(s)
09-16 11:51:52.678  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:51:52.678  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 11:51:52.682  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:52.690  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:51:52.693  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:51:52.693  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:51:52.693  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:51:52.694  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:51:52.694  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:51:52.694  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:51:52.694  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:51:52.697  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:52.699  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:51:52.699  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:51:52.701  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:51:52.703  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:51:52.704  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:51:52.704  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 11:51:52.708  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 11:51:52.708  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:51:52.708  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:51:52.709  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:51:52.712  5612  5640 D BtGatt.GattService: registerClient() - UUID=764d4dac-2bee-497e-abdf-f979750fca51
09-16 11:51:52.712  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=764d4dac-2bee-497e-abdf-f979750fca51, clientIf=5
,09-16 11:51:52.712  5357  5458 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 11:51:52.713  5612  5648 D BtGatt.GattService: start scan with filters
,09-16 11:51:52.716  5612  5631 D BtGatt.ScanManager: handling starting scan
09-16 11:51:52.717  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:51:52.717  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:51:52.717  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 11:51:52.717  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 11:51:52.721  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:51:52.721  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:51:52.721  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:51:52.722  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 11:51:52.722  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:51:52.723  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:52.723  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 11:51:52.728  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 11:51:52.729  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:52.729  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:51:52.729  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:51:52.739  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 11:51:52.739  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:51:52.745  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 11:51:52.745  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:51:52.846   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:51:53.167  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:51:53.221  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 11:51:53.221  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 11:51:53.221  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:51:53.846   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:51:55.216   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:51:55.219   927  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 56
,09-16 11:51:55.732  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:51:55.732  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 11:51:55.732  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:51:55.732  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:55.733  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 11:51:55.733  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 11:51:55.733  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 11:51:55.733  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 11:51:55.733  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 11:51:55.734  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:51:55.734  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 11:51:55.736  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:51:55.737  5612  5648 D BtGatt.GattService: stopScan() - queue size =1
,09-16 11:51:55.739  5612  5623 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 11:51:55.741  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:51:55.742  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-16 11:51:55.742  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 11:51:55.743  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:51:55.743  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 11:51:55.751  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:51:55.751  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:51:55.751  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:51:55.752  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:51:55.753  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:51:55.754  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 11:51:55.754  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:55.754  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
09-16 11:51:55.756  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:55.757  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:51:55.757  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:55.757  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:51:55.757  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:51:55.757  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 11:51:55.757  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:51:55.757  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83c4747 removed from the list
09-16 11:51:55.757  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:55.757  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74c2b74 removed from the list
09-16 11:51:55.757  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:55.757  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:55.758  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:55.758  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:55.759  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:55.759  5612  5612 D BtGatt.ScanManager: awakened up at time 421426
09-16 11:51:55.759  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:51:55.759  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:55.759  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74c2b74 not in the list
,09-16 11:51:55.759  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:55.759  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:55.761  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:51:55.761  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:55.761  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:55.761  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74c2b74 not in the list
,09-16 11:51:55.761  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:55.761  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 11:51:55.761  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:55.761  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83c4747 not in the list
,09-16 11:51:55.762  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 11:51:55.762  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd9199 added. We now have 3 listener(s)
09-16 11:51:55.764  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 11:51:55.764  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 11:51:55.764  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:55.764  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 11:51:55.764  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:51:55.764  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 11:51:55.765  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:51:55.765  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9cc5e added. We now have 4 listener(s)
09-16 11:51:55.765  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:51:55.765  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 11:51:55.770  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:51:55.774  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 11:51:55.777  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:51:55.777  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:51:55.778  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:51:55.778  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:51:55.778  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:51:55.778  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 11:51:55.778  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:55.778  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 11:51:55.778  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 11:51:55.778  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd9199 removed from the list
09-16 11:51:55.778  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:55.778  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9cc5e removed from the list
09-16 11:51:55.781  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:55.781  5357  5403 D io.jxcore.node.ConnectivityMonitor: stop
09-16 11:51:55.781  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:55.782  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:55.783  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:55.784  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:55.784  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:51:55.785  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:55.785  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9cc5e not in the list
09-16 11:51:55.785  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:55.785  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 11:51:55.786  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:51:55.786  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:51:55.786  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 11:51:55.786  5357  5403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9cc5e not in the list
09-16 11:51:55.786  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 11:51:55.786  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 11:51:55.786  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:51:55.786  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 11:51:55.786  5357  5403 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd9199 not in the list
09-16 11:51:55.787  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-16 11:51:55.787  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 11:51:55.787  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 11:51:55.787  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:51:55.787  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:51:55.787  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:51:55.794  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=10
,09-16 11:51:55.795  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:51:55.795  5612  5628 D BtGatt.GattService: current time is 421461715778
09-16 11:51:55.795  5612  5628 D BtGatt.GattService: Batch record : [40, -77, 62, -98, 2, 117, 1, -128, -59, 60, 0, 0, 0, 111, -48, 121, 119, -3, 123, 1, -128, -72, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -88, -127, -107, -23, 95, 111, 0, 85, -113, -37, 31, -33, 8, 0, 4, -99, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 40, -77, 62, -98, 2, 117, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -82, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -88, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 11:51:55.796  5612  5628 D BtGatt.GattService: ScanRecord : []
09-16 11:51:55.797  5612  5628 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -88, -127, -107, -23, 95, 111]
09-16 11:51:55.797  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-16 11:51:55.797  5612  5628 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62]
,09-16 11:51:55.797  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-16 11:51:55.798  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 11:51:55.798  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 11:51:55.798  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 11:51:55.798  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 11:51:55.798  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 11:51:56.257  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:51:57.798  5357  5706 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: My test thread name)
,09-16 11:51:58.237   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:51:58.241   927  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-16 11:51:59.797  5357  5403 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 182
,09-16 11:51:59.798  5357  5403 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 182, name: My test thread name)
09-16 11:51:59.802  5357  5707 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: My test thread name)
09-16 11:51:59.803  5357  5707 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: My test thread name)
,09-16 11:51:59.803  5357  5707 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-16 11:51:59.807  5357  5403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 11:51:59.813  5357  5708 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-16 11:51:59.814  5357  5708 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 187, thread name: My test thread name): Test exception.
09-16 11:51:59.814  5357  5708 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-16 11:51:59.820  5357  5403 I jxcore-log: Total number of executed tests:  82
09-16 11:51:59.820  5357  5403 I jxcore-log: 
,09-16 11:51:59.821  5357  5403 I jxcore-log: Number of passed tests:  81
09-16 11:51:59.821  5357  5403 I jxcore-log: 
09-16 11:51:59.821  5357  5403 I jxcore-log: Number of failed tests:  1
09-16 11:51:59.821  5357  5403 I jxcore-log: 
,09-16 11:51:59.821  5357  5403 I jxcore-log: Number of ignored tests:  0
09-16 11:51:59.821  5357  5403 I jxcore-log: 
09-16 11:51:59.821  5357  5403 I jxcore-log: Total duration:  95782
09-16 11:51:59.821  5357  5403 I jxcore-log: 
,09-16 11:51:59.823  5357  5403 I jxcore-log: Failures: 
09-16 11:51:59.823  5357  5403 I jxcore-log:  DiscoveryManager1 isRunning should return true
09-16 11:51:59.823  5357  5403 I jxcore-log: Expected: is <true>
09-16 11:51:59.823  5357  5403 I jxcore-log:      but: was <false>
09-16 11:51:59.823  5357  5403 I jxcore-log: 
09-16 11:51:59.823  5357  5403 I jxcore-log: 
09-16 11:51:59.823  5357  5403 I jxcore-log: Failed to execute UT.
09-16 11:51:59.823  5357  5403 I jxcore-log: 
,09-16 11:51:59.828  5357  5403 I jxcore-log: Unit Test app is loaded
09-16 11:51:59.828  5357  5403 I jxcore-log: 
,09-16 11:51:59.841  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.841  5357  5403 I jxcore-log: 
,09-16 11:51:59.847  5357  5357 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-16 11:51:59.847  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.847  5357  5403 I jxcore-log: 
,09-16 11:51:59.849  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.849  5357  5403 I jxcore-log: 
,09-16 11:51:59.851  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.851  5357  5403 I jxcore-log: 
,09-16 11:51:59.853  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.853  5357  5403 I jxcore-log: 
,09-16 11:51:59.856  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.856  5357  5403 I jxcore-log: 
,09-16 11:51:59.859  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.859  5357  5403 I jxcore-log: 
,09-16 11:51:59.861  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.861  5357  5403 I jxcore-log: 
,09-16 11:51:59.862  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.862  5357  5403 I jxcore-log: 
,09-16 11:51:59.863  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.863  5357  5403 I jxcore-log: 
,09-16 11:51:59.864  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.864  5357  5403 I jxcore-log: 
09-16 11:51:59.865  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.865  5357  5403 I jxcore-log: 
09-16 11:51:59.866  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.866  5357  5403 I jxcore-log: 
09-16 11:51:59.867  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.867  5357  5403 I jxcore-log: 
09-16 11:51:59.868  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.868  5357  5403 I jxcore-log: 
,09-16 11:51:59.869  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.869  5357  5403 I jxcore-log: 
09-16 11:51:59.869  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.869  5357  5403 I jxcore-log: 
,09-16 11:51:59.870  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.870  5357  5403 I jxcore-log: 
,09-16 11:51:59.871  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.871  5357  5403 I jxcore-log: 
09-16 11:51:59.873  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.873  5357  5403 I jxcore-log: 
09-16 11:51:59.874  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.874  5357  5403 I jxcore-log: 
,09-16 11:51:59.875  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.875  5357  5403 I jxcore-log: 
,09-16 11:51:59.876  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.876  5357  5403 I jxcore-log: 
09-16 11:51:59.876  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.876  5357  5403 I jxcore-log: 
09-16 11:51:59.877  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.877  5357  5403 I jxcore-log: 
,09-16 11:51:59.878  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.878  5357  5403 I jxcore-log: 
,09-16 11:51:59.878  5357  5706 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
09-16 11:51:59.879  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.879  5357  5403 I jxcore-log: 
09-16 11:51:59.880  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.880  5357  5403 I jxcore-log: 
09-16 11:51:59.881  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.881  5357  5403 I jxcore-log: 
09-16 11:51:59.881  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.881  5357  5403 I jxcore-log: 
09-16 11:51:59.881  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.881  5357  5403 I jxcore-log: 
09-16 11:51:59.882  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.882  5357  5403 I jxcore-log: 
09-16 11:51:59.882  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.882  5357  5403 I jxcore-log: 
09-16 11:51:59.883  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 11:51:59.883  5357  5403 I jxcore-log: 
,09-16 11:51:59.884  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.884  5357  5403 I jxcore-log: 
,09-16 11:51:59.885  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 11:51:59.885  5357  5403 I jxcore-log: 
09-16 11:51:59.886  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.886  5357  5403 I jxcore-log: 
09-16 11:51:59.886  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.886  5357  5403 I jxcore-log: 
09-16 11:51:59.887  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.887  5357  5403 I jxcore-log: 
09-16 11:51:59.888  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.888  5357  5403 I jxcore-log: 
09-16 11:51:59.888  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.888  5357  5403 I jxcore-log: 
09-16 11:51:59.889  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.889  5357  5403 I jxcore-log: 
09-16 11:51:59.889  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.889  5357  5403 I jxcore-log: 
09-16 11:51:59.890  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 11:51:59.890  5357  5403 I jxcore-log: 
,09-16 11:51:59.891  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.891  5357  5403 I jxcore-log: 
,09-16 11:51:59.892  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.892  5357  5403 I jxcore-log: 
,09-16 11:51:59.894  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 11:51:59.894  5357  5403 I jxcore-log: 
,09-16 11:51:59.895  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:51:59.895  5357  5403 I jxcore-log: 
,09-16 11:51:59.895  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:51:59.895  5357  5403 I jxcore-log: 
,09-16 11:51:59.901  5357  5403 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'off',
09-16 11:51:59.901  5357  5403 I jxcore-log:   bluetooth: 'off',
09-16 11:51:59.901  5357  5403 I jxcore-log:   wifi: 'on',
09-16 11:51:59.901  5357  5403 I jxcore-log:   cellular: 'doNotCare',
09-16 11:51:59.901  5357  5403 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 11:51:59.901  5357  5403 I jxcore-log: 
,09-16 11:51:59.902  5357  5403 I jxcore-log: Toggling BLUETOOTH ON
09-16 11:51:59.902  5357  5403 I jxcore-log: 
,09-16 11:51:59.904  5357  5403 D BluetoothAdapter: enable(): BT is already enabled..!
,09-16 11:51:59.912  5357  5403 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-16 11:51:59.912  5357  5403 I jxcore-log:   bluetooth: 'on',
09-16 11:51:59.912  5357  5403 I jxcore-log:   wifi: 'on',
09-16 11:51:59.912  5357  5403 I jxcore-log:   cellular: 'doNotCare',
09-16 11:51:59.912  5357  5403 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 11:51:59.912  5357  5403 I jxcore-log: 
,09-16 11:51:59.913  5357  5403 I jxcore-log: My device name is: Huawei-Nexus 6P
09-16 11:51:59.913  5357  5403 I jxcore-log: 
,09-16 11:51:59.914  5357  5403 I jxcore-log: WARN testUtils: myNameCallback not set!
09-16 11:51:59.914  5357  5403 I jxcore-log: 
09-16 11:51:59.914  5357  5403 I jxcore-log: Running for WIFI network type
09-16 11:51:59.914  5357  5403 I jxcore-log: 
,09-16 11:52:01.654  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-16 11:52:01.654  5357  5403 I jxcore-log: 
,09-16 11:52:01.950  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-16 11:52:01.950  5357  5403 I jxcore-log: 
,09-16 11:52:01.967  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-16 11:52:01.967  5357  5403 I jxcore-log: 
,09-16 11:52:01.970  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-16 11:52:01.970  5357  5403 I jxcore-log: 
,09-16 11:52:01.975  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-16 11:52:01.975  5357  5403 I jxcore-log: 
,09-16 11:52:02.014  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-16 11:52:02.014  5357  5403 I jxcore-log: 
,09-16 11:52:02.024  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-16 11:52:02.024  5357  5403 I jxcore-log: 
,09-16 11:52:02.027  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-16 11:52:02.027  5357  5403 I jxcore-log: 
,09-16 11:52:02.527  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-16 11:52:02.527  5357  5403 I jxcore-log: 
,09-16 11:52:02.535  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-16 11:52:02.535  5357  5403 I jxcore-log: 
,09-16 11:52:02.541  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-16 11:52:02.541  5357  5403 I jxcore-log: 
,09-16 11:52:02.700  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-16 11:52:02.700  5357  5403 I jxcore-log: 
,09-16 11:52:03.705  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-16 11:52:03.705  5357  5403 I jxcore-log: 
,09-16 11:52:03.738  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-16 11:52:03.738  5357  5403 I jxcore-log: 
,09-16 11:52:03.744  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-16 11:52:03.744  5357  5403 I jxcore-log: 
,09-16 11:52:03.830  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-16 11:52:03.830  5357  5403 I jxcore-log: 
,09-16 11:52:03.845  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-16 11:52:03.845  5357  5403 I jxcore-log: 
,09-16 11:52:03.848  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-16 11:52:03.848  5357  5403 I jxcore-log: 
,09-16 11:52:03.852  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-16 11:52:03.852  5357  5403 I jxcore-log: 
,09-16 11:52:03.864  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-16 11:52:03.864  5357  5403 I jxcore-log: 
,09-16 11:52:03.923  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-16 11:52:03.923  5357  5403 I jxcore-log: 
,09-16 11:52:03.927  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-16 11:52:03.927  5357  5403 I jxcore-log: 
,09-16 11:52:03.947  5357  5403 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-16 11:52:03.947  5357  5403 I jxcore-log: 
,09-16 11:52:03.955  5357  5403 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-16 11:52:03.956  5357  5403 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-16 11:52:03.956  5357  5403 I jxcore-log: 
,09-16 11:52:03.958  5357  5403 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-16 11:52:03.958  5357  5403 I jxcore-log: 
,09-16 11:52:03.958  5357  5403 I jxcore-log: ThaliTape :: Started ThaliTape
09-16 11:52:03.958  5357  5403 I jxcore-log: 
,09-16 11:52:03.962  5357  5403 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-16 11:52:03.962  5357  5403 I jxcore-log: 
,09-16 11:52:04.279  5357  5403 I jxcore-log: ThaliTape :: Connected to the test server
09-16 11:52:04.279  5357  5403 I jxcore-log: 
,09-16 11:52:06.821  5357  5403 I jxcore-log: TAP version 13
09-16 11:52:06.821  5357  5403 I jxcore-log: 
,09-16 11:52:06.825  5357  5403 I jxcore-log: # setup
09-16 11:52:06.825  5357  5403 I jxcore-log: 
,09-16 11:52:06.955  5357  5403 I jxcore-log: # 1. calling createNativeListener directly rejects
09-16 11:52:06.955  5357  5403 I jxcore-log: 
,09-16 11:52:07.218  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:07.218  5357  5403 I jxcore-log: 
,09-16 11:52:07.224  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 48907
09-16 11:52:07.224  5357  5403 I jxcore-log: 
,09-16 11:52:07.235  5357  5403 I jxcore-log: ok 1 Should throw
09-16 11:52:07.235  5357  5403 I jxcore-log: 
,09-16 11:52:07.239  5357  5403 I jxcore-log: # teardown
09-16 11:52:07.239  5357  5403 I jxcore-log: 
,09-16 11:52:07.499  5357  5403 I jxcore-log: # setup
09-16 11:52:07.499  5357  5403 I jxcore-log: 
,09-16 11:52:07.898  5357  5403 I jxcore-log: # 2. emits incomingConnectionState
09-16 11:52:07.898  5357  5403 I jxcore-log: 
,09-16 11:52:08.091  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:08.091  5357  5403 I jxcore-log: 
,09-16 11:52:08.099  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 47147
09-16 11:52:08.099  5357  5403 I jxcore-log: 
,09-16 11:52:08.112  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:08.112  5357  5403 I jxcore-log: 
,09-16 11:52:08.116  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:08.116  5357  5403 I jxcore-log: 
,09-16 11:52:08.154  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:08.154  5357  5403 I jxcore-log: 
,09-16 11:52:08.160  5357  5403 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-16 11:52:08.160  5357  5403 I jxcore-log: 
,09-16 11:52:08.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:08.180  5357  5403 I jxcore-log: 
,09-16 11:52:08.181  5357  5403 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-16 11:52:08.181  5357  5403 I jxcore-log: 
,09-16 11:52:08.187  5357  5403 I jxcore-log: # teardown
09-16 11:52:08.187  5357  5403 I jxcore-log: 
,09-16 11:52:08.348  5357  5403 I jxcore-log: # setup
09-16 11:52:08.348  5357  5403 I jxcore-log: 
,09-16 11:52:08.722  5357  5403 I jxcore-log: # 3. emits routerPortConnectionFailed
09-16 11:52:08.722  5357  5403 I jxcore-log: 
,09-16 11:52:08.840  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:08.840  5357  5403 I jxcore-log: 
,09-16 11:52:08.846  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 48699
09-16 11:52:08.846  5357  5403 I jxcore-log: 
,09-16 11:52:08.857  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:08.857  5357  5403 I jxcore-log: 
,09-16 11:52:08.859  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:08.859  5357  5403 I jxcore-log: 
,09-16 11:52:08.861  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:08.861  5357  5403 I jxcore-log: 
,09-16 11:52:08.896  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:08.896  5357  5403 I jxcore-log: 
,09-16 11:52:08.898  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:08.898  5357  5403 I jxcore-log: 
,09-16 11:52:08.903  5357  5403 I jxcore-log: DEBUG createNativeListener: 
09-16 11:52:08.903  5357  5403 I jxcore-log: 
,09-16 11:52:08.904  5357  5403 I jxcore-log: ok 4 tried to connect to right port
09-16 11:52:08.904  5357  5403 I jxcore-log: 
,09-16 11:52:08.905  5357  5403 I jxcore-log: ok 5 failed due to refused connection
09-16 11:52:08.905  5357  5403 I jxcore-log: 
,09-16 11:52:08.906  5357  5403 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-16 11:52:08.906  5357  5403 I jxcore-log: 
,09-16 11:52:08.908  5357  5403 I jxcore-log: # teardown
09-16 11:52:08.908  5357  5403 I jxcore-log: 
,09-16 11:52:08.909  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:08.909  5357  5403 I jxcore-log: 
,09-16 11:52:09.044  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:09.044  5357  5403 I jxcore-log: 
,09-16 11:52:09.050  5357  5403 I jxcore-log: # setup
09-16 11:52:09.050  5357  5403 I jxcore-log: 
09-16 11:52:09.052  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:09.052  5357  5403 I jxcore-log: 
,09-16 11:52:09.225  5357  5403 I jxcore-log: # 4. native server connections all up
09-16 11:52:09.225  5357  5403 I jxcore-log: 
,09-16 11:52:09.404  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:09.404  5357  5403 I jxcore-log: 
,09-16 11:52:09.413  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 38365
09-16 11:52:09.413  5357  5403 I jxcore-log: 
,09-16 11:52:09.425  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:09.425  5357  5403 I jxcore-log: 
,09-16 11:52:09.427  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:09.427  5357  5403 I jxcore-log: 
,09-16 11:52:09.429  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:09.429  5357  5403 I jxcore-log: 
,09-16 11:52:09.463  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:09.463  5357  5403 I jxcore-log: 
,09-16 11:52:09.467  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:09.467  5357  5403 I jxcore-log: 
,09-16 11:52:09.470  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:09.470  5357  5403 I jxcore-log: 
,09-16 11:52:09.473  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:09.473  5357  5403 I jxcore-log: 
,09-16 11:52:09.512  5357  5403 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-16 11:52:09.512  5357  5403 I jxcore-log: 
,09-16 11:52:09.512  5357  5403 I jxcore-log: ok 8 Send/recvd #1 should be same
09-16 11:52:09.512  5357  5403 I jxcore-log: 
,09-16 11:52:09.516  5357  5403 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-16 11:52:09.516  5357  5403 I jxcore-log: 
,09-16 11:52:09.516  5357  5403 I jxcore-log: ok 10 Send/recvd #2 should be same
09-16 11:52:09.516  5357  5403 I jxcore-log: 
09-16 11:52:09.519  5357  5403 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-16 11:52:09.519  5357  5403 I jxcore-log: 
,09-16 11:52:09.527  5357  5403 I jxcore-log: # teardown
09-16 11:52:09.527  5357  5403 I jxcore-log: 
,09-16 11:52:09.557  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:09.557  5357  5403 I jxcore-log: 
,09-16 11:52:09.558  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:09.558  5357  5403 I jxcore-log: 
,09-16 11:52:09.560  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:09.560  5357  5403 I jxcore-log: 
,09-16 11:52:09.564  5357  5403 I jxcore-log: # setup
09-16 11:52:09.564  5357  5403 I jxcore-log: 
,09-16 11:52:09.566  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:09.566  5357  5403 I jxcore-log: 
,09-16 11:52:09.633  5357  5403 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-16 11:52:09.633  5357  5403 I jxcore-log: 
,09-16 11:52:09.708  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:09.708  5357  5403 I jxcore-log: 
,09-16 11:52:09.715  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 43723
09-16 11:52:09.715  5357  5403 I jxcore-log: 
,09-16 11:52:09.728  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:09.728  5357  5403 I jxcore-log: 
,09-16 11:52:09.730  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:09.730  5357  5403 I jxcore-log: 
09-16 11:52:09.732  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:09.732  5357  5403 I jxcore-log: 
,09-16 11:52:09.752  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:09.752  5357  5403 I jxcore-log: 
,09-16 11:52:09.756  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:09.756  5357  5403 I jxcore-log: 
,09-16 11:52:09.770  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:09.770  5357  5403 I jxcore-log: 
,09-16 11:52:09.784  5357  5403 I jxcore-log: ok 12 socket shouldn't close until after stream
09-16 11:52:09.784  5357  5403 I jxcore-log: 
,09-16 11:52:09.785  5357  5403 I jxcore-log: ok 13 incoming remains open
09-16 11:52:09.785  5357  5403 I jxcore-log: 
,09-16 11:52:09.788  5357  5403 I jxcore-log: # teardown
09-16 11:52:09.788  5357  5403 I jxcore-log: 
,09-16 11:52:09.843  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:09.843  5357  5403 I jxcore-log: 
,09-16 11:52:09.852  5357  5403 I jxcore-log: # setup
09-16 11:52:09.852  5357  5403 I jxcore-log: 
,09-16 11:52:09.856  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:09.856  5357  5403 I jxcore-log: 
,09-16 11:52:09.959  5357  5403 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-16 11:52:09.959  5357  5403 I jxcore-log: 
,09-16 11:52:10.018  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:10.018  5357  5403 I jxcore-log: 
,09-16 11:52:10.023  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 44340
09-16 11:52:10.023  5357  5403 I jxcore-log: 
,09-16 11:52:10.033  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.033  5357  5403 I jxcore-log: 
,09-16 11:52:10.035  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.035  5357  5403 I jxcore-log: 
,09-16 11:52:10.038  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.038  5357  5403 I jxcore-log: 
,09-16 11:52:10.052  5357  5403 I jxcore-log: ok 14 we should not have gotten an error
09-16 11:52:10.052  5357  5403 I jxcore-log: 
,09-16 11:52:10.065  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:10.065  5357  5403 I jxcore-log: 
,09-16 11:52:10.070  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:10.070  5357  5403 I jxcore-log: 
,09-16 11:52:10.079  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:10.079  5357  5403 I jxcore-log: 
,09-16 11:52:10.081  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:10.081  5357  5403 I jxcore-log: 
,09-16 11:52:10.089  5357  5403 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-16 11:52:10.089  5357  5403 I jxcore-log: 
,09-16 11:52:10.089  5357  5403 I jxcore-log: ok 16 incoming is cleaned up
09-16 11:52:10.089  5357  5403 I jxcore-log: 
,09-16 11:52:10.092  5357  5403 I jxcore-log: # teardown
09-16 11:52:10.092  5357  5403 I jxcore-log: 
,09-16 11:52:10.137  5357  5403 I jxcore-log: # setup
09-16 11:52:10.137  5357  5403 I jxcore-log: 
,09-16 11:52:10.180  5357  5403 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-16 11:52:10.180  5357  5403 I jxcore-log: 
,09-16 11:52:10.270  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:10.270  5357  5403 I jxcore-log: 
,09-16 11:52:10.277  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 47979
09-16 11:52:10.277  5357  5403 I jxcore-log: 
,09-16 11:52:10.289  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.289  5357  5403 I jxcore-log: 
,09-16 11:52:10.291  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.291  5357  5403 I jxcore-log: 
,09-16 11:52:10.294  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.294  5357  5403 I jxcore-log: 
,09-16 11:52:10.310  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:10.310  5357  5403 I jxcore-log: 
,09-16 11:52:10.312  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:10.312  5357  5403 I jxcore-log: 
,09-16 11:52:10.325  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:10.325  5357  5403 I jxcore-log: 
,09-16 11:52:10.337  5357  5403 I jxcore-log: ok 17 stream was closed
09-16 11:52:10.337  5357  5403 I jxcore-log: 
,09-16 11:52:10.337  5357  5403 I jxcore-log: ok 18 incoming should survive
09-16 11:52:10.337  5357  5403 I jxcore-log: 
09-16 11:52:10.338  5357  5403 I jxcore-log: ok 19 mux should have no streams
09-16 11:52:10.338  5357  5403 I jxcore-log: 
,09-16 11:52:10.342  5357  5403 I jxcore-log: # teardown
09-16 11:52:10.342  5357  5403 I jxcore-log: 
,09-16 11:52:10.422  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:10.422  5357  5403 I jxcore-log: 
,09-16 11:52:10.427  5357  5403 I jxcore-log: # setup
09-16 11:52:10.427  5357  5403 I jxcore-log: 
,09-16 11:52:10.428  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:10.428  5357  5403 I jxcore-log: 
,09-16 11:52:10.538  5357  5403 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-16 11:52:10.538  5357  5403 I jxcore-log: 
,09-16 11:52:10.608  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:10.608  5357  5403 I jxcore-log: 
,09-16 11:52:10.614  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 40833
09-16 11:52:10.614  5357  5403 I jxcore-log: 
,09-16 11:52:10.623  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.623  5357  5403 I jxcore-log: 
,09-16 11:52:10.625  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.625  5357  5403 I jxcore-log: 
,09-16 11:52:10.627  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.627  5357  5403 I jxcore-log: 
,09-16 11:52:10.638  5357  5403 I jxcore-log: ok 20 we should not have gotten an error
09-16 11:52:10.638  5357  5403 I jxcore-log: 
,09-16 11:52:10.648  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:10.648  5357  5403 I jxcore-log: 
,09-16 11:52:10.652  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:10.652  5357  5403 I jxcore-log: 
,09-16 11:52:10.663  5357  5403 I jxcore-log: ok 21 Buffers are identical
09-16 11:52:10.663  5357  5403 I jxcore-log: 
,09-16 11:52:10.665  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:10.665  5357  5403 I jxcore-log: 
,09-16 11:52:10.667  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:10.667  5357  5403 I jxcore-log: 
09-16 11:52:10.669  5357  5403 I jxcore-log: ok 22 native server is nulled out
09-16 11:52:10.669  5357  5403 I jxcore-log: 
09-16 11:52:10.670  5357  5403 I jxcore-log: ok 23 native server should be closed
09-16 11:52:10.670  5357  5403 I jxcore-log: 
09-16 11:52:10.670  5357  5403 I jxcore-log: ok 24 incoming has been removed
09-16 11:52:10.670  5357  5403 I jxcore-log: 
,09-16 11:52:10.671  5357  5403 I jxcore-log: ok 25 Incoming should be done
09-16 11:52:10.671  5357  5403 I jxcore-log: 
,09-16 11:52:10.671  5357  5403 I jxcore-log: ok 26 The mux object should be closed
09-16 11:52:10.671  5357  5403 I jxcore-log: 
09-16 11:52:10.672  5357  5403 I jxcore-log: ok 27 The mux stream should be closed
09-16 11:52:10.672  5357  5403 I jxcore-log: 
09-16 11:52:10.673  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:10.673  5357  5403 I jxcore-log: 
,09-16 11:52:10.685  5357  5403 I jxcore-log: # teardown
09-16 11:52:10.685  5357  5403 I jxcore-log: 
,09-16 11:52:10.739  5357  5403 I jxcore-log: # setup
09-16 11:52:10.739  5357  5403 I jxcore-log: 
,09-16 11:52:10.780  5357  5403 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-16 11:52:10.780  5357  5403 I jxcore-log: 
,09-16 11:52:10.866  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:10.866  5357  5403 I jxcore-log: 
,09-16 11:52:10.870  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 38675
09-16 11:52:10.870  5357  5403 I jxcore-log: 
,09-16 11:52:10.904  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.904  5357  5403 I jxcore-log: 
,09-16 11:52:10.905  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.905  5357  5403 I jxcore-log: 
09-16 11:52:10.907  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.907  5357  5403 I jxcore-log: 
,09-16 11:52:10.910  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.910  5357  5403 I jxcore-log: 
,09-16 11:52:10.911  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.911  5357  5403 I jxcore-log: 
,09-16 11:52:10.913  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.913  5357  5403 I jxcore-log: 
,09-16 11:52:10.916  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.916  5357  5403 I jxcore-log: 
,09-16 11:52:10.917  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.917  5357  5403 I jxcore-log: 
09-16 11:52:10.918  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.918  5357  5403 I jxcore-log: 
,09-16 11:52:10.921  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.921  5357  5403 I jxcore-log: 
,09-16 11:52:10.922  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.922  5357  5403 I jxcore-log: 
09-16 11:52:10.923  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.923  5357  5403 I jxcore-log: 
,09-16 11:52:10.926  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.926  5357  5403 I jxcore-log: 
,09-16 11:52:10.927  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.927  5357  5403 I jxcore-log: 
,09-16 11:52:10.928  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.928  5357  5403 I jxcore-log: 
09-16 11:52:10.931  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.931  5357  5403 I jxcore-log: 
,09-16 11:52:10.931  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.931  5357  5403 I jxcore-log: 
,09-16 11:52:10.932  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.932  5357  5403 I jxcore-log: 
,09-16 11:52:10.935  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.935  5357  5403 I jxcore-log: 
,09-16 11:52:10.935  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.935  5357  5403 I jxcore-log: 
,09-16 11:52:10.941  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.941  5357  5403 I jxcore-log: 
,09-16 11:52:10.947  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.947  5357  5403 I jxcore-log: 
,09-16 11:52:10.949  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.949  5357  5403 I jxcore-log: 
,09-16 11:52:10.950  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.950  5357  5403 I jxcore-log: 
,09-16 11:52:10.952  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.952  5357  5403 I jxcore-log: 
,09-16 11:52:10.953  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.953  5357  5403 I jxcore-log: 
,09-16 11:52:10.954  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.954  5357  5403 I jxcore-log: 
,09-16 11:52:10.956  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:10.956  5357  5403 I jxcore-log: 
,09-16 11:52:10.956  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:10.956  5357  5403 I jxcore-log: 
,09-16 11:52:10.958  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:10.958  5357  5403 I jxcore-log: 
,09-16 11:52:11.016  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.016  5357  5403 I jxcore-log: 
,09-16 11:52:11.017  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.017  5357  5403 I jxcore-log: 
,09-16 11:52:11.025  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.025  5357  5403 I jxcore-log: 
,09-16 11:52:11.027  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.027  5357  5403 I jxcore-log: 
,09-16 11:52:11.028  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.028  5357  5403 I jxcore-log: 
,09-16 11:52:11.029  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.029  5357  5403 I jxcore-log: 
,09-16 11:52:11.030  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.030  5357  5403 I jxcore-log: 
,09-16 11:52:11.031  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.031  5357  5403 I jxcore-log: 
,09-16 11:52:11.033  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.033  5357  5403 I jxcore-log: 
,09-16 11:52:11.034  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.034  5357  5403 I jxcore-log: 
,09-16 11:52:11.035  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.035  5357  5403 I jxcore-log: 
09-16 11:52:11.036  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.036  5357  5403 I jxcore-log: 
09-16 11:52:11.036  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.036  5357  5403 I jxcore-log: 
,09-16 11:52:11.037  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.037  5357  5403 I jxcore-log: 
,09-16 11:52:11.038  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.038  5357  5403 I jxcore-log: 
,09-16 11:52:11.039  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.039  5357  5403 I jxcore-log: 
09-16 11:52:11.040  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.040  5357  5403 I jxcore-log: 
,09-16 11:52:11.041  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.041  5357  5403 I jxcore-log: 
,09-16 11:52:11.042  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.042  5357  5403 I jxcore-log: 
,09-16 11:52:11.043  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.043  5357  5403 I jxcore-log: 
09-16 11:52:11.044  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.044  5357  5403 I jxcore-log: 
09-16 11:52:11.044  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.044  5357  5403 I jxcore-log: 
,09-16 11:52:11.045  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.045  5357  5403 I jxcore-log: 
,09-16 11:52:11.046  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.046  5357  5403 I jxcore-log: 
09-16 11:52:11.047  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.047  5357  5403 I jxcore-log: 
,09-16 11:52:11.050  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.050  5357  5403 I jxcore-log: 
,09-16 11:52:11.051  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.051  5357  5403 I jxcore-log: 
,09-16 11:52:11.051  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.051  5357  5403 I jxcore-log: 
,09-16 11:52:11.052  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.052  5357  5403 I jxcore-log: 
09-16 11:52:11.053  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.053  5357  5403 I jxcore-log: 
,09-16 11:52:11.054  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.054  5357  5403 I jxcore-log: 
,09-16 11:52:11.054  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.054  5357  5403 I jxcore-log: 
,09-16 11:52:11.055  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.055  5357  5403 I jxcore-log: 
09-16 11:52:11.056  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.056  5357  5403 I jxcore-log: 
,09-16 11:52:11.057  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.057  5357  5403 I jxcore-log: 
09-16 11:52:11.058  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.058  5357  5403 I jxcore-log: 
09-16 11:52:11.058  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.058  5357  5403 I jxcore-log: 
,09-16 11:52:11.059  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.059  5357  5403 I jxcore-log: 
,09-16 11:52:11.064  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.064  5357  5403 I jxcore-log: 
,09-16 11:52:11.065  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.065  5357  5403 I jxcore-log: 
,09-16 11:52:11.067  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.067  5357  5403 I jxcore-log: 
,09-16 11:52:11.068  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.068  5357  5403 I jxcore-log: 
,09-16 11:52:11.068  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.068  5357  5403 I jxcore-log: 
,09-16 11:52:11.069  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.069  5357  5403 I jxcore-log: 
09-16 11:52:11.070  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.070  5357  5403 I jxcore-log: 
,09-16 11:52:11.071  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.071  5357  5403 I jxcore-log: 
09-16 11:52:11.071  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.071  5357  5403 I jxcore-log: 
,09-16 11:52:11.072  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.072  5357  5403 I jxcore-log: 
09-16 11:52:11.073  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.073  5357  5403 I jxcore-log: 
,09-16 11:52:11.074  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.074  5357  5403 I jxcore-log: 
09-16 11:52:11.074  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.074  5357  5403 I jxcore-log: 
,09-16 11:52:11.075  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.075  5357  5403 I jxcore-log: 
09-16 11:52:11.075  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.075  5357  5403 I jxcore-log: 
,09-16 11:52:11.076  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.076  5357  5403 I jxcore-log: 
09-16 11:52:11.077  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.077  5357  5403 I jxcore-log: 
,09-16 11:52:11.077  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.077  5357  5403 I jxcore-log: 
,09-16 11:52:11.078  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.078  5357  5403 I jxcore-log: 
09-16 11:52:11.079  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.079  5357  5403 I jxcore-log: 
,09-16 11:52:11.080  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.080  5357  5403 I jxcore-log: 
09-16 11:52:11.080  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.080  5357  5403 I jxcore-log: 
,09-16 11:52:11.081  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.081  5357  5403 I jxcore-log: 
09-16 11:52:11.082  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.082  5357  5403 I jxcore-log: 
,09-16 11:52:11.083  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.083  5357  5403 I jxcore-log: 
,09-16 11:52:11.084  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.084  5357  5403 I jxcore-log: 
,09-16 11:52:11.085  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.085  5357  5403 I jxcore-log: 
,09-16 11:52:11.086  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.086  5357  5403 I jxcore-log: 
09-16 11:52:11.086  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.086  5357  5403 I jxcore-log: 
,09-16 11:52:11.087  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.087  5357  5403 I jxcore-log: 
09-16 11:52:11.088  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.088  5357  5403 I jxcore-log: 
,09-16 11:52:11.088  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.088  5357  5403 I jxcore-log: 
09-16 11:52:11.089  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.089  5357  5403 I jxcore-log: 
,09-16 11:52:11.090  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.090  5357  5403 I jxcore-log: 
,09-16 11:52:11.091  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.091  5357  5403 I jxcore-log: 
09-16 11:52:11.091  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.091  5357  5403 I jxcore-log: 
,09-16 11:52:11.092  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.092  5357  5403 I jxcore-log: 
09-16 11:52:11.093  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.093  5357  5403 I jxcore-log: 
09-16 11:52:11.093  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.093  5357  5403 I jxcore-log: 
,09-16 11:52:11.094  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.094  5357  5403 I jxcore-log: 
,09-16 11:52:11.095  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:11.095  5357  5403 I jxcore-log: 
09-16 11:52:11.095  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:11.095  5357  5403 I jxcore-log: 
,09-16 11:52:11.141  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.141  5357  5403 I jxcore-log: 
,09-16 11:52:11.142  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.142  5357  5403 I jxcore-log: 
09-16 11:52:11.142  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.142  5357  5403 I jxcore-log: 
,09-16 11:52:11.143  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.143  5357  5403 I jxcore-log: 
09-16 11:52:11.144  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.144  5357  5403 I jxcore-log: 
,09-16 11:52:11.145  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.145  5357  5403 I jxcore-log: 
09-16 11:52:11.145  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.145  5357  5403 I jxcore-log: 
,09-16 11:52:11.146  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.146  5357  5403 I jxcore-log: 
09-16 11:52:11.146  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.146  5357  5403 I jxcore-log: 
,09-16 11:52:11.147  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.147  5357  5403 I jxcore-log: 
09-16 11:52:11.148  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.148  5357  5403 I jxcore-log: 
,09-16 11:52:11.149  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.149  5357  5403 I jxcore-log: 
,09-16 11:52:11.150  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.150  5357  5403 I jxcore-log: 
09-16 11:52:11.151  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.151  5357  5403 I jxcore-log: 
,09-16 11:52:11.151  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.151  5357  5403 I jxcore-log: 
,09-16 11:52:11.154  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.154  5357  5403 I jxcore-log: 
,09-16 11:52:11.155  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.155  5357  5403 I jxcore-log: 
,09-16 11:52:11.156  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.156  5357  5403 I jxcore-log: 
09-16 11:52:11.156  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.156  5357  5403 I jxcore-log: 
,09-16 11:52:11.157  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.157  5357  5403 I jxcore-log: 
09-16 11:52:11.157  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.157  5357  5403 I jxcore-log: 
,09-16 11:52:11.158  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.158  5357  5403 I jxcore-log: 
09-16 11:52:11.158  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.158  5357  5403 I jxcore-log: 
,09-16 11:52:11.159  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.159  5357  5403 I jxcore-log: 
09-16 11:52:11.159  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.159  5357  5403 I jxcore-log: 
09-16 11:52:11.160  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.160  5357  5403 I jxcore-log: 
,09-16 11:52:11.161  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.161  5357  5403 I jxcore-log: 
,09-16 11:52:11.161  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.161  5357  5403 I jxcore-log: 
09-16 11:52:11.162  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.162  5357  5403 I jxcore-log: 
,09-16 11:52:11.162  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.162  5357  5403 I jxcore-log: 
09-16 11:52:11.163  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.163  5357  5403 I jxcore-log: 
,09-16 11:52:11.164  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.164  5357  5403 I jxcore-log: 
09-16 11:52:11.164  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.164  5357  5403 I jxcore-log: 
,09-16 11:52:11.165  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.165  5357  5403 I jxcore-log: 
,09-16 11:52:11.165  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.165  5357  5403 I jxcore-log: 
09-16 11:52:11.166  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.166  5357  5403 I jxcore-log: 
,09-16 11:52:11.166  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.166  5357  5403 I jxcore-log: 
09-16 11:52:11.167  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.167  5357  5403 I jxcore-log: 
,09-16 11:52:11.169  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.169  5357  5403 I jxcore-log: 
,09-16 11:52:11.170  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.170  5357  5403 I jxcore-log: 
,09-16 11:52:11.171  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.171  5357  5403 I jxcore-log: 
09-16 11:52:11.171  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.171  5357  5403 I jxcore-log: 
,09-16 11:52:11.172  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.172  5357  5403 I jxcore-log: 
09-16 11:52:11.172  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.172  5357  5403 I jxcore-log: 
,09-16 11:52:11.173  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.173  5357  5403 I jxcore-log: 
,09-16 11:52:11.173  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.173  5357  5403 I jxcore-log: 
09-16 11:52:11.174  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.174  5357  5403 I jxcore-log: 
,09-16 11:52:11.174  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.174  5357  5403 I jxcore-log: 
09-16 11:52:11.175  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:11.175  5357  5403 I jxcore-log: 
,09-16 11:52:11.175  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:11.175  5357  5403 I jxcore-log: 
,09-16 11:52:11.177  5357  5403 I jxcore-log: ok 28 native server is nulled out
09-16 11:52:11.177  5357  5403 I jxcore-log: 
,09-16 11:52:11.177  5357  5403 I jxcore-log: ok 29 native server should be closed
09-16 11:52:11.177  5357  5403 I jxcore-log: 
09-16 11:52:11.178  5357  5403 I jxcore-log: ok 30 incoming has been removed
09-16 11:52:11.178  5357  5403 I jxcore-log: 
,09-16 11:52:11.178  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.178  5357  5403 I jxcore-log: 
09-16 11:52:11.179  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.179  5357  5403 I jxcore-log: 
09-16 11:52:11.179  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.179  5357  5403 I jxcore-log: 
,09-16 11:52:11.179  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.179  5357  5403 I jxcore-log: 
09-16 11:52:11.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.180  5357  5403 I jxcore-log: 
09-16 11:52:11.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.180  5357  5403 I jxcore-log: 
09-16 11:52:11.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.180  5357  5403 I jxcore-log: 
09-16 11:52:11.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.180  5357  5403 I jxcore-log: 
09-16 11:52:11.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.180  5357  5403 I jxcore-log: 
09-16 11:52:11.180  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:11.180  5357  5403 I jxcore-log: 
,09-16 11:52:11.261  5357  5403 I jxcore-log: # teardown
09-16 11:52:11.261  5357  5403 I jxcore-log: 
,09-16 11:52:11.343  5357  5403 I jxcore-log: # setup
09-16 11:52:11.343  5357  5403 I jxcore-log: 
,09-16 11:52:12.496  5357  5403 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-16 11:52:12.496  5357  5403 I jxcore-log: 
,09-16 11:52:12.904  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:12.904  5357  5403 I jxcore-log: 
,09-16 11:52:12.910  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 45815
09-16 11:52:12.910  5357  5403 I jxcore-log: 
,09-16 11:52:12.920  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:12.920  5357  5403 I jxcore-log: 
,09-16 11:52:12.922  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:12.922  5357  5403 I jxcore-log: 
,09-16 11:52:12.924  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:12.924  5357  5403 I jxcore-log: 
,09-16 11:52:12.935  5357  5403 I jxcore-log: ok 31 we should not have gotten an error
09-16 11:52:12.935  5357  5403 I jxcore-log: 
,09-16 11:52:12.942  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:12.942  5357  5403 I jxcore-log: 
,09-16 11:52:12.945  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:12.945  5357  5403 I jxcore-log: 
,09-16 11:52:12.957  5357  5403 I jxcore-log: ok 32 Buffers are identical
09-16 11:52:12.957  5357  5403 I jxcore-log: 
,09-16 11:52:12.958  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:12.958  5357  5403 I jxcore-log: 
09-16 11:52:12.960  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:12.960  5357  5403 I jxcore-log: 
,09-16 11:52:12.975  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:12.975  5357  5403 I jxcore-log: 
,09-16 11:52:12.976  5357  5403 I jxcore-log: ok 33 server should be fine
09-16 11:52:12.976  5357  5403 I jxcore-log: 
09-16 11:52:12.976  5357  5403 I jxcore-log: ok 34 server should be open
09-16 11:52:12.976  5357  5403 I jxcore-log: 
09-16 11:52:12.977  5357  5403 I jxcore-log: ok 35 incoming has been removed
09-16 11:52:12.977  5357  5403 I jxcore-log: 
,09-16 11:52:12.977  5357  5403 I jxcore-log: ok 36 The mux object should be closed
09-16 11:52:12.977  5357  5403 I jxcore-log: 
09-16 11:52:12.977  5357  5403 I jxcore-log: ok 37 The mux stream should be closed
09-16 11:52:12.977  5357  5403 I jxcore-log: 
,09-16 11:52:12.981  5357  5403 I jxcore-log: # teardown
09-16 11:52:12.981  5357  5403 I jxcore-log: 
,09-16 11:52:13.932  5357  5403 I jxcore-log: # setup
09-16 11:52:13.932  5357  5403 I jxcore-log: 
,09-16 11:52:14.252   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:52:14.288  5357  5403 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-16 11:52:14.288  5357  5403 I jxcore-log: 
,09-16 11:52:15.058  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:15.058  5357  5403 I jxcore-log: 
,09-16 11:52:15.065  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 49525
09-16 11:52:15.065  5357  5403 I jxcore-log: 
,09-16 11:52:15.086  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:15.086  5357  5403 I jxcore-log: 
,09-16 11:52:15.088  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:15.088  5357  5403 I jxcore-log: 
,09-16 11:52:15.089  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:15.089  5357  5403 I jxcore-log: 
,09-16 11:52:15.097  5357  5403 I jxcore-log: ok 38 we should not have gotten an error
09-16 11:52:15.097  5357  5403 I jxcore-log: 
,09-16 11:52:15.104  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:15.104  5357  5403 I jxcore-log: 
,09-16 11:52:15.107  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:15.107  5357  5403 I jxcore-log: 
,09-16 11:52:15.114  5357  5403 I jxcore-log: ok 39 Buffers are identical
09-16 11:52:15.114  5357  5403 I jxcore-log: 
,09-16 11:52:15.120  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 11:52:15.120  5357  5403 I jxcore-log: 
,09-16 11:52:15.121  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:15.121  5357  5403 I jxcore-log: 
09-16 11:52:15.122  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:52:15.122  5357  5403 I jxcore-log: 
,09-16 11:52:15.127  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:52:15.127  5357  5403 I jxcore-log: 
,09-16 11:52:15.127  5357  5403 I jxcore-log: ok 40 server should be fine
09-16 11:52:15.127  5357  5403 I jxcore-log: 
09-16 11:52:15.127  5357  5403 I jxcore-log: ok 41 server should be open
09-16 11:52:15.127  5357  5403 I jxcore-log: 
09-16 11:52:15.128  5357  5403 I jxcore-log: ok 42 incoming has been removed
09-16 11:52:15.128  5357  5403 I jxcore-log: 
09-16 11:52:15.128  5357  5403 I jxcore-log: ok 43 The mux object should be closed
09-16 11:52:15.128  5357  5403 I jxcore-log: 
09-16 11:52:15.128  5357  5403 I jxcore-log: ok 44 The mux stream should be closed
09-16 11:52:15.128  5357  5403 I jxcore-log: 
,09-16 11:52:15.133  5357  5403 I jxcore-log: # teardown
09-16 11:52:15.133  5357  5403 I jxcore-log: 
,09-16 11:52:15.574  5357  5403 I jxcore-log: # setup
09-16 11:52:15.574  5357  5403 I jxcore-log: 
,09-16 11:52:16.283  5357  5403 I jxcore-log: # 12. closeAll can close even when connections open
09-16 11:52:16.283  5357  5403 I jxcore-log: 
,09-16 11:52:16.821  5357  5403 I jxcore-log: ok 45 not possible to connect to the server anymore
09-16 11:52:16.821  5357  5403 I jxcore-log: 
,09-16 11:52:16.825  5357  5403 I jxcore-log: # teardown
09-16 11:52:16.825  5357  5403 I jxcore-log: 
,09-16 11:52:17.511  5357  5403 I jxcore-log: # setup
09-16 11:52:17.511  5357  5403 I jxcore-log: 
,09-16 11:52:17.567  5357  5403 I jxcore-log: # 13. closeAll with promise
09-16 11:52:17.567  5357  5403 I jxcore-log: 
,09-16 11:52:18.252  5357  5403 I jxcore-log: ok 46 not possible to connect to the server anymore
09-16 11:52:18.252  5357  5403 I jxcore-log: 
,09-16 11:52:18.261  5357  5403 I jxcore-log: # teardown
09-16 11:52:18.261  5357  5403 I jxcore-log: 
,09-16 11:52:18.291  5357  5403 I jxcore-log: # setup
09-16 11:52:18.291  5357  5403 I jxcore-log: 
,09-16 11:52:18.367  5357  5403 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
09-16 11:52:18.367  5357  5403 I jxcore-log: 
,09-16 11:52:18.539  5357  5403 I jxcore-log: ok 47 Got the right error
09-16 11:52:18.539  5357  5403 I jxcore-log: 
,09-16 11:52:18.548  5357  5403 I jxcore-log: # teardown
09-16 11:52:18.548  5357  5403 I jxcore-log: 
,09-16 11:52:18.606  5357  5403 I jxcore-log: # setup
09-16 11:52:18.606  5357  5403 I jxcore-log: 
,09-16 11:52:18.692  5357  5403 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-16 11:52:18.692  5357  5403 I jxcore-log: 
,09-16 11:52:18.847   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:52:18.848   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:52:18.867  5357  5403 I jxcore-log: # teardown
09-16 11:52:18.867  5357  5403 I jxcore-log: 
,09-16 11:52:18.918  5357  5403 I jxcore-log: # setup
09-16 11:52:18.918  5357  5403 I jxcore-log: 
,09-16 11:52:18.974  5357  5403 I jxcore-log: # 16. onPeerLost calls jxcore
09-16 11:52:18.974  5357  5403 I jxcore-log: 
,09-16 11:52:19.031  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 11:52:19.032  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ed750c added. We now have 3 listener(s)
,09-16 11:52:19.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 11:52:19.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 11:52:19.035  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 11:52:19.036  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 11:52:19.036  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cae55 added. We now have 4 listener(s)
09-16 11:52:19.036  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 11:52:19.037  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 11:52:19.043  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:52:19.052  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:52:19.055  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:52:19.055  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:52:19.055  5357  5403 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-16 11:52:19.055  5357  5403 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-16 11:52:19.060  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:52:19.063  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:52:21.058  5357  5403 I jxcore-log: onPeerLost
09-16 11:52:21.058  5357  5403 I jxcore-log: 
09-16 11:52:21.062  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:52:21.062  5357  5403 I jxcore-log: 
,09-16 11:52:21.071  5357  5403 I jxcore-log: # teardown
09-16 11:52:21.071  5357  5403 I jxcore-log: 
,09-16 11:52:21.082  5357  5403 I jxcore-log: ok 48 check if callback was fired by onPeerLost
09-16 11:52:21.082  5357  5403 I jxcore-log: 
,09-16 11:52:21.083  5357  5403 I jxcore-log: ok 49 check if peerAvailable is false
09-16 11:52:21.083  5357  5403 I jxcore-log: 
,09-16 11:52:21.136  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 11:52:21.136  5357  5403 I jxcore-log: 
,09-16 11:52:21.139  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 11:52:21.139  5357  5403 I jxcore-log: 
,09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:52:21.148  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:52:21.152  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:52:21.154  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 11:52:21.154  5357  5403 I jxcore-log: 
,09-16 11:52:21.159  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 11:52:21.159  5357  5403 I jxcore-log: 
,09-16 11:52:21.162  5357  5403 I jxcore-log: # setup
09-16 11:52:21.162  5357  5403 I jxcore-log: 
,09-16 11:52:21.164  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:52:21.164  5357  5403 I jxcore-log: 
,09-16 11:52:21.227  5357  5403 I jxcore-log: # 17. onPeerDiscovered calls jxcore
09-16 11:52:21.227  5357  5403 I jxcore-log: 
,09-16 11:52:21.310  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 11:52:21.310  5357  5403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b8b95b added. We now have 4 listener(s)
,09-16 11:52:21.315  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 11:52:21.315  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 11:52:21.315  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 11:52:21.316  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 11:52:21.362  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f82d5f8 added. We now have 5 listener(s)
09-16 11:52:21.362  5357  5403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 11:52:21.363  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 11:52:21.368  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:52:21.375  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:52:21.378  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 11:52:21.378  5357  5403 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 11:52:21.378  5357  5403 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-16 11:52:21.383  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:52:21.386  5357  5357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 11:52:23.382  5357  5403 I jxcore-log: onPeerDiscovered
09-16 11:52:23.382  5357  5403 I jxcore-log: 
,09-16 11:52:23.385  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:52:23.385  5357  5403 I jxcore-log: 
,09-16 11:52:23.395  5357  5403 I jxcore-log: # teardown
09-16 11:52:23.395  5357  5403 I jxcore-log: 
,09-16 11:52:23.403  5357  5403 I jxcore-log: ok 50 check if callback was fired by onPeerDiscovered
09-16 11:52:23.403  5357  5403 I jxcore-log: 
,09-16 11:52:23.404  5357  5403 I jxcore-log: ok 51 check if peerAvailable is true
09-16 11:52:23.404  5357  5403 I jxcore-log: 
,09-16 11:52:23.445  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 11:52:23.445  5357  5403 I jxcore-log: 
,09-16 11:52:23.448  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 11:52:23.448  5357  5403 I jxcore-log: 
,09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 11:52:23.456  5357  5403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 11:52:23.459  5357  5403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 11:52:23.461  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 11:52:23.461  5357  5403 I jxcore-log: 
,09-16 11:52:23.463  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 11:52:23.463  5357  5403 I jxcore-log: 
,09-16 11:52:23.465  5357  5403 I jxcore-log: # setup
09-16 11:52:23.465  5357  5403 I jxcore-log: 
,09-16 11:52:23.467  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 11:52:23.467  5357  5403 I jxcore-log: 
,09-16 11:52:23.567  5357  5403 I jxcore-log: # 18. test defaultDirectory
09-16 11:52:23.567  5357  5403 I jxcore-log: 
,09-16 11:52:23.650  5357  5403 I jxcore-log: ok 52 should be equal
09-16 11:52:23.650  5357  5403 I jxcore-log: 
,09-16 11:52:23.656  5357  5403 I jxcore-log: ok 53 should be equal
09-16 11:52:23.656  5357  5403 I jxcore-log: 
,09-16 11:52:23.671  5357  5403 I jxcore-log: ok 54 should be equal
09-16 11:52:23.671  5357  5403 I jxcore-log: 
,09-16 11:52:23.673  5357  5403 I jxcore-log: # teardown
09-16 11:52:23.673  5357  5403 I jxcore-log: 
,09-16 11:52:23.766  5357  5403 I jxcore-log: # setup
09-16 11:52:23.766  5357  5403 I jxcore-log: 
,09-16 11:52:23.813  5357  5403 I jxcore-log: # 19. test defaultAdapter
09-16 11:52:23.813  5357  5403 I jxcore-log: 
,09-16 11:52:23.918  5357  5403 I jxcore-log: ok 55 should be equal
09-16 11:52:23.918  5357  5403 I jxcore-log: 
,09-16 11:52:23.919  5357  5403 I jxcore-log: ok 56 should be equal
09-16 11:52:23.919  5357  5403 I jxcore-log: 
,09-16 11:52:23.925  5357  5403 I jxcore-log: ok 57 should be equal
09-16 11:52:23.925  5357  5403 I jxcore-log: 
09-16 11:52:23.926  5357  5403 I jxcore-log: ok 58 should be equal
09-16 11:52:23.926  5357  5403 I jxcore-log: 
,09-16 11:52:23.935  5357  5403 I jxcore-log: ok 59 should be equal
09-16 11:52:23.935  5357  5403 I jxcore-log: 
,09-16 11:52:23.936  5357  5403 I jxcore-log: ok 60 should be equal
09-16 11:52:23.936  5357  5403 I jxcore-log: 
,09-16 11:52:24.109  5357  5403 I jxcore-log: ok 61 should be equal
09-16 11:52:24.109  5357  5403 I jxcore-log: 
,09-16 11:52:24.110  5357  5403 I jxcore-log: ok 62 should be equal
09-16 11:52:24.110  5357  5403 I jxcore-log: 
,09-16 11:52:24.111  5357  5403 I jxcore-log: # teardown
09-16 11:52:24.111  5357  5403 I jxcore-log: 
,09-16 11:52:24.189  5357  5403 I jxcore-log: # setup
09-16 11:52:24.189  5357  5403 I jxcore-log: 
,09-16 11:52:24.297  5357  5403 I jxcore-log: # 20. enqueue and run in order
09-16 11:52:24.297  5357  5403 I jxcore-log: 
,09-16 11:52:24.465  5357  5403 I jxcore-log: ok 63 firstPromise setTimeout
09-16 11:52:24.465  5357  5403 I jxcore-log: 
,09-16 11:52:24.466  5357  5403 I jxcore-log: ok 64 firstPromise result
09-16 11:52:24.466  5357  5403 I jxcore-log: 
09-16 11:52:24.470  5357  5403 I jxcore-log: ok 65 firstPromise testValue
09-16 11:52:24.470  5357  5403 I jxcore-log: 
,09-16 11:52:24.575  5357  5403 I jxcore-log: ok 66 secondPromise setTimeout
09-16 11:52:24.575  5357  5403 I jxcore-log: 
,09-16 11:52:24.577  5357  5403 I jxcore-log: ok 67 secondPromise result
09-16 11:52:24.577  5357  5403 I jxcore-log: 
,09-16 11:52:24.578  5357  5403 I jxcore-log: ok 68 secondPromise testValue
09-16 11:52:24.578  5357  5403 I jxcore-log: 
,09-16 11:52:24.580  5357  5403 I jxcore-log: ok 69 thirdPromise in promise
09-16 11:52:24.580  5357  5403 I jxcore-log: 
,09-16 11:52:24.582  5357  5403 I jxcore-log: ok 70 thirdPromise result
09-16 11:52:24.582  5357  5403 I jxcore-log: 
,09-16 11:52:24.584  5357  5403 I jxcore-log: ok 71 thirdPromise testValue
09-16 11:52:24.584  5357  5403 I jxcore-log: 
,09-16 11:52:24.592  5357  5403 I jxcore-log: # teardown
09-16 11:52:24.592  5357  5403 I jxcore-log: 
,09-16 11:52:24.648  5357  5403 I jxcore-log: # setup
09-16 11:52:24.648  5357  5403 I jxcore-log: 
,09-16 11:52:24.719  5357  5403 I jxcore-log: # 21. enqueueAtTop and run backwards
09-16 11:52:24.719  5357  5403 I jxcore-log: 
,09-16 11:52:24.776  5357  5403 I jxcore-log: ok 72 thirdPromise - first to run
09-16 11:52:24.776  5357  5403 I jxcore-log: 
,09-16 11:52:24.778  5357  5403 I jxcore-log: ok 73 thirdPromise - in resolve
09-16 11:52:24.778  5357  5403 I jxcore-log: 
,09-16 11:52:24.779  5357  5403 I jxcore-log: ok 74 secondPromise - second to run
09-16 11:52:24.779  5357  5403 I jxcore-log: 
,09-16 11:52:24.782  5357  5403 I jxcore-log: ok 75 secondPromise - in catch
09-16 11:52:24.782  5357  5403 I jxcore-log: 
,09-16 11:52:24.784  5357  5403 I jxcore-log: ok 76 firstPromise - third to run
09-16 11:52:24.784  5357  5403 I jxcore-log: 
,09-16 11:52:24.786  5357  5403 I jxcore-log: ok 77 firstPromise - in then
09-16 11:52:24.786  5357  5403 I jxcore-log: 
,09-16 11:52:24.787  5357  5403 I jxcore-log: ok 78 testing promises
09-16 11:52:24.787  5357  5403 I jxcore-log: 
,09-16 11:52:24.792  5357  5403 I jxcore-log: # teardown
09-16 11:52:24.792  5357  5403 I jxcore-log: 
,09-16 11:52:24.843  5357  5403 I jxcore-log: # setup
09-16 11:52:24.843  5357  5403 I jxcore-log: 
,09-16 11:52:24.912  5357  5403 I jxcore-log: # 22. mix enqueue and enqueueAtTop
09-16 11:52:24.912  5357  5403 I jxcore-log: 
,09-16 11:52:24.975  5357  5403 I jxcore-log: ok 79 fourth
09-16 11:52:24.975  5357  5403 I jxcore-log: 
,09-16 11:52:24.977  5357  5403 I jxcore-log: ok 80 fourth
09-16 11:52:24.977  5357  5403 I jxcore-log: 
,09-16 11:52:24.979  5357  5403 I jxcore-log: ok 81 second
09-16 11:52:24.979  5357  5403 I jxcore-log: 
09-16 11:52:24.981  5357  5403 I jxcore-log: ok 82 secondPromise - in then
09-16 11:52:24.981  5357  5403 I jxcore-log: 
,09-16 11:52:25.085  5357  5403 I jxcore-log: ok 83 first
09-16 11:52:25.085  5357  5403 I jxcore-log: 
,09-16 11:52:25.091  5357  5403 I jxcore-log: ok 84 firstPromise - in catch
09-16 11:52:25.091  5357  5403 I jxcore-log: 
,09-16 11:52:25.093  5357  5403 I jxcore-log: ok 85 third
09-16 11:52:25.093  5357  5403 I jxcore-log: 
,09-16 11:52:25.096  5357  5403 I jxcore-log: ok 86 thirdPromise - in then
09-16 11:52:25.096  5357  5403 I jxcore-log: 
,09-16 11:52:25.098  5357  5403 I jxcore-log: ok 87 testingPromises
09-16 11:52:25.098  5357  5403 I jxcore-log: 
,09-16 11:52:25.106  5357  5403 I jxcore-log: # teardown
09-16 11:52:25.106  5357  5403 I jxcore-log: 
,09-16 11:52:25.162  5357  5403 I jxcore-log: # setup
09-16 11:52:25.162  5357  5403 I jxcore-log: 
,09-16 11:52:25.234  5357  5403 I jxcore-log: # 23. queues handled independently
09-16 11:52:25.234  5357  5403 I jxcore-log: 
,09-16 11:52:25.346  5357  5403 I jxcore-log: ok 88 all short operations completed before the long resolves
09-16 11:52:25.346  5357  5403 I jxcore-log: 
,09-16 11:52:25.355  5357  5403 I jxcore-log: # teardown
09-16 11:52:25.355  5357  5403 I jxcore-log: 
,09-16 11:52:25.494  5357  5403 I jxcore-log: # setup
09-16 11:52:25.494  5357  5403 I jxcore-log: 
,09-16 11:52:25.565  5357  5403 I jxcore-log: # 24. basic
09-16 11:52:25.565  5357  5403 I jxcore-log: 
,09-16 11:52:25.652  5357  5403 I jxcore-log: ok 89 sane
09-16 11:52:25.652  5357  5403 I jxcore-log: 
,09-16 11:52:25.658  5357  5403 I jxcore-log: # teardown
09-16 11:52:25.658  5357  5403 I jxcore-log: 
,09-16 11:52:25.712  5357  5403 I jxcore-log: # setup
09-16 11:52:25.712  5357  5403 I jxcore-log: 
,09-16 11:52:25.766  5357  5403 I jxcore-log: # 25. another
09-16 11:52:25.766  5357  5403 I jxcore-log: 
,09-16 11:52:25.816  5357  5403 I jxcore-log: ok 90 sane
09-16 11:52:25.816  5357  5403 I jxcore-log: 
,09-16 11:52:25.820  5357  5403 I jxcore-log: # teardown
09-16 11:52:25.820  5357  5403 I jxcore-log: 
,09-16 11:52:25.877  5357  5403 I jxcore-log: # setup
09-16 11:52:25.877  5357  5403 I jxcore-log: 
,09-16 11:52:25.932  5357  5403 I jxcore-log: # 26. can pass data in setup
09-16 11:52:25.932  5357  5403 I jxcore-log: 
,09-16 11:52:25.987  5357  5403 I jxcore-log: [{"uuid":"d37e4893-4d50-4c55-a58c-3359420700d3","data":"custom data"},{"uuid":"3f5b8ceb-3fc5-492d-ad5a-d1a0fd44b11c","data":"custom data"},{"uuid":"7e1d86b5-5c69-46f5-b053-76027fab52e7","data":"custom data"}]
09-16 11:52:25.987  5357  5403 I jxcore-log: 
,09-16 11:52:25.988  5357  5403 I jxcore-log: ok 91 test participant has uuid
09-16 11:52:25.988  5357  5403 I jxcore-log: 
09-16 11:52:25.989  5357  5403 I jxcore-log: ok 92 participant data matches
09-16 11:52:25.989  5357  5403 I jxcore-log: 
,09-16 11:52:25.989  5357  5403 I jxcore-log: ok 93 test participant has uuid
09-16 11:52:25.989  5357  5403 I jxcore-log: 
09-16 11:52:25.989  5357  5403 I jxcore-log: ok 94 participant data matches
09-16 11:52:25.989  5357  5403 I jxcore-log: 
09-16 11:52:25.990  5357  5403 I jxcore-log: ok 95 test participant has uuid
09-16 11:52:25.990  5357  5403 I jxcore-log: 
09-16 11:52:25.990  5357  5403 I jxcore-log: ok 96 participant data matches
09-16 11:52:25.990  5357  5403 I jxcore-log: 
,09-16 11:52:25.991  5357  5403 I jxcore-log: ok 97 own UUID is found from the participants list
09-16 11:52:25.991  5357  5403 I jxcore-log: 
09-16 11:52:25.994  5357  5403 I jxcore-log: # teardown
09-16 11:52:25.994  5357  5403 I jxcore-log: 
,09-16 11:52:26.048  5357  5403 I jxcore-log: # setup
09-16 11:52:26.048  5357  5403 I jxcore-log: 
,09-16 11:52:26.116  5357  5403 I jxcore-log: # 27. #startListeningForAdvertisements should fail if start not called
09-16 11:52:26.116  5357  5403 I jxcore-log: 
,09-16 11:52:26.175  5357  5403 I jxcore-log: ok 98 specific error should be returned
09-16 11:52:26.175  5357  5403 I jxcore-log: 
,09-16 11:52:26.178  5357  5403 I jxcore-log: # teardown
09-16 11:52:26.178  5357  5403 I jxcore-log: 
,09-16 11:52:26.231  5357  5403 I jxcore-log: ok 99 error should be null
09-16 11:52:26.231  5357  5403 I jxcore-log: 
,09-16 11:52:26.232  5357  5403 I jxcore-log: ok 100 error should be null
09-16 11:52:26.232  5357  5403 I jxcore-log: 
,09-16 11:52:26.235  5357  5403 I jxcore-log: # setup
09-16 11:52:26.235  5357  5403 I jxcore-log: 
,09-16 11:52:26.286  5357  5403 I jxcore-log: # 28. #startUpdateAdvertisingAndListening should fail if start not called
09-16 11:52:26.286  5357  5403 I jxcore-log: 
,09-16 11:52:26.356  5357  5403 I jxcore-log: ok 101 specific error should be returned
09-16 11:52:26.356  5357  5403 I jxcore-log: 
,09-16 11:52:26.359  5357  5403 I jxcore-log: # teardown
09-16 11:52:26.359  5357  5403 I jxcore-log: 
,09-16 11:52:26.407  5357  5403 I jxcore-log: ok 102 error should be null
09-16 11:52:26.407  5357  5403 I jxcore-log: 
,09-16 11:52:26.408  5357  5403 I jxcore-log: ok 103 error should be null
09-16 11:52:26.408  5357  5403 I jxcore-log: 
,09-16 11:52:26.411  5357  5403 I jxcore-log: # setup
09-16 11:52:26.411  5357  5403 I jxcore-log: 
,09-16 11:52:26.473  5357  5403 I jxcore-log: # 29. should be able to call #stopListeningForAdvertisements many times
09-16 11:52:26.473  5357  5403 I jxcore-log: 
,09-16 11:52:26.653  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 42638
09-16 11:52:26.653  5357  5403 I jxcore-log: 
,09-16 11:52:26.654  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:26.654  5357  5403 I jxcore-log: 
,09-16 11:52:26.655  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 42466
09-16 11:52:26.655  5357  5403 I jxcore-log: 
,09-16 11:52:26.657  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:52:26.657  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:26.657  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:26.658  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:26.661  5357  5403 I jxcore-log: ok 104 error should be null
09-16 11:52:26.661  5357  5403 I jxcore-log: 
,09-16 11:52:26.661  5357  5403 I jxcore-log: ok 105 error should be null
09-16 11:52:26.661  5357  5403 I jxcore-log: 
,09-16 11:52:26.662  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 11:52:26.662  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:26.662  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:26.662  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:26.664  5357  5403 I jxcore-log: ok 106 error should be null
09-16 11:52:26.664  5357  5403 I jxcore-log: 
,09-16 11:52:26.664  5357  5403 I jxcore-log: ok 107 error should be null
09-16 11:52:26.664  5357  5403 I jxcore-log: 
,09-16 11:52:26.675  5357  5403 I jxcore-log: # teardown
09-16 11:52:26.675  5357  5403 I jxcore-log: 
,09-16 11:52:26.715  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:26.716  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:26.716  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:26.716  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:26.718  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:52:26.719  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:26.719  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-16 11:52:26.719  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:26.724  5357  5403 I jxcore-log: ok 108 error should be null
09-16 11:52:26.724  5357  5403 I jxcore-log: 
,09-16 11:52:26.725  5357  5403 I jxcore-log: ok 109 error should be null
09-16 11:52:26.725  5357  5403 I jxcore-log: 
,09-16 11:52:26.729  5357  5403 I jxcore-log: # setup
09-16 11:52:26.729  5357  5403 I jxcore-log: 
,09-16 11:52:26.810  5357  5403 I jxcore-log: # 30. should be able to call #startListeningForAdvertisements many times
09-16 11:52:26.810  5357  5403 I jxcore-log: 
,09-16 11:52:26.884  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 48740
09-16 11:52:26.884  5357  5403 I jxcore-log: 
,09-16 11:52:26.887  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:26.887  5357  5403 I jxcore-log: 
,09-16 11:52:26.892  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 40869
09-16 11:52:26.892  5357  5403 I jxcore-log: 
,09-16 11:52:26.899  5357  5403 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 11:52:26.904  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-16 11:52:26.904  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 11:52:26.904  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:52:26.904  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:52:26.904  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:52:26.904  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:26.904  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:52:26.910  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:52:26.910  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:52:26.916  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:52:26.917  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:52:26.917  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:52:26.922  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 11:52:26.922  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-16 11:52:26.922  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:52:26.922  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:52:26.926  5612  5640 D BtGatt.GattService: registerClient() - UUID=3df88835-ec64-4086-9762-28ce20419a74
,09-16 11:52:26.927  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=3df88835-ec64-4086-9762-28ce20419a74, clientIf=5
,09-16 11:52:26.927  5357  5368 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 11:52:26.928  5612  5623 D BtGatt.GattService: start scan with filters
09-16 11:52:26.931  5612  5631 D BtGatt.ScanManager: handling starting scan
09-16 11:52:26.931  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:52:26.932  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 11:52:26.932  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-16 11:52:26.932  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 11:52:26.935  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:52:26.935  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:52:26.935  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:52:26.936  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 11:52:26.939  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:52:26.939  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:26.939  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 11:52:26.939  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:26.946  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 11:52:26.946  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:26.946  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:52:26.946  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:52:26.958  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 11:52:26.958  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:26.964  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 11:52:26.964  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:27.436  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 11:52:27.437  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:52:27.437  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:27.442  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 11:52:27.442  5357  5403 I jxcore-log: 
,09-16 11:52:27.445  5357  5403 I jxcore-log: ok 110 error should be null
09-16 11:52:27.445  5357  5403 I jxcore-log: 
09-16 11:52:27.446  5357  5403 I jxcore-log: ok 111 error should be null
09-16 11:52:27.446  5357  5403 I jxcore-log: 
,09-16 11:52:27.452  5357  5403 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 11:52:27.459  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
09-16 11:52:27.460  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 11:52:27.460  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:52:27.460  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:52:27.460  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:27.464  5357  5403 I jxcore-log: ok 112 error should be null
09-16 11:52:27.464  5357  5403 I jxcore-log: 
,09-16 11:52:27.466  5357  5403 I jxcore-log: ok 113 error should be null
09-16 11:52:27.466  5357  5403 I jxcore-log: 
,09-16 11:52:27.472  5357  5403 I jxcore-log: # teardown
09-16 11:52:27.472  5357  5403 I jxcore-log: 
,09-16 11:52:27.658  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:27.658  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:27.658  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:27.658  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:52:27.658  5357  5403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 11:52:27.659  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 11:52:27.659  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:52:27.659  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 11:52:27.659  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:52:27.659  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:52:27.659  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:52:27.659  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 11:52:27.663  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:52:27.667  5612  5623 D BtGatt.GattService: stopScan() - queue size =1
,09-16 11:52:27.668  5612  5648 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 11:52:27.669  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:52:27.669  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:52:27.669  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 11:52:27.670  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:52:27.670  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:52:27.675  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:52:27.675  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:52:27.675  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:52:27.675  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:52:27.677  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 11:52:27.677  5612  5612 D BtGatt.ScanManager: awakened up at time 453343
09-16 11:52:27.680  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:52:27.680  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:52:27.680  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:52:27.684  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 11:52:27.684  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:27.684  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
,09-16 11:52:27.686  5357  5403 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 11:52:27.686  5357  5403 I jxcore-log: 
,09-16 11:52:27.697  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 11:52:27.697  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:27.697  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:27.712  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-16 11:52:27.712  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:27.712  5612  5628 D BtGatt.GattService: current time is 453378885677
09-16 11:52:27.712  5612  5628 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
09-16 11:52:27.712  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 11:52:27.713  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-16 11:52:28.181  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:52:28.182  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:52:28.182  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:28.185  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:52:28.185  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-16 11:52:28.185  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:28.186  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:52:28.188  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:52:28.188  5357  5403 I jxcore-log: 
,09-16 11:52:28.196  5357  5403 I jxcore-log: ok 114 error should be null
09-16 11:52:28.196  5357  5403 I jxcore-log: 
,09-16 11:52:28.197  5357  5403 I jxcore-log: ok 115 error should be null
09-16 11:52:28.197  5357  5403 I jxcore-log: 
,09-16 11:52:28.202  5357  5403 I jxcore-log: # setup
09-16 11:52:28.202  5357  5403 I jxcore-log: 
,09-16 11:52:28.289  5357  5403 I jxcore-log: # 31. should be able to call #startUpdateAdvertisingAndListening many times
09-16 11:52:28.289  5357  5403 I jxcore-log: 
,09-16 11:52:28.377  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 44888
09-16 11:52:28.377  5357  5403 I jxcore-log: 
,09-16 11:52:28.381  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:28.381  5357  5403 I jxcore-log: 
,09-16 11:52:28.386  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 49416
09-16 11:52:28.386  5357  5403 I jxcore-log: 
,09-16 11:52:28.403  5357  5403 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 11:52:28.408  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 49416, start advertisements: true
,09-16 11:52:28.408  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 11:52:28.408  5357  5403 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-16 11:52:28.408  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-16 11:52:28.409  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
09-16 11:52:28.409  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 11:52:28.409  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-16 11:52:28.409  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:28.410  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 11:52:28.410  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 11:52:28.410  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 11:52:28.410  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 11:52:28.410  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 11:52:28.410  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 11:52:28.410  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:28.410  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 11:52:28.412  5357  5717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:52:28.414  5648  5648 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[34024]" dev="sockfs" ino=34024 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:28.414  5648  5648 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[34024]" dev="sockfs" ino=34024 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:28.415  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:52:28.415  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 11:52:28.417  5357  5717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 11:52:28.419  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 11:52:28.420  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:52:28.420  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:52:28.422  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 11:52:28.422  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:52:28.422  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-16 11:52:28.423  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:28.423  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:28.423  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 11:52:28.423  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:28.425  5612  5622 D BtGatt.GattService: registerClient() - UUID=84d37ab4-19fe-4b8c-97be-bc6df4b55f54
09-16 11:52:28.426  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=84d37ab4-19fe-4b8c-97be-bc6df4b55f54, clientIf=5
09-16 11:52:28.426  5357  5368 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-16 11:52:28.427  5612  5630 D BtGatt.AdvertiseManager: message : 0
,09-16 11:52:28.430  5612  5630 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 11:52:28.441  5612  5628 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 11:52:28.447  5612  5628 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 11:52:28.448  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 11:52:28.448  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:52:28.449  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:52:28.450  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
09-16 11:52:28.450  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 11:52:28.451  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 11:52:28.451  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 11:52:28.451  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-16 11:52:28.451  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 11:52:28.451  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-16 11:52:28.452  5357  5403 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 38877
09-16 11:52:28.452  5357  5403 I jxcore-log: 
,09-16 11:52:28.455  5357  5357 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 11:52:28.455  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 11:52:28.956  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 11:52:28.956  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 11:52:28.957  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:28.964  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 11:52:28.964  5357  5403 I jxcore-log: 
,09-16 11:52:28.968  5357  5403 I jxcore-log: ok 116 error should be null
09-16 11:52:28.968  5357  5403 I jxcore-log: 
,09-16 11:52:28.970  5357  5403 I jxcore-log: ok 117 error should be null
09-16 11:52:28.970  5357  5403 I jxcore-log: 
,09-16 11:52:28.981  5357  5403 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 11:52:28.984  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 49416, start advertisements: true
,09-16 11:52:28.984  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 11:52:28.984  5357  5403 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 11:52:28.985  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 11:52:28.986  5612  5630 D BtGatt.AdvertiseManager: message : 1
,09-16 11:52:28.988  5612  5630 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 11:52:28.999  5612  5628 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 11:52:28.999  5612  5628 D BtGatt.GattService: Client app is not null!
09-16 11:52:29.000  5612  5622 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 11:52:29.001  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 11:52:29.001  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 11:52:29.001  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:52:29.002  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 11:52:29.002  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:52:29.002  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-16 11:52:29.002  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:29.002  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:29.002  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 11:52:29.005  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:52:29.009  5612  5622 D BtGatt.GattService: registerClient() - UUID=78077e03-6815-4990-9567-d16010ae21fd
,09-16 11:52:29.010  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=78077e03-6815-4990-9567-d16010ae21fd, clientIf=5
09-16 11:52:29.011  5357  5368 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 11:52:29.012  5612  5630 D BtGatt.AdvertiseManager: message : 0
,09-16 11:52:29.016  5612  5630 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 11:52:29.028  5612  5628 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 11:52:29.036  5612  5628 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 11:52:29.037  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 11:52:29.037  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 11:52:29.037  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:52:29.037  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 11:52:29.037  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 11:52:29.037  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 11:52:29.037  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 11:52:29.037  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 11:52:29.037  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:29.045  5357  5403 I jxcore-log: ok 118 error should be null
09-16 11:52:29.045  5357  5403 I jxcore-log: 
,09-16 11:52:29.046  5357  5403 I jxcore-log: ok 119 error should be null
09-16 11:52:29.046  5357  5403 I jxcore-log: 
,09-16 11:52:29.051  5357  5403 I jxcore-log: # teardown
09-16 11:52:29.051  5357  5403 I jxcore-log: 
,09-16 11:52:29.255  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:29.255  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:29.256  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-16 11:52:29.256  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:52:29.256  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 11:52:29.256  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 11:52:29.256  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 11:52:29.257  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 11:52:29.257  5357  5717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 11:52:29.257  5357  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 11:52:29.257  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-16 11:52:29.257  5357  5717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 11:52:29.257  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:52:29.257  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 11:52:29.257  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 11:52:29.258  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 11:52:29.258  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:52:29.258  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:52:29.260  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:29.261  5357  5403 D BluetoothLeScanner: could not find callback wrapper
,09-16 11:52:29.261  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:52:29.261  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 11:52:29.263  5612  5630 D BtGatt.AdvertiseManager: message : 1
09-16 11:52:29.265  5612  5630 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 11:52:29.278  5612  5628 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 11:52:29.278  5612  5628 D BtGatt.GattService: Client app is not null!
09-16 11:52:29.279  5612  5622 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 11:52:29.280  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 11:52:29.280  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-16 11:52:29.280  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 11:52:29.280  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-16 11:52:29.280  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-16 11:52:29.282  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:52:29.282  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:52:29.282  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 11:52:29.283  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 11:52:29.285  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:29.285  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 11:52:29.285  5357  5357 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 11:52:29.285  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:52:29.285  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 11:52:29.285  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:52:29.286  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 11:52:29.286  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:29.286  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-16 11:52:29.286  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.293  5357  5403 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 11:52:29.293  5357  5403 I jxcore-log: 
,09-16 11:52:29.300  5357  5403 I jxcore-log: ok 120 error should be null
09-16 11:52:29.300  5357  5403 I jxcore-log: 
,09-16 11:52:29.300  5357  5403 I jxcore-log: ok 121 error should be null
09-16 11:52:29.300  5357  5403 I jxcore-log: 
,09-16 11:52:29.305  5357  5403 I jxcore-log: # setup
09-16 11:52:29.305  5357  5403 I jxcore-log: 
,09-16 11:52:29.353  5357  5403 I jxcore-log: # 32. should be able to call #stopAdvertisingAndListening many times
09-16 11:52:29.353  5357  5403 I jxcore-log: 
,09-16 11:52:29.429  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 44236
09-16 11:52:29.429  5357  5403 I jxcore-log: 
,09-16 11:52:29.431  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:29.431  5357  5403 I jxcore-log: 
,09-16 11:52:29.437  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 41221
09-16 11:52:29.437  5357  5403 I jxcore-log: 
,09-16 11:52:29.442  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:29.443  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:29.443  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:29.443  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.446  5357  5403 I jxcore-log: ok 122 error should be null
09-16 11:52:29.446  5357  5403 I jxcore-log: 
,09-16 11:52:29.447  5357  5403 I jxcore-log: ok 123 error should be null
09-16 11:52:29.447  5357  5403 I jxcore-log: 
09-16 11:52:29.450  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
09-16 11:52:29.450  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:29.450  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:52:29.450  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.454  5357  5403 I jxcore-log: ok 124 error should be null
09-16 11:52:29.454  5357  5403 I jxcore-log: 
09-16 11:52:29.454  5357  5403 I jxcore-log: ok 125 error should be null
09-16 11:52:29.454  5357  5403 I jxcore-log: 
,09-16 11:52:29.459  5357  5403 I jxcore-log: # teardown
09-16 11:52:29.459  5357  5403 I jxcore-log: 
,09-16 11:52:29.504  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:29.504  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:29.504  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:29.504  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.506  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:52:29.506  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:29.507  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:29.507  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.512  5357  5403 I jxcore-log: ok 126 error should be null
09-16 11:52:29.512  5357  5403 I jxcore-log: 
,09-16 11:52:29.513  5357  5403 I jxcore-log: ok 127 error should be null
09-16 11:52:29.513  5357  5403 I jxcore-log: 
,09-16 11:52:29.518  5357  5403 I jxcore-log: # setup
09-16 11:52:29.518  5357  5403 I jxcore-log: 
,09-16 11:52:29.556  5357  5403 I jxcore-log: # 33. #start should fail if called twice in a row
09-16 11:52:29.556  5357  5403 I jxcore-log: 
,09-16 11:52:29.647  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 46759
09-16 11:52:29.647  5357  5403 I jxcore-log: 
09-16 11:52:29.649  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:29.649  5357  5403 I jxcore-log: 
,09-16 11:52:29.654  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 41689
09-16 11:52:29.654  5357  5403 I jxcore-log: 
,09-16 11:52:29.657  5357  5403 I jxcore-log: ok 128 first call should succeed
09-16 11:52:29.657  5357  5403 I jxcore-log: 
,09-16 11:52:29.658  5357  5403 I jxcore-log: ok 129 first call should succeed
09-16 11:52:29.658  5357  5403 I jxcore-log: 
09-16 11:52:29.662  5357  5403 I jxcore-log: ok 130 specific error should be returned
09-16 11:52:29.662  5357  5403 I jxcore-log: 
,09-16 11:52:29.665  5357  5403 I jxcore-log: # teardown
09-16 11:52:29.665  5357  5403 I jxcore-log: 
,09-16 11:52:29.750  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:29.750  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 11:52:29.751  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:29.751  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.755  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:52:29.755  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:29.756  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-16 11:52:29.756  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:29.769  5357  5403 I jxcore-log: ok 131 error should be null
09-16 11:52:29.769  5357  5403 I jxcore-log: 
,09-16 11:52:29.770  5357  5403 I jxcore-log: ok 132 error should be null
09-16 11:52:29.770  5357  5403 I jxcore-log: 
,09-16 11:52:29.782  5357  5403 I jxcore-log: # setup
09-16 11:52:29.782  5357  5403 I jxcore-log: 
,09-16 11:52:29.786  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:52:29.791  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:52:29.791  5357  5403 I jxcore-log: 
,09-16 11:52:29.815  5357  5403 I jxcore-log: # 34. does not emit duplicate discoveryAdvertisingStateUpdate
09-16 11:52:29.815  5357  5403 I jxcore-log: 
,09-16 11:52:29.887  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 37947
09-16 11:52:29.887  5357  5403 I jxcore-log: 
,09-16 11:52:29.889  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:29.889  5357  5403 I jxcore-log: 
,09-16 11:52:29.895  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 47861,
09-16 11:52:29.895  5357  5403 I jxcore-log: 
,09-16 11:52:29.901  5357  5403 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 11:52:29.905  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 49416, start advertisements: false
,09-16 11:52:29.905  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-16 11:52:29.905  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:52:29.905  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:52:29.905  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:52:29.905  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:29.905  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:52:29.910  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:52:29.911  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 11:52:29.915  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:52:29.918  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 11:52:29.918  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 11:52:29.921  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 11:52:29.922  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:52:29.922  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:52:29.922  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:52:29.926  5612  5622 D BtGatt.GattService: registerClient() - UUID=ab93b8e6-5102-4054-b854-3c98b61eb0f7
,09-16 11:52:29.926  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=ab93b8e6-5102-4054-b854-3c98b61eb0f7, clientIf=5
09-16 11:52:29.927  5357  5367 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 11:52:29.927  5612  5648 D BtGatt.GattService: start scan with filters
,09-16 11:52:29.930  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 11:52:29.930  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:52:29.930  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 11:52:29.930  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 11:52:29.930  5612  5631 D BtGatt.ScanManager: handling starting scan
,09-16 11:52:29.932  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:52:29.933  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:52:29.933  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:52:29.934  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:52:29.936  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:29.938  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:52:29.938  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:29.938  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 11:52:29.945  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 11:52:29.945  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:29.945  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:52:29.945  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:52:29.955  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 11:52:29.955  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:29.961  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 11:52:29.961  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:30.434  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 11:52:30.434  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:52:30.434  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:30.439  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 11:52:30.439  5357  5403 I jxcore-log: 
,09-16 11:52:30.465  5357  5403 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 11:52:30.469  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 47861, start advertisements: true
,09-16 11:52:30.469  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-16 11:52:30.469  5357  5403 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-16 11:52:30.469  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 11:52:30.470  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 11:52:30.470  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:52:30.471  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:30.473  5612  5623 D BtGatt.GattService: stopScan() - queue size =1
09-16 11:52:30.478  5612  5640 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 11:52:30.478  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 11:52:30.479  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:52:30.479  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:52:30.479  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 11:52:30.479  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:52:30.479  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:52:30.481  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:30.484  5612  5612 D BtGatt.ScanManager: awakened up at time 456150
,09-16 11:52:30.487  5612  5640 D BtGatt.GattService: registerClient() - UUID=a1d865c2-676a-4597-950e-6f93089adcc2
,09-16 11:52:30.487  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=a1d865c2-676a-4597-950e-6f93089adcc2, clientIf=5
09-16 11:52:30.488  5357  5458 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 11:52:30.488  5612  5622 D BtGatt.GattService: start scan with filters
,09-16 11:52:30.489  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 11:52:30.490  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:30.490  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
,09-16 11:52:30.494  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 11:52:30.494  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:52:30.494  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 11:52:30.494  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 11:52:30.494  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-16 11:52:30.494  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:30.495  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 11:52:30.496  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 11:52:30.496  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 11:52:30.496  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 11:52:30.496  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 11:52:30.496  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 11:52:30.496  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 11:52:30.496  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 11:52:30.497  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 11:52:30.497  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:30.497  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 11:52:30.497  5357  5718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:52:30.497  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:30.498  5612  5622 D BtGatt.GattService: stopScan() - queue size =0
,09-16 11:52:30.497  5640  5640 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34046]" dev="sockfs" ino=34046 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 11:52:30.497  5640  5640 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34046]" dev="sockfs" ino=34046 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:30.499  5612  5648 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 11:52:30.499  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:52:30.499  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-16 11:52:30.499  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 11:52:30.499  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:52:30.500  5357  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 11:52:30.500  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:52:30.503  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:52:30.504  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:52:30.506  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 11:52:30.506  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:52:30.506  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-16 11:52:30.506  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-16 11:52:30.507  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:30.507  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 11:52:30.507  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:30.509  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
09-16 11:52:30.509  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:30.509  5612  5628 D BtGatt.GattService: current time is 456176053925
09-16 11:52:30.509  5612  5628 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -86, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -92, 5, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 11:52:30.509  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-16 11:52:30.510  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-16 11:52:30.510  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 11:52:30.511  5612  5622 D BtGatt.GattService: registerClient() - UUID=7e10e3cb-1c37-4b95-97b9-556165c93e35
09-16 11:52:30.511  5612  5631 D BtGatt.ScanManager: handling starting scan
09-16 11:52:30.511  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=7e10e3cb-1c37-4b95-97b9-556165c93e35, clientIf=5
09-16 11:52:30.511  5357  5368 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 11:52:30.512  5612  5630 D BtGatt.AdvertiseManager: message : 0
,09-16 11:52:30.514  5612  5630 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 11:52:30.516  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:52:30.516  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:30.517  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 11:52:30.525  5612  5628 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 11:52:30.529  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 11:52:30.529  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:30.530  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:52:30.530  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:52:30.534  5612  5628 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 11:52:30.534  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 11:52:30.534  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:52:30.536  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 11:52:30.537  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:30.538  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 11:52:30.538  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:52:30.538  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 11:52:30.538  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 11:52:30.538  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 11:52:30.538  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 11:52:30.538  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-16 11:52:30.539  5357  5403 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 43335
09-16 11:52:30.539  5357  5403 I jxcore-log: 
09-16 11:52:30.540  5357  5357 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 11:52:30.541  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 11:52:30.543  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 11:52:30.543  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:30.549  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 11:52:30.549  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:30.555  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 11:52:30.555  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:30.555  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
,09-16 11:52:30.561  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 11:52:30.561  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:30.561  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:30.565  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:30.565  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:31.041  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 11:52:31.042  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 11:52:31.042  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:31.051  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 11:52:31.051  5357  5403 I jxcore-log: 
,09-16 11:52:31.063  5357  5403 I jxcore-log: ok 133 called only once
09-16 11:52:31.063  5357  5403 I jxcore-log: 
,09-16 11:52:31.064  5357  5403 I jxcore-log: ok 134 discovery state matches
09-16 11:52:31.064  5357  5403 I jxcore-log: 
,09-16 11:52:31.065  5357  5403 I jxcore-log: ok 135 advertising state matches
09-16 11:52:31.065  5357  5403 I jxcore-log: 
,09-16 11:52:31.076  5357  5403 I jxcore-log: # teardown
09-16 11:52:31.076  5357  5403 I jxcore-log: 
,09-16 11:52:31.446  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:31.446  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:52:31.446  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-16 11:52:31.447  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 11:52:31.447  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 11:52:31.447  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 11:52:31.447  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 11:52:31.448  5357  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 11:52:31.448  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 11:52:31.448  5357  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 11:52:31.448  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-16 11:52:31.448  5357  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 11:52:31.448  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 11:52:31.448  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 11:52:31.448  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 11:52:31.448  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 11:52:31.448  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 11:52:31.448  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 11:52:31.452  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:31.452  5357  5403 D BluetoothLeScanner: could not find callback wrapper
,09-16 11:52:31.452  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:52:31.452  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 11:52:31.456  5612  5630 D BtGatt.AdvertiseManager: message : 1
,09-16 11:52:31.457  5612  5630 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 11:52:31.467  5612  5628 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 11:52:31.467  5612  5628 D BtGatt.GattService: Client app is not null!
09-16 11:52:31.469  5612  5640 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 11:52:31.470  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:52:31.471  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 11:52:31.471  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 11:52:31.471  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-16 11:52:31.471  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-16 11:52:31.472  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:52:31.473  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 11:52:31.473  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:52:31.473  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 11:52:31.477  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 11:52:31.477  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 11:52:31.477  5357  5357 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 11:52:31.477  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:52:31.477  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 11:52:31.477  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:52:31.478  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 11:52:31.478  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:31.478  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:31.478  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:52:31.482  5357  5403 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
09-16 11:52:31.482  5357  5403 I jxcore-log: 
,09-16 11:52:31.483  5357  5403 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 11:52:31.483  5357  5403 I jxcore-log: 
,09-16 11:52:31.484  5357  5403 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 11:52:31.484  5357  5403 I jxcore-log: 
09-16 11:52:31.488  5357  5403 I jxcore-log: ok 136 error should be null
09-16 11:52:31.488  5357  5403 I jxcore-log: 
,09-16 11:52:31.488  5357  5403 I jxcore-log: ok 137 error should be null
09-16 11:52:31.488  5357  5403 I jxcore-log: 
,09-16 11:52:31.494  5357  5403 I jxcore-log: # setup
09-16 11:52:31.494  5357  5403 I jxcore-log: 
,09-16 11:52:31.536  5357  5403 I jxcore-log: # 35. does not send duplicate availability changes
09-16 11:52:31.536  5357  5403 I jxcore-log: 
,09-16 11:52:31.719  5357  5403 I jxcore-log: ok 138 should be called once
09-16 11:52:31.719  5357  5403 I jxcore-log: 
,09-16 11:52:31.721  5357  5403 I jxcore-log: ok 139 should not have been called more than once
09-16 11:52:31.721  5357  5403 I jxcore-log: 
09-16 11:52:31.724  5357  5403 I jxcore-log: # teardown
09-16 11:52:31.724  5357  5403 I jxcore-log: 
,09-16 11:52:31.775  5357  5403 I jxcore-log: ok 140 error should be null
09-16 11:52:31.775  5357  5403 I jxcore-log: 
,09-16 11:52:31.776  5357  5403 I jxcore-log: ok 141 error should be null
09-16 11:52:31.776  5357  5403 I jxcore-log: 
,09-16 11:52:31.779  5357  5403 I jxcore-log: # setup
09-16 11:52:31.779  5357  5403 I jxcore-log: 
,09-16 11:52:31.869  5357  5403 I jxcore-log: # 36. can get the network status
09-16 11:52:31.869  5357  5403 I jxcore-log: 
,09-16 11:52:31.978  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:52:31.982  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:52:31.982  5357  5403 I jxcore-log: 
,09-16 11:52:32.012  5357  5403 I jxcore-log: ok 142 network status should have certain non-empty properties
09-16 11:52:32.012  5357  5403 I jxcore-log: 
,09-16 11:52:32.017  5357  5403 I jxcore-log: # teardown
09-16 11:52:32.017  5357  5403 I jxcore-log: 
,09-16 11:52:32.081  5357  5403 I jxcore-log: ok 143 error should be null
09-16 11:52:32.081  5357  5403 I jxcore-log: 
,09-16 11:52:32.082  5357  5403 I jxcore-log: ok 144 error should be null
09-16 11:52:32.082  5357  5403 I jxcore-log: 
,09-16 11:52:32.086  5357  5403 I jxcore-log: # setup
09-16 11:52:32.086  5357  5403 I jxcore-log: 
,09-16 11:52:32.147  5357  5403 I jxcore-log: # 37. wifi peer is marked unavailable if announcements stop
09-16 11:52:32.147  5357  5403 I jxcore-log: 
,09-16 11:52:32.231  5357  5403 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
09-16 11:52:32.231  5357  5403 I jxcore-log: 
,09-16 11:52:32.261  5357  5403 I jxcore-log: ok 145 host address should match
09-16 11:52:32.261  5357  5403 I jxcore-log: 
,09-16 11:52:32.262  5357  5403 I jxcore-log: ok 146 port should match
09-16 11:52:32.262  5357  5403 I jxcore-log: 
,09-16 11:52:34.229  5357  5403 I jxcore-log: ok 147 host address should be null
09-16 11:52:34.229  5357  5403 I jxcore-log: 
,09-16 11:52:34.233  5357  5403 I jxcore-log: ok 148 port should should be null
09-16 11:52:34.233  5357  5403 I jxcore-log: 
,09-16 11:52:34.249  5357  5403 I jxcore-log: # teardown
09-16 11:52:34.249  5357  5403 I jxcore-log: 
,09-16 11:52:34.314  5357  5403 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 11:52:34.314  5357  5403 I jxcore-log: 
,09-16 11:52:34.320  5357  5403 I jxcore-log: ok 149 error should be null
09-16 11:52:34.320  5357  5403 I jxcore-log: 
,09-16 11:52:34.321  5357  5403 I jxcore-log: ok 150 error should be null
09-16 11:52:34.321  5357  5403 I jxcore-log: 
,09-16 11:52:34.324  5357  5403 I jxcore-log: # setup
09-16 11:52:34.324  5357  5403 I jxcore-log: 
,09-16 11:52:34.419  5357  5403 I jxcore-log: # 38. Client to server request coordinated
09-16 11:52:34.419  5357  5403 I jxcore-log: 
,09-16 11:52:34.500  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 41168
09-16 11:52:34.500  5357  5403 I jxcore-log: 
,09-16 11:52:34.502  5357  5403 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 11:52:34.502  5357  5403 I jxcore-log: 
,09-16 11:52:34.504  5357  5403 I jxcore-log: DEBUG createNativeListener: listening 49892
09-16 11:52:34.504  5357  5403 I jxcore-log: 
,09-16 11:52:34.507  5357  5403 I jxcore-log: ok 151 error should be null
09-16 11:52:34.507  5357  5403 I jxcore-log: 
,09-16 11:52:34.507  5357  5403 I jxcore-log: ok 152 error should be null
09-16 11:52:34.507  5357  5403 I jxcore-log: 
,09-16 11:52:34.570  5357  5403 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 11:52:34.573  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 49892, start advertisements: true
09-16 11:52:34.573  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 11:52:34.573  5357  5403 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-16 11:52:34.573  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-16 11:52:34.573  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 11:52:34.573  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-16 11:52:34.573  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 11:52:34.573  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:34.574  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 11:52:34.575  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 11:52:34.575  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 11:52:34.575  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 11:52:34.575  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 11:52:34.575  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 11:52:34.575  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 11:52:34.575  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 11:52:34.579  5357  5719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:52:34.583  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 11:52:34.583  5357  5403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 11:52:34.583  5357  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 11:52:34.585  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 11:52:34.585  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 11:52:34.585  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 11:52:34.577  5640  5640 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30683]" dev="sockfs" ino=30683 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 11:52:34.577  5640  5640 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30683]" dev="sockfs" ino=30683 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:34.587  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 11:52:34.587  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 11:52:34.587  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-16 11:52:34.587  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:34.587  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 11:52:34.587  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 11:52:34.587  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:52:34.589  5612  5648 D BtGatt.GattService: registerClient() - UUID=1e866c41-0996-442d-9cf7-dfe25d5b3513
09-16 11:52:34.589  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=1e866c41-0996-442d-9cf7-dfe25d5b3513, clientIf=5
,09-16 11:52:34.590  5357  5367 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 11:52:34.594  5612  5630 D BtGatt.AdvertiseManager: message : 0
09-16 11:52:34.598  5612  5630 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 11:52:34.613  5612  5628 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 11:52:34.621  5612  5628 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 11:52:34.622  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 11:52:34.622  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:52:34.622  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 11:52:34.623  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:34.623  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 11:52:34.623  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 11:52:34.623  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-16 11:52:34.623  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 11:52:34.623  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-16 11:52:34.624  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-16 11:52:34.625  5357  5403 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 38756
09-16 11:52:34.625  5357  5403 I jxcore-log: 
09-16 11:52:34.628  5357  5357 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 11:52:34.628  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 11:52:35.129  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 11:52:35.129  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 11:52:35.129  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:35.134  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 11:52:35.134  5357  5403 I jxcore-log: 
,09-16 11:52:35.140  5357  5403 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 11:52:35.146  5357  5403 I io.jxcore.node.ConnectionHelper: start: Port number: 49892, start advertisements: false
,09-16 11:52:35.146  5357  5403 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-16 11:52:35.146  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
09-16 11:52:35.146  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 11:52:35.147  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 11:52:35.147  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 11:52:35.147  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-16 11:52:35.149  5612  5630 D BtGatt.AdvertiseManager: message : 1
09-16 11:52:35.150  5612  5630 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 11:52:35.158  5612  5628 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-16 11:52:35.158  5612  5628 D BtGatt.GattService: Client app is not null!
,09-16 11:52:35.159  5612  5640 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 11:52:35.160  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 11:52:35.160  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-16 11:52:35.160  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 11:52:35.160  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-16 11:52:35.160  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-16 11:52:35.161  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:52:35.162  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:52:35.163  5357  5403 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 11:52:35.167  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 11:52:35.168  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-16 11:52:35.168  5357  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 11:52:35.169  5357  5403 D BluetoothAdapter: STATE_ON
,09-16 11:52:35.172  5612  5648 D BtGatt.GattService: registerClient() - UUID=114bc928-7af5-436c-9563-9fa3fe744f24
09-16 11:52:35.172  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=114bc928-7af5-436c-9563-9fa3fe744f24, clientIf=5
,09-16 11:52:35.172  5357  5367 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 11:52:35.173  5612  5622 D BtGatt.GattService: start scan with filters
,09-16 11:52:35.175  5612  5631 D BtGatt.ScanManager: handling starting scan
,09-16 11:52:35.176  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 11:52:35.176  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:52:35.176  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 11:52:35.176  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 11:52:35.179  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 11:52:35.180  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 11:52:35.180  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 11:52:35.181  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 11:52:35.182  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:52:35.182  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:35.183  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 11:52:35.183  5357  5403 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 11:52:35.189  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 11:52:35.189  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:35.189  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:52:35.189  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:52:35.200  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 11:52:35.200  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:35.206  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 11:52:35.206  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:35.681  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 11:52:35.681  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 11:52:35.681  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:35.700  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 11:52:35.700  5357  5403 I jxcore-log: 
,09-16 11:52:35.703  5357  5403 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
09-16 11:52:35.703  5357  5403 I jxcore-log: 
,09-16 11:52:35.714  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:35.714  5357  5403 I jxcore-log: 
,09-16 11:52:35.721  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:35.721  5357  5403 I jxcore-log: 
,09-16 11:52:35.867  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:35.867  5357  5403 I jxcore-log: 
,09-16 11:52:35.903  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:35.903  5357  5403 I jxcore-log: 
,09-16 11:52:36.222  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:36.222  5357  5403 I jxcore-log: 
,09-16 11:52:36.251  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:36.251  5357  5403 I jxcore-log: 
,09-16 11:52:36.874  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:36.874  5357  5403 I jxcore-log: 
,09-16 11:52:36.909  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:36.909  5357  5403 I jxcore-log: 
,09-16 11:52:38.152  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:38.152  5357  5403 I jxcore-log: 
,09-16 11:52:38.205  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:38.205  5357  5403 I jxcore-log: 
,09-16 11:52:38.849   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:39.850   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:40.211  5612  5612 D BtGatt.ScanManager: awakened up at time 465877
,09-16 11:52:40.214  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:40.246  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-16 11:52:40.246  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:40.246  5612  5628 D BtGatt.GattService: current time is 465913267186
09-16 11:52:40.247  5612  5628 D BtGatt.GattService: Batch record : [-116, -86, 73, 6, -76, 93, 1, -128, -63, 98, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 43, -128, -28, -69, 90, 72, 1, -128, -62, 99, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -89, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
09-16 11:52:40.247  5612  5628 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-16 11:52:40.248  5612  5628 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
09-16 11:52:40.248  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-16 11:52:40.248  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 11:52:40.249  5612  5628 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-16 11:52:40.255  5357  5357 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 5], added - the peer count is 1
,09-16 11:52:40.256  5357  5357 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 44:78:3E:94:4A:3E 5], added - the peer count is 2
09-16 11:52:40.256  5357  5357 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
09-16 11:52:40.257  5357  5357 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 5], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
,09-16 11:52:40.263  5357  5403 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 11:52:40.263  5357  5403 I jxcore-log: 
,09-16 11:52:40.269  5357  5403 I jxcore-log: DEBUG createPeerListener: listening 43992
09-16 11:52:40.269  5357  5403 I jxcore-log: 
,09-16 11:52:40.270  5357  5403 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 11:52:40.270  5357  5403 I jxcore-log: 
,09-16 11:52:40.290  5357  5403 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 11:52:40.290  5357  5403 I jxcore-log: 
,09-16 11:52:40.297  5357  5403 I jxcore-log: DEBUG createPeerListener: listening 49167
09-16 11:52:40.297  5357  5403 I jxcore-log: 
,09-16 11:52:40.303  5357  5403 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 11:52:40.303  5357  5403 I jxcore-log: 
,09-16 11:52:40.317  5357  5403 I jxcore-log: DEBUG createPeerListener: first connection
09-16 11:52:40.317  5357  5403 I jxcore-log: 
,09-16 11:52:40.320  5357  5403 D io.jxcore.node.JXcoreExtension: connect: A8:81:95:E9:5F:6F
,09-16 11:52:40.320  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID A8:81:95:E9:5F:6F
09-16 11:52:40.320  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> A8:81:95:E9:5F:6F 5]
,09-16 11:52:40.322  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address A8:81:95:E9:5F:6F
,09-16 11:52:40.323  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 11:52:40.323  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 11:52:40.323  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null A8:81:95:E9:5F:6F
,09-16 11:52:40.323  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address A8:81:95:E9:5F:6F
,09-16 11:52:40.323  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: A8:81:95:E9:5F:6F)
,09-16 11:52:40.324  5357  5721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address A8:81:95:E9:5F:6F (thread ID: 192)
,09-16 11:52:40.325  5357  5721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:52:40.325  5357  5403 I jxcore-log: DEBUG createPeerListener: first connection
09-16 11:52:40.325  5357  5403 I jxcore-log: 
09-16 11:52:40.324  5623  5623 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31562]" dev="sockfs" ino=31562 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:40.324  5623  5623 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31562]" dev="sockfs" ino=31562 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:40.329  5357  5403 D io.jxcore.node.JXcoreExtension: connect: 44:78:3E:94:4A:3E
09-16 11:52:40.329  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 44:78:3E:94:4A:3E
09-16 11:52:40.329  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 44:78:3E:94:4A:3E 5]
,09-16 11:52:40.331  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 44:78:3E:94:4A:3E
,09-16 11:52:40.331  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 11:52:40.331  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 11:52:40.331  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 44:78:3E:94:4A:3E
09-16 11:52:40.331  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 44:78:3E:94:4A:3E
09-16 11:52:40.331  5357  5403 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 44:78:3E:94:4A:3E)
09-16 11:52:40.332  5357  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 44:78:3E:94:4A:3E (thread ID: 193)
09-16 11:52:40.333  5357  5722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:52:40.330  5623  5623 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32671]" dev="sockfs" ino=32671 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:40.330  5623  5623 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32671]" dev="sockfs" ino=32671 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:40.437   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:52:40.611  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:40.611  5357  5403 I jxcore-log: 
,09-16 11:52:40.641  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:40.641  5357  5403 I jxcore-log: 
,09-16 11:52:40.751  5612  5612 D BtGatt.ScanManager: awakened up at time 466418
09-16 11:52:40.754  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:40.770  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:40.770  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:40.850   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:41.002  5612  5635 W bt_btif : bta_dm_acl_change info: 0x10
,09-16 11:52:41.003  5612  5628 D bt_btif_dm: remote version info [a8:81:95:e9:5f:6f]: 8, f, 6106
09-16 11:52:41.003  5612  5628 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,09-16 11:52:41.079  5612  5635 W bt_sdp  : process_service_search_attr_rsp
,09-16 11:52:41.274  5612  5612 D BtGatt.ScanManager: awakened up at time 466941
,09-16 11:52:41.276  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:41.279  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 11:52:41.280  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:41.851   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:41.905  5612  5612 D BtGatt.ScanManager: awakened up at time 467571
,09-16 11:52:41.908  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:41.918  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 1
,09-16 11:52:41.919  5612  5628 I bt_btif_dm: check_cod remote_cod = 0x00001f00 cod = 0x00000580
,09-16 11:52:41.922  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 10 NewState: 11
09-16 11:52:41.922  5612  5629 I BluetoothBondStateMachine: Entering PendingCommandState State
09-16 11:52:41.925  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 11:52:41.926  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 11:52:41.928  5438  5438 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 11:52:41.930  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:41.931  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:41.933  3106  3366 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 11:52:41.940  5612  5635 W bt_btif : bta_dm_acl_change info: 0x10
09-16 11:52:41.940  5612  5628 D bt_btif_dm: remote version info [44:78:3e:94:4a:3e]: 8, f, 6106
,09-16 11:52:41.943  5612  5628 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,09-16 11:52:41.990  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 0
,09-16 11:52:41.991  5612  5629 D BluetoothAdapterProperties: Failed to remove device: A8:81:95:E9:5F:6F
,09-16 11:52:41.992  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 11 NewState: 10
,09-16 11:52:41.994  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 11:52:41.995  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 11:52:41.996  3106  3366 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 11:52:41.999  5438  5438 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 11:52:42.009  5612  5629 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@91b8e91
,09-16 11:52:42.011  5612  5629 D HidService: Saved priority A8:81:95:E9:5F:6F = -1
,09-16 11:52:42.014  5612  5629 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:52:42.017  5612  5635 W bt_smp  : for SMP over BR max_key_size: 0x10,                        local_i_key: 0x07, local_r_key: 0x07
,09-16 11:52:42.028  5612  5635 W bt_sdp  : process_service_search_attr_rsp
,09-16 11:52:42.042  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 1
,09-16 11:52:42.043  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 10 NewState: 11
09-16 11:52:42.043  5612  5629 I BluetoothBondStateMachine: Entering PendingCommandState State
,09-16 11:52:42.044  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 11:52:42.044  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 11:52:42.046  5612  5635 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-16 11:52:42.046  5612  5635 W bt_smp  : flag = 0 round = 1
09-16 11:52:42.046  5612  5635 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-16 11:52:42.046  5612  5635 W bt_smp  : flag = 0 round = 1
,09-16 11:52:42.046  5438  5438 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
09-16 11:52:42.046  5612  5635 W bt_smp  : smp_send_id_info
,09-16 11:52:42.048  3106  3366 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 11:52:42.060  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 0
09-16 11:52:42.060  5612  5629 D BluetoothAdapterProperties: Failed to remove device: A8:81:95:E9:5F:6F
,09-16 11:52:42.062  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 11 NewState: 10
,09-16 11:52:42.064  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 11:52:42.066  5612  5629 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@91b8e91
09-16 11:52:42.067  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 11:52:42.067  5612  5629 D HidService: Saved priority A8:81:95:E9:5F:6F = -1
09-16 11:52:42.069  3106  3366 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
09-16 11:52:42.069  5438  5438 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
09-16 11:52:42.069  5612  5629 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:52:42.088  5612  5635 W bt_btif : new conn_srvc id:26, app_id:1
,09-16 11:52:42.088  5612  5635 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
09-16 11:52:42.088  5612  5635 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-16 11:52:42.089  5357  5721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> A8:81:95:E9:5F:6F 5] (thread ID: 192)
09-16 11:52:42.089  5357  5721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 192)
,09-16 11:52:42.091  5357  5721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 194)
,09-16 11:52:42.091  5357  5721 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 194)
09-16 11:52:42.091  5357  5721 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 192)
09-16 11:52:42.091  5357  5728 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 194)
,09-16 11:52:42.201  5357  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 194)
,09-16 11:52:42.204  5357  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> A8:81:95:E9:5F:6F]
09-16 11:52:42.204  5357  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> A8:81:95:E9:5F:6F] (thread ID: 192)
09-16 11:52:42.204  5357  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> A8:81:95:E9:5F:6F] (thread ID: 192)
,09-16 11:52:42.205  5357  5728 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 194)
09-16 11:52:42.206  5357  5357 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> A8:81:95:E9:5F:6F]
09-16 11:52:42.207  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> A8:81:95:E9:5F:6F]
,09-16 11:52:42.208  5357  5357 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,09-16 11:52:42.209  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 2 -> 0
09-16 11:52:42.210  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 3 -> 1
09-16 11:52:42.210  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 2 -> 0
,09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 11:52:42.211  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
09-16 11:52:42.211  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:52:42.213  5357  5357 D BluetoothAdapter: STATE_ON
,09-16 11:52:42.215  5612  5648 D BtGatt.GattService: stopScan() - queue size =1
09-16 11:52:42.219  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 11:52:42.220  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:42.219  5612  5640 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 11:52:42.220  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
09-16 11:52:42.221  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:52:42.221  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:52:42.221  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
09-16 11:52:42.221  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 11:52:42.221  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 11:52:42.221  5357  5357 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 11:52:42.223  5357  5357 D BluetoothAdapter: STATE_ON
09-16 11:52:42.224  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 11:52:42.225  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:42.225  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 11:52:42.228  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 11:52:42.228  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:42.230  5612  5640 D BtGatt.GattService: registerClient() - UUID=6c51fba3-dfc7-4913-b829-b87367d5dbe2
,09-16 11:52:42.231  5612  5628 D BtGatt.GattService: onClientRegistered() - UUID=6c51fba3-dfc7-4913-b829-b87367d5dbe2, clientIf=5
09-16 11:52:42.232  5357  5458 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 11:52:42.233  5612  5622 D BtGatt.GattService: start scan with filters
,09-16 11:52:42.242  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 11:52:42.242  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 11:52:42.242  5612  5631 D BtGatt.ScanManager: handling starting scan
09-16 11:52:42.242  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> A8:81:95:E9:5F:6F], created successfully
09-16 11:52:42.243  5357  5357 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,09-16 11:52:42.243  5357  5729 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 195)
09-16 11:52:42.244  5357  5729 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37818
09-16 11:52:42.244  5357  5729 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-16 11:52:42.245  5357  5729 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 37818 (peer ID: A8:81:95:E9:5F:6F)
09-16 11:52:42.245  5357  5729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "A8:81:95:E9:5F:6F" removed
09-16 11:52:42.247  5612  5628 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 11:52:42.247  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:42.249  5612  5631 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 11:52:42.251  5357  5403 I jxcore-log: DEBUG createPeerListener: forward connection
09-16 11:52:42.251  5357  5403 I jxcore-log: 
,09-16 11:52:42.252  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 11:52:42.254  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:42.254  5612  5631 D BtGatt.ScanManager: Starting BLE batch scan
09-16 11:52:42.254  5612  5631 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 11:52:42.255  5357  5729 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 37818
09-16 11:52:42.255  5357  5729 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-16 11:52:42.256  5357  5729 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:42.256  5357  5729 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:42.257  5357  5730 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: OutgoingSocketThread/Sender)
,09-16 11:52:42.257  5612  5628 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 11:52:42.257  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:42.258  5357  5729 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 195)
09-16 11:52:42.258  5357  5729 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 195)
09-16 11:52:42.259  5357  5731 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: OutgoingSocketThread/Receiver)
09-16 11:52:42.259  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 11:52:42.259  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:42.521  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 1
,09-16 11:52:42.521  5612  5628 I bt_btif_dm: check_cod remote_cod = 0x00001f00 cod = 0x00000580
,09-16 11:52:42.525  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 10 NewState: 11
09-16 11:52:42.525  5612  5629 I BluetoothBondStateMachine: Entering PendingCommandState State
,09-16 11:52:42.528  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 11:52:42.529  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 11:52:42.533  3106  3366 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 11:52:42.533  5438  5438 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 11:52:42.721  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:42.721  5357  5403 I jxcore-log: 
,09-16 11:52:42.763  5612  5612 D BtGatt.ScanManager: awakened up at time 468429
,09-16 11:52:42.766  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:42.776  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 0
,09-16 11:52:42.776  5612  5629 D BluetoothAdapterProperties: Failed to remove device: 44:78:3E:94:4A:3E
,09-16 11:52:42.778  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:42.778  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:42.778  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 11 NewState: 10
09-16 11:52:42.779  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 11:52:42.781  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 11:52:42.781  5612  5629 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@91b8e91
,09-16 11:52:42.782  5438  5438 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 11:52:42.783  5612  5629 D HidService: Saved priority 44:78:3E:94:4A:3E = -1
09-16 11:52:42.785  3106  3366 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 11:52:42.786  5612  5629 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:52:42.843  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:42.843  5357  5403 I jxcore-log: 
,09-16 11:52:42.852   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:42.981  5612  5635 W bt_smp  : for SMP over BR max_key_size: 0x10,                        local_i_key: 0x07, local_r_key: 0x07
,09-16 11:52:43.032  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 1
,09-16 11:52:43.035  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 10 NewState: 11
09-16 11:52:43.035  5612  5629 I BluetoothBondStateMachine: Entering PendingCommandState State
09-16 11:52:43.037  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
,09-16 11:52:43.041  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
,09-16 11:52:43.044  3106  3366 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 11:52:43.050  5438  5438 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 11:52:43.064  5612  5635 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
,09-16 11:52:43.065  5612  5635 W bt_smp  : flag = 0 round = 1
,09-16 11:52:43.065  5612  5635 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-16 11:52:43.065  5612  5635 W bt_smp  : flag = 0 round = 1
09-16 11:52:43.065  5612  5635 W bt_smp  : smp_send_id_info
,09-16 11:52:43.128  5357  5403 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:AndroidBluetooth, 127.0.0.1, 127.0.0.1, 43992
09-16 11:52:43.128  5357  5403 I jxcore-log: 
,09-16 11:52:43.156  5612  5628 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 0
09-16 11:52:43.156  5612  5629 D BluetoothAdapterProperties: Failed to remove device: 44:78:3E:94:4A:3E
09-16 11:52:43.158  5612  5629 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 11 NewState: 10
,09-16 11:52:43.159  5612  5629 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@91b8e91
09-16 11:52:43.162  5612  5629 D HidService: Saved priority 44:78:3E:94:4A:3E = -1
09-16 11:52:43.162  5438  5438 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 11:52:43.163  3106  3366 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 11:52:43.163  5438  5438 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 11:52:43.165  3106  3366 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 11:52:43.166  5612  5629 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 11:52:43.195  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:43.195  5357  5403 I jxcore-log: 
,09-16 11:52:43.281  5612  5612 D BtGatt.ScanManager: awakened up at time 468947
,09-16 11:52:43.282  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:43.284  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:43.284  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:43.788  5612  5612 D BtGatt.ScanManager: awakened up at time 469455
,09-16 11:52:43.790  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:43.794  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 11:52:43.794  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:43.847  5623  5623 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32704]" dev="sockfs" ino=32704 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:43.842  5357  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
09-16 11:52:43.844  5357  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 198)
09-16 11:52:43.845  5357  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-16 11:52:43.845  5357  5732 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 198)
09-16 11:52:43.846  5357  5719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 11:52:43.848  5612  5635 W bt_btif : new conn_srvc id:26, app_id:255
09-16 11:52:43.848  5612  5635 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
09-16 11:52:43.848  5612  5635 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
09-16 11:52:43.849  5612  5635 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-16 11:52:43.852  5357  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-16 11:52:43.853   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
09-16 11:52:43.847  5623  5623 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32704]" dev="sockfs" ino=32704 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:43.883  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:43.883  5357  5403 I jxcore-log: 
,09-16 11:52:43.994  5612  5635 W bt_btif : new conn_srvc id:26, app_id:1
,09-16 11:52:43.994  5612  5635 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
09-16 11:52:43.994  5612  5635 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-16 11:52:43.995  5357  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> 44:78:3E:94:4A:3E 5] (thread ID: 193)
09-16 11:52:43.995  5357  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 193)
09-16 11:52:43.997  5357  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 199)
09-16 11:52:43.997  5357  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 199)
,09-16 11:52:43.997  5357  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 193)
09-16 11:52:43.998  5357  5733 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 199)
,09-16 11:52:44.299  5612  5612 D BtGatt.ScanManager: awakened up at time 469966
,09-16 11:52:44.301  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:44.318  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:44.318  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:44.406  5357  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 198)
,09-16 11:52:44.409  5357  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> A8:81:95:E9:5F:6F]
,09-16 11:52:44.410  5357  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 198)
09-16 11:52:44.410  5357  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 198
09-16 11:52:44.410  5357  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 198)
09-16 11:52:44.410  5357  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> A8:81:95:E9:5F:6F]
09-16 11:52:44.412  5357  5732 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 198)
09-16 11:52:44.412  5357  5357 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> A8:81:95:E9:5F:6F]
,09-16 11:52:44.412  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> A8:81:95:E9:5F:6F]
09-16 11:52:44.415  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> A8:81:95:E9:5F:6F], created successfully
09-16 11:52:44.415  5357  5734 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 200)
09-16 11:52:44.416  5357  5357 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,09-16 11:52:44.424  5357  5734 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 49892
09-16 11:52:44.425  5357  5734 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-16 11:52:44.425  5357  5734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:44.426  5357  5734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 11:52:44.428  5357  5736 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: IncomingSocketThread/Sender)
,09-16 11:52:44.428  5357  5734 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 200)
,09-16 11:52:44.429  5357  5734 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 200)
09-16 11:52:44.431  5357  5737 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 202, name: IncomingSocketThread/Receiver)
,09-16 11:52:44.434  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:44.434  5357  5403 I jxcore-log: 
,09-16 11:52:44.440  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:44.440  5357  5403 I jxcore-log: 
,09-16 11:52:44.443  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:44.443  5357  5403 I jxcore-log: 
,09-16 11:52:44.499  5357  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 199)
,09-16 11:52:44.502  5357  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> 44:78:3E:94:4A:3E]
,09-16 11:52:44.502  5357  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 193)
09-16 11:52:44.502  5357  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 193)
09-16 11:52:44.502  5357  5733 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 199)
,09-16 11:52:44.503  5357  5357 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-16 11:52:44.503  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> 44:78:3E:94:4A:3E]
,09-16 11:52:44.506  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
09-16 11:52:44.507  5357  5357 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
09-16 11:52:44.507  5357  5738 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 203)
09-16 11:52:44.508  5357  5738 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49463
09-16 11:52:44.508  5357  5738 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-16 11:52:44.508  5357  5738 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 49463 (peer ID: 44:78:3E:94:4A:3E)
09-16 11:52:44.508  5357  5738 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "44:78:3E:94:4A:3E" removed
,09-16 11:52:44.511  5357  5403 I jxcore-log: DEBUG createPeerListener: forward connection
09-16 11:52:44.511  5357  5403 I jxcore-log: 
09-16 11:52:44.514  5357  5738 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 49463
09-16 11:52:44.514  5357  5738 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-16 11:52:44.514  5357  5738 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:44.514  5357  5738 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:44.515  5357  5739 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: OutgoingSocketThread/Sender)
09-16 11:52:44.515  5357  5738 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 203)
09-16 11:52:44.516  5357  5738 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 203)
09-16 11:52:44.516  5357  5740 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 205, name: OutgoingSocketThread/Receiver)
,09-16 11:52:44.551  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:44.551  5357  5403 I jxcore-log: 
,09-16 11:52:44.555  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:44.555  5357  5403 I jxcore-log: 
,09-16 11:52:44.824  5612  5612 D BtGatt.ScanManager: awakened up at time 470490
,09-16 11:52:44.829  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:44.833  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 11:52:44.833  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:45.195  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:45.195  5357  5403 I jxcore-log: 
,09-16 11:52:45.337  5612  5612 D BtGatt.ScanManager: awakened up at time 471004
,09-16 11:52:45.339  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:45.341  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:45.341  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:45.494  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:45.494  5357  5403 I jxcore-log: 
,09-16 11:52:45.581  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:45.581  5357  5403 I jxcore-log: 
,09-16 11:52:45.588  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:45.588  5357  5403 I jxcore-log: 
,09-16 11:52:45.717  5357  5403 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:AndroidBluetooth, 127.0.0.1, 127.0.0.1, 49167
09-16 11:52:45.717  5357  5403 I jxcore-log: 
,09-16 11:52:45.737  5357  5403 I jxcore-log: DEBUG createNativeListener: 
09-16 11:52:45.737  5357  5403 I jxcore-log: 
,09-16 11:52:45.738  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:45.738  5357  5403 I jxcore-log: 
,09-16 11:52:45.845  5612  5612 D BtGatt.ScanManager: awakened up at time 471512
,09-16 11:52:45.846  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:45.848  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:45.848  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:45.994  5357  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,09-16 11:52:45.995  5357  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 206)
09-16 11:52:45.995  5357  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 11:52:45.997  5357  5741 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 206)
,09-16 11:52:46.000  5648  5648 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31606]" dev="sockfs" ino=31606 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:46.000  5648  5648 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31606]" dev="sockfs" ino=31606 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 11:52:45.999  5357  5719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 11:52:46.002  5612  5635 W bt_btif : new conn_srvc id:26, app_id:255
09-16 11:52:46.002  5612  5635 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
09-16 11:52:46.002  5612  5635 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,09-16 11:52:46.002  5612  5635 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-16 11:52:46.005  5357  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-16 11:52:46.317  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:46.317  5357  5403 I jxcore-log: 
,09-16 11:52:46.351  5612  5612 D BtGatt.ScanManager: awakened up at time 472017
09-16 11:52:46.351  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:46.359  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:46.359  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:46.454   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:52:46.532  5357  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 206)
09-16 11:52:46.534  5357  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> 44:78:3E:94:4A:3E]
,09-16 11:52:46.536  5357  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 206)
09-16 11:52:46.536  5357  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 206
,09-16 11:52:46.536  5357  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 206)
09-16 11:52:46.537  5357  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-16 11:52:46.537  5357  5741 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 206)
09-16 11:52:46.537  5357  5357 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-16 11:52:46.537  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> 44:78:3E:94:4A:3E]
09-16 11:52:46.542  5357  5357 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
09-16 11:52:46.542  5357  5357 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 4
09-16 11:52:46.543  5357  5742 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 207)
,09-16 11:52:46.551  5357  5742 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 49892
09-16 11:52:46.551  5357  5742 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-16 11:52:46.551  5357  5742 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:46.552  5357  5742 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 11:52:46.554  5357  5744 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 208, name: IncomingSocketThread/Sender)
,09-16 11:52:46.556  5357  5742 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 207)
09-16 11:52:46.556  5357  5742 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 207)
09-16 11:52:46.557  5357  5745 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 209, name: IncomingSocketThread/Receiver)
09-16 11:52:46.559  5357  5403 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 11:52:46.559  5357  5403 I jxcore-log: 
,09-16 11:52:46.563  5357  5403 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 11:52:46.563  5357  5403 I jxcore-log: 
,09-16 11:52:46.565  5357  5403 I jxcore-log: DEBUG createNativeListener: new mux
09-16 11:52:46.565  5357  5403 I jxcore-log: 
,09-16 11:52:46.688  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:46.688  5357  5403 I jxcore-log: 
,09-16 11:52:46.694  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:46.694  5357  5403 I jxcore-log: 
,09-16 11:52:46.865  5612  5612 D BtGatt.ScanManager: awakened up at time 472531
,09-16 11:52:46.867  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:46.885  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 11:52:46.885  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:47.390  5612  5612 D BtGatt.ScanManager: awakened up at time 473057
,09-16 11:52:47.394  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:47.398  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:47.398  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:47.647  5357  5403 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 11:52:47.647  5357  5403 I jxcore-log: 
,09-16 11:52:47.656  5357  5403 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 11:52:47.656  5357  5403 I jxcore-log: 
,09-16 11:52:47.684  5357  5403 I jxcore-log: DEBUG createNativeListener: 
09-16 11:52:47.684  5357  5403 I jxcore-log: 
,09-16 11:52:47.685  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:47.685  5357  5403 I jxcore-log: 
,09-16 11:52:47.717  5357  5403 I jxcore-log: DEBUG thaliPeerPoolDefault: Got err   Could not establish TCP connection
09-16 11:52:47.717  5357  5403 I jxcore-log: 
,09-16 11:52:48.300  5357  5403 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 11:52:48.300  5357  5403 I jxcore-log: 
,09-16 11:52:48.858   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:49.504  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:52:49.504  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:52:49.504  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:49.504  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
09-16 11:52:49.505  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 11:52:49.505  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 11:52:49.508  5357  5403 D BluetoothAdapter: STATE_ON
09-16 11:52:49.510  5612  5640 D BtGatt.GattService: stopScan() - queue size =1
,09-16 11:52:49.512  5612  5622 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 11:52:49.513  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 11:52:49.514  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 11:52:49.514  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 11:52:49.514  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 11:52:49.514  5357  5403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 11:52:49.516  5612  5628 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 11:52:49.517  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:49.517  5357  5403 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 11:52:49.517  5612  5631 D BtGatt.ScanManager: stopping BLe Batch
09-16 11:52:49.518  5357  5357 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 11:52:49.522  5612  5628 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 11:52:49.522  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 11:52:49.523  5612  5631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 11:52:49.525  5612  5628 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 11:52:49.525  5612  5628 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 11:52:49.859   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:50.019  5357  5357 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 11:52:50.019  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 11:52:50.020  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 11:52:50.028  5357  5403 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 11:52:50.028  5357  5403 I jxcore-log: 
,09-16 11:52:50.042  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:52:50.042  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:52:50.043  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> A8:81:95:E9:5F:6F]
,09-16 11:52:50.043  5357  5403 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 195)
,09-16 11:52:50.043  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
09-16 11:52:50.043  5357  5403 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 197
09-16 11:52:50.043  5357  5403 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 197, name: OutgoingSocketThread/Receiver)
09-16 11:52:50.043  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
09-16 11:52:50.043  5357  5403 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 196
09-16 11:52:50.043  5357  5403 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 196, name: OutgoingSocketThread/Sender)
09-16 11:52:50.043  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Closing the Bluetooth socket...
09-16 11:52:50.044  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Closing the localhost socket...
09-16 11:52:50.044  5357  5403 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 195)
09-16 11:52:50.044  5357  5403 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 44:78:3E:94:4A:3E]
09-16 11:52:50.044  5357  5403 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 203)
,09-16 11:52:50.044  5357  5731 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
09-16 11:52:50.044  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
09-16 11:52:50.044  5357  5403 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 205
09-16 11:52:50.044  5357  5730 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: OutgoingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 907 and the total number of bytes written 907
09-16 11:52:50.044  5357  5403 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 205, name: OutgoingSocketThread/Receiver)
09-16 11:52:50.044  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,09-16 11:52:50.044  5357  5403 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 204
09-16 11:52:50.044  5357  5403 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 204, name: OutgoingSocketThread/Sender)
09-16 11:52:50.044  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Closing the Bluetooth socket...
09-16 11:52:50.044  5357  5403 V io.jxcore.node.OutgoingSocketThread: close: Closing the localhost socket...
09-16 11:52:50.045  5357  5403 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 203)
,09-16 11:52:50.045  5357  5740 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 205, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
09-16 11:52:50.045  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:50.046  5357  5739 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: OutgoingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 907 and the total number of bytes written 907
09-16 11:52:50.046  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 11:52:50.046  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 11:52:50.046  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 11:52:50.046  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 11:52:50.046  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 11:52:50.046  5357  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 11:52:50.046  5357  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 11:52:50.046  5357  5403 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 11:52:50.046  5357  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 11:52:50.046  5357  5403 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 11:52:50.047  5357  5403 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 11:52:50.047  5357  5357 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 11:52:50.048  5357  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 11:52:50.049  5357  5403 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-16 11:52:50.050  5357  5357 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:52:50.051  5357  5357 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 11:52:50.051  5357  5357 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 11:52:50.051  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:52:50.062  5612  5635 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,09-16 11:52:50.062  5612  5635 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 11:52:50.064  5357  5403 I jxcore-log: DEBUG createPeerListener: Recreating listener
09-16 11:52:50.064  5357  5403 I jxcore-log: 
,09-16 11:52:50.065  5357  5403 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 11:52:50.065  5357  5403 I jxcore-log: 
,09-16 11:52:50.071  5612  5635 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,09-16 11:52:50.071  5612  5635 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
09-16 11:52:50.072  5357  5403 I jxcore-log: DEBUG createPeerListener: listening 41846
09-16 11:52:50.072  5357  5403 I jxcore-log: 
09-16 11:52:50.072  5357  5403 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 11:52:50.072  5357  5403 I jxcore-log: 
,09-16 11:52:50.076  5357  5403 I jxcore-log: DEBUG createPeerListener: Recreating listener
09-16 11:52:50.076  5357  5403 I jxcore-log: 
,09-16 11:52:50.077  5357  5403 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 11:52:50.077  5357  5403 I jxcore-log: 
,09-16 11:52:50.080  5357  5403 I jxcore-log: DEBUG createPeerListener: listening 45406
09-16 11:52:50.080  5357  5403 I jxcore-log: 
,09-16 11:52:50.080  5357  5403 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 11:52:50.080  5357  5403 I jxcore-log: 
,09-16 11:52:50.084  5357  5403 I jxcore-log: ok 153 Peer made successful https requests to all peers
09-16 11:52:50.084  5357  5403 I jxcore-log: 
,09-16 11:52:50.085  5357  5403 I jxcore-log: ok 154 Peer received right amount of https requests
09-16 11:52:50.085  5357  5403 I jxcore-log: 
,09-16 11:52:50.086  5357  5403 I jxcore-log: ok 155 HTTPS server received zero PSK Identities. Count:0
09-16 11:52:50.086  5357  5403 I jxcore-log: 
,09-16 11:52:50.092  5357  5403 I jxcore-log: # teardown
09-16 11:52:50.092  5357  5403 I jxcore-log: 
,09-16 11:52:50.119  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:52:50.129  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-16 11:52:50.860   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:51.861   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:52.863   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:52:53.863   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:53:03.865   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:04.866   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:05.868   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:06.869   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:07.870   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:08.871   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:53:14.255   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:53:19.439  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 11:53:19.439  5357  5403 I jxcore-log: 
,09-16 11:53:19.441  5357  5736 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 201, thread name: IncomingSocketThread/Sender)
09-16 11:53:19.441  5357  5736 I io.jxcore.node.IncomingSocketThread: The sending thread is done
,09-16 11:53:19.441  5357  5736 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: IncomingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
,09-16 11:53:19.446  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:53:19.446  5357  5403 I jxcore-log: 
,09-16 11:53:19.451  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 11:53:19.451  5357  5403 I jxcore-log: 
,09-16 11:53:19.453  5357  5744 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 208, thread name: IncomingSocketThread/Sender)
09-16 11:53:19.453  5357  5744 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-16 11:53:19.453  5357  5744 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 208, name: IncomingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
09-16 11:53:19.454  5357  5403 I jxcore-log: DEBUG createNativeListener: mux close
09-16 11:53:19.454  5357  5403 I jxcore-log: 
,09-16 11:53:19.462  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:53:19.462  5357  5403 I jxcore-log: 
,09-16 11:53:19.465  5357  5403 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 11:53:19.465  5357  5403 I jxcore-log: 
,09-16 11:53:23.872   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:24.874   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:25.875   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:26.877   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:27.878   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:28.879   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:53:34.256   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:53:42.311  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 11:53:42.314  5357  5357 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,09-16 11:53:42.321  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:53:42.329  5357  5737 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 202, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
,09-16 11:53:42.329  5357  5737 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
09-16 11:53:42.329  5357  5737 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> A8:81:95:E9:5F:6F] disconnected: Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)
,09-16 11:53:42.330  5357  5737 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 200
09-16 11:53:42.330  5357  5737 V io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
09-16 11:53:42.330  5357  5737 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 202
09-16 11:53:42.330  5357  5737 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 202, name: IncomingSocketThread/Receiver)
09-16 11:53:42.330  5357  5737 V io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,09-16 11:53:42.331  5357  5737 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 201
09-16 11:53:42.331  5357  5737 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 201, name: IncomingSocketThread/Sender)
09-16 11:53:42.331  5357  5737 V io.jxcore.node.IncomingSocketThread: close: Closing the Bluetooth socket...
09-16 11:53:42.331  5357  5737 V io.jxcore.node.IncomingSocketThread: close: Closing the localhost socket...
09-16 11:53:42.331  5357  5737 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 200)
,09-16 11:53:42.331  5357  5737 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 11:53:42.331  5357  5737 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 202, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1023 and the total number of bytes written 905
09-16 11:53:42.336  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:53:42.346  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:53:42.814  5612  5635 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,09-16 11:53:42.815  5612  5635 E bt_btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,09-16 11:53:42.815  5612  5635 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 11:53:43.797  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:53:43.964   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:53:44.855  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
09-16 11:53:44.857  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:53:44.862  5357  5745 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 209, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
,09-16 11:53:44.862  5357  5745 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
09-16 11:53:44.863  5357  5745 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> 44:78:3E:94:4A:3E] disconnected: Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)
09-16 11:53:44.863  5357  5745 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 207
09-16 11:53:44.863  5357  5745 V io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
09-16 11:53:44.864  5357  5745 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 209
09-16 11:53:44.865  5357  5745 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 209, name: IncomingSocketThread/Receiver)
09-16 11:53:44.865  5357  5745 V io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,09-16 11:53:44.865  5357  5745 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 208
09-16 11:53:44.865  5357  5745 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 208, name: IncomingSocketThread/Sender)
09-16 11:53:44.866  5357  5745 V io.jxcore.node.IncomingSocketThread: close: Closing the Bluetooth socket...
09-16 11:53:44.866  5357  5745 V io.jxcore.node.IncomingSocketThread: close: Closing the localhost socket...
09-16 11:53:44.866  5357  5745 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 207)
09-16 11:53:44.866  5357  5745 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 11:53:44.866  5357  5745 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 209, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 907 and the total number of bytes written 905
,09-16 11:53:44.896  5612  5635 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,09-16 11:53:44.896  5612  5635 E bt_btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
09-16 11:53:44.896  5612  5635 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 11:53:48.881   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:49.882   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:49.923  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:53:49.972  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:53:50.012   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:53:50.799  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
09-16 11:53:50.815  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:53:50.883   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:51.885   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:52.886   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:53:53.038   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:53:53.887   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:53:56.054   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:53:56.908  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:53:56.970  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:53:59.269  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:53:59.874  5357  5357 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,09-16 11:53:59.874  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 0 -> 2
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 1 -> 3
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 0 -> 2
,09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 11:53:59.875  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 11:53:59.876  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 11:53:59.876  5357  5357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 11:53:59.876  5357  5357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 11:54:05.330  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:54:05.347  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:54:07.304  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:54:08.141   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:13.327  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:54:13.454  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:54:14.202   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:14.258   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:54:15.258  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 11:54:15.261  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:54:18.887   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:54:18.888   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:54:20.261   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:21.313  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:54:21.329  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:54:21.715  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 11:54:21.753  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:54:23.292   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:27.759  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:54:27.825  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:54:28.201  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 11:54:28.753  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-16 11:54:32.379   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:34.260   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:54:34.666  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:54:34.696  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:54:35.397   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:35.679  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 11:54:35.681  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:54:38.425   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:40.361  5357  5403 I jxcore-log: INFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
09-16 11:54:40.361  5357  5403 I jxcore-log: 
,09-16 11:54:40.373  5357  5403 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 11:54:40.373  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 11:54:40.374  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 11:54:40.374  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:54:40.377  5357  5403 I jxcore-log: # setup
09-16 11:54:40.377  5357  5403 I jxcore-log: 
,09-16 11:54:40.379  5357  5403 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 11:54:40.380  5357  5403 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 11:54:40.380  5357  5403 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-16 11:54:40.380  5357  5403 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 11:54:40.528  5357  5403 I jxcore-log: # 39. Test BEACONS_RETRIEVED_AND_PARSED locally
09-16 11:54:40.528  5357  5403 I jxcore-log: 
,09-16 11:54:41.439   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:54:41.471  5357  5403 I jxcore-log: ok 156 peerIdentifier should be identifier
09-16 11:54:41.471  5357  5403 I jxcore-log: 
,09-16 11:54:41.472  5357  5403 I jxcore-log: ok 157 Response should be BEACONS_RETRIEVED_AND_PARSED
09-16 11:54:41.472  5357  5403 I jxcore-log: 
,09-16 11:54:41.473  5357  5403 I jxcore-log: ok 158 good beacon
09-16 11:54:41.473  5357  5403 I jxcore-log: 
09-16 11:54:41.474  5357  5403 I jxcore-log: ok 159 good preAmble
09-16 11:54:41.474  5357  5403 I jxcore-log: 
09-16 11:54:41.474  5357  5403 I jxcore-log: ok 160 public keys match!
09-16 11:54:41.474  5357  5403 I jxcore-log: 
,09-16 11:54:41.476  5357  5403 I jxcore-log: ok 161 must return null after successful call
09-16 11:54:41.476  5357  5403 I jxcore-log: 
,09-16 11:54:41.476  5357  5403 I jxcore-log: ok 162 Once start returns the action should be in KILLED state
09-16 11:54:41.476  5357  5403 I jxcore-log: 
,09-16 11:54:41.485  5357  5403 I jxcore-log: # teardown
09-16 11:54:41.485  5357  5403 I jxcore-log: 
,09-16 11:54:41.812  5612  5635 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 11:54:41.833  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 11:54:42.214  5357  5403 I jxcore-log: # setup
09-16 11:54:42.214  5357  5403 I jxcore-log: 
,09-16 11:54:43.022  5357  5403 I jxcore-log: # 40. Test HTTP_BAD_RESPONSE locally
09-16 11:54:43.022  5357  5403 I jxcore-log: 
,09-16 11:54:43.283  5357  5403 I jxcore-log: ok 163 Response should be HTTP_BAD_RESPONSE
09-16 11:54:43.283  5357  5403 I jxcore-log: 
,09-16 11:54:43.289  5357  5403 I jxcore-log: ok 164 must return null after successful call
09-16 11:54:43.289  5357  5403 I jxcore-log: 
,09-16 11:54:43.306  5357  5403 I jxcore-log: # teardown
09-16 11:54:43.306  5357  5403 I jxcore-log: 
,09-16 11:54:43.657  5612  5635 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 11:54:43.698  5612  5635 I bt_btm_sec: btm_sec_disconnected clearing pending flag handle:12 reason:22
,09-16 11:54:43.704  5612  5628 E BluetoothRemoteDevices: state12newState1
,09-16 11:54:43.711  5612  5612 D BluetoothMapService: onReceive
09-16 11:54:43.711  5612  5612 D BluetoothMapService: onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,09-16 11:54:43.725   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acc718e:true
,09-16 11:54:43.734  4763  4763 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:78:3E:94:4A:3E, alias=null, name=Samsung Galaxy S7, majorDeviceClass=7936, deviceClass=7936]
,09-16 11:54:43.735  5612  5635 I bt_btm_sec: btm_sec_disconnected clearing pending flag handle:11 reason:22
09-16 11:54:43.736  5612  5628 E BluetoothRemoteDevices: state12newState1
,09-16 11:54:43.738  4763  4763 I BluetoothClassifier: Bluetooth Device Name: Samsung Galaxy S7
,09-16 11:54:43.739  5612  5612 D BluetoothMapService: onReceive
09-16 11:54:43.739  5612  5612 D BluetoothMapService: onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,09-16 11:54:43.759  4763  4763 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=A8:81:95:E9:5F:6F, alias=null, name=Samsung Galaxy S7 edge, majorDeviceClass=7936, deviceClass=7936]
,09-16 11:54:43.760  4763  4763 I BluetoothClassifier: Bluetooth Device Name: Samsung Galaxy S7 edge
,09-16 11:54:43.898   535  1358 E QC-QMI  : qmi_client [535] 8: failed to locate client data
,09-16 11:54:43.901   519   519 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-16 11:54:43.902   519   519 E QC-QMI  : QMUX qmux_client_id=8 not found in qmux client list, unable to remove
,09-16 11:54:43.908   535   535 I Atfwd_Daemon: Stop the daemon....
,09-16 11:54:44.029  5752  5752 I libmdmdetect: ESOC framework not supported
,09-16 11:54:44.030  5752  5752 I libmdmdetect: Found internal modem: modem
09-16 11:54:44.027  5752  5752 W ATFWD-daemon: type=1400 audit(0.0:128): avc: denied { read write } for name="diag" dev="tmpfs" ino=12329 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-16 11:54:44.031  5752  5752 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 11:54:44.043  5752  5752 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-16 11:54:44.044  5752  5752 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 11:54:44.045  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:44.054  5357  5403 I jxcore-log: # setup
09-16 11:54:44.054  5357  5403 I jxcore-log: 
,09-16 11:54:44.663  5357  5403 I jxcore-log: # 41. Test NETWORK_PROBLEM locally
09-16 11:54:44.663  5357  5403 I jxcore-log: 
,09-16 11:54:45.049  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:45.373  5357  5403 I jxcore-log: ok 165 Response should be NETWORK_PROBLEM
09-16 11:54:45.373  5357  5403 I jxcore-log: 
,09-16 11:54:45.381  5357  5403 I jxcore-log: ok 166 reject reason should be: Could not establish TCP connection
09-16 11:54:45.381  5357  5403 I jxcore-log: 
,09-16 11:54:45.392  5357  5403 I jxcore-log: # teardown
09-16 11:54:45.392  5357  5403 I jxcore-log: 
,09-16 11:54:45.896  5357  5403 I jxcore-log: # setup
09-16 11:54:45.896  5357  5403 I jxcore-log: 
,09-16 11:54:46.050  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:46.591  5357  5403 I jxcore-log: # 42. Call the start two times
09-16 11:54:46.591  5357  5403 I jxcore-log: 
,09-16 11:54:47.051  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:47.138  5357  5403 I jxcore-log: ok 167 Call start once
09-16 11:54:47.138  5357  5403 I jxcore-log: 
,09-16 11:54:47.274  5357  5403 I jxcore-log: ok 168 Response should be BEACONS_RETRIEVED_AND_PARSED
09-16 11:54:47.274  5357  5403 I jxcore-log: 
,09-16 11:54:47.277  5357  5403 I jxcore-log: ok 169 must return null after successful call.
09-16 11:54:47.277  5357  5403 I jxcore-log: 
,09-16 11:54:47.290  5357  5403 I jxcore-log: # teardown
09-16 11:54:47.290  5357  5403 I jxcore-log: 
,09-16 11:54:48.040  5357  5403 I jxcore-log: # setup
09-16 11:54:48.040  5357  5403 I jxcore-log: 
,09-16 11:54:48.052  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:48.657  5357  5403 I jxcore-log: # 43. Call the kill before calling the start
09-16 11:54:48.657  5357  5403 I jxcore-log: 
,09-16 11:54:49.052  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 11:54:49.270  5357  5403 I jxcore-log: ok 170 Should be Killed
09-16 11:54:49.270  5357  5403 I jxcore-log: 
,09-16 11:54:49.277  5357  5403 I jxcore-log: ok 171 Start after killed
09-16 11:54:49.277  5357  5403 I jxcore-log: 
,09-16 11:54:49.286  5357  5403 I jxcore-log: # teardown
09-16 11:54:49.286  5357  5403 I jxcore-log: 
,09-16 11:54:49.887  5357  5403 I jxcore-log: # setup
09-16 11:54:49.887  5357  5403 I jxcore-log: 
,09-16 11:54:50.704  5357  5403 I jxcore-log: # 44. Call the kill immediately after the start
09-16 11:54:50.704  5357  5403 I jxcore-log: 
,09-16 11:54:51.225  5357  5403 I jxcore-log: ok 172 Should be KILLED
09-16 11:54:51.225  5357  5403 I jxcore-log: 
,09-16 11:54:51.228  5357  5403 I jxcore-log: ok 173 must return null after successful kill
09-16 11:54:51.228  5357  5403 I jxcore-log: 
,09-16 11:54:51.237  5357  5403 I jxcore-log: # teardown
09-16 11:54:51.237  5357  5403 I jxcore-log: 
,09-16 11:54:51.932  5357  5403 I jxcore-log: # setup
09-16 11:54:51.932  5357  5403 I jxcore-log: 
,09-16 11:54:52.448  5357  5403 I jxcore-log: # 45. Call the kill while waiting a response from the server
09-16 11:54:52.448  5357  5403 I jxcore-log: 
,09-16 11:54:54.054  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:54.263   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:54:55.055  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:55.166  5357  5403 I jxcore-log: ok 174 Should be KILLED
09-16 11:54:55.166  5357  5403 I jxcore-log: 
,09-16 11:54:55.177  5357  5403 I jxcore-log: ok 175 must return null after successful kill
09-16 11:54:55.177  5357  5403 I jxcore-log: 
,09-16 11:54:55.227  5357  5403 I jxcore-log: # teardown
09-16 11:54:55.227  5357  5403 I jxcore-log: 
,09-16 11:54:55.271  5357  5403 I jxcore-log: # setup
09-16 11:54:55.271  5357  5403 I jxcore-log: 
,09-16 11:54:55.432  5357  5403 I jxcore-log: # 46. Test to exceed the max content size locally
09-16 11:54:55.432  5357  5403 I jxcore-log: 
,09-16 11:54:55.657  5357  5403 I jxcore-log: ok 176 HTTP_BAD_RESPONSE should be response when content size is exceeded
09-16 11:54:55.657  5357  5403 I jxcore-log: 
,09-16 11:54:55.667  5357  5403 I jxcore-log: ok 177 must return null after successful call
09-16 11:54:55.667  5357  5403 I jxcore-log: 
,09-16 11:54:55.688  5357  5403 I jxcore-log: # teardown
09-16 11:54:55.688  5357  5403 I jxcore-log: 
,09-16 11:54:55.724  5357  5403 I jxcore-log: # setup
09-16 11:54:55.724  5357  5403 I jxcore-log: 
,09-16 11:54:55.907  5357  5403 I jxcore-log: # 47. Close the server socket while the client is waiting a response from the server. Local test.
09-16 11:54:55.907  5357  5403 I jxcore-log: 
,09-16 11:54:56.056  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:57.057  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:57.961  5357  5403 I jxcore-log: ok 178 Should be NETWORK_PROBLEM caused closing server socket
09-16 11:54:57.961  5357  5403 I jxcore-log: 
,09-16 11:54:57.968  5357  5403 I jxcore-log: ok 179 Should be Could not establish TCP connection
09-16 11:54:57.968  5357  5403 I jxcore-log: 
,09-16 11:54:57.979  5357  5403 I jxcore-log: # teardown
09-16 11:54:57.979  5357  5403 I jxcore-log: 
,09-16 11:54:58.059  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:54:58.089  5357  5403 I jxcore-log: # setup
09-16 11:54:58.089  5357  5403 I jxcore-log: 
,09-16 11:54:58.264  5357  5403 I jxcore-log: # 48. Close the client socket while the client is waiting a response from the server. Local test.
09-16 11:54:58.264  5357  5403 I jxcore-log: 
,09-16 11:54:59.060  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:55:00.314  5357  5403 I jxcore-log: ok 180 Should be NETWORK_PROBLEM caused closing client socket
09-16 11:55:00.314  5357  5403 I jxcore-log: 
,09-16 11:55:00.323  5357  5403 I jxcore-log: ok 181 Should be Could not establish TCP connection
09-16 11:55:00.323  5357  5403 I jxcore-log: 
,09-16 11:55:00.346  5357  5403 I jxcore-log: # teardown
09-16 11:55:00.346  5357  5403 I jxcore-log: 
,09-16 11:55:00.418  5357  5403 I jxcore-log: # setup
09-16 11:55:00.418  5357  5403 I jxcore-log: 
,09-16 11:55:00.482  5357  5403 I jxcore-log: # 49. #generatePreambleAndBeacons bad args
09-16 11:55:00.482  5357  5403 I jxcore-log: 
,09-16 11:55:00.574  5357  5403 I jxcore-log: ok 182 publicKeysToNotify cannot be null
09-16 11:55:00.574  5357  5403 I jxcore-log: 
,09-16 11:55:00.578  5357  5403 I jxcore-log: ok 183 ecdh for local device cannot be null
09-16 11:55:00.578  5357  5403 I jxcore-log: 
,09-16 11:55:00.581  5357  5403 I jxcore-log: ok 184 milliseconds cannot be less than 0
09-16 11:55:00.581  5357  5403 I jxcore-log: 
,09-16 11:55:00.585  5357  5403 I jxcore-log: ok 185 milliseconds cannot be 0
09-16 11:55:00.585  5357  5403 I jxcore-log: 
,09-16 11:55:00.587  5357  5403 I jxcore-log: ok 186 milliseconds cannot be greater than one_day
09-16 11:55:00.587  5357  5403 I jxcore-log: 
,09-16 11:55:00.590  5357  5403 I jxcore-log: # teardown
09-16 11:55:00.590  5357  5403 I jxcore-log: 
,09-16 11:55:00.642  5357  5403 I jxcore-log: # setup
09-16 11:55:00.642  5357  5403 I jxcore-log: 
,09-16 11:55:00.702  5357  5403 I jxcore-log: # 50. #generatePreambleAndBeacons empty keys to notify
09-16 11:55:00.702  5357  5403 I jxcore-log: 
,09-16 11:55:00.799  5357  5403 I jxcore-log: ok 187 should be equal
09-16 11:55:00.799  5357  5403 I jxcore-log: 
,09-16 11:55:00.803  5357  5403 I jxcore-log: # teardown
09-16 11:55:00.803  5357  5403 I jxcore-log: 
,09-16 11:55:00.851  5357  5403 I jxcore-log: # setup
09-16 11:55:00.851  5357  5403 I jxcore-log: 
,09-16 11:55:00.904  5357  5403 I jxcore-log: # 51. #generatePreambleAndBeacons multiple keys to notify
09-16 11:55:00.904  5357  5403 I jxcore-log: 
,09-16 11:55:01.073  5357  5403 I jxcore-log: ok 188 should be equal
09-16 11:55:01.073  5357  5403 I jxcore-log: 
,09-16 11:55:01.074  5357  5403 I jxcore-log: ok 189 should be equal
09-16 11:55:01.074  5357  5403 I jxcore-log: 
09-16 11:55:01.075  5357  5403 I jxcore-log: ok 190 (unnamed assert)
09-16 11:55:01.075  5357  5403 I jxcore-log: 
09-16 11:55:01.075  5357  5403 I jxcore-log: ok 191 should be equal
09-16 11:55:01.075  5357  5403 I jxcore-log: 
,09-16 11:55:01.076  5357  5403 I jxcore-log: # teardown
09-16 11:55:01.076  5357  5403 I jxcore-log: 
,09-16 11:55:01.117  5357  5403 I jxcore-log: # setup
09-16 11:55:01.117  5357  5403 I jxcore-log: 
,09-16 11:55:01.191  5357  5403 I jxcore-log: # 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
09-16 11:55:01.191  5357  5403 I jxcore-log: 
,09-16 11:55:01.286  5357  5403 I jxcore-log: ok 192 should throw
09-16 11:55:01.286  5357  5403 I jxcore-log: 
,09-16 11:55:01.290  5357  5403 I jxcore-log: # teardown
09-16 11:55:01.290  5357  5403 I jxcore-log: 
,09-16 11:55:01.347  5357  5403 I jxcore-log: # setup
09-16 11:55:01.347  5357  5403 I jxcore-log: 
,09-16 11:55:01.428  5357  5403 I jxcore-log: # 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble
09-16 11:55:01.428  5357  5403 I jxcore-log: 
,09-16 11:55:01.510  5357  5403 I jxcore-log: ok 193 Preamble expiration must be a 64 bit integer
09-16 11:55:01.510  5357  5403 I jxcore-log: 
,09-16 11:55:01.513  5357  5403 I jxcore-log: # teardown
09-16 11:55:01.513  5357  5403 I jxcore-log: 
,09-16 11:55:01.551  5357  5403 I jxcore-log: # setup
09-16 11:55:01.551  5357  5403 I jxcore-log: 
,09-16 11:55:01.611  5357  5403 I jxcore-log: # 54. #parseBeacons expiration out of range lower
09-16 11:55:01.611  5357  5403 I jxcore-log: 
,09-16 11:55:01.713  5357  5403 I jxcore-log: ok 194 Expiration out of range
09-16 11:55:01.713  5357  5403 I jxcore-log: 
,09-16 11:55:01.716  5357  5403 I jxcore-log: # teardown
09-16 11:55:01.716  5357  5403 I jxcore-log: 
,09-16 11:55:01.807  5357  5403 I jxcore-log: # setup
09-16 11:55:01.807  5357  5403 I jxcore-log: 
,09-16 11:55:01.925  5357  5403 I jxcore-log: # 55. #parseBeacons expiration out of range lower
09-16 11:55:01.925  5357  5403 I jxcore-log: 
,09-16 11:55:02.016  5357  5403 I jxcore-log: ok 195 Expiration out of range
09-16 11:55:02.016  5357  5403 I jxcore-log: 
,09-16 11:55:02.019  5357  5403 I jxcore-log: # teardown
09-16 11:55:02.019  5357  5403 I jxcore-log: 
,09-16 11:55:02.065  5357  5403 I jxcore-log: # setup
09-16 11:55:02.065  5357  5403 I jxcore-log: 
,09-16 11:55:02.147  5357  5403 I jxcore-log: # 56. #parseBeacons no beacons returns null
09-16 11:55:02.147  5357  5403 I jxcore-log: 
,09-16 11:55:02.227  5357  5403 I jxcore-log: ok 196 should be equal
09-16 11:55:02.227  5357  5403 I jxcore-log: 
,09-16 11:55:02.229  5357  5403 I jxcore-log: # teardown
09-16 11:55:02.229  5357  5403 I jxcore-log: 
,09-16 11:55:02.298  5357  5403 I jxcore-log: # setup
09-16 11:55:02.298  5357  5403 I jxcore-log: 
,09-16 11:55:02.361  5357  5403 I jxcore-log: # 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
09-16 11:55:02.361  5357  5403 I jxcore-log: 
,09-16 11:55:02.448  5357  5403 I jxcore-log: ok 197 Malformed encrypted beacon key ID
09-16 11:55:02.448  5357  5403 I jxcore-log: 
,09-16 11:55:02.452  5357  5403 I jxcore-log: # teardown
09-16 11:55:02.452  5357  5403 I jxcore-log: 
,09-16 11:55:02.496  5357  5403 I jxcore-log: # setup
09-16 11:55:02.496  5357  5403 I jxcore-log: 
,09-16 11:55:02.553  5357  5403 I jxcore-log: # 58. #parseBeacons addressBookCallback fails decrypt
09-16 11:55:02.553  5357  5403 I jxcore-log: 
,09-16 11:55:02.740  5357  5403 I jxcore-log: ok 198 should be equal
09-16 11:55:02.740  5357  5403 I jxcore-log: 
,09-16 11:55:02.741  5357  5403 I jxcore-log: # teardown
09-16 11:55:02.741  5357  5403 I jxcore-log: 
,09-16 11:55:02.802  5357  5403 I jxcore-log: # setup
09-16 11:55:02.802  5357  5403 I jxcore-log: 
,09-16 11:55:02.851  5357  5403 I jxcore-log: # 59. #parseBeacons addressBookCallback returns no matches
09-16 11:55:02.851  5357  5403 I jxcore-log: 
,09-16 11:55:03.062  5357  5403 I jxcore-log: ok 199 should be equal
09-16 11:55:03.062  5357  5403 I jxcore-log: 
,09-16 11:55:03.063  5357  5403 I jxcore-log: ok 200 should be equal
09-16 11:55:03.063  5357  5403 I jxcore-log: 
,09-16 11:55:03.064  5357  5403 I jxcore-log: # teardown
09-16 11:55:03.064  5357  5403 I jxcore-log: 
,09-16 11:55:03.105  5357  5403 I jxcore-log: # setup
09-16 11:55:03.105  5357  5403 I jxcore-log: 
,09-16 11:55:03.178  5357  5403 I jxcore-log: # 60. #parseBeacons addressBookCallback returns spurious match
09-16 11:55:03.178  5357  5403 I jxcore-log: 
,09-16 11:55:03.369  5357  5403 I jxcore-log: ok 201 should be equal
09-16 11:55:03.369  5357  5403 I jxcore-log: 
,09-16 11:55:03.370  5357  5403 I jxcore-log: ok 202 should be equal
09-16 11:55:03.370  5357  5403 I jxcore-log: 
09-16 11:55:03.371  5357  5403 I jxcore-log: # teardown
09-16 11:55:03.371  5357  5403 I jxcore-log: 
,09-16 11:55:03.408  5357  5403 I jxcore-log: # setup
09-16 11:55:03.408  5357  5403 I jxcore-log: 
,09-16 11:55:03.511  5357  5403 I jxcore-log: # 61. #parseBeacons addressBookCallback returns public key
09-16 11:55:03.511  5357  5403 I jxcore-log: 
,09-16 11:55:03.695  5357  5403 I jxcore-log: ok 203 right number of calls to address book
09-16 11:55:03.695  5357  5403 I jxcore-log: 
,09-16 11:55:03.696  5357  5403 I jxcore-log: ok 204 good preAmble
09-16 11:55:03.696  5357  5403 I jxcore-log: 
09-16 11:55:03.696  5357  5403 I jxcore-log: ok 205 good unencryptedKeyId
09-16 11:55:03.696  5357  5403 I jxcore-log: 
09-16 11:55:03.696  5357  5403 I jxcore-log: ok 206 good beacon
09-16 11:55:03.696  5357  5403 I jxcore-log: 
,09-16 11:55:03.697  5357  5403 I jxcore-log: # teardown
09-16 11:55:03.697  5357  5403 I jxcore-log: 
,09-16 11:55:03.745  5357  5403 I jxcore-log: # setup
09-16 11:55:03.745  5357  5403 I jxcore-log: 
,09-16 11:55:03.796  5357  5403 I jxcore-log: # 62. validate generatePskIdentityField
09-16 11:55:03.796  5357  5403 I jxcore-log: 
,09-16 11:55:03.899  5357  5403 I jxcore-log: ok 207 decoded buffers match
09-16 11:55:03.899  5357  5403 I jxcore-log: 
,09-16 11:55:03.904  5357  5403 I jxcore-log: # teardown
09-16 11:55:03.904  5357  5403 I jxcore-log: 
,09-16 11:55:03.958  5357  5403 I jxcore-log: # setup
09-16 11:55:03.958  5357  5403 I jxcore-log: 
,09-16 11:55:04.019  5357  5403 I jxcore-log: # 63. validate generatePskSecret
09-16 11:55:04.019  5357  5403 I jxcore-log: 
,09-16 11:55:04.130  5357  5403 I jxcore-log: ok 208 secrets match
09-16 11:55:04.130  5357  5403 I jxcore-log: 
,09-16 11:55:04.134  5357  5403 I jxcore-log: # teardown
09-16 11:55:04.134  5357  5403 I jxcore-log: 
,09-16 11:55:04.172  5357  5403 I jxcore-log: # setup
09-16 11:55:04.172  5357  5403 I jxcore-log: 
,09-16 11:55:04.213  5357  5403 I jxcore-log: # 64. validate generatePskSecrets
09-16 11:55:04.213  5357  5403 I jxcore-log: 
,09-16 11:55:04.414  5357  5403 I jxcore-log: ok 209 Matching numbers
09-16 11:55:04.414  5357  5403 I jxcore-log: 
,09-16 11:55:04.420  5357  5403 I jxcore-log: ok 210 We have an entry!,
09-16 11:55:04.420  5357  5403 I jxcore-log: 
09-16 11:55:04.420  5357  5403 I jxcore-log: ok 211 keys match
09-16 11:55:04.420  5357  5403 I jxcore-log: 
,09-16 11:55:04.420  5357  5403 I jxcore-log: ok 212 secrets match
09-16 11:55:04.420  5357  5403 I jxcore-log: 
,09-16 11:55:04.426  5357  5403 I jxcore-log: ok 213 We have an entry!
09-16 11:55:04.426  5357  5403 I jxcore-log: 
,09-16 11:55:04.426  5357  5403 I jxcore-log: ok 214 keys match
09-16 11:55:04.426  5357  5403 I jxcore-log: 
09-16 11:55:04.426  5357  5403 I jxcore-log: ok 215 secrets match
09-16 11:55:04.426  5357  5403 I jxcore-log: 
,09-16 11:55:04.431  5357  5403 I jxcore-log: ok 216 We have an entry!
09-16 11:55:04.431  5357  5403 I jxcore-log: 
,09-16 11:55:04.431  5357  5403 I jxcore-log: ok 217 keys match
09-16 11:55:04.431  5357  5403 I jxcore-log: 
,09-16 11:55:04.432  5357  5403 I jxcore-log: ok 218 secrets match
09-16 11:55:04.432  5357  5403 I jxcore-log: 
,09-16 11:55:04.433  5357  5403 I jxcore-log: # teardown
09-16 11:55:04.433  5357  5403 I jxcore-log: 
,09-16 11:55:04.475  5357  5403 I jxcore-log: # setup
09-16 11:55:04.475  5357  5403 I jxcore-log: 
,09-16 11:55:04.546  5357  5403 I jxcore-log: # 65. validate generateBeaconStreamAndSecrets
09-16 11:55:04.546  5357  5403 I jxcore-log: 
,09-16 11:55:04.729  5357  5403 I jxcore-log: ok 219 Streams have same length
09-16 11:55:04.729  5357  5403 I jxcore-log: 
,09-16 11:55:04.736  5357  5403 I jxcore-log: ok 220 matching size
09-16 11:55:04.736  5357  5403 I jxcore-log: 
,09-16 11:55:04.737  5357  5403 I jxcore-log: ok 221 keys match
09-16 11:55:04.737  5357  5403 I jxcore-log: 
09-16 11:55:04.737  5357  5403 I jxcore-log: ok 222 secrets match
09-16 11:55:04.737  5357  5403 I jxcore-log: 
,09-16 11:55:04.738  5357  5403 I jxcore-log: # teardown
09-16 11:55:04.738  5357  5403 I jxcore-log: 
,09-16 11:55:04.781  5357  5403 I jxcore-log: # setup
09-16 11:55:04.781  5357  5403 I jxcore-log: 
,09-16 11:55:04.937  5357  5403 I jxcore-log: # 66. Add two Peers.
09-16 11:55:04.937  5357  5403 I jxcore-log: 
,09-16 11:55:05.010  5357  5403 I jxcore-log: ok 223 should be equal
09-16 11:55:05.010  5357  5403 I jxcore-log: 
,09-16 11:55:05.013  5357  5403 I jxcore-log: ok 224 should be equal
09-16 11:55:05.013  5357  5403 I jxcore-log: 
,09-16 11:55:05.015  5357  5403 I jxcore-log: ok 225 should be equal
09-16 11:55:05.015  5357  5403 I jxcore-log: 
,09-16 11:55:05.017  5357  5403 I jxcore-log: ok 226 should be equal
09-16 11:55:05.017  5357  5403 I jxcore-log: 
,09-16 11:55:05.022  5357  5403 I jxcore-log: ok 227 should be equal
09-16 11:55:05.022  5357  5403 I jxcore-log: 
,09-16 11:55:05.027  5357  5403 I jxcore-log: # teardown
09-16 11:55:05.027  5357  5403 I jxcore-log: 
,09-16 11:55:05.082  5357  5403 I jxcore-log: # setup
09-16 11:55:05.082  5357  5403 I jxcore-log: 
,09-16 11:55:05.275  5357  5403 I jxcore-log: # 67. TCP_NATIVE peer loses DNS
09-16 11:55:05.275  5357  5403 I jxcore-log: 
,09-16 11:55:05.345  5357  5403 I jxcore-log: ok 228 should be equal
09-16 11:55:05.345  5357  5403 I jxcore-log: 
,09-16 11:55:05.349  5357  5403 I jxcore-log: ok 229 should be equal
09-16 11:55:05.349  5357  5403 I jxcore-log: 
,09-16 11:55:05.353  5357  5403 I jxcore-log: # teardown
09-16 11:55:05.353  5357  5403 I jxcore-log: 
,09-16 11:55:05.397  5357  5403 I jxcore-log: # setup
09-16 11:55:05.397  5357  5403 I jxcore-log: 
,09-16 11:55:05.550  5357  5403 I jxcore-log: # 68. Received beacons with no values for us
09-16 11:55:05.550  5357  5403 I jxcore-log: 
,09-16 11:55:05.752  5357  5403 I jxcore-log: ok 230 entry exists
09-16 11:55:05.752  5357  5403 I jxcore-log: 
09-16 11:55:05.753  5357  5403 I jxcore-log: ok 231 entry is resolved
09-16 11:55:05.753  5357  5403 I jxcore-log: 
,09-16 11:55:05.767  5357  5403 I jxcore-log: # teardown
09-16 11:55:05.767  5357  5403 I jxcore-log: 
,09-16 11:55:05.839  5357  5403 I jxcore-log: # setup
09-16 11:55:05.839  5357  5403 I jxcore-log: 
,09-16 11:55:06.015  5357  5403 I jxcore-log: # 69. Resolves an action locally
09-16 11:55:06.015  5357  5403 I jxcore-log: 
,09-16 11:55:06.195  5357  5403 I jxcore-log: ok 232 Host address must match
09-16 11:55:06.195  5357  5403 I jxcore-log: 
,09-16 11:55:06.196  5357  5403 I jxcore-log: ok 233 suggestedTCPTimeout must match
09-16 11:55:06.196  5357  5403 I jxcore-log: 
09-16 11:55:06.197  5357  5403 I jxcore-log: ok 234 connectionType must match
09-16 11:55:06.197  5357  5403 I jxcore-log: 
,09-16 11:55:06.198  5357  5403 I jxcore-log: ok 235 portNumber must match
09-16 11:55:06.198  5357  5403 I jxcore-log: 
,09-16 11:55:06.207  5357  5403 I jxcore-log: # teardown
09-16 11:55:06.207  5357  5403 I jxcore-log: 
,09-16 11:55:06.266  5357  5403 I jxcore-log: # setup
09-16 11:55:06.266  5357  5403 I jxcore-log: 
,09-16 11:55:06.422  5357  5403 I jxcore-log: # 70. Resolves an action locally using ThaliPeerPoolDefault
09-16 11:55:06.422  5357  5403 I jxcore-log: 
,09-16 11:55:06.603  5357  5403 I jxcore-log: ok 236 Host address must match
09-16 11:55:06.603  5357  5403 I jxcore-log: 
,09-16 11:55:06.604  5357  5403 I jxcore-log: ok 237 suggestedTCPTimeout must match
09-16 11:55:06.604  5357  5403 I jxcore-log: 
09-16 11:55:06.604  5357  5403 I jxcore-log: ok 238 connectionType must match
09-16 11:55:06.604  5357  5403 I jxcore-log: 
,09-16 11:55:06.604  5357  5403 I jxcore-log: ok 239 portNumber must match
09-16 11:55:06.604  5357  5403 I jxcore-log: 
,09-16 11:55:06.609  5357  5403 I jxcore-log: # teardown
09-16 11:55:06.609  5357  5403 I jxcore-log: 
,09-16 11:55:06.737  5357  5403 I jxcore-log: # setup
09-16 11:55:06.737  5357  5403 I jxcore-log: 
,09-16 11:55:06.889  5357  5403 I jxcore-log: # 71. Action fails because of a bad hostname.
09-16 11:55:06.889  5357  5403 I jxcore-log: 
,09-16 11:55:09.061  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:10.062  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:11.063  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:11.962  5357  5403 I jxcore-log: ok 240 should be equal
09-16 11:55:11.962  5357  5403 I jxcore-log: 
,09-16 11:55:11.963  5357  5403 I jxcore-log: ok 241 should be equal
09-16 11:55:11.963  5357  5403 I jxcore-log: 
09-16 11:55:11.964  5357  5403 I jxcore-log: ok 242 should be equal
09-16 11:55:11.964  5357  5403 I jxcore-log: 
,09-16 11:55:11.973  5357  5403 I jxcore-log: # teardown
09-16 11:55:11.973  5357  5403 I jxcore-log: 
,09-16 11:55:12.056  5357  5403 I jxcore-log: # setup
09-16 11:55:12.056  5357  5403 I jxcore-log: 
,09-16 11:55:12.066  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:12.219  5357  5403 I jxcore-log: # 72. hostaddress is removed when the action is running. 
09-16 11:55:12.219  5357  5403 I jxcore-log: 
,09-16 11:55:13.067  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:14.068  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:55:14.263   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:55:14.298  5357  5403 I jxcore-log: ok 243 should be equal
09-16 11:55:14.298  5357  5403 I jxcore-log: 
,09-16 11:55:14.324  5357  5403 I jxcore-log: # teardown
09-16 11:55:14.324  5357  5403 I jxcore-log: 
,09-16 11:55:14.426  5357  5403 I jxcore-log: # setup
09-16 11:55:14.426  5357  5403 I jxcore-log: 
,09-16 11:55:14.567  5357  5403 I jxcore-log: # 73. Client to server request locally
09-16 11:55:14.567  5357  5403 I jxcore-log: 
,09-16 11:55:14.767  5357  5403 I jxcore-log: ok 244 secrets are equal
09-16 11:55:14.767  5357  5403 I jxcore-log: 
,09-16 11:55:14.768  5357  5403 I jxcore-log: ok 245 Public key matches with the server key
09-16 11:55:14.768  5357  5403 I jxcore-log: 
09-16 11:55:14.768  5357  5403 I jxcore-log: ok 246 Host address must match
09-16 11:55:14.768  5357  5403 I jxcore-log: 
,09-16 11:55:14.768  5357  5403 I jxcore-log: ok 247 suggestedTCPTimeout must match
09-16 11:55:14.768  5357  5403 I jxcore-log: 
,09-16 11:55:14.768  5357  5403 I jxcore-log: ok 248 connectionType must match
09-16 11:55:14.768  5357  5403 I jxcore-log: 
,09-16 11:55:14.769  5357  5403 I jxcore-log: ok 249 portNumber must match
09-16 11:55:14.769  5357  5403 I jxcore-log: 
,09-16 11:55:14.778  5357  5403 I jxcore-log: # teardown
09-16 11:55:14.778  5357  5403 I jxcore-log: 
,09-16 11:55:14.863  5357  5403 I jxcore-log: # setup
09-16 11:55:14.863  5357  5403 I jxcore-log: 
,09-16 11:55:14.985  5357  5403 I jxcore-log: # 74. Test ThaliPskMapCache clean and expiration
09-16 11:55:14.985  5357  5403 I jxcore-log: 
,09-16 11:55:15.024  5357  5403 I jxcore-log: ok 250 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
09-16 11:55:15.024  5357  5403 I jxcore-log: 
,09-16 11:55:15.024  5357  5403 I jxcore-log: ok 251 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
09-16 11:55:15.024  5357  5403 I jxcore-log: 
,09-16 11:55:16.027  5357  5403 I jxcore-log: ok 252 All entries should be expired after 1 second
09-16 11:55:16.027  5357  5403 I jxcore-log: 
,09-16 11:55:16.036  5357  5403 I jxcore-log: # teardown
09-16 11:55:16.036  5357  5403 I jxcore-log: 
,09-16 11:55:16.093  5357  5403 I jxcore-log: # setup
09-16 11:55:16.093  5357  5403 I jxcore-log: 
,09-16 11:55:16.198  5357  5403 I jxcore-log: # 75. Test ThaliPskMapCache getSecret and getPublic
09-16 11:55:16.198  5357  5403 I jxcore-log: 
,09-16 11:55:16.344  5357  5403 I jxcore-log: ok 253 All keys need to be available in the cache
09-16 11:55:16.344  5357  5403 I jxcore-log: 
,09-16 11:55:17.348  5357  5403 I jxcore-log: ok 254 All entries should be expired after 1 second
09-16 11:55:17.348  5357  5403 I jxcore-log: 
,09-16 11:55:17.358  5357  5403 I jxcore-log: # teardown
09-16 11:55:17.358  5357  5403 I jxcore-log: 
,09-16 11:55:17.422  5357  5403 I jxcore-log: # setup
09-16 11:55:17.422  5357  5403 I jxcore-log: 
,09-16 11:55:17.539  5357  5403 I jxcore-log: # 76. Test ThaliPskMapCache multiple entries
09-16 11:55:17.539  5357  5403 I jxcore-log: 
,09-16 11:55:18.891  5357  5403 I jxcore-log: ok 255 Size of the cache should be 2
09-16 11:55:18.891  5357  5403 I jxcore-log: 
,09-16 11:55:18.895  5357  5403 I jxcore-log: ok 256 Cache doesn't contain dictionary1
09-16 11:55:18.895  5357  5403 I jxcore-log: 
,09-16 11:55:20.106  5357  5403 I jxcore-log: ok 257 Size of the cache should be 1
09-16 11:55:20.106  5357  5403 I jxcore-log: 
09-16 11:55:20.108  5357  5403 I jxcore-log: ok 258 Cache doesn't contain beaconStreamAndSecretDictionary2
09-16 11:55:20.108  5357  5403 I jxcore-log: 
,09-16 11:55:20.119  5357  5403 I jxcore-log: # teardown
09-16 11:55:20.119  5357  5403 I jxcore-log: 
,09-16 11:55:20.241  5357  5403 I jxcore-log: # setup
09-16 11:55:20.241  5357  5403 I jxcore-log: 
,09-16 11:55:20.346  5357  5403 I jxcore-log: # 77. Start and stop ThaliNotificationServer
09-16 11:55:20.346  5357  5403 I jxcore-log: 
,09-16 11:55:20.475  5357  5403 I jxcore-log: ok 259 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
09-16 11:55:20.475  5357  5403 I jxcore-log: 
,09-16 11:55:20.476  5357  5403 I jxcore-log: ok 260 ThaliMobile.StopAdvertisingAndListeningshould be called once
09-16 11:55:20.476  5357  5403 I jxcore-log: 
09-16 11:55:20.477  5357  5403 I jxcore-log: # teardown
09-16 11:55:20.477  5357  5403 I jxcore-log: 
,09-16 11:55:20.551  5357  5403 I jxcore-log: # setup
09-16 11:55:20.551  5357  5403 I jxcore-log: 
,09-16 11:55:20.646  5357  5403 I jxcore-log: # 78. Pass an empty array to ThaliNotificationServer.start
09-16 11:55:20.646  5357  5403 I jxcore-log: 
,09-16 11:55:20.703  5357  5403 I jxcore-log: ok 261 StartUpdateAdvertisingAndListening should not be called
09-16 11:55:20.703  5357  5403 I jxcore-log: 
,09-16 11:55:20.724  5357  5403 I jxcore-log: ok 262 ThaliMobile.StopAdvertisingAndListening should be called once
09-16 11:55:20.724  5357  5403 I jxcore-log: 
,09-16 11:55:20.761  5357  5403 I jxcore-log: ok 263 no error
09-16 11:55:20.761  5357  5403 I jxcore-log: 
,09-16 11:55:20.762  5357  5403 I jxcore-log: ok 264 should be 204
09-16 11:55:20.762  5357  5403 I jxcore-log: 
,09-16 11:55:20.766  5357  5403 I jxcore-log: # teardown
09-16 11:55:20.766  5357  5403 I jxcore-log: 
,09-16 11:55:20.832  5357  5403 I jxcore-log: # setup
09-16 11:55:20.832  5357  5403 I jxcore-log: 
,09-16 11:55:20.961  5357  5403 I jxcore-log: # 79. Pass a string to ThaliNotificationServer.start
09-16 11:55:20.961  5357  5403 I jxcore-log: 
,09-16 11:55:21.023  5357  5403 I jxcore-log: ok 265 StartUpdateAdvertisingAndListening should not be called
09-16 11:55:21.023  5357  5403 I jxcore-log: 
,09-16 11:55:21.026  5357  5403 I jxcore-log: # teardown
09-16 11:55:21.026  5357  5403 I jxcore-log: 
,09-16 11:55:21.093  5357  5403 I jxcore-log: # setup
09-16 11:55:21.093  5357  5403 I jxcore-log: 
,09-16 11:55:21.187  5357  5403 I jxcore-log: # 80. Pass an empty parameter to ThaliNotificationServer.start
09-16 11:55:21.187  5357  5403 I jxcore-log: 
,09-16 11:55:21.252  5357  5403 I jxcore-log: ok 266 StartUpdateAdvertisingAndListening should not be called
09-16 11:55:21.252  5357  5403 I jxcore-log: 
,09-16 11:55:21.254  5357  5403 I jxcore-log: # teardown
09-16 11:55:21.254  5357  5403 I jxcore-log: 
,09-16 11:55:21.313  5357  5403 I jxcore-log: # setup
09-16 11:55:21.313  5357  5403 I jxcore-log: 
,09-16 11:55:21.434  5357  5403 I jxcore-log: # 81. Make an HTTP request to /NotificationBeacons
09-16 11:55:21.434  5357  5403 I jxcore-log: 
,09-16 11:55:21.572  5357  5403 I jxcore-log: ok 267 no error
09-16 11:55:21.572  5357  5403 I jxcore-log: 
,09-16 11:55:21.572  5357  5403 I jxcore-log: ok 268 should be 200
09-16 11:55:21.572  5357  5403 I jxcore-log: 
,09-16 11:55:21.572  5357  5403 I jxcore-log: ok 269 should be equal
09-16 11:55:21.572  5357  5403 I jxcore-log: 
09-16 11:55:21.572  5357  5403 I jxcore-log: ok 270 should be equal
09-16 11:55:21.572  5357  5403 I jxcore-log: 
,09-16 11:55:21.588  5357  5403 I jxcore-log: ok 271 (unnamed assert)
09-16 11:55:21.588  5357  5403 I jxcore-log: 
,09-16 11:55:21.605  5357  5403 I jxcore-log: ok 272 no error
09-16 11:55:21.605  5357  5403 I jxcore-log: 
,09-16 11:55:21.605  5357  5403 I jxcore-log: ok 273 should be 204
09-16 11:55:21.605  5357  5403 I jxcore-log: 
09-16 11:55:21.607  5357  5403 I jxcore-log: # teardown
09-16 11:55:21.607  5357  5403 I jxcore-log: 
,09-16 11:55:21.708  5357  5403 I jxcore-log: # setup
09-16 11:55:21.708  5357  5403 I jxcore-log: 
,09-16 11:55:21.808  5357  5403 I jxcore-log: # 82. Make an HTTP request to /NotificationBeacons (no keys)
09-16 11:55:21.808  5357  5403 I jxcore-log: 
,09-16 11:55:21.905  5357  5403 I jxcore-log: ok 274 error should be null
09-16 11:55:21.905  5357  5403 I jxcore-log: 
,09-16 11:55:21.906  5357  5403 I jxcore-log: ok 275 should be 204
09-16 11:55:21.906  5357  5403 I jxcore-log: 
09-16 11:55:21.910  5357  5403 I jxcore-log: # teardown
09-16 11:55:21.910  5357  5403 I jxcore-log: 
,09-16 11:55:21.949  5357  5403 I jxcore-log: # setup
09-16 11:55:21.949  5357  5403 I jxcore-log: 
,09-16 11:55:22.026  5357  5403 I jxcore-log: # 83. Make an HTTP request to /NotificationBeaconsbefore calling start
09-16 11:55:22.026  5357  5403 I jxcore-log: 
,09-16 11:55:22.156  5357  5403 I jxcore-log: ok 276 should be 404
09-16 11:55:22.156  5357  5403 I jxcore-log: 
,09-16 11:55:22.159  5357  5403 I jxcore-log: # teardown
09-16 11:55:22.159  5357  5403 I jxcore-log: 
,09-16 11:55:22.213  5357  5403 I jxcore-log: # setup
09-16 11:55:22.213  5357  5403 I jxcore-log: 
,09-16 11:55:22.311  5357  5403 I jxcore-log: # 84. #testThaliPeerAction - test getters
09-16 11:55:22.311  5357  5403 I jxcore-log: 
,09-16 11:55:22.368  5357  5403 I jxcore-log: ok 277 getPeerIdentifier
09-16 11:55:22.368  5357  5403 I jxcore-log: 
,09-16 11:55:22.369  5357  5403 I jxcore-log: ok 278 getConnectionType
09-16 11:55:22.369  5357  5403 I jxcore-log: 
,09-16 11:55:22.372  5357  5403 I jxcore-log: ok 279 getActionType
09-16 11:55:22.372  5357  5403 I jxcore-log: 
09-16 11:55:22.373  5357  5403 I jxcore-log: ok 280 getActionState
09-16 11:55:22.373  5357  5403 I jxcore-log: 
09-16 11:55:22.374  5357  5403 I jxcore-log: ok 281 getPskIdentity
09-16 11:55:22.374  5357  5403 I jxcore-log: 
,09-16 11:55:22.375  5357  5403 I jxcore-log: ok 282 getPskKey
09-16 11:55:22.375  5357  5403 I jxcore-log: 
,09-16 11:55:22.379  5357  5403 I jxcore-log: # teardown
09-16 11:55:22.379  5357  5403 I jxcore-log: 
,09-16 11:55:22.421  5357  5403 I jxcore-log: # setup
09-16 11:55:22.421  5357  5403 I jxcore-log: 
,09-16 11:55:22.474  5357  5403 I jxcore-log: # 85. #testThaliPeerAction - start and kill
09-16 11:55:22.474  5357  5403 I jxcore-log: 
,09-16 11:55:22.540  5357  5403 I jxcore-log: ok 283 initial state
09-16 11:55:22.540  5357  5403 I jxcore-log: 
,09-16 11:55:22.542  5357  5403 I jxcore-log: ok 284 after start
09-16 11:55:22.542  5357  5403 I jxcore-log: 
09-16 11:55:22.543  5357  5403 I jxcore-log: ok 285 after kill
09-16 11:55:22.543  5357  5403 I jxcore-log: 
,09-16 11:55:22.546  5357  5403 I jxcore-log: # teardown
09-16 11:55:22.546  5357  5403 I jxcore-log: 
,09-16 11:55:22.606  5357  5403 I jxcore-log: # setup
09-16 11:55:22.606  5357  5403 I jxcore-log: 
,09-16 11:55:22.674  5357  5403 I jxcore-log: # 86. #testThaliPeerAction - double start
09-16 11:55:22.674  5357  5403 I jxcore-log: 
,09-16 11:55:22.739  5357  5403 I jxcore-log: ok 286 should be equal
09-16 11:55:22.739  5357  5403 I jxcore-log: 
,09-16 11:55:22.743  5357  5403 I jxcore-log: # teardown
09-16 11:55:22.743  5357  5403 I jxcore-log: 
,09-16 11:55:22.796  5357  5403 I jxcore-log: # setup
09-16 11:55:22.796  5357  5403 I jxcore-log: 
,09-16 11:55:22.855  5357  5403 I jxcore-log: # 87. #testThaliPeerAction - start after kill
09-16 11:55:22.855  5357  5403 I jxcore-log: 
,09-16 11:55:22.914  5357  5403 I jxcore-log: ok 287 clean kill
09-16 11:55:22.914  5357  5403 I jxcore-log: 
,09-16 11:55:22.918  5357  5403 I jxcore-log: ok 288 should be equal
09-16 11:55:22.918  5357  5403 I jxcore-log: 
,09-16 11:55:22.923  5357  5403 I jxcore-log: # teardown
09-16 11:55:22.923  5357  5403 I jxcore-log: 
,09-16 11:55:22.967  5357  5403 I jxcore-log: # setup
09-16 11:55:22.967  5357  5403 I jxcore-log: 
,09-16 11:55:23.023  5357  5403 I jxcore-log: # 88. #testThaliPeerAction - make sure ids are unique
09-16 11:55:23.023  5357  5403 I jxcore-log: 
,09-16 11:55:23.105  5357  5403 I jxcore-log: ok 289 should not be equal
09-16 11:55:23.105  5357  5403 I jxcore-log: 
,09-16 11:55:23.110  5357  5403 I jxcore-log: # teardown
09-16 11:55:23.110  5357  5403 I jxcore-log: 
,09-16 11:55:23.157  5357  5403 I jxcore-log: # setup
09-16 11:55:23.157  5357  5403 I jxcore-log: 
,09-16 11:55:23.218  5357  5403 I jxcore-log: # 89. Test PeerConnectionInformation basics
09-16 11:55:23.218  5357  5403 I jxcore-log: 
,09-16 11:55:23.271  5357  5403 I jxcore-log: ok 290 connection type works
09-16 11:55:23.271  5357  5403 I jxcore-log: 
,09-16 11:55:23.271  5357  5403 I jxcore-log: ok 291 getHostAddress works
09-16 11:55:23.271  5357  5403 I jxcore-log: 
09-16 11:55:23.272  5357  5403 I jxcore-log: ok 292 getPortNumber works
09-16 11:55:23.272  5357  5403 I jxcore-log: 
09-16 11:55:23.272  5357  5403 I jxcore-log: ok 293 getSuggestedTCPTimeout works
09-16 11:55:23.272  5357  5403 I jxcore-log: 
,09-16 11:55:23.275  5357  5403 I jxcore-log: # teardown
09-16 11:55:23.275  5357  5403 I jxcore-log: 
,09-16 11:55:23.331  5357  5403 I jxcore-log: # setup
09-16 11:55:23.331  5357  5403 I jxcore-log: 
,09-16 11:55:23.395  5357  5403 I jxcore-log: # 90. Test PeerDictionary basic functionality
09-16 11:55:23.395  5357  5403 I jxcore-log: 
,09-16 11:55:23.491  5357  5403 I jxcore-log: ok 294 Entry counter must be 1
09-16 11:55:23.491  5357  5403 I jxcore-log: 
,09-16 11:55:23.492  5357  5403 I jxcore-log: ok 295 Size must be 1
09-16 11:55:23.492  5357  5403 I jxcore-log: 
,09-16 11:55:23.493  5357  5403 I jxcore-log: ok 296 Entry counter must be 2
09-16 11:55:23.493  5357  5403 I jxcore-log: 
,09-16 11:55:23.493  5357  5403 I jxcore-log: ok 297 Size must be 2
09-16 11:55:23.493  5357  5403 I jxcore-log: 
,09-16 11:55:23.495  5357  5403 I jxcore-log: ok 298 Entry2 should not be found
09-16 11:55:23.495  5357  5403 I jxcore-log: 
,09-16 11:55:23.495  5357  5403 I jxcore-log: ok 299 Size must be 1
09-16 11:55:23.495  5357  5403 I jxcore-log: 
,09-16 11:55:23.496  5357  5403 I jxcore-log: ok 300 Size must be 0
09-16 11:55:23.496  5357  5403 I jxcore-log: 
09-16 11:55:23.500  5357  5403 I jxcore-log: # teardown
09-16 11:55:23.500  5357  5403 I jxcore-log: 
,09-16 11:55:23.583  5357  5403 I jxcore-log: # setup
09-16 11:55:23.583  5357  5403 I jxcore-log: 
,09-16 11:55:23.658  5357  5403 I jxcore-log: # 91. Test PeerDictionary with multiple entries.
09-16 11:55:23.658  5357  5403 I jxcore-log: 
,09-16 11:55:24.313  5357  5403 I jxcore-log: ok 301 Size must be100
09-16 11:55:24.313  5357  5403 I jxcore-log: 
,09-16 11:55:24.315  5357  5403 I jxcore-log: ok 302 Entries between 20 and MAXSIZE + 20 should exist
09-16 11:55:24.315  5357  5403 I jxcore-log: 
,09-16 11:55:24.829  5357  5403 I jxcore-log: ok 303 WAITING state entry should not be removed
09-16 11:55:24.829  5357  5403 I jxcore-log: 
,09-16 11:55:24.830  5357  5403 I jxcore-log: # teardown
09-16 11:55:24.830  5357  5403 I jxcore-log: 
,09-16 11:55:24.863  5357  5403 I jxcore-log: # setup
09-16 11:55:24.863  5357  5403 I jxcore-log: 
,09-16 11:55:25.925  5357  5403 I jxcore-log: # 92. RESOLVED entries are removed before WAITING state entry.
09-16 11:55:25.925  5357  5403 I jxcore-log: 
,09-16 11:55:26.509  5357  5403 I jxcore-log: ok 304 Entries between 6 and MAXSIZE + 4 should exist
09-16 11:55:26.509  5357  5403 I jxcore-log: 
,09-16 11:55:26.510  5357  5403 I jxcore-log: ok 305 Size should be MAXSIZE
09-16 11:55:26.510  5357  5403 I jxcore-log: 
09-16 11:55:26.511  5357  5403 I jxcore-log: ok 306 Size should be MAXSIZE+6
09-16 11:55:26.511  5357  5403 I jxcore-log: 
09-16 11:55:26.512  5357  5403 I jxcore-log: # teardown
09-16 11:55:26.512  5357  5403 I jxcore-log: 
,09-16 11:55:26.543  5357  5403 I jxcore-log: # setup
09-16 11:55:26.543  5357  5403 I jxcore-log: 
,09-16 11:55:26.616  5357  5403 I jxcore-log: # 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
09-16 11:55:26.616  5357  5403 I jxcore-log: 
,09-16 11:55:27.203  5357  5403 I jxcore-log: ok 307 WAITING state entry should not be removed
09-16 11:55:27.203  5357  5403 I jxcore-log: 
,09-16 11:55:27.204  5357  5403 I jxcore-log: ok 308 Waiting entries between 6 and MAXSIZE + 4 should exist
09-16 11:55:27.204  5357  5403 I jxcore-log: 
09-16 11:55:27.204  5357  5403 I jxcore-log: ok 309 Size should be MAXSIZE
09-16 11:55:27.204  5357  5403 I jxcore-log: 
,09-16 11:55:27.205  5357  5403 I jxcore-log: ok 310 entryCounter should be MAXSIZE+6
09-16 11:55:27.205  5357  5403 I jxcore-log: 
09-16 11:55:27.206  5357  5403 I jxcore-log: # teardown
09-16 11:55:27.206  5357  5403 I jxcore-log: 
,09-16 11:55:27.243  5357  5403 I jxcore-log: # setup
09-16 11:55:27.243  5357  5403 I jxcore-log: 
,09-16 11:55:27.318  5357  5403 I jxcore-log: # 94. When CONTROLLED_BY_POOL entry is removed and kill is called.
09-16 11:55:27.318  5357  5403 I jxcore-log: 
,09-16 11:55:27.928  5357  5403 I jxcore-log: ok 311 Kill should be called once
09-16 11:55:27.928  5357  5403 I jxcore-log: 
,09-16 11:55:27.929  5357  5403 I jxcore-log: ok 312 Size should be 100
09-16 11:55:27.929  5357  5403 I jxcore-log: 
09-16 11:55:27.930  5357  5403 I jxcore-log: # teardown
09-16 11:55:27.930  5357  5403 I jxcore-log: 
,09-16 11:55:27.967  5357  5403 I jxcore-log: # setup
09-16 11:55:27.967  5357  5403 I jxcore-log: 
,09-16 11:55:28.041  5357  5403 I jxcore-log: # 95. compareBufferArrays
09-16 11:55:28.041  5357  5403 I jxcore-log: 
,09-16 11:55:28.105  5357  5403 I jxcore-log: ok 313 should throw
09-16 11:55:28.105  5357  5403 I jxcore-log: 
,09-16 11:55:28.109  5357  5403 I jxcore-log: ok 314 should throw
09-16 11:55:28.109  5357  5403 I jxcore-log: 
,09-16 11:55:28.111  5357  5403 I jxcore-log: ok 315 (unnamed assert)
09-16 11:55:28.111  5357  5403 I jxcore-log: 
,09-16 11:55:28.112  5357  5403 I jxcore-log: ok 316 (unnamed assert)
09-16 11:55:28.112  5357  5403 I jxcore-log: 
09-16 11:55:28.114  5357  5403 I jxcore-log: ok 317 (unnamed assert)
09-16 11:55:28.114  5357  5403 I jxcore-log: 
,09-16 11:55:28.115  5357  5403 I jxcore-log: ok 318 (unnamed assert)
09-16 11:55:28.115  5357  5403 I jxcore-log: 
,09-16 11:55:28.117  5357  5403 I jxcore-log: ok 319 (unnamed assert)
09-16 11:55:28.117  5357  5403 I jxcore-log: 
,09-16 11:55:28.121  5357  5403 I jxcore-log: # teardown
09-16 11:55:28.121  5357  5403 I jxcore-log: 
,09-16 11:55:28.169  5357  5403 I jxcore-log: # setup
09-16 11:55:28.169  5357  5403 I jxcore-log: 
,09-16 11:55:28.247  5357  5403 I jxcore-log: # 96. Call start twice and get error
09-16 11:55:28.247  5357  5403 I jxcore-log: 
,09-16 11:55:28.307  5357  5403 I jxcore-log: ok 320 should throw
09-16 11:55:28.307  5357  5403 I jxcore-log: 
,09-16 11:55:28.311  5357  5403 I jxcore-log: # teardown
09-16 11:55:28.311  5357  5403 I jxcore-log: 
,09-16 11:55:28.371  5357  5403 I jxcore-log: # setup
09-16 11:55:28.371  5357  5403 I jxcore-log: 
,09-16 11:55:28.423  5357  5403 I jxcore-log: # 97. Start and make sure it runs
09-16 11:55:28.423  5357  5403 I jxcore-log: 
,09-16 11:55:28.482  5357  5403 I jxcore-log: # teardown
09-16 11:55:28.482  5357  5403 I jxcore-log: 
,09-16 11:55:28.535  5357  5403 I jxcore-log: # setup
09-16 11:55:28.535  5357  5403 I jxcore-log: 
,09-16 11:55:28.587  5357  5403 I jxcore-log: # 98. Make sure getTimeWhenRun is right after start
09-16 11:55:28.587  5357  5403 I jxcore-log: 
,09-16 11:55:28.641  5357  5403 I jxcore-log: ok 321 (unnamed assert)
09-16 11:55:28.641  5357  5403 I jxcore-log: 
,09-16 11:55:28.644  5357  5403 I jxcore-log: # teardown
09-16 11:55:28.644  5357  5403 I jxcore-log: 
,09-16 11:55:28.704  5357  5403 I jxcore-log: # setup
09-16 11:55:28.704  5357  5403 I jxcore-log: 
,09-16 11:55:28.759  5357  5403 I jxcore-log: # 99. Make sure getTimeWhenRun is -1 after function is called
09-16 11:55:28.759  5357  5403 I jxcore-log: 
,09-16 11:55:28.822  5357  5403 I jxcore-log: ok 322 should be equal
09-16 11:55:28.822  5357  5403 I jxcore-log: 
,09-16 11:55:28.828  5357  5403 I jxcore-log: # teardown
09-16 11:55:28.828  5357  5403 I jxcore-log: 
,09-16 11:55:28.885  5357  5403 I jxcore-log: # setup
09-16 11:55:28.885  5357  5403 I jxcore-log: 
,09-16 11:55:28.986  5357  5403 I jxcore-log: # 100. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
09-16 11:55:28.986  5357  5403 I jxcore-log: 
,09-16 11:55:29.032  5357  5403 I jxcore-log: ok 323 should be equal
09-16 11:55:29.032  5357  5403 I jxcore-log: 
,09-16 11:55:29.034  5357  5403 I jxcore-log: ok 324 should be equal
09-16 11:55:29.034  5357  5403 I jxcore-log: 
,09-16 11:55:29.038  5357  5403 I jxcore-log: ok 325 should throw
09-16 11:55:29.038  5357  5403 I jxcore-log: 
,09-16 11:55:29.042  5357  5403 I jxcore-log: # teardown
09-16 11:55:29.042  5357  5403 I jxcore-log: 
,09-16 11:55:29.069  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:29.095  5357  5403 I jxcore-log: # setup
09-16 11:55:29.095  5357  5403 I jxcore-log: 
,09-16 11:55:29.162  5357  5403 I jxcore-log: # 101. Test TransientState
09-16 11:55:29.162  5357  5403 I jxcore-log: 
,09-16 11:55:29.210  5357  5403 I jxcore-log: ok 326 should throw
09-16 11:55:29.210  5357  5403 I jxcore-log: 
,09-16 11:55:29.214  5357  5403 I jxcore-log: ok 327 should throw
09-16 11:55:29.214  5357  5403 I jxcore-log: 
,09-16 11:55:29.215  5357  5403 I jxcore-log: ok 328 should be equal
09-16 11:55:29.215  5357  5403 I jxcore-log: 
09-16 11:55:29.216  5357  5403 I jxcore-log: ok 329 should be equal
09-16 11:55:29.216  5357  5403 I jxcore-log: 
,09-16 11:55:29.217  5357  5403 I jxcore-log: ok 330 should be equal
09-16 11:55:29.217  5357  5403 I jxcore-log: 
,09-16 11:55:29.218  5357  5403 I jxcore-log: ok 331 should be equal
09-16 11:55:29.218  5357  5403 I jxcore-log: 
09-16 11:55:29.220  5357  5403 I jxcore-log: ok 332 (unnamed assert)
09-16 11:55:29.220  5357  5403 I jxcore-log: 
09-16 11:55:29.221  5357  5403 I jxcore-log: ok 333 (unnamed assert)
09-16 11:55:29.221  5357  5403 I jxcore-log: 
,09-16 11:55:29.225  5357  5403 I jxcore-log: # teardown
09-16 11:55:29.225  5357  5403 I jxcore-log: 
,09-16 11:55:29.273  5357  5403 I jxcore-log: # setup
09-16 11:55:29.273  5357  5403 I jxcore-log: 
,09-16 11:55:29.327  5357  5403 I jxcore-log: # 102. No peers and empty database
09-16 11:55:29.327  5357  5403 I jxcore-log: 
,09-16 11:55:29.551  5357  5403 I jxcore-log: ok 334 verify failed
09-16 11:55:29.551  5357  5403 I jxcore-log: 
,09-16 11:55:29.551  5357  5403 I jxcore-log: ok 335 constructor called once
09-16 11:55:29.551  5357  5403 I jxcore-log: 
09-16 11:55:29.553  5357  5403 I jxcore-log: ok 336 constructor called with right args
09-16 11:55:29.553  5357  5403 I jxcore-log: 
09-16 11:55:29.555  5357  5403 I jxcore-log: ok 337 match start arg
09-16 11:55:29.555  5357  5403 I jxcore-log: 
,09-16 11:55:29.555  5357  5403 I jxcore-log: ok 338 start called once
09-16 11:55:29.555  5357  5403 I jxcore-log: 
09-16 11:55:29.556  5357  5403 I jxcore-log: ok 339 stop called once
09-16 11:55:29.556  5357  5403 I jxcore-log: 
,09-16 11:55:29.556  5357  5403 I jxcore-log: ok 340 stop after start
09-16 11:55:29.556  5357  5403 I jxcore-log: 
,09-16 11:55:29.560  5357  5403 I jxcore-log: # teardown
09-16 11:55:29.560  5357  5403 I jxcore-log: 
,09-16 11:55:29.587  5357  5403 I jxcore-log: # setup
09-16 11:55:29.587  5357  5403 I jxcore-log: 
,09-16 11:55:29.658  5357  5403 I jxcore-log: # 103. One peer and empty DB
09-16 11:55:29.658  5357  5403 I jxcore-log: 
,09-16 11:55:29.893  5357  5403 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
09-16 11:55:29.893  5357  5403 I jxcore-log: 
,09-16 11:55:29.895  5357  5403 I jxcore-log: ok 341 verify failed
09-16 11:55:29.895  5357  5403 I jxcore-log: 
,09-16 11:55:29.895  5357  5403 I jxcore-log: ok 342 constructor called once
09-16 11:55:29.895  5357  5403 I jxcore-log: 
09-16 11:55:29.896  5357  5403 I jxcore-log: ok 343 constructor called with right args
09-16 11:55:29.896  5357  5403 I jxcore-log: 
,09-16 11:55:29.897  5357  5403 I jxcore-log: ok 344 match start arg
09-16 11:55:29.897  5357  5403 I jxcore-log: 
,09-16 11:55:29.897  5357  5403 I jxcore-log: ok 345 start called once
09-16 11:55:29.897  5357  5403 I jxcore-log: 
09-16 11:55:29.897  5357  5403 I jxcore-log: ok 346 stop called once
09-16 11:55:29.897  5357  5403 I jxcore-log: 
09-16 11:55:29.897  5357  5403 I jxcore-log: ok 347 stop after start
09-16 11:55:29.897  5357  5403 I jxcore-log: 
,09-16 11:55:29.900  5357  5403 I jxcore-log: # teardown
09-16 11:55:29.900  5357  5403 I jxcore-log: 
,09-16 11:55:29.968  5357  5403 I jxcore-log: # setup
09-16 11:55:29.968  5357  5403 I jxcore-log: 
,09-16 11:55:30.047  5357  5403 I jxcore-log: # 104. One peer with _Local set behind current seq
09-16 11:55:30.047  5357  5403 I jxcore-log: 
,09-16 11:55:30.071  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:30.296  5357  5403 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
09-16 11:55:30.296  5357  5403 I jxcore-log: 
,09-16 11:55:30.297  5357  5403 I jxcore-log: ok 348 verify failed
09-16 11:55:30.297  5357  5403 I jxcore-log: 
,09-16 11:55:30.298  5357  5403 I jxcore-log: ok 349 constructor called once
09-16 11:55:30.298  5357  5403 I jxcore-log: 
,09-16 11:55:30.299  5357  5403 I jxcore-log: ok 350 constructor called with right args
09-16 11:55:30.299  5357  5403 I jxcore-log: 
,09-16 11:55:30.300  5357  5403 I jxcore-log: ok 351 match start arg
09-16 11:55:30.300  5357  5403 I jxcore-log: 
,09-16 11:55:30.300  5357  5403 I jxcore-log: ok 352 start called once
09-16 11:55:30.300  5357  5403 I jxcore-log: 
09-16 11:55:30.300  5357  5403 I jxcore-log: ok 353 stop called once
09-16 11:55:30.300  5357  5403 I jxcore-log: 
,09-16 11:55:30.301  5357  5403 I jxcore-log: ok 354 stop after start
09-16 11:55:30.301  5357  5403 I jxcore-log: 
,09-16 11:55:30.304  5357  5403 I jxcore-log: # teardown
09-16 11:55:30.304  5357  5403 I jxcore-log: 
,09-16 11:55:30.343  5357  5403 I jxcore-log: # setup
09-16 11:55:30.343  5357  5403 I jxcore-log: 
,09-16 11:55:30.426  5357  5403 I jxcore-log: # 105. One peer with _Local set equal to current seq
09-16 11:55:30.426  5357  5403 I jxcore-log: 
,09-16 11:55:30.687  5357  5403 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
09-16 11:55:30.687  5357  5403 I jxcore-log: 
,09-16 11:55:30.689  5357  5403 I jxcore-log: ok 355 verify failed
09-16 11:55:30.689  5357  5403 I jxcore-log: 
,09-16 11:55:30.690  5357  5403 I jxcore-log: ok 356 constructor called once
09-16 11:55:30.690  5357  5403 I jxcore-log: 
,09-16 11:55:30.690  5357  5403 I jxcore-log: ok 357 constructor called with right args
09-16 11:55:30.690  5357  5403 I jxcore-log: 
09-16 11:55:30.691  5357  5403 I jxcore-log: ok 358 match start arg
09-16 11:55:30.691  5357  5403 I jxcore-log: 
,09-16 11:55:30.691  5357  5403 I jxcore-log: ok 359 start called once
09-16 11:55:30.691  5357  5403 I jxcore-log: 
09-16 11:55:30.691  5357  5403 I jxcore-log: ok 360 stop called once
09-16 11:55:30.691  5357  5403 I jxcore-log: 
,09-16 11:55:30.692  5357  5403 I jxcore-log: ok 361 stop after start
09-16 11:55:30.692  5357  5403 I jxcore-log: 
,09-16 11:55:30.695  5357  5403 I jxcore-log: # teardown
09-16 11:55:30.695  5357  5403 I jxcore-log: 
,09-16 11:55:31.072  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:32.073  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:33.074  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:34.074  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:55:34.265   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:55:54.076  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:55.077  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:56.078  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:57.080  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:58.081  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:55:59.081  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:56:03.031   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:56:09.093   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:56:14.269   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:56:15.134   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:56:18.167   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:56:24.082  5752  5752 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:56:24.083  5752  5752 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:56:29.084  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:30.085  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:31.087  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:32.088  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:33.090  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:34.091  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 11:56:34.271   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:56:39.092  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:40.094  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:41.095  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:42.097  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:43.098  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:44.099  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:56:54.101  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:54.274   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:56:55.102  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:56.104  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:57.105  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:58.106  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:56:59.107  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:57:14.108  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:14.276   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:57:15.110  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:16.112  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:17.113  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:18.115  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:19.116  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:57:34.277   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:57:36.866   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:57:39.118  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:39.898   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:57:40.119  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:41.120  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:42.121  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:43.123  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:57:44.124  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:58:07.135   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:09.124  5752  5752 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:58:09.125  5752  5752 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:58:14.282   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:58:16.219   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:19.126  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:20.127  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:21.129  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:22.131  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:23.132  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:24.133  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 11:58:28.327   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:29.135  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:30.136  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:31.138  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:31.353   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:32.139  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:33.141  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:34.142  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:58:34.286   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:58:37.405   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:40.436   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:43.466   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:44.144  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:45.145  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:46.147  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:46.491   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:58:47.148  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:48.150  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:58:49.151  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:58:54.289   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:58:58.608   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:01.651   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:04.153  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:05.154  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:06.155  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:07.157  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:08.158  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:09.159  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:59:14.291   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:59:16.799   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:22.856   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:28.908   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:29.161  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:30.162  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:31.164  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:32.165  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:33.167  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:59:34.168  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:59:34.292   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:59:34.971   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:50.116   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:54.294   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:59:56.172   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 11:59:59.168  5752  5752 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:59:59.169  5752  5752 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:00:05.252   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:11.306   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:14.170  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:14.295   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:00:15.171  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:16.173  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:17.174  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:18.176  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:19.177  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:00:23.403   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:24.178  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:25.180  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:26.181  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:26.435   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:27.182  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:28.184  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:29.185  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:00:32.488   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:35.501   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:38.532   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:39.186  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:40.187  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:41.188  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:42.189  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:43.191  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:44.191  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:00:44.590   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:53.674   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:00:54.299   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:00:59.192  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:00:59.733   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:00.193  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:01.195  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:02.196  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:03.198  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:04.199  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:01:11.854   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:14.302   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:01:17.915   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:20.942   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:23.975   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:24.200  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:25.202  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:26.203  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:27.007   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:27.205  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:28.206  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:01:29.206  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:01:33.067   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:34.304   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:01:39.127   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:48.217   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:01:54.207  5752  5752 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 12:01:54.208  5752  5752 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:01:54.305   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:02:03.374   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:06.390   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:14.209  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:14.305   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:02:15.210  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:16.211  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:17.212  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:18.214  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:18.499   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:19.215  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:02:24.217  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:24.556   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:25.218  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:26.220  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:27.221  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:28.223  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:29.224  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:02:33.648   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:34.307   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:02:39.225  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:39.710   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:40.227  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:41.228  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:42.229  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:43.231  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:02:44.232  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-16 12:02:45.773   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:48.808   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:54.308   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:02:54.875   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:57.905   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:02:59.233  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:00.234  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:01.235  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:02.236  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:03.238  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:04.239  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:03:06.999   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:03:13.056   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:03:14.310   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:03:24.240  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:25.178   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:03:25.241  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:26.243  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:27.244  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:28.210   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:03:28.246  5752  5752 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:03:29.247  5752  5752 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:03:34.310   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:03:40.333   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:03:46.390   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:03:54.248  5752  5752 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 12:03:54.248  5752  5752 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:03:54.313   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:03:58.506   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:04:01.538   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:04:13.652   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:04:14.315   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:04:19.258  5752  5754 E QC-QMI  : qmi_client [5752] 1d: failed to locate client data
,09-16 12:04:19.260   519   519 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-16 12:04:19.261   519   519 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-16 12:04:19.266  5752  5752 I Atfwd_Daemon: Stop the daemon....
,09-16 12:04:19.304  5772  5772 I libmdmdetect: ESOC framework not supported
,09-16 12:04:19.304  5772  5772 I libmdmdetect: Found internal modem: modem
09-16 12:04:19.300  5772  5772 W ATFWD-daemon: type=1400 audit(0.0:129): avc: denied { read write } for name="diag" dev="tmpfs" ino=12329 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-16 12:04:19.305  5772  5772 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 12:04:19.314  5772  5772 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-16 12:04:19.314  5772  5772 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 12:04:19.315  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:19.707   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:04:20.320  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:21.322  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:22.323  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:23.325  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:24.325  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:04:24.491   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1170157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:04:29.326  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:30.328  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:31.329  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:32.330  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:33.332  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:34.332  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:04:41.651   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1187317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:04:44.334  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:45.335  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:46.336  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:47.337  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:48.339  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:04:49.340  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:04:49.611   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1195276, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:04:54.319   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:05:04.341  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:05.343  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:06.344  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:06.784   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1212450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:05:07.346  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:08.347  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:09.348  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:05:11.180   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:05:13.976   927   939 I UsageStatsService: User[0] Flushing usage stats to disk
,09-16 12:05:14.320   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:05:14.650   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1220316, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:05:17.238   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:05:29.349  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:30.351  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:31.352  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:31.824   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1237490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:05:32.353  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:33.354  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:05:34.322   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:05:34.355  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:05:39.691   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:05:54.324   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:05:56.878   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1262544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:05:59.356  5772  5772 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-16 12:05:59.356  5772  5772 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:06:04.357  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:04.758   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:06:05.358  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:06.360  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:07.361  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:08.363  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:09.364  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:06:14.324   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:06:14.365  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:15.367  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:16.368  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:17.369  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:18.371  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:19.372  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:06:21.918   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1287584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:06:29.373  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:29.798   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:06:29.887   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:06:30.375  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:31.376  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:32.378  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:32.931   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:06:33.380  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:34.326   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:06:34.381  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:06:46.971   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1312637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:06:49.382  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:50.384  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:51.385  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:52.386  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:53.388  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:06:54.327   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:06:54.388  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:06:54.837   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:07:12.011   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1337677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:07:14.330   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:07:14.390  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:15.291   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:07:15.391  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:16.392  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:17.393  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:18.312   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:07:18.394  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:19.394  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:07:19.877   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:07:34.331   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:07:37.051   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1362717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:07:44.395  5772  5772 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 12:07:44.396  5772  5772 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:07:44.918   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:07:48.589   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:07:54.335   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:07:54.397  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:55.398  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:56.399  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:57.401  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:57.665   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:07:58.402  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:07:59.403  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:08:02.091   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1387757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:08:04.405  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:05.406  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:06.408  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:07.409  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:08.410  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:09.411  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:08:09.957   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:08:14.337   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:08:18.877   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:08:19.412  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:20.414  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:21.415  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:22.418  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:23.420  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:24.421  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:08:27.131   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1412797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:08:27.967   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:08:34.338   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:08:35.291   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:08:39.422  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:40.093   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:08:40.423  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:41.425  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:42.426  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:43.123   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:08:43.428  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:08:44.429  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:08:52.464   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1438130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:08:54.341   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:08:55.239   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:00.332   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:09:01.300   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:04.430  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:05.432  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:06.434  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:07.435  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:08.437  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:09.438  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:09:13.421   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:14.342   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:09:16.460   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:17.504   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:09:23.344   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1469010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:09:28.571   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:34.344   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:09:34.439  5772  5772 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 12:09:34.439  5772  5772 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:09:34.609   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:42.558   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1488224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:09:46.714   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:48.384   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1494050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:09:49.440  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:50.442  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:51.443  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:52.445  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:52.781   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:09:53.447  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:09:54.347   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:09:54.448  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:09:59.449  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:00.450  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:01.451  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:01.876   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:02.452  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:03.454  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:04.455  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:10:07.611   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1513276, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:10:07.939   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:13.437   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1519103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:10:14.348   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:10:14.456  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:15.457  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:16.458  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:17.029   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:17.460  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:18.462  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:19.462  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:10:23.088   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:32.678   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1538344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:10:34.464  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:35.465  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:36.467  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:37.468  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:38.230   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:38.469  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:10:38.491   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1544157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:10:39.470  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:10:41.259   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:50.352   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:53.388   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:10:54.351   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:10:57.718   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1563384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:10:59.472  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:00.473  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:01.475  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:02.476  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:03.478  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:03.531   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1569197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:11:04.478  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:11:08.537   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:14.355   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:11:14.580   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:22.757   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1588423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:11:23.672   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:28.571   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1594237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:11:29.479  5772  5772 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 12:11:29.479  5772  5772 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:11:29.736   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:34.357   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:11:41.860   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:44.893   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:47.811   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1613477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:11:49.481  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:50.482  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:51.483  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:52.484  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:53.486  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:11:53.624   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1619290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:11:54.358   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:11:54.486  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:11:57.010   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:11:59.488  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:00.489  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:01.490  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:02.491  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:03.078   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:03.493  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:04.494  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:12:12.851   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1638517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:12:14.361   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:12:14.495  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:15.496  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:16.498  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:17.499  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:18.501  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:18.678   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1644344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:12:19.502  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:12:30.343   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:34.363   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:12:34.503  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:35.504  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:36.382   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:36.505  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:37.507  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:37.891   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1663557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:12:38.508  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:12:39.412   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:39.509  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 12:12:42.444   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:44.304   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1669970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:12:48.500   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:51.530   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:12:54.367   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:12:59.510  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:13:00.511  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:13:01.512  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:13:02.514  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:13:03.515  5772  5772 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:13:03.531   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1689197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:13:03.632   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:13:04.516  5772  5772 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 12:13:09.357   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1695023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:13:09.698   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:13:14.368   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:13:18.786   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:13:24.846   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 12:13:28.584   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1714250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 12:13:29.517  5772  5772 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 12:13:29.517  5772  5772 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 12:13:34.369   927  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 12:13:34.411   927  5668 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1720077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 12:13:36.956   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,TIME-OUT KILL (timeout was 1400000ms),09-16 12:13:43.018   927  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-16 12:13:43.530  5785  5785 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 12:13:43.536  5785  5785 D AndroidRuntime: CheckJNI is OFF
09-16 12:13:43.569  5785  5785 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 12:13:43.610  5785  5785 I Radio-JNI: register_android_hardware_Radio DONE
09-16 12:13:43.627  5785  5785 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-16 12:13:43.635   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-16 12:13:43.636   927   940 I ActivityManager: Killing 5357:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-16 12:13:43.740   927  3144 D GraphicsStats: Buffer count: 2
09-16 12:13:43.740   927   938 I WindowState: WIN DEATH: Window{f07d72f u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-16 12:13:43.740   927  2965 D WifiService: Client connection lost with reason: 4
09-16 12:13:43.783   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-16 12:13:43.783   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-16 12:13:43.784   927   950 I art     : Starting a blocking GC Explicit
09-16 12:13:43.784   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-16 12:13:43.784   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-16 12:13:43.784   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:13:43.784   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:43.784   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:13:43.784   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:13:43.786   927   940 I ActivityManager:   Force finishing activity ActivityRecord{f9ebdb0 u0 com.test.thalitest/.MainActivity t4}
09-16 12:13:43.796   927  3545 W ActivityManager: Spurious death for ProcessRecord{579cdaf 0:com.test.thalitest/u0a77}, curProc for 5357: null
09-16 12:13:43.800   927   945 W WindowManager: Attempted to add application window with unknown token Token{a829429 ActivityRecord{f9ebdb0 u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
09-16 12:13:43.800   927   945 W WindowManager: Token{a829429 ActivityRecord{f9ebdb0 u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{a829429 ActivityRecord{f9ebdb0 u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-16 12:13:43.800   927   945 W WindowManager: view not successfully added to wm, removing view
09-16 12:13:43.800   927   945 W WindowManager: Exception when adding starting window
09-16 12:13:43.800   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{1f92466 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-16 12:13:43.800   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-16 12:13:43.800   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-16 12:13:43.800   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-16 12:13:43.800   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-16 12:13:43.800   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-16 12:13:43.800   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:13:43.800   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:43.800   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:13:43.800   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:13:43.867   927   950 I art     : Explicit concurrent mark sweep GC freed 65356(3MB) AllocSpace objects, 19(532KB) LOS objects, 33% free, 29MB/44MB, paused 1.391ms total 83.118ms
09-16 12:13:43.892   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-16 12:13:43.896  5785  5785 I art     : System.exit called, status: 0
09-16 12:13:43.896  5785  5785 I AndroidRuntime: VM exiting with result code 0.
09-16 12:13:43.901   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-16 12:13:43.914   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-16 12:13:43.917  3390  3390 I Keyboard.Facilitator: resetDictionaries() : en_US
09-16 12:13:43.918  5612  5612 D BluetoothMapAppObserver: onReceive
09-16 12:13:43.918  5612  5612 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-16 12:13:43.921  3449  3937 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-16 12:13:43.927   927  2930 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-16 12:13:43.947  3390  5799 I Keyboard.Facilitator.DecoderInitializer: run()
09-16 12:13:43.956  3406  5800 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-16 12:13:43.956  3525  3525 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-16 12:13:43.957  3390  5799 I Decoder : createOrResetDecoder
09-16 12:13:43.987   492   492 W kworker/3:2: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 12:13:43.996   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-16 12:13:43.990   492   492 W kworker/3:2: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 12:13:44.000   492   492 W kworker/3:2: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 12:13:44.008  3613  3613 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-16 12:13:44.009  3613  3613 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-16 12:13:44.009  3613  3613 E AndroidRuntime: FATAL EXCEPTION: main
09-16 12:13:44.009  3613  3613 E AndroidRuntime: Process: com.google.process.gapps, PID: 3613
09-16 12:13:44.009  3613  3613 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-16 12:13:44.009  3613  3613 E AndroidRuntime: 	... 8 more
09-16 12:13:44.018  3613  3613 I Process : Sending signal. PID: 3613 SIG: 9
09-16 12:13:44.019  3556  3695 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-16 12:13:44.019   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-16 12:13:44.020   927   939 E PackageManager: Failed to write settings, restoring backup
09-16 12:13:44.020   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-16 12:13:44.020   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-16 12:13:44.020   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-16 12:13:44.020   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-16 12:13:44.020   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-16 12:13:44.020   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:13:44.020   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:44.020   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: Can't write: system_app_crash
09-16 12:13:44.021   927  5806 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 12:13:44.021   927  5806 E DropBoxManagerService: 	... 5 more
09-16 12:13:44.023   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-16 12:13:44.023   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 12:13:44.023   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 12:13:44.023   927   940 E DropBoxManagerService: 	... 13 more
09-16 12:13:44.036   927  3420 I ActivityManager: Start proc 5807:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-16 12:13:44.036  3556  3695 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-16 12:13:44.036  3556  3695 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3556
09-16 12:13:44.036  3556  3695 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:44.036  3556  3695 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:13:44.041   927  3919 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 12:13:44.043   927  5815 E DropBoxManagerService: Can't write: system_app_crash
09-16 12:13:44.043   927  5815 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 12:13:44.043   927  5815 E DropBoxManagerService: 	... 5 more
09-16 12:13:44.045  3556  3695 I Process : Sending signal. PID: 3556 SIG: 9
09-16 12:13:44.046   927  2965 D WifiService: Client connection lost with reason: 4
09-16 12:13:44.052   927  3545 I ActivityManager: Process com.google.process.gapps (pid 3613) has died
09-16 12:13:44.053   927  3545 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
09-16 12:13:44.053   927  3545 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
09-16 12:13:44.053   927  3545 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
09-16 12:13:44.053   927  3545 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
09-16 12:13:44.053   927  3545 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.herrevad.services.LightweightNetworkQualityAndroidService in 40999ms
09-16 12:13:44.077   927  3427 I ActivityManager: Start proc 5821:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-16 12:13:44.083  3406  3425 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjCB726A990) - 
09-16 12:13:44.108   927  2929 W InputDispatcher: channel 'ed6ebbf com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-16 12:13:44.109   927  2929 E InputDispatcher: channel 'ed6ebbf com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-16 12:13:44.111   927  3144 D GraphicsStats: Buffer count: 1
09-16 12:13:44.111   927  3147 I WindowState: WIN DEATH: Window{ed6ebbf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-16 12:13:44.111   927  3147 W InputDispatcher: Attempted to unregister already unregistered input channel 'ed6ebbf com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-16 12:13:44.125  3406  3425 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-16 12:13:44.125  3406  3425 E AndroidRuntime: Process: android.process.acore, PID: 3406
09-16 12:13:44.125  3406  3425 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:13:44.125  3406  3425 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 12:13:44.127   927  3545 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3556) has died
09-16 12:13:44.128   927  3545 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-16 12:13:44.133   927  5835 E DropBoxManagerService: Can't write: system_app_crash
09-16 12:13:44.133   927  5835 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 12:13:44.133   927  5835 E DropBoxManagerService: 	... 5 more
09-16 12:13:44.140  3406  3425 I Process : Sending signal. PID: 3406 SIG: 9
09-16 12:13:44.387   383   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
