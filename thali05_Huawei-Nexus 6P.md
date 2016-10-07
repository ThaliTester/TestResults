#### Test 87899936b4f2b1c_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-07 06:40:18.863   545   545 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-07 06:40:18.863   545   545 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-07 06:40:20.299  5692  5692 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-07 06:40:20.305  5692  5692 D AndroidRuntime: CheckJNI is OFF
10-07 06:40:20.335  5692  5692 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-07 06:40:20.371  5692  5692 I Radio-JNI: register_android_hardware_Radio DONE
10-07 06:40:20.389  5692  5692 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-07 06:40:20.394   930  3646 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-07 06:40:20.444   930  3646 I ActivityManager: Start proc 5701:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-07 06:40:20.467  5692  5692 D AndroidRuntime: Shutting down VM
,10-07 06:40:20.767   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 06:40:20.789   930  3607 I WindowManager: Screenshot max retries 4 of Token{931f85d ActivityRecord{d610234 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{a6e63cc u0 Starting com.test.thalitest} drawState=2
,10-07 06:40:20.871  5701  5701 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-07 06:40:20.909  5701  5701 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-07 06:40:20.936  5701  5701 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 955-975)
,10-07 06:40:20.936  5701  5701 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 06:40:20.956  5701  5701 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a8e00a2}
,10-07 06:40:20.957  5701  5701 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-07 06:40:20.957  5701  5701 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-07 06:40:20.962  5701  5701 I BrowserStartupController: Initializing chromium process, singleProcess=true
10-07 06:40:20.963  5701  5701 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-07 06:40:20.998  5701  5701 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-07 06:40:21.013  5701  5701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-07 06:40:21.014  5701  5701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 06:40:21.014  5701  5701 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-07 06:40:21.014  5701  5701 I Adreno  : Build Date                       : 12/06/15
10-07 06:40:21.014  5701  5701 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-07 06:40:21.014  5701  5701 I Adreno  : Local Branch                     : mybranch17112971
10-07 06:40:21.014  5701  5701 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-07 06:40:21.014  5701  5701 I Adreno  : Remote Branch                    : NONE
10-07 06:40:21.014  5701  5701 I Adreno  : Reconstruct Branch               : NOTHING
,10-07 06:40:21.062   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e4be93:true
,10-07 06:40:21.096   402   402 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34926]" dev="sockfs" ino=34926 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:21.096   402   402 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34926]" dev="sockfs" ino=34926 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:21.107  5701  5701 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-07 06:40:21.116  5701  5701 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-07 06:40:21.140  5701  5738 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-07 06:40:21.139   402   402 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32112]" dev="sockfs" ino=32112 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-07 06:40:21.139   402   402 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32112]" dev="sockfs" ino=32112 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:21.139  3201  3201 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16879]" dev="sockfs" ino=16879 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:21.139  3201  3201 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16879]" dev="sockfs" ino=16879 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:21.146  5701  5725 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-07 06:40:21.163  5701  5738 I OpenGLRenderer: Initialized EGL, version 1.4
,10-07 06:40:21.237   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +446ms (total +813ms)
,10-07 06:40:21.274  5701  5701 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5701
,10-07 06:40:21.404  5701  5701 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-07 06:40:21.499  5701  5740 D jxcore_app_log: JniHelper::setJavaVM(0xf4f3c000), pthread_self() = -565970640
,10-07 06:40:21.503  5701  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-07 06:40:21.503  5701  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-07 06:40:21.503  5701  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-07 06:40:21.503  5701  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-07 06:40:21.503  5701  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-07 06:40:21.503  5701  5740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5f3ec8 added. We now have 1 listener(s)
,10-07 06:40:21.505  5701  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-07 06:40:21.506  5701  5740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:40:21.506  5701  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 06:40:21.506  5701  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-07 06:40:21.508  5701  5740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e6b47 added. We now have 1 listener(s)
,10-07 06:40:21.508  5701  5740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:40:21.513   930  3018 D WifiService: New client listening to asynchronous messages
,10-07 06:40:21.514  5701  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:40:21.514  5701  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-07 06:40:21.514  5701  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-07 06:40:21.514  5701  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-07 06:40:21.514  5701  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-07 06:40:21.516  5701  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:21.516  5701  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-07 06:40:21.520  5701  5740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:21.520  5701  5740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 06:40:21.520  5701  5740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-07 06:40:21.520  5701  5740 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:40:21.520  5701  5740 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-07 06:40:21.606  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:21.608  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:21.611  5701  5701 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-07 06:40:21.810  5701  5747 W jxcore-log: Initializing JXcore engine
10-07 06:40:21.810  5701  5747 W jxcore-log: JXcore engine is ready
,10-07 06:40:21.832  5747  5747 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12046 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-07 06:40:21.832  5747  5747 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15454]" dev="sockfs" ino=15454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-07 06:40:21.832  5747  5747 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-07 06:40:21.832  5747  5747 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32092]" dev="sockfs" ino=32092 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-07 06:40:21.843  5701  5747 W jxcore-log: Starting JXcore engine
,10-07 06:40:21.901  5701  5747 W jxcore-log: Platform android
10-07 06:40:21.901  5701  5747 W jxcore-log: 
,10-07 06:40:21.901  5701  5747 W jxcore-log: Process ARCH arm
10-07 06:40:21.901  5701  5747 W jxcore-log: 
,10-07 06:40:22.000  5701  5747 I jxcore-log: JXcore Cordova bridge is ready!
10-07 06:40:22.000  5701  5747 I jxcore-log: 
,10-07 06:40:22.000  5701  5747 W jxcore-log: JXcore engine is started
,10-07 06:40:22.003  5701  5740 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-07 06:40:22.006  5701  5701 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-07 06:40:28.865   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:29.866   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:30.867   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:31.739  5701  5747 I jxcore-log: 2016-10-07 10:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-07 06:40:31.739  5701  5747 I jxcore-log: 
,10-07 06:40:31.740  5701  5747 I jxcore-log: 2016-10-07 10:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-07 06:40:31.740  5701  5747 I jxcore-log: 
,10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:31.744  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 06:40:31.746  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 06:40:31.747  5701  5747 I jxcore-log: 2016-10-07 10:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-07 06:40:31.747  5701  5747 I jxcore-log: 
,10-07 06:40:31.749  5701  5747 I jxcore-log: 2016-10-07 10:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-07 06:40:31.749  5701  5747 I jxcore-log: 
,10-07 06:40:31.868   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:31.999  5701  5747 I jxcore-log: 2016-10-07 10:40:31 - DEBUG UnitTest_app: 'Running unit tests'
10-07 06:40:31.999  5701  5747 I jxcore-log: 
,10-07 06:40:32.000  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 06:40:32.000  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1e95ab added. We now have 2 listener(s)
,10-07 06:40:32.000  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 06:40:32.001  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 06:40:32.001  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:40:32.001  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:40:32.001  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e20408 added. We now have 2 listener(s)
10-07 06:40:32.001  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:40:32.001  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:40:32.003  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:32.006  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:40:32.006  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:32.007  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 06:40:32.007  5701  5747 D executeNativeTests: Running unit tests
,10-07 06:40:32.012  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:32.020  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:32.043  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 06:40:32.043  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 added. We now have 3 listener(s)
,10-07 06:40:32.043  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:40:32.044  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 06:40:32.044  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:40:32.044  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:40:32.044  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 added. We now have 3 listener(s)
10-07 06:40:32.044  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:40:32.044  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:40:32.046  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:32.048  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:40:32.049  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:32.049  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 06:40:32.050  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-07 06:40:32.050  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:32.050  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:32.050  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:32.051  5701  5747 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-07 06:40:32.051  5701  5747 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-07 06:40:32.051  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 06:40:32.051  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:32.051  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:32.051  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:32.051  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:32.051  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:40:32.051  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:32.052  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:32.052  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.052  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:40:32.052  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:32.052  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:40:32.053  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 removed from the list
10-07 06:40:32.053  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:32.053  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 removed from the list
10-07 06:40:32.056  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:32.064  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:32.065  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:32.065  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.065  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.065  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.066  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:32.066  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:32.066  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:32.066  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:32.067  5701  5747 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-07 06:40:32.067  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:32.067  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:32.067  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:32.067  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:32.067  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.067  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:32.067  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:32.067  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:32.067  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:32.067  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:32.067  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:32.067  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.067  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.067  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.068  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.068  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 06:40:32.068  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:32.068  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:32.068  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:32.070  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-07 06:40:32.071  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-07 06:40:32.072  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:32.072  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:32.072  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:32.072  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:32.072  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.072  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.072  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:32.072  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:32.072  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:32.072  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:32.072  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:32.072  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.072  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.072  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:32.072  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:32.073  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:32.073  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:32.073  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:32.073  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:32.073  5701  5747 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-07 06:40:32.074  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:32.076  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:40:32.077  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:32.077  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:40:32.077  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:40:32.077  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 06:40:32.077  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 06:40:32.077  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:32.077  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 06:40:32.079  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:40:32.080  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 06:40:32.080  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 06:40:32.082  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:40:32.084  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 06:40:32.086  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 06:40:32.086  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 06:40:32.087  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-07 06:40:32.089  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-07 06:40:32.089  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 06:40:32.089  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 06:40:32.089  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 06:40:32.089  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 06:40:32.089  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 06:40:32.090  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:40:32.092  4628  4645 D BtGatt.GattService: registerClient() - UUID=3af1d09c-0805-4540-93d6-3ac7e463b1e0
10-07 06:40:32.093  4628  4715 D BtGatt.GattService: onClientRegistered() - UUID=3af1d09c-0805-4540-93d6-3ac7e463b1e0, clientIf=5
10-07 06:40:32.093  5701  5712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 06:40:32.094  4628  4859 D BtGatt.GattService: start scan with filters
10-07 06:40:32.100  4628  4718 D BtGatt.ScanManager: handling starting scan
10-07 06:40:32.100  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 06:40:32.100  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 06:40:32.100  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:40:32.100  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 06:40:32.100  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 06:40:32.100  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 06:40:32.100  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 06:40:32.101  4628  4718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:40:32.101  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:40:32.101  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 06:40:32.102  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:40:32.102  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 06:40:32.103  5701  5747 I io.jxcore.node.ConnectionHelper: start: OK
10-07 06:40:32.109  4628  4715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 06:40:32.109  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:32.110  4628  4718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 06:40:32.116  4628  4715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 06:40:32.116  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:32.116  4628  4718 D BtGatt.ScanManager: Starting BLE batch scan
10-07 06:40:32.116  4628  4718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 06:40:32.126  4628  4715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 06:40:32.126  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:32.133  4628  4715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 06:40:32.133  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:40:32.604  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-07 06:40:32.604  5701  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 06:40:32.604  5701  5701 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 06:40:32.869   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:33.870   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-07 06:40:34.563   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 06:40:34.569   930  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-07 06:40:37.107  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:37.107  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:40:37.108  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 06:40:37.108  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:40:37.108  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 06:40:37.108  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:37.108  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 06:40:37.108  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 06:40:37.108  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 06:40:37.108  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-07 06:40:37.109  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 06:40:37.109  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 06:40:37.110  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:40:37.111  4628  4645 D BtGatt.GattService: stopScan() - queue size =1
10-07 06:40:37.113  4628  4859 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 06:40:37.114  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 06:40:37.114  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 06:40:37.115  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 06:40:37.115  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-07 06:40:37.115  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 06:40:37.115  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 06:40:37.115  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 06:40:37.115  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-07 06:40:37.118  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:37.119  4628  4628 D BtGatt.ScanManager: awakened up at time 237158
10-07 06:40:37.119  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 06:40:37.119  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 06:40:37.119  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-07 06:40:37.120  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 06:40:37.123  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:40:37.125  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:37.125  4628  4715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 06:40:37.126  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:40:37.126  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:37.126  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:40:37.126  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:37.126  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:37.126  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
,10-07 06:40:37.126  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:37.126  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:37.127  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:37.127  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:37.127  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:37.127  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:37.127  4628  4718 D BtGatt.ScanManager: stopping BLe Batch
,10-07 06:40:37.137  4628  4715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 06:40:37.138  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:37.138  4628  4718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 06:40:37.163  4628  4715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-07 06:40:37.163  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:37.163  4628  4715 D BtGatt.GattService: current time is 237203645575
10-07 06:40:37.164  4628  4715 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -79, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -82, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -99, 75, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-07 06:40:37.166  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-07 06:40:37.169  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-07 06:40:37.169  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-07 06:40:37.169  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-07 06:40:37.170  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-07 06:40:37.170  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
10-07 06:40:37.171  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-07 06:40:37.591   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 06:40:37.595   930  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-07 06:40:37.628  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 06:40:38.871   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:39.873   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:40.874   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:41.876   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:42.129  5701  5747 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-07 06:40:42.134  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:42.144  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 06:40:42.149  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 06:40:42.149  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:40:42.149  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:40:42.150  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 06:40:42.150  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 06:40:42.150  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:40:42.150  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 06:40:42.155  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:42.157  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 06:40:42.157  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 06:40:42.158  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:42.161  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 06:40:42.162  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 06:40:42.162  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 06:40:42.166  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 06:40:42.166  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 06:40:42.166  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 06:40:42.166  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 06:40:42.166  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 06:40:42.167  5701  5747 D BluetoothAdapter: STATE_ON
,10-07 06:40:42.170  4628  4645 D BtGatt.GattService: registerClient() - UUID=eaae4ae1-f1a0-4cd6-88cc-59bb01663124
,10-07 06:40:42.171  4628  4715 D BtGatt.GattService: onClientRegistered() - UUID=eaae4ae1-f1a0-4cd6-88cc-59bb01663124, clientIf=5
10-07 06:40:42.172  5701  5712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 06:40:42.173  4628  4859 D BtGatt.GattService: start scan with filters
,10-07 06:40:42.176  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 06:40:42.176  4628  4718 D BtGatt.ScanManager: handling starting scan
10-07 06:40:42.176  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-07 06:40:42.176  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:40:42.176  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 06:40:42.176  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 06:40:42.176  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 06:40:42.176  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 06:40:42.178  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:40:42.179  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 06:40:42.179  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:40:42.180  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 06:40:42.182  5701  5747 I io.jxcore.node.ConnectionHelper: start: OK
,10-07 06:40:42.182  4628  4715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 06:40:42.182  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.182  4628  4718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-07 06:40:42.184  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:42.184  5701  5747 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-07 06:40:42.184  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:42.185  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 06:40:42.185  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:42.185  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 06:40:42.185  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:42.185  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 06:40:42.185  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 06:40:42.185  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 06:40:42.185  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 06:40:42.185  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-07 06:40:42.185  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 06:40:42.186  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:40:42.186  4628  4859 D BtGatt.GattService: stopScan() - queue size =1
10-07 06:40:42.187  4628  4644 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 06:40:42.187  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 06:40:42.187  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 06:40:42.187  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 06:40:42.187  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:40:42.187  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 06:40:42.187  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 06:40:42.188  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 06:40:42.188  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 06:40:42.188  4628  4715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 06:40:42.188  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:40:42.188  4628  4718 D BtGatt.ScanManager: Starting BLE batch scan
10-07 06:40:42.188  4628  4718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 06:40:42.188  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:42.189  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 06:40:42.189  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 06:40:42.189  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 06:40:42.189  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 06:40:42.189  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:40:42.190  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:42.190  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:42.190  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:42.190  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:42.190  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:40:42.190  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:42.190  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:42.190  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:42.191  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:42.191  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:42.191  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:42.191  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:42.192  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:42.192  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:42.193  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:42.193  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:42.193  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:42.193  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:42.194  5701  5747 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-07 06:40:42.196  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:42.198  4628  4715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 06:40:42.198  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:40:42.200  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:40:42.202  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:40:42.202  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:40:42.202  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:40:42.202  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 06:40:42.202  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 06:40:42.202  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:42.202  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 06:40:42.203  4628  4715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 06:40:42.203  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.205  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:40:42.205  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 06:40:42.205  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 06:40:42.207  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:40:42.209  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 06:40:42.210  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 06:40:42.210  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 06:40:42.211  4628  4715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 06:40:42.211  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.211  4628  4718 D BtGatt.ScanManager: stopping BLe Batch
,10-07 06:40:42.214  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 06:40:42.214  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 06:40:42.214  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-07 06:40:42.214  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 06:40:42.214  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 06:40:42.215  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:40:42.216  4628  4715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 06:40:42.217  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.217  4628  4644 D BtGatt.GattService: registerClient() - UUID=6f6a4639-9e95-4815-93e6-52cb2c5eeca7
10-07 06:40:42.217  4628  4718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 06:40:42.217  4628  4715 D BtGatt.GattService: onClientRegistered() - UUID=6f6a4639-9e95-4815-93e6-52cb2c5eeca7, clientIf=5
,10-07 06:40:42.217  5701  5711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 06:40:42.217  4628  4645 D BtGatt.GattService: start scan with filters
,10-07 06:40:42.222  4628  4715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 06:40:42.222  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.223  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 06:40:42.223  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 06:40:42.223  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:40:42.223  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 06:40:42.223  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 06:40:42.223  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 06:40:42.223  4628  4718 D BtGatt.ScanManager: handling starting scan
10-07 06:40:42.223  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 06:40:42.225  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:40:42.226  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 06:40:42.226  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 06:40:42.227  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 06:40:42.229  4628  4715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 06:40:42.229  5701  5747 I io.jxcore.node.ConnectionHelper: start: OK
10-07 06:40:42.229  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.229  4628  4718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 06:40:42.234  4628  4715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-07 06:40:42.234  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:42.235  4628  4718 D BtGatt.ScanManager: Starting BLE batch scan
10-07 06:40:42.235  4628  4718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-07 06:40:42.243  4628  4715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 06:40:42.243  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:40:42.248  4628  4715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 06:40:42.248  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:40:42.727  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-07 06:40:42.727  5701  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 06:40:42.728  5701  5701 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 06:40:42.878   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:43.639   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 06:40:43.644   930  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-07 06:40:43.879   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-07 06:40:46.666   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 06:40:46.672   930  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-07 06:40:47.229  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:47.230  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:40:47.230  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 06:40:47.230  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:47.230  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 06:40:47.230  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 06:40:47.231  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 06:40:47.231  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 06:40:47.231  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-07 06:40:47.231  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 06:40:47.231  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-07 06:40:47.231  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 06:40:47.235  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:40:47.237  4628  4881 D BtGatt.GattService: stopScan() - queue size =1
,10-07 06:40:47.239  4628  4859 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 06:40:47.240  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 06:40:47.240  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-07 06:40:47.240  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 06:40:47.241  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:40:47.241  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 06:40:47.241  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 06:40:47.241  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 06:40:47.241  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 06:40:47.244  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:47.244  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 06:40:47.244  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 06:40:47.244  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-07 06:40:47.244  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 06:40:47.246  4628  4628 D BtGatt.ScanManager: awakened up at time 247285
10-07 06:40:47.246  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:40:47.249  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:47.249  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:47.249  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:47.252  4628  4715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 06:40:47.252  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:47.253  4628  4718 D BtGatt.ScanManager: stopping BLe Batch
,10-07 06:40:47.262  4628  4715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 06:40:47.263  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:47.263  4628  4718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 06:40:47.285  4628  4715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-07 06:40:47.285  4628  4715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:40:47.285  4628  4715 D BtGatt.GattService: current time is 247325156453
10-07 06:40:47.285  4628  4715 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -80, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -79, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -95, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-07 06:40:47.286  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-07 06:40:47.286  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-07 06:40:47.286  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-07 06:40:47.286  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-07 06:40:47.286  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-07 06:40:47.287  4628  4715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-07 06:40:47.750  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 06:40:47.751  5701  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:47.751  5701  5701 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 06:40:52.251  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:52.251  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.251  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.251  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.251  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.252  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-07 06:40:52.252  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.252  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.252  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.252  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.252  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.253  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:52.254  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.254  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.257  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.257  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.258  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.258  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.259  5701  5747 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-07 06:40:52.261  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.261  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:40:52.261  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.262  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.262  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.262  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:52.262  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.262  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.262  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.263  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.263  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.263  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.263  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.263  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.263  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:52.266  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.266  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.266  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.266  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.269  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-07 06:40:52.269  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:52.269  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.269  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.269  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.269  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.269  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.270  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 06:40:52.270  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.270  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.271  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.271  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.271  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.271  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:52.271  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.271  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.273  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.273  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.273  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.273  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.274  5701  5747 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-07 06:40:52.275  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.275  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.275  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 06:40:52.275  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.275  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.275  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.275  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.275  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.276  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.276  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.276  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.276  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.276  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.276  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.276  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:52.278  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.278  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 06:40:52.278  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.278  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.279  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-07 06:40:52.280  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.280  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.280  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 06:40:52.280  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.280  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.280  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.280  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.281  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.281  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.281  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.281  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.281  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.281  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.281  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.281  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.283  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.283  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.283  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.283  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.284  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-07 06:40:52.285  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:52.285  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:52.285  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 06:40:52.285  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:52.285  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:52.285  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-07 06:40:52.285  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:52.286  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 06:40:52.286  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.286  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.286  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.286  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.286  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.286  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.286  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.287  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
,10-07 06:40:52.287  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.287  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.287  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.287  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.287  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.287  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.287  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.289  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.289  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.289  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.289  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.291  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-07 06:40:52.291  5701  5747 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-07 06:40:52.291  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-07 06:40:52.297  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-07 06:40:52.297  5701  5747 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-07 06:40:52.297  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-07 06:40:52.298  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-07 06:40:52.299  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-07 06:40:52.299  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-07 06:40:52.299  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-07 06:40:52.299  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-07 06:40:52.299  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-07 06:40:52.299  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-07 06:40:52.299  5701  5747 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 06:40:52.299  5701  5747 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,10-07 06:40:52.300  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 06:40:52.300  5701  5747 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 06:40:52.300  5701  5747 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-07 06:40:52.300  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 06:40:52.300  5701  5747 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 06:40:52.300  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-07 06:40:52.305  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-07 06:40:52.306  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-07 06:40:52.306  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-07 06:40:52.306  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-07 06:40:52.307  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-07 06:40:52.307  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,10-07 06:40:52.307  5701  5747 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 06:40:52.307  5701  5747 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-07 06:40:52.308  5701  5748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-07 06:40:52.308  5701  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-07 06:40:52.308  5701  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-07 06:40:52.308  5701  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-07 06:40:52.308  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:52.308  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.308  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.308  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.308  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:40:52.309  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.309  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.309  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-07 06:40:52.310  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.310  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:40:52.310  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.310  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.310  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.310  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.310  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.310  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.310  5701  5749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-07 06:40:52.312  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 06:40:52.312  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.312  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.312  5701  5748 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-07 06:40:52.312  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.312  5701  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 06:40:52.313  5701  5747 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-07 06:40:52.312  4859  4859 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30419]" dev="sockfs" ino=30419 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 06:40:52.312  4859  4859 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30419]" dev="sockfs" ino=30419 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:52.317  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.317  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.317  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.317  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.317  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.317  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.317  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.317  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.317  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.317  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.317  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.317  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.317  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.317  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.318  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.319  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.319  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.319  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.319  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.320  5701  5747 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-07 06:40:52.320  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.321  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:40:52.321  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.321  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.321  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.321  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.321  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.321  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.321  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.321  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.321  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.321  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:40:52.321  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.321  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.321  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.322  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.322  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.322  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.322  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:52.323  5701  5747 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,10-07 06:40:52.323  5701  5747 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-07 06:40:52.323  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 06:40:52.324  5701  5747 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-07 06:40:52.324  5701  5747 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-07 06:40:52.324  5701  5747 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-07 06:40:52.324  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 06:40:52.324  5701  5747 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-07 06:40:52.324  5701  5747 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-07 06:40:52.324  5701  5747 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-07 06:40:52.324  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 06:40:52.324  5701  5747 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-07 06:40:52.324  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:52.324  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:52.324  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:52.324  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.324  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.324  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.325  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.325  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:52.325  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.325  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.325  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 06:40:52.325  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.325  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.325  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.325  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.327  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:52.327  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:52.327  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.327  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.328  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:52.328  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.328  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:52.328  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:52.328  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
,10-07 06:40:52.328  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:52.328  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:52.328  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:52.328  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:52.328  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:53.880   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:54.881   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:55.882   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:56.883   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:57.329  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:40:57.329  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.329  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 06:40:57.329  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.330  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.330  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 06:40:57.330  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
,10-07 06:40:57.330  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:57.331  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:40:57.331  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 06:40:57.331  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:57.331  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.331  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.331  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:57.332  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:57.332  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.332  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.332  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:57.332  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:40:57.332  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.332  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.332  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.337  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:57.337  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:57.337  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.337  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:57.342  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-07 06:40:57.349  4881  4881 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30425]" dev="sockfs" ino=30425 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 06:40:57.342  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:40:57.345  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-07 06:40:57.348  5701  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-07 06:40:57.347  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-07 06:40:57.348  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-07 06:40:57.348  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-07 06:40:57.348  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-07 06:40:57.348  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 06:40:57.348  5701  5701 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-07 06:40:57.349  5701  5750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 06:40:57.349  4881  4881 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30425]" dev="sockfs" ino=30425 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-07 06:40:57.349  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:57.349  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-07 06:40:57.349  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-07 06:40:57.349  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-07 06:40:57.349  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.349  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-07 06:40:57.349  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-07 06:40:57.350  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
,10-07 06:40:57.350  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.350  5701  5701 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-07 06:40:57.350  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 06:40:57.350  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 06:40:57.350  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 06:40:57.350  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.350  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.351  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:40:57.351  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.351  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:57.351  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:57.351  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:40:57.351  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 06:40:57.351  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:57.352  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:57.352  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:57.352  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.352  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.352  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-07 06:40:57.352  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:57.352  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.352  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.352  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:57.352  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.352  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.352  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.352  5701  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-07 06:40:57.352  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.352  5701  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-07 06:40:57.353  5701  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-07 06:40:57.353  5701  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-07 06:40:57.353  5701  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:57.354  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:57.354  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:57.354  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:40:57.354  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.355  5701  5747 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-07 06:40:57.356  5701  5747 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-07 06:40:57.356  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 06:40:57.356  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:57.356  5701  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 06:40:57.356  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:40:57.356  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:57.356  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:57.356  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:57.356  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.357  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.357  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:57.357  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
,10-07 06:40:57.357  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.357  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.357  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:57.358  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.358  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.358  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.358  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:40:57.360  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:57.360  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:57.360  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.361  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.365  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:57.365  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:57.365  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:57.365  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 06:40:57.365  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.366  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.366  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:57.366  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:57.366  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.366  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.366  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 06:40:57.366  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.366  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.366  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.366  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.369  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:57.369  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:57.369  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:40:57.369  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.370  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:40:57.371  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:40:57.371  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:40:57.371  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:40:57.371  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.371  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.371  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:40:57.371  5701  5747 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f9f476 not in the list
10-07 06:40:57.371  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.371  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
,10-07 06:40:57.371  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:40:57.371  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.371  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.371  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:40:57.371  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:40:57.373  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:40:57.373  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:40:57.373  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:40:57.373  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d3a77 not in the list
10-07 06:40:57.374  5701  5747 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-07 06:40:57.374  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 06:40:57.374  5701  5747 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-07 06:40:57.374  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 06:40:57.374  5701  5747 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-07 06:40:57.374  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 06:40:57.376  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-07 06:40:57.376  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-07 06:40:57.377  5701  5747 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-07 06:40:57.378  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-07 06:40:57.378  5701  5747 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-07 06:40:57.378  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-07 06:40:57.378  5701  5747 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-07 06:40:57.378  5701  5747 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-07 06:40:57.379  5701  5747 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-07 06:40:57.379  5701  5747 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-07 06:40:57.380  5701  5747 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-07 06:40:57.380  5701  5747 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-07 06:40:57.380  5701  5747 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-07 06:40:57.380  5701  5747 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-07 06:40:57.381  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 06:40:57.381  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ec43a81 added. We now have 3 listener(s)
10-07 06:40:57.381  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:40:57.383  5701  5747 D BluetoothAdapter: enable(): BT is already enabled..!
10-07 06:40:57.383   930  3607 D WifiService: setWifiEnabled: true pid=5701, uid=10077
10-07 06:40:57.383   930  3607 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 06:40:57.443  4628  4831 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-07 06:40:57.444  4628  4852 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
10-07 06:40:57.444  5701  5748 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-07 06:40:57.444  5701  5748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-07 06:40:57.444  5701  5748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,10-07 06:40:57.853  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 06:40:57.884   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:40:58.885   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-07 06:41:00.771   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 06:41:02.388  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:02.389  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4266726 added. We now have 4 listener(s)
,10-07 06:41:02.389  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:41:02.402  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:41:02.402  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4266726 removed from the list
10-07 06:41:02.403  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 06:41:02.403  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:02.403  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:02.405  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:02.405  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52baf67 added. We now have 4 listener(s)
,10-07 06:41:02.405  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:41:02.409  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:02.410  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52baf67 removed from the list
,10-07 06:41:02.410  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:02.411  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:02.411  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:02.413  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:02.413  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b54114 added. We now have 4 listener(s)
10-07 06:41:02.413  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:02.418   930  3201 D WifiService: setWifiEnabled: false pid=5701, uid=10077
10-07 06:41:02.418   930  3201 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-07 06:41:02.422   930  3017 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-07 06:41:02.423   930  3017 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-07 06:41:02.423   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 06:41:02.423   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:02.432  4628  4710 D BluetoothAdapterState: Current state: ON, message: 23
10-07 06:41:02.432  4628  4710 D BluetoothAdapterProperties: Setting state to 13
10-07 06:41:02.432  4628  4710 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-07 06:41:02.433  4628  4710 D BluetoothAdapterProperties: onBluetoothDisable()
10-07 06:41:02.434  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:41:02.435  4628  4710 I BluetoothAdapterState: Entering PendingCommandState
10-07 06:41:02.442  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:02.442  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:02.445   930  5433 D DhcpClient: Clearing IP address
10-07 06:41:02.445  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.446  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:02.446  4628  4628 D BluetoothMapService: onReceive
10-07 06:41:02.446  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:41:02.446  4628  4628 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 06:41:02.446  4628  4628 D BluetoothMapService: STATE_TURNING_OFF
,10-07 06:41:02.447  4628  4628 D BluetoothMapService: MAP Service closeService in
10-07 06:41:02.447  4628  4628 D BluetoothMapMasInstance0: MAP Service shutdown
10-07 06:41:02.447  4628  4628 D ObexServerSockets0: shutdown(block = true)
10-07 06:41:02.447   508   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 06:41:02.447  4628  4628 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 06:41:02.447  4628  4628 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 06:41:02.448  4628  4852 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-07 06:41:02.448  4628  4884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-07 06:41:02.448  4628  4885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-07 06:41:02.450  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.453  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.454  4628  4628 I BtOppRfcommListener: stopping Accept Thread
10-07 06:41:02.454  4628  5378 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-07 06:41:02.457  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:02.457  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:02.458   508   921 D CommandListener: Setting iface cfg
10-07 06:41:02.458  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.458  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:02.460  4628  5378 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-07 06:41:02.460  3629  5489 V NativeCrypto: Read error: ssl=0x7f927cb880: I/O error during system call, Connection timed out
10-07 06:41:02.463  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:02.463  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:02.463  3629  5489 V NativeCrypto: SSL shutdown failed: ssl=0x7f927cb880: I/O error during system call, Broken pipe
10-07 06:41:02.464  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:02.464  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:02.466   930  3916 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-07 06:41:02.467   930  5431 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-07 06:41:02.467  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.470   930  5431 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-07 06:41:02.470   930   943 I ActivityManager: Start proc 5754:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-07 06:41:02.471  4628  4715 D BluetoothAdapterProperties: Scan Mode:20
10-07 06:41:02.471   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-07 06:41:02.471  4628  4710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-07 06:41:02.472   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-07 06:41:02.473   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-07 06:41:02.473   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-07 06:41:02.473   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-07 06:41:02.479   930   930 D RttService: SCAN_AVAILABLE : 1
10-07 06:41:02.480   930  3129 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-07 06:41:02.480   543   543 E Parcel  : Reading a NULL string not supported here.
10-07 06:41:02.481  4628  4628 D HeadsetService: Received stop request...Stopping profile...
10-07 06:41:02.482  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.483  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:02.484  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.484   930  3019 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-07 06:41:02.484  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:02.484   930  5434 D DhcpClient: Receive thread stopped
,10-07 06:41:02.486  3820  3961 W QCNEJ   : |CORE| network lost: 100
10-07 06:41:02.487   930   930 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:02.487  3820  3961 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-07 06:41:02.488  3855  4046 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:02.490  4628  4628 D A2dpService: Received stop request...Stopping profile...
10-07 06:41:02.490  3174  3188 D BluetoothHeadset: Proxy object disconnected
10-07 06:41:02.490  4628  4867 D A2dpStateMachine: Exit Disconnected: -1
10-07 06:41:02.490   930   930 D BluetoothHeadset: Proxy object disconnected
10-07 06:41:02.490   930   930 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:02.491  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.491  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:02.492   930   930 D BluetoothA2dp: Proxy object disconnected
10-07 06:41:02.492  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.492  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:02.495  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.497  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:02.499  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.499  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:02.499  4628  4628 D HidService: Received stop request...Stopping profile...
10-07 06:41:02.499  4628  4628 D HidService: Stopping Bluetooth HidService
,10-07 06:41:02.503  4628  4628 D HealthService: Received stop request...Stopping profile...
10-07 06:41:02.504  3174  3174 D HeadsetProfile: Bluetooth service disconnected
,10-07 06:41:02.504  3174  3174 D BluetoothA2dp: Proxy object disconnected
10-07 06:41:02.505  3174  3174 D BluetoothInputDevice: Proxy object disconnected
10-07 06:41:02.505  3174  3174 D HidProfile: Bluetooth service disconnected
,10-07 06:41:02.506  4628  4628 D PanService: Received stop request...Stopping profile...
,10-07 06:41:02.507  4628  4628 D BluetoothMapService: Received stop request...Stopping profile...
10-07 06:41:02.507  4628  4628 D BluetoothMapService: stop()
10-07 06:41:02.508  4628  4628 D BluetoothMapAppObserver: deinitObservers()
10-07 06:41:02.508  4628  4628 D BluetoothMapAppObserver: removeReceiver()
10-07 06:41:02.509   930  3017 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-07 06:41:02.514  4628  4628 D SapService: Received stop request...Stopping profile...
,10-07 06:41:02.514  4628  4628 V SapService: stop()
10-07 06:41:02.514  3174  3174 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-07 06:41:02.515  3174  3174 D PanProfile: Bluetooth service disconnected
,10-07 06:41:02.515  3174  3174 D BluetoothMap: Proxy object disconnected
10-07 06:41:02.515  3174  3174 D MapProfile: Bluetooth service disconnected
,10-07 06:41:02.515  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.515  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.515  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:02.515  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.518  4628  4628 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-07 06:41:02.518  4628  4628 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-07 06:41:02.518  4628  4715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-07 06:41:02.519  4628  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:02.519  4628  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:02.519  4628  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:02.519  4628  4715 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-07 06:41:02.519  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.519  4628  4628 V BluetoothAdapterState: isTurningOn()=false
,10-07 06:41:02.519  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 06:41:02.519  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.521  4628  4715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-07 06:41:02.521  4628  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.521  4628  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:02.521  4628  4831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.521  4628  4831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 06:41:02.521  4628  4831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 06:41:02.521  4628  4831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 06:41:02.521  4628  4628 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-07 06:41:02.521  4628  4628 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-07 06:41:02.521  4628  4715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.521  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:02.522  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.522  4628  4628 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-07 06:41:02.522  4628  4628 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-07 06:41:02.522  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.522  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.522  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:02.522  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.523  4628  4628 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-07 06:41:02.523  4628  4628 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-07 06:41:02.523  4628  4715 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-07 06:41:02.523  4628  4628 D BluetoothMapService: MAP Service closeService in
10-07 06:41:02.523  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.523  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.524  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 06:41:02.524  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.524  4628  4628 D BluetoothMapService: cleanup()
10-07 06:41:02.524  4628  4628 D BluetoothMapService: MAP Service closeService in
10-07 06:41:02.524  4628  4628 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:02.524  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.524  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:02.524  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:02.524   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 06:41:02.525  4628  4710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-07 06:41:02.525  4628  4710 D BluetoothAdapterProperties: Setting state to 15
10-07 06:41:02.525  4628  4710 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-07 06:41:02.525   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:02.525   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 06:41:02.526  3174  3404 D BluetoothMap: onBluetoothStateChange: up=false
10-07 06:41:02.526  4628  4710 I BluetoothAdapterState: Entering BleOnState
10-07 06:41:02.526  3174  4010 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:02.527  3174  3188 D BluetoothPan: onBluetoothStateChange on: false
10-07 06:41:02.527  3855  4273 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:02.527   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-07 06:41:02.528   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:02.528  3174  3187 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 06:41:02.529  3174  3187 D BluetoothPbap: onBluetoothStateChange: up=false
,10-07 06:41:02.529   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:02.529  3174  3188 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 06:41:02.530  4628  4710 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-07 06:41:02.530  4628  4710 D BluetoothAdapterProperties: Setting state to 16
10-07 06:41:02.530  4628  4710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-07 06:41:02.531  4628  4710 D BluetoothAdapterProperties: onBleDisable
10-07 06:41:02.531  4628  4710 I BluetoothAdapterState: Entering PendingCommandState
10-07 06:41:02.531  4628  4712 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-07 06:41:02.533  4628  4715 D BluetoothAdapterProperties: Scan Mode:20
10-07 06:41:02.533  4628  4831 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-07 06:41:02.533  4628  4831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:02.534  5754  5754 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-07 06:41:02.535  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:02.538  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:02.539  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:02.540  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.541  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.542  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:02.549   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:02.550   508   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 06:41:02.550   508   921 D TetherController: Setting IP forward enable = 0
10-07 06:41:02.550  5754  5754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 06:41:02.551   930  3019 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-07 06:41:02.551   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-07 06:41:02.554   930  3017 D DhcpClient: doQuit
,10-07 06:41:02.554   930  3017 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-07 06:41:02.555   930  5433 D DhcpClient: onQuitting
10-07 06:41:02.556  3507  3507 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-07 06:41:02.557   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-07 06:41:02.559  5349  5349 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6aacfae and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-07 06:41:02.559  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.559  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:02.561  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.561  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:02.563  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.564  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:02.564  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.564  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:02.566  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:02.566  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:02.566  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:02.567  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:02.570  4986  4986 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-07 06:41:02.573  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 06:41:02.574  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.574  5095  5119 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-07 06:41:02.575  5095  5119 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 06:41:02.575  5095  5119 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-07 06:41:02.575  5095  5119 E SarControlService: no key has been found,reset the power
10-07 06:41:02.575  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 06:41:02.575  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 06:41:02.575  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 06:41:02.575  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:02.576  5120  5120 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 06:41:02.576  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.578  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:02.578  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-07 06:41:02.578  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 06:41:02.578  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 06:41:02.579  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:02.579  5120  5120 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 06:41:02.581  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000ea03000000000000ffffffff]
10-07 06:41:02.581  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:02.581  5120  5134 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,10-07 06:41:02.581  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:02.582  5095  5106 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 06:41:02.584   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b9646db:true
10-07 06:41:02.584  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000eb03000000000000ffffffff]
10-07 06:41:02.584  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:02.585  5120  5134 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-07 06:41:02.585  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:02.585  5095  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-07 06:41:02.586  3507  3507 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-07 06:41:02.588   930  3607 I ActivityManager: Start proc 5782:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-07 06:41:02.591  3507  3507 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-07 06:41:02.604  5754  5754 D LocalBluetoothProfileManager: Adding local MAP profile
,10-07 06:41:02.607  5754  5754 D BluetoothMap: Create BluetoothMap proxy object
10-07 06:41:02.608  3507  3507 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-07 06:41:02.616  5754  5754 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-07 06:41:02.621   508   921 E Netd    : netlink response contains error (No such file or directory)
,10-07 06:41:02.624   508   921 D TetherController: Setting IP forward enable = 0
,10-07 06:41:02.625   930  3019 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-07 06:41:02.625   930  3019 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-07 06:41:02.630  3507  3507 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-07 06:41:02.632  5754  5754 D DockEventReceiver: finishStartingService: stopping service
,10-07 06:41:02.637  5782  5782 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-07 06:41:02.640   930  3237 I ActivityManager: Killing 5026:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-07 06:41:02.735   930  3017 D wifi    : In wifi stop Hal
10-07 06:41:02.735   930  3017 D wifi    : halHandle = 0x7f91062e00, mVM = 0x7fad68d140, mCls = 0x100a02
10-07 06:41:02.735   930  3506 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-07 06:41:02.735   930  3506 D WifiHAL : Got a signal to exit!!!
10-07 06:41:02.736   930  3506 I WifiHAL : Exit wifi_event_loop
,10-07 06:41:02.736   930  3017 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-07 06:41:02.736   930  3017 E WifiHAL : Event processing terminated
10-07 06:41:02.736   930  3017 D wifi    : In wifi cleaned up handler
10-07 06:41:02.736   930  3017 I WifiHAL : Internal cleanup completed
10-07 06:41:02.737  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 06:41:02.739  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.741  4126  4266 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 06:41:02.741  4628  4715 I bt_hci  : shut_down
10-07 06:41:02.742  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:02.744  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:02.744  4628  4719 D bt_hwcfg: hw_epilog_process
,10-07 06:41:02.748  4628  4719 I bt_vendor: low_power_mode_cb
,10-07 06:41:02.751  4628  4719 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-07 06:41:02.751  4628  4719 I bt_vendor: epilog_cb
10-07 06:41:02.751  4628  4719 I bt_hci  : epilog_finished_callback
,10-07 06:41:02.754  4628  4715 I bt_hci_h4: hal_close
,10-07 06:41:02.754  4628  4715 I bt_userial_vendor: device fd = 54 close
,10-07 06:41:02.762   930  3506 D wifi    : set interface wlan0 flags (DOWN)
,10-07 06:41:02.763   930  3017 D WifiNative-HAL: HAL event thread stopped successfully
,10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:170)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.k.d(PG:583)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:170)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.840  5782  5782 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:41:02.840  5782  5782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:41:02.860  4628  4712 D bt_stack_manager: event_shut_down_stack finished.
10-07 06:41:02.861  4628  4710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-07 06:41:02.862  4628  4710 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-07 06:41:02.863  4628  4628 D BtGatt.DebugUtils: handleDebugAction() action=null
10-07 06:41:02.863  4628  4628 D BtGatt.GattService: Received stop request...Stopping profile...
10-07 06:41:02.863  4628  4628 D BtGatt.GattService: stop()
10-07 06:41:02.863  4628  4628 D BtGatt.AdvertiseManager: advertise clients cleared
10-07 06:41:02.865  4628  4628 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:02.865  4628  4628 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:02.865  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:02.865  4628  4628 V BluetoothAdapterState: isBleTurningOff()=true
10-07 06:41:02.865  4628  4710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-07 06:41:02.865  4628  4710 D BluetoothAdapterProperties: Setting state to 10
10-07 06:41:02.865  4628  4710 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-07 06:41:02.866  4628  4710 I BluetoothAdapterState: Entering OffState
10-07 06:41:02.866   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-07 06:41:02.873  4628  4628 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-07 06:41:02.873  4628  4628 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-07 06:41:02.873  4628  4628 I BluetoothServiceJni: cleanupNative: return from cleanup
10-07 06:41:02.874  4628  4712 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-07 06:41:02.877  4628  4628 I art     : System.exit called, status: 0
10-07 06:41:02.878  4628  4628 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-07 06:41:02.889  5754  5754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 06:41:02.903  5754  5754 D DockEventReceiver: finishStartingService: stopping service
10-07 06:41:02.904   930  3646 I ActivityManager: Killing 5183:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-07 06:41:02.937   930  3891 I ActivityManager: Process com.android.bluetooth (pid 4628) has died
,10-07 06:41:02.940  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 06:41:02.952   930  3916 I ActivityManager: Start proc 5819:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-07 06:41:02.965   930   947 D Tethering: InitialState.processMessage what=4
,10-07 06:41:02.969   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-07 06:41:03.013  5819  5819 D AdapterServiceConfig: Adding HeadsetService
,10-07 06:41:03.013  5819  5819 D AdapterServiceConfig: Adding A2dpService
10-07 06:41:03.014  5819  5819 D AdapterServiceConfig: Adding HidService
10-07 06:41:03.014  5819  5819 D AdapterServiceConfig: Adding HealthService
10-07 06:41:03.014  5819  5819 D AdapterServiceConfig: Adding PanService
10-07 06:41:03.014  5819  5819 D AdapterServiceConfig: Adding GattService
10-07 06:41:03.014  5819  5819 D AdapterServiceConfig: Adding BluetoothMapService
10-07 06:41:03.014  5819  5819 D AdapterServiceConfig: Adding SapService
,10-07 06:41:03.018   930  3645 I ActivityManager: Killing 5509:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-07 06:41:03.037  3795  3795 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-07 06:41:03.039  3795  3795 D SystemUpdateService: onCreate
,10-07 06:41:03.042  3795  3795 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-07 06:41:03.045  3795  5831 I SystemUpdateService: active receiver: enabled
,10-07 06:41:03.048  3795  3795 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-07 06:41:03.052  3795  5458 I iu.UploadsManager: num queued entries: 0
10-07 06:41:03.052  3795  5458 I iu.UploadsManager: num updated entries: 0
10-07 06:41:03.053  3795  5458 I iu.SyncManager: NEXT; no task
,10-07 06:41:03.055  3795  3795 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 06:41:03.056  3795  3795 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 06:41:03.064  3795  5831 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 06:41:03.068  3795  5831 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-07 06:41:03.068  3795  5831 I SystemUpdateService: now status is 0 (complete)
10-07 06:41:03.068  3795  5831 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 06:41:03.068  3795  5831 I SystemUpdateService: file has been verified
,10-07 06:41:03.068  3795  5831 I SystemUpdateService: OTA package size = 21989297
,10-07 06:41:03.071   930   940 I ActivityManager: Start proc 5833:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-07 06:41:03.087  3795  5831 I SystemUpdateService: showing system update notification
,10-07 06:41:03.104  5833  5833 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-07 06:41:03.107  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 06:41:03.113  5833  5833 D SprintDMHelper: simOperator: 
,10-07 06:41:03.113  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 06:41:03.125   930   940 I ActivityManager: Start proc 5845:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-07 06:41:03.138  3795  3795 D SystemUpdateService: onDestroy
,10-07 06:41:03.152   930  3607 I ActivityManager: Killing 5493:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-07 06:41:03.226  5069  5859 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-07 06:41:03.235   930  3201 I ActivityManager: Start proc 5860:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-07 06:41:03.237   930   940 I ActivityManager: Killing 5349:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-07 06:41:03.304  5860  5860 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-07 06:41:03.417  5782  5813 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-07 06:41:03.488   930  3916 I ActivityManager: Killing 4725:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-07 06:41:03.504   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b6df31:true
,10-07 06:41:03.530   930   941 I ActivityManager: Start proc 5874:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-07 06:41:03.564  5874  5874 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-07 06:41:03.571   930  3891 I ActivityManager: Killing 5565:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-07 06:41:07.449   930  3914 D WifiService: setWifiEnabled: true pid=5701, uid=10077
10-07 06:41:07.449   930  3914 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 06:41:07.461   508   921 D SoftapController: Softap fwReload - Ok
,10-07 06:41:07.465   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:07.466   508   921 D CommandListener: Trying to bring down wlan0
10-07 06:41:07.467   508   921 D CommandListener: Clearing all IP addresses on wlan0
,10-07 06:41:07.471   930  3017 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 06:41:08.041   930  3017 D wifi    : set interface wlan0 flags (UP)
,10-07 06:41:08.043   930  3017 I WifiHAL : Initializing wifi
10-07 06:41:08.043   930  3017 I WifiHAL : Creating socket
,10-07 06:41:08.045   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-07 06:41:08.048   930  3017 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-07 06:41:08.049   930  3017 D wifi    : Did set static halHandle = 0x7f91062e00
,10-07 06:41:08.049   930  3017 D wifi    : halHandle = 0x7f91062e00, mVM = 0x7fad68d140, mCls = 0x19ca
10-07 06:41:08.049   930  3017 D wifi    : array field set
10-07 06:41:08.049   930  3017 I WifiNative-HAL: interface[0] = wlan0
10-07 06:41:08.050   930  5892 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547893947904
10-07 06:41:08.050   930  5892 D wifi    : waitForHalEvents called, vm = 0x7fad68d140, obj = 0x19ca, env = 0x7f8e8d0d40
,10-07 06:41:08.122  5893  5893 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-07 06:41:08.134  5893  5893 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 06:41:08.140  5893  5893 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 06:41:08.140  5893  5893 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-07 06:41:08.152   930  3017 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-07 06:41:08.154  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:08.155  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:08.155  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:08.155  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:08.156  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:08.157  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:08.157  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:08.157  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:08.158  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:08.158  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:08.158  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:08.158  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:08.161  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:08.161   930  3017 D WifiConfigStore: Loading config and enabling all networks 
10-07 06:41:08.163  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:08.163  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:08.170   930  3017 D WifiConfigStore: loaded 0 passpoint configs
10-07 06:41:08.171   930  3017 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-07 06:41:08.171   930  3017 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-07 06:41:08.172   930  3017 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-07 06:41:08.172   930  3017 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-07 06:41:08.172   930  3017 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-07 06:41:08.172   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-07 06:41:08.173   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-07 06:41:08.175   930  3017 D WifiNative-HAL: Setting external_sim to 1
,10-07 06:41:08.175   930  3017 D wifi    : setting dfs flag to true, 0x7f948ff100
10-07 06:41:08.175  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 06:41:08.176   930  3017 D WifiStateMachine: Setting OUI to DA-A1-19
10-07 06:41:08.176   930  3017 D wifi    : setting scan oui 0x7f948ff100
10-07 06:41:08.176   930  3017 D WifiHAL : Sending mac address OUI
,10-07 06:41:08.179   930  3017 E native  : do suspend false
,10-07 06:41:08.186   930   930 D RttService: SCAN_AVAILABLE : 3
,10-07 06:41:08.186   930  3017 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-07 06:41:08.187   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-07 06:41:08.187   930  3129 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-07 06:41:08.188   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:08.192   930  3016 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-07 06:41:08.192   930  3016 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-07 06:41:08.201   930  3016 D WifiNative-HAL: p2pGetDeviceAddress
,10-07 06:41:08.205   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268245 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
10-07 06:41:08.205   930  3016 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-07 06:41:11.357  5893  5893 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 06:41:11.362  5893  5893 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 06:41:11.367  5893  5893 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
10-07 06:41:11.372  5893  5893 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 06:41:11.424   930  3017 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-07 06:41:11.424   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-07 06:41:11.424   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:11.432   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-07 06:41:11.465   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-07 06:41:11.467  5893  5893 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-07 06:41:11.954  5893  5893 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-07 06:41:11.989  5893  5893 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-07 06:41:11.989  5893  5893 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-07 06:41:11.999   930  3017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-07 06:41:11.999   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:11.999   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-07 06:41:12.015   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:12.027   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:12.033   930  3017 D WifiStateMachine: Start Dhcp Watchdog 2
,10-07 06:41:12.039   930  5901 D DhcpClient: Receive thread started
,10-07 06:41:12.042   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 06:41:12.042   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-07 06:41:12.042   930  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-07 06:41:12.122   930  3017 E native  : do suspend false
,10-07 06:41:12.136   930  5900 D DhcpClient: Broadcasting DHCPDISCOVER
,10-07 06:41:12.151   930  5901 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,10-07 06:41:12.152   930  5900 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,10-07 06:41:12.153   930  5900 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-07 06:41:12.166   930  5901 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-07 06:41:12.167   930  5900 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-07 06:41:12.169   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:12.174   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-07 06:41:12.180   930  5900 D DhcpClient: Scheduling renewal in 86399s
,10-07 06:41:12.192   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-07 06:41:12.193   930  3017 D WifiConfigStore: No blacklist allowed without epno enabled
,10-07 06:41:12.195   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-07 06:41:12.197   930  3019 D ConnectivityService: Adding iface wlan0 to network 101
,10-07 06:41:12.208   930  3017 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-07 06:41:12.255   930  3019 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-07 06:41:12.255   930  3019 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-07 06:41:12.257   930  3019 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-07 06:41:12.259   930  3019 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-07 06:41:12.261   930  3019 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-07 06:41:12.272   930  3019 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 06:41:12.278   930  3019 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-07 06:41:12.278   930  3019 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-07 06:41:12.278   930  3019 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-07 06:41:12.278   930  3017 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-07 06:41:12.278   930  3019 D ConnectivityService:    accepting network in place of null
10-07 06:41:12.278   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-07 06:41:12.279   930  3019 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 06:41:12.298   930  5899 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272338, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-07 06:41:12.301   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:12.325   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:12.328   930  3019 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-07 06:41:12.328  3820  3961 W QCNEJ   : |CORE| network available: 101
10-07 06:41:12.328   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-07 06:41:12.329   930  3019 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-07 06:41:12.330   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-07 06:41:12.331  3820  3961 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-07 06:41:12.332  3820  3961 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-07 06:41:12.332  3820  3961 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-07 06:41:12.334  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:12.334  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:12.334  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.334  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:12.337  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:12.337  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:12.337  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.337  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:12.340  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:12.340  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 06:41:12.340  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for mu,ltiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.340  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 06:41:12.344  5095  5119 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 06:41:12.344  5095  5119 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 06:41:12.344  5095  5119 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-07 06:41:12.344  5095  5119 E SarControlService: no key has been found,reset the power
10-07 06:41:12.344  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 06:41:12.344  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 06:41:12.344  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 06:41:12.345  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:12.345  5120  5120 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-07 06:41:12.346  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 06:41:12.346  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 06:41:12.346  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 06:41:12.346  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:12.346  5120  5120 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-07 06:41:12.350  4986  4986 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-07 06:41:12.352  3795  3795 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 06:41:12.353  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000ec03000000000000ffffffff]
10-07 06:41:12.353  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:12.353  5120  5134 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-07 06:41:12.355  3795  3795 D SystemUpdateService: onCreate
10-07 06:41:12.356  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:12.356  5095  5106 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 06:41:12.360  3795  3795 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-07 06:41:12.362  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000ed03000000000000ffffffff]
10-07 06:41:12.362  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:12.362  5120  5134 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-07 06:41:12.362  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-07 06:41:12.362  5095  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-07 06:41:12.367   930  5898 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-07 06:41:12.371  3795  3795 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-07 06:41:12.377  3795  5458 I iu.UploadsManager: num queued entries: 0
,10-07 06:41:12.377  3795  5458 I iu.UploadsManager: num updated entries: 0
10-07 06:41:12.378  3795  5458 I iu.SyncManager: NEXT; no task
,10-07 06:41:12.379  3795  5912 I SystemUpdateService: active receiver: enabled
,10-07 06:41:12.380  3795  3795 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 06:41:12.382  3795  3795 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 06:41:12.383  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 06:41:12.387  5833  5833 D SprintDMHelper: simOperator: 
10-07 06:41:12.387  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 06:41:12.408  3795  5912 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 06:41:12.411   930  5898 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 07 Oct 2016 10:41:12 GMT], X-Android-Received-Millis=[1475836872411], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475836872390]}
,10-07 06:41:12.412   930  3019 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-07 06:41:12.412   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-07 06:41:12.412   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-07 06:41:12.413   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-07 06:41:12.425  3795  5912 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-07 06:41:12.425  3795  5912 I SystemUpdateService: now status is 0 (complete)
10-07 06:41:12.425  3795  5912 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 06:41:12.425  3795  5912 I SystemUpdateService: file has been verified
10-07 06:41:12.425  3795  5912 I SystemUpdateService: OTA package size = 21989297
,10-07 06:41:12.432  3795  5912 I SystemUpdateService: showing system update notification
,10-07 06:41:12.442  3795  3795 D SystemUpdateService: onDestroy
,10-07 06:41:12.459   930  3645 D WifiService: setWifiEnabled: false pid=5701, uid=10077
10-07 06:41:12.460   930  3645 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 06:41:12.461   930  3017 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-07 06:41:12.461   930  3017 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-07 06:41:12.461   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 06:41:12.461   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:12.469   930  5900 D DhcpClient: Clearing IP address
,10-07 06:41:12.469   508   921 D CommandListener: Clearing all IP addresses on wlan0
,10-07 06:41:12.472   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:12.473   930  5901 D DhcpClient: Receive thread stopped
,10-07 06:41:12.475   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-07 06:41:12.475   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-07 06:41:12.477   543   543 E Parcel  : Reading a NULL string not supported here.
,10-07 06:41:12.479   930   930 D RttService: SCAN_AVAILABLE : 1
10-07 06:41:12.479   930  3019 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-07 06:41:12.479   930  3129 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-07 06:41:12.481  3820  3961 W QCNEJ   : |CORE| network lost: 101
,10-07 06:41:12.482  3820  3961 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-07 06:41:12.485  3629  5913 V NativeCrypto: SSL handshake aborted: ssl=0x7fa380e400: I/O error during system call, Connection timed out
,10-07 06:41:12.491  5069  5916 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-07 06:41:12.493   930  3017 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-07 06:41:12.497   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-07 06:41:12.507   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
10-07 06:41:12.508  ,5069  5916 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
10-07 06:41:12.508  5069  5916 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-07 06:41:12.508  5069  5916 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-07 06:41:12.527   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:12.527   508   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 06:41:12.528   930  3019 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-07 06:41:12.528   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-07 06:41:12.530   930   947 D Tethering: MasterInitialState.processMessage what=3
10-07 06:41:12.531   930  3017 D DhcpClient: doQuit
10-07 06:41:12.531   930  3017 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-07 06:41:12.532  5893  5893 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-07 06:41:12.532   930  5900 D DhcpClient: onQuitting
10-07 06:41:12.533  4986  4986 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-07 06:41:12.535  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:12.535  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:12.535  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.535  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:12.536  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:12.537  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:12.537  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.537  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:12.538  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:12.538  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:12.538  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:12.538  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:12.538  5095  5119 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-07 06:41:12.539  5095  5119 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-07 06:41:12.539  5095  5119 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-07 06:41:12.539  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:12.539  3795  3795 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 06:41:12.540  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:12.541  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:12.543  5095  5119 E SarControlService: no key has been found,reset the power
10-07 06:41:12.543  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 06:41:12.543  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 06:41:12.543  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 06:41:12.544  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-07 06:41:12.544  5120  5120 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-07 06:41:12.545  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 06:41:12.545  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 06:41:12.545  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 06:41:12.546  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:12.546  5120  5120 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 06:41:12.547  3795  3795 D SystemUpdateService: onCreate
10-07 06:41:12.551  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000ee03000000000000ffffffff]
10-07 06:41:12.551  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:12.551  5120  5134 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-07 06:41:12.551  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000ef03000000000000ffffffff]
10-07 06:41:12.551  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:12.551  5120  5134 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,10-07 06:41:12.552  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:12.552  5095  5105 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 06:41:12.552  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:12.553  5095  5106 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-07 06:41:12.553  3795  3795 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-07 06:41:12.555  5893  5893 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-07 06:41:12.560  5893  5893 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-07 06:41:12.561  3795  5930 I SystemUpdateService: active receiver: enabled
,10-07 06:41:12.563  3795  3795 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-07 06:41:12.568  3795  5458 I iu.UploadsManager: num queued entries: 0
,10-07 06:41:12.569  3795  5458 I iu.UploadsManager: num updated entries: 0
10-07 06:41:12.569  3795  5458 I iu.SyncManager: NEXT; no task
,10-07 06:41:12.571  3795  3795 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 06:41:12.573  3795  3795 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 06:41:12.575  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 06:41:12.578  5833  5833 D SprintDMHelper: simOperator: 
10-07 06:41:12.578  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 06:41:12.581   508   921 E Netd    : netlink response contains error (No such file or directory)
,10-07 06:41:12.582   930  3019 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-07 06:41:12.586  3795  5930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 06:41:12.590  5069  5934 I Babel   : connection state changed from CONNECTED to DISCONNECTED
10-07 06:41:12.590  5893  5893 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-07 06:41:12.593  3795  5930 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-07 06:41:12.593  3795  5930 I SystemUpdateService: now status is 0 (complete)
10-07 06:41:12.593  3795  5930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 06:41:12.593  3795  5930 I SystemUpdateService: file has been verified
10-07 06:41:12.595  3795  5930 I SystemUpdateService: OTA package size = 21989297
,10-07 06:41:12.608  5893  5893 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-07 06:41:12.612  3795  5930 I SystemUpdateService: showing system update notification
,10-07 06:41:12.620  3795  3795 D SystemUpdateService: onDestroy
,10-07 06:41:12.711   930  3017 D wifi    : In wifi stop Hal
,10-07 06:41:12.711   930  3017 D wifi    : halHandle = 0x7f91062e00, mVM = 0x7fad68d140, mCls = 0x19ca
,10-07 06:41:12.712   930  5892 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-07 06:41:12.712   930  5892 D WifiHAL : Got a signal to exit!!!
,10-07 06:41:12.712   930  5892 I WifiHAL : Exit wifi_event_loop
,10-07 06:41:12.713   930  3017 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-07 06:41:12.713   930  3017 E WifiHAL : Event processing terminated
10-07 06:41:12.714   930  3017 D wifi    : In wifi cleaned up handler
,10-07 06:41:12.714   930  3017 I WifiHAL : Internal cleanup completed
,10-07 06:41:12.720  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:12.722  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 06:41:12.723  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:12.725  4126  4266 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 06:41:12.727  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:12.741   930  5892 D wifi    : set interface wlan0 flags (DOWN)
,10-07 06:41:12.741   930  3017 D WifiNative-HAL: HAL event thread stopped successfully
,10-07 06:41:12.949   930   947 D Tethering: InitialState.processMessage what=4
,10-07 06:41:12.956   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-07 06:41:13.329   930  3019 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-07 06:41:13.886   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:14.887   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:15.888   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:16.889   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:17.498   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8386e5:true
,10-07 06:41:17.499  5819  5819 D BluetoothAdapterState: make() - Creating AdapterState
,10-07 06:41:17.506  5819  5819 I bt_bluedroid: init
,10-07 06:41:17.506  5819  5936 I BluetoothAdapterState: Entering OffState
,10-07 06:41:17.511  5819  5937 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-07 06:41:17.511  5819  5937 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,10-07 06:41:17.511  5819  5937 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-07 06:41:17.512  5819  5937 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-07 06:41:17.513  5819  5819 I bt_bluedroid: get_profile_interface socket
,10-07 06:41:17.516  5819  5940 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-07 06:41:17.516  5819  5819 I bt_bluedroid: get_profile_interface sdp
10-07 06:41:17.520  5819  5940 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 06:41:17.526  5819  5830 I bt_bluedroid: config_hci_snoop_log
,10-07 06:41:17.529   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-07 06:41:17.536  5819  5936 D BluetoothAdapterState: Current state: OFF, message: 0
,10-07 06:41:17.536  5819  5936 D BluetoothAdapterProperties: Setting state to 14
,10-07 06:41:17.536  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-07 06:41:17.540  5819  5936 D BluetoothBondStateMachine: make
,10-07 06:41:17.544  5819  5941 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-07 06:41:17.549  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
,10-07 06:41:17.551  5819  5819 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-07 06:41:17.556  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:17.557  5819  5819 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 06:41:17.558  5819  5819 D BtGatt.GattService: Received start request. Starting profile...
10-07 06:41:17.559  5819  5819 D BtGatt.GattService: start()
,10-07 06:41:17.559  5819  5819 I bt_bluedroid: get_profile_interface gatt
,10-07 06:41:17.561  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:17.561  5819  5819 D BtGatt.AdvertiseManager: advertise manager created
,10-07 06:41:17.570  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,10-07 06:41:17.571  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:17.571  5819  5819 V BluetoothAdapterState: isBleTurningOn()=true
10-07 06:41:17.571  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:17.571  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-07 06:41:17.573  5819  5936 I bt_bluedroid: bt_bluedroid
,10-07 06:41:17.573  5819  5937 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-07 06:41:17.574  5819  5937 I bt_hci  : start_up
,10-07 06:41:17.583  5819  5937 I bt_vendor: alloc value 0xf3b78871
,10-07 06:41:17.583  5819  5937 I bt_vendor: init
10-07 06:41:17.583  5819  5937 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-07 06:41:17.583  5819  5937 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-07 06:41:17.697  5819  5937 D bt_hci  : start_up starting async portion
,10-07 06:41:17.697  5819  5944 I bt_hci  : event_finish_startup
10-07 06:41:17.697  5819  5944 I bt_hci_h4: hal_open
,10-07 06:41:17.697  5819  5944 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-07 06:41:17.696  5945  5945 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-07 06:41:17.700  5819  5944 I bt_userial_vendor: device fd = 54 open
,10-07 06:41:17.713  5819  5944 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 06:41:17.716  5819  5944 D bt_hwcfg: Chipset BCM4358A3
,10-07 06:41:17.716  5819  5944 D bt_hwcfg: Target name = [BCM4358A3]
10-07 06:41:17.716  5819  5944 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-07 06:41:17.889   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:18.099  5819  5944 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-07 06:41:18.099  5819  5944 D bt_hwcfg: Settlement delay -- 100 ms
10-07 06:41:18.099  5819  5944 I bt_hwcfg: Setting fw settlement delay to 100 
,10-07 06:41:18.234  5819  5944 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 06:41:18.234  5819  5944 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-07 06:41:18.235  5819  5944 I bt_hwcfg: vendor lib fwcfg completed
10-07 06:41:18.236  5819  5944 I bt_vendor: firmware callback
10-07 06:41:18.236  5819  5944 I bt_hci  : firmware_config_callback
,10-07 06:41:18.246  5819  5947 I bt_btu  : btu_task pending for preload complete event
,10-07 06:41:18.246  5819  5947 I bt_btu_task: Bluetooth chip preload is complete
10-07 06:41:18.246  5819  5947 I bt_btu  : btu_task received preload complete event
,10-07 06:41:18.253  5819  5947 I         : BTE_InitTraceLevels -- TRC_HCI
,10-07 06:41:18.253  5819  5947 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_AVDT
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_A2D
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_BNEP
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_BTM
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_GAP
10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_PAN
,10-07 06:41:18.254  5819  5947 I         : BTE_InitTraceLevels -- TRC_SDP
10-07 06:41:18.255  5819  5947 I         : BTE_InitTraceLevels -- TRC_GATT
,10-07 06:41:18.255  5819  5947 I         : BTE_InitTraceLevels -- TRC_SMP
,10-07 06:41:18.255  5819  5947 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-07 06:41:18.255  5819  5947 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-07 06:41:18.335  5819  5947 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3af6549
,10-07 06:41:18.335  5819  5947 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3af6549 
,10-07 06:41:18.352  5819  5940 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-07 06:41:18.353  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-07 06:41:18.354  5819  5940 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 06:41:18.355  5819  5940 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 06:41:18.358  5819  5940 D BluetoothAdapterProperties: Scan Mode:20
10-07 06:41:18.359  5819  5940 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-07 06:41:18.359  5819  5940 D bt_hci  : do_postload posting postload work item
10-07 06:41:18.359  5819  5944 I bt_hci  : event_postload
,10-07 06:41:18.359  5819  5944 I bt_vendor: sco_config_cb
10-07 06:41:18.359  5819  5944 I bt_hci  : sco_config_callback postload finished.
10-07 06:41:18.363  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:18.366  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:18.368  5819  5944 I bt_vendor: low_power_mode_cb
,10-07 06:41:18.370  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:18.371  5819  5940 D bt_bte_conf: Device ID record 1 : primary
,10-07 06:41:18.371  5819  5940 D bt_bte_conf:   vendorId            = 000f
10-07 06:41:18.371  5819  5940 D bt_bte_conf:   vendorIdSource      = 0001
10-07 06:41:18.371  5819  5940 D bt_bte_conf:   product             = 1200
10-07 06:41:18.371  5819  5940 D bt_bte_conf:   version             = 1436
10-07 06:41:18.371  5819  5940 D bt_bte_conf:   clientExecutableURL = 
,10-07 06:41:18.371  5819  5940 D bt_bte_conf:   serviceDescription  = 
10-07 06:41:18.371  5819  5940 D bt_bte_conf:   documentationURL    = 
10-07 06:41:18.371  5819  5940 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-07 06:41:18.372  5819  5937 D bt_stack_manager: event_start_up_stack finished
,10-07 06:41:18.372  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-07 06:41:18.373  5819  5936 D BluetoothAdapterProperties: Setting state to 15
10-07 06:41:18.373  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-07 06:41:18.374  5819  5936 I BluetoothAdapterState: Entering BleOnState
,10-07 06:41:18.378  5819  5936 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-07 06:41:18.378  5819  5936 D BluetoothAdapterProperties: Setting state to 11
10-07 06:41:18.378  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-07 06:41:18.382  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:18.385  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:18.385  5819  5819 D HeadsetService: Received start request. Starting profile...
10-07 06:41:18.388  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:18.388  5819  5819 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-07 06:41:18.390  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:18.391  5819  5819 D HeadsetStateMachine: make
,10-07 06:41:18.401  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
,10-07 06:41:18.401  5819  5819 D HeadsetStateMachine: max_hf_connections = 1
10-07 06:41:18.401  5819  5819 I bt_bluedroid: get_profile_interface handsfree
,10-07 06:41:18.401  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-07 06:41:18.402  5819  5940 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-07 06:41:18.405  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:18.406  5819  5819 D A2dpService: Received start request. Starting profile...
,10-07 06:41:18.406  5819  5819 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-07 06:41:18.406  5819  5819 I bt_bluedroid: get_profile_interface avrcp
,10-07 06:41:18.412  5819  5819 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-07 06:41:18.412  5819  5819 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-07 06:41:18.412  5819  5819 D A2dpStateMachine: make
10-07 06:41:18.413  5819  5819 I bt_bluedroid: get_profile_interface a2dp
10-07 06:41:18.414  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-07 06:41:18.415  5819  5955 D A2dpStateMachine: Enter Disconnected: -2
,10-07 06:41:18.416  5819  5819 I BluetoothHidServiceJni: classInitNative: succeeds
,10-07 06:41:18.417  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:41:18.417  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 06:41:18.419  5819  5819 D HidService: Received start request. Starting profile...
10-07 06:41:18.419  5819  5819 I bt_bluedroid: get_profile_interface hidhost
10-07 06:41:18.419  5754  5754 D BluetoothInputDevice: Proxy object connected
10-07 06:41:18.419  5819  5819 D HidService: setHidService(): set to: null
10-07 06:41:18.419  5819  5940 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ad756d
10-07 06:41:18.419  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-07 06:41:18.419  5819  5819 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-07 06:41:18.420  5754  5754 D HidProfile: Bluetooth service connected
,10-07 06:41:18.420  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:18.421  5819  5819 D HealthService: Received start request. Starting profile...
10-07 06:41:18.423  5819  5819 I bt_bluedroid: get_profile_interface health
,10-07 06:41:18.424  5819  5819 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-07 06:41:18.424  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:18.426  5754  5754 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 06:41:18.427  5819  5819 D PanService: Received start request. Starting profile...
,10-07 06:41:18.427  5819  5819 D BluetoothPanServiceJni: initializeNative(L110): pan
10-07 06:41:18.427  5819  5819 I bt_bluedroid: get_profile_interface pan
10-07 06:41:18.426  5754  5754 D PanProfile: Bluetooth service connected
10-07 06:41:18.427  5819  5940 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-07 06:41:18.431  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:18.433  5754  5754 D BluetoothMap: Proxy object connected
,10-07 06:41:18.433  5754  5754 D MapProfile: Bluetooth service connected
10-07 06:41:18.433  5819  5819 D BluetoothMapService: Received start request. Starting profile...
10-07 06:41:18.433  5819  5819 D BluetoothMapService: start()
10-07 06:41:18.436  5819  5819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-07 06:41:18.437  5819  5819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-07 06:41:18.437  5819  5819 D BluetoothMapAppObserver: createReceiver()
10-07 06:41:18.439  5819  5819 D BluetoothMapAppObserver: initObservers()
10-07 06:41:18.439  5819  5819 D BluetoothMapAppObserver: getEnabledAccountItems()
10-07 06:41:18.445  5819  5819 V SapService: SapBinder()
10-07 06:41:18.445  5819  5819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:41:18.445  5819  5819 D SapService: Received start request. Starting profile...
10-07 06:41:18.445  5819  5819 V SapService: start()
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:18.447  5819  5953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:18.447  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:18.448  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:18.449  5819  5819 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:18.449  5819  5819 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:18.449  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:18.449  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:18.450  5819  5819 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:18.450  5819  5819 V BluetoothAdapterState: isTurningOn()=true
,10-07 06:41:18.450  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:18.450  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:18.450  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-07 06:41:18.450  5819  5936 D BluetoothAdapterProperties: ScanMode =  20
10-07 06:41:18.450  5819  5936 D BluetoothAdapterProperties: State =  11
10-07 06:41:18.451  5819  5936 D BluetoothAdapterProperties: Setting state to 12
10-07 06:41:18.451  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-07 06:41:18.452  5819  5936 I BluetoothAdapterState: Entering OnState
,10-07 06:41:18.452   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:18.452   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 06:41:18.453  3174  3187 D BluetoothMap: onBluetoothStateChange: up=true
10-07 06:41:18.454  5754  5754 D BluetoothMap: getConnectedDevices()
,10-07 06:41:18.454   930   930 D BluetoothA2dp: Proxy object connected
10-07 06:41:18.455  3174  4010 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-07 06:41:18.455  3174  3174 D BluetoothMap: Proxy object connected
,10-07 06:41:18.455  3174  3174 D MapProfile: Bluetooth service connected
,10-07 06:41:18.455  3174  3174 D BluetoothMap: getConnectedDevices()
,10-07 06:41:18.456  5754  5766 D BluetoothMap: onBluetoothStateChange: up=true
,10-07 06:41:18.457  5819  5940 D BluetoothAdapterProperties: Scan Mode:21
,10-07 06:41:18.457  5819  5940 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 06:41:18.457  5701  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 06:41:18.457  3174  3404 D BluetoothPan: onBluetoothStateChange on: true
10-07 06:41:18.460  3174  3174 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 06:41:18.460  3174  3174 D PanProfile: Bluetooth service connected
10-07 06:41:18.460  5754  5769 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 06:41:18.462  3855  4273 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:18.462  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:18.462   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:18.462  3174  3188 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 06:41:18.464  5819  5819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 06:41:18.464  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:18.464  3174  3174 D BluetoothA2dp: Proxy object connected
10-07 06:41:18.464  3174  3187 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 06:41:18.464  5819  5819 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-07 06:41:18.465  5754  5766 D BluetoothPan: onBluetoothStateChange on: true
10-07 06:41:18.466   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:18.466  5754  5769 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 06:41:18.466  5819  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 06:41:18.466  3174  3404 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:18.467  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:18.468  5819  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 06:41:18.468  3174  3174 D BluetoothInputDevice: Proxy object connected
10-07 06:41:18.469  3174  3174 D HidProfile: Bluetooth service connected
10-07 06:41:18.469  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:18.469   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-07 06:41:18.472  5754  5754 D LocalBluetoothProfileManager: Adding local A2DP profile
10-07 06:41:18.473  5819  5819 D ObexServerSockets: Succeed to create listening sockets 
10-07 06:41:18.473  5819  5819 D ObexServerSockets0: startAccept()
10-07 06:41:18.473  5819  5819 D ObexServerSockets0: prepareForNewConnect()
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:18.474  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:18.476  5754  5754 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-07 06:41:18.476  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:18.477  5701  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 06:41:18.477  5819  5819 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-07 06:41:18.477  5819  5819 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-07 06:41:18.478  5819  5964 D ObexServerSockets0: Accepting socket connection...
10-07 06:41:18.479  5819  5965 D ObexServerSockets0: Accepting socket connection...
10-07 06:41:18.479  5819  5819 D BluetoothMapService: onReceive
10-07 06:41:18.479  5819  5819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 06:41:18.479  5819  5819 D BluetoothMapService: STATE_ON
10-07 06:41:18.479  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:18.482  5819  5966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:18.483  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:18.483  5754  5754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 06:41:18.485  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:18.486  5819  5966 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-07 06:41:18.486  5819  5966 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-07 06:41:18.488  5754  5754 D BluetoothA2dp: Proxy object connected
,10-07 06:41:18.495  5754  5754 D DockEventReceiver: finishStartingService: stopping service
,10-07 06:41:18.495  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 06:41:18.501  5819  5819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-07 06:41:18.501  5819  5819 D ObexServerSockets0: prepareForNewConnect()
10-07 06:41:18.501  3174  3174 D BluetoothPbap: Proxy object connected
10-07 06:41:18.501  5754  5754 D BluetoothPbap: Proxy object connected
10-07 06:41:18.501  3174  3174 D PbapServerProfile: Bluetooth service connected
10-07 06:41:18.502  5754  5754 D PbapServerProfile: Bluetooth service connected
,10-07 06:41:18.509  5819  5970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:18.522  5819  5974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:18.523  5819  5974 I BtOppRfcommListener: Accept thread started.
,10-07 06:41:18.554   930   930 D BluetoothHeadset: Proxy object connected
,10-07 06:41:18.554  3855  4046 D BluetoothHeadset: Proxy object connected
10-07 06:41:18.555  3174  3187 D BluetoothHeadset: Proxy object connected
10-07 06:41:18.555  3174  3174 D HeadsetProfile: Bluetooth service connected
10-07 06:41:18.555   930   930 D BluetoothHeadset: Proxy object connected
10-07 06:41:18.555   930   930 D BluetoothHeadset: Proxy object connected
10-07 06:41:18.555  3174  3404 D BluetoothHeadset: Proxy object connected
,10-07 06:41:18.557  3174  3174 D HeadsetProfile: Bluetooth service connected
,10-07 06:41:18.563  3855  3879 D BluetoothHeadset: Proxy object connected
,10-07 06:41:18.563   930   947 D BluetoothHeadset: Proxy object connected
,10-07 06:41:18.566   930   947 D BluetoothHeadset: Proxy object connected
,10-07 06:41:18.581  5754  5766 D BluetoothHeadset: Proxy object connected
,10-07 06:41:18.582  5754  5754 D HeadsetProfile: Bluetooth service connected
,10-07 06:41:18.890   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-07 06:41:20.285   930  3019 D ConnectivityService: handlePromptUnvalidated 101
,10-07 06:41:22.476  5819  5936 D BluetoothAdapterState: Current state: ON, message: 23
,10-07 06:41:22.477  5819  5936 D BluetoothAdapterProperties: Setting state to 13
10-07 06:41:22.477  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-07 06:41:22.478  5819  5936 D BluetoothAdapterProperties: onBluetoothDisable()
,10-07 06:41:22.480  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
10-07 06:41:22.486  5819  5819 D BluetoothMapService: onReceive
10-07 06:41:22.487  5819  5819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 06:41:22.487  5819  5819 D BluetoothMapService: STATE_TURNING_OFF
10-07 06:41:22.488  5819  5819 D BluetoothMapService: MAP Service closeService in
10-07 06:41:22.488  5819  5819 D BluetoothMapMasInstance0: MAP Service shutdown
10-07 06:41:22.488  5819  5819 D ObexServerSockets0: shutdown(block = true)
10-07 06:41:22.489  5819  5964 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-07 06:41:22.491  5819  5940 D BluetoothAdapterProperties: Scan Mode:20
10-07 06:41:22.491  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-07 06:41:22.491  5819  5819 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 06:41:22.492  5819  5819 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 06:41:22.493  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:22.493  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:22.494  5819  5965 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-07 06:41:22.495  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:22.495  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:22.495  5819  5819 I BtOppRfcommListener: stopping Accept Thread
10-07 06:41:22.496  5819  5974 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-07 06:41:22.496  5819  5974 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-07 06:41:22.497  5819  5949 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-07 06:41:22.498  5819  5819 D HeadsetService: Received stop request...Stopping profile...
,10-07 06:41:22.498  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:22.499  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:22.499  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:22.500  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:22.501   930   930 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:22.502  3855  4273 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:22.502  5754  5754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 06:41:22.502  3174  3188 D BluetoothHeadset: Proxy object disconnected
10-07 06:41:22.503   930   930 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:22.503   930   930 D BluetoothHeadset: Proxy object disconnected
10-07 06:41:22.503  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:22.504  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:22.504  5754  5769 D BluetoothHeadset: Proxy object disconnected
,10-07 06:41:22.504  5701  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 06:41:22.505  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:22.505  5819  5819 D A2dpService: Received stop request...Stopping profile...
10-07 06:41:22.505  5819  5955 D A2dpStateMachine: Exit Disconnected: -1
10-07 06:41:22.507  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:22.508  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:22.509  5819  5819 D HidService: Received stop request...Stopping profile...
10-07 06:41:22.509  5754  5754 D HeadsetProfile: Bluetooth service disconnected
10-07 06:41:22.509  5819  5819 D HidService: Stopping Bluetooth HidService
10-07 06:41:22.509   930   930 D BluetoothA2dp: Proxy object disconnected
10-07 06:41:22.510  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:22.511  3174  3174 D HeadsetProfile: Bluetooth service disconnected
10-07 06:41:22.511  3174  3174 D BluetoothA2dp: Proxy object disconnected
10-07 06:41:22.512  3174  3174 D BluetoothInputDevice: Proxy object disconnected
,10-07 06:41:22.512  3174  3174 D HidProfile: Bluetooth service disconnected
10-07 06:41:22.513  5754  5754 D DockEventReceiver: finishStartingService: stopping service
10-07 06:41:22.513  5819  5819 D HealthService: Received stop request...Stopping profile...
10-07 06:41:22.514  5754  5754 D BluetoothA2dp: Proxy object disconnected
10-07 06:41:22.515  5754  5754 D BluetoothInputDevice: Proxy object disconnected
10-07 06:41:22.515  5754  5754 D HidProfile: Bluetooth service disconnected
,10-07 06:41:22.517  5819  5819 D PanService: Received stop request...Stopping profile...
10-07 06:41:22.518  5819  5819 V BluetoothAdapterState: isTurningOff()=true
,10-07 06:41:22.518  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.518  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.518  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:22.519  5819  5819 D BluetoothMapService: Received stop request...Stopping profile...
10-07 06:41:22.519  5819  5819 D BluetoothMapService: stop()
10-07 06:41:22.519  3174  3174 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-07 06:41:22.519  3174  3174 D PanProfile: Bluetooth service disconnected
10-07 06:41:22.519  5819  5819 D BluetoothMapAppObserver: deinitObservers()
10-07 06:41:22.520  5819  5819 D BluetoothMapAppObserver: removeReceiver()
10-07 06:41:22.521  3174  3174 D BluetoothMap: Proxy object disconnected
10-07 06:41:22.521  3174  3174 D MapProfile: Bluetooth service disconnected
,10-07 06:41:22.522  5819  5819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-07 06:41:22.523  5819  5819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-07 06:41:22.523  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:22.523  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:22.523  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:22.523  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-07 06:41:22.523  5819  5940 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-07 06:41:22.523  5819  5819 D SapService: Received stop request...Stopping profile...
10-07 06:41:22.524  5819  5819 V SapService: stop()
10-07 06:41:22.525  5754  5754 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 06:41:22.525  5754  5754 D PanProfile: Bluetooth service disconnected
10-07 06:41:22.525  5754  5754 D BluetoothMap: Proxy object disconnected
10-07 06:41:22.525  5754  5754 D MapProfile: Bluetooth service disconnected
10-07 06:41:22.525  5819  5819 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:22.525  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.526  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.526  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:22.527  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-07 06:41:22.527  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:22.527  5819  5819 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:22.527  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:22.527  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.527  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.527  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 06:41:22.527  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:22.527  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 06:41:22.527  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 06:41:22.527  5819  5947 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-07 06:41:22.528  5819  5819 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-07 06:41:22.528  5819  5819 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-07 06:41:22.528  5819  5819 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:22.529  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.529  5819  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 06:41:22.529  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.529  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:22.529  5819  5819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-07 06:41:22.529  5819  5940 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-07 06:41:22.529  5819  5819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-07 06:41:22.529  5819  5819 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:22.530  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.530  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.530  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:22.530  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 06:41:22.530  5819  5819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-07 06:41:22.530  5819  5819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-07 06:41:22.534  5819  5819 D BluetoothMapService: MAP Service closeService in
,10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:22.534  5819  5819 D BluetoothMapService: cleanup()
10-07 06:41:22.534  5819  5819 D BluetoothMapService: MAP Service closeService in
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isTurningOff()=true
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:22.534  5819  5819 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 06:41:22.535  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-07 06:41:22.535  5819  5936 D BluetoothAdapterProperties: Setting state to 15
10-07 06:41:22.535  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-07 06:41:22.536  5819  5936 I BluetoothAdapterState: Entering BleOnState
10-07 06:41:22.536  5754  5754 D BluetoothPbap: Proxy object disconnected
10-07 06:41:22.536  5754  5754 D PbapServerProfile: Bluetooth service disconnected
10-07 06:41:22.536  3174  3174 D BluetoothPbap: Proxy object disconnected
10-07 06:41:22.536  3174  3174 D PbapServerProfile: Bluetooth service disconnected
,10-07 06:41:22.536   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:22.536   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 06:41:22.536  3174  3187 D BluetoothMap: onBluetoothStateChange: up=false
,10-07 06:41:22.537  5754  5766 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-07 06:41:22.537  5754  5769 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:22.538  3174  3404 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:22.538  5754  5766 D BluetoothMap: onBluetoothStateChange: up=false
10-07 06:41:22.539  3174  3188 D BluetoothPan: onBluetoothStateChange on: false
10-07 06:41:22.540  5754  5769 D BluetoothPbap: onBluetoothStateChange: up=false
10-07 06:41:22.540  3855  4046 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:22.541   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:22.541  3174  4010 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 06:41:22.541  3174  3187 D BluetoothPbap: onBluetoothStateChange: up=false
10-07 06:41:22.542  5754  5766 D BluetoothPan: onBluetoothStateChange on: false
10-07 06:41:22.543   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 06:41:22.543  5754  5769 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 06:41:22.544  3174  3404 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 06:41:22.544  5819  5936 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-07 06:41:22.544  5819  5936 D BluetoothAdapterProperties: Setting state to 16
,10-07 06:41:22.544  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-07 06:41:22.545  5819  5936 D BluetoothAdapterProperties: onBleDisable
10-07 06:41:22.545  5819  5936 I BluetoothAdapterState: Entering PendingCommandState
10-07 06:41:22.545  5819  5937 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-07 06:41:22.546  5819  5947 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-07 06:41:22.546  5819  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 06:41:22.546  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:22.548  5819  5940 D BluetoothAdapterProperties: Scan Mode:20
10-07 06:41:22.549  5754  5754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 06:41:22.552  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:22.554  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 06:41:22.554  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:22.554  5754  5754 D DockEventReceiver: finishStartingService: stopping service
10-07 06:41:22.556  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:22.557  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:22.560  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:22.764  5819  5940 I bt_hci  : shut_down
,10-07 06:41:22.774  5819  5944 D bt_hwcfg: hw_epilog_process
,10-07 06:41:22.774  5819  5944 I bt_vendor: low_power_mode_cb
,10-07 06:41:22.777  5819  5944 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-07 06:41:22.778  5819  5944 I bt_vendor: epilog_cb
10-07 06:41:22.778  5819  5944 I bt_hci  : epilog_finished_callback
,10-07 06:41:22.782  5819  5940 I bt_hci_h4: hal_close
,10-07 06:41:22.782  5819  5940 I bt_userial_vendor: device fd = 54 close
,10-07 06:41:22.897  5819  5937 D bt_stack_manager: event_shut_down_stack finished.
,10-07 06:41:22.898  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-07 06:41:22.902  5819  5936 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-07 06:41:22.903  5819  5819 D BtGatt.DebugUtils: handleDebugAction() action=null
10-07 06:41:22.904  5819  5819 D BtGatt.GattService: Received stop request...Stopping profile...
10-07 06:41:22.904  5819  5819 D BtGatt.GattService: stop()
10-07 06:41:22.904  5819  5819 D BtGatt.AdvertiseManager: advertise clients cleared
,10-07 06:41:22.908  5819  5819 V BluetoothAdapterState: isTurningOff()=false
,10-07 06:41:22.909  5819  5819 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:22.909  5819  5819 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 06:41:22.909  5819  5819 V BluetoothAdapterState: isBleTurningOff()=true
,10-07 06:41:22.909  5819  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-07 06:41:22.910  5819  5936 D BluetoothAdapterProperties: Setting state to 10
,10-07 06:41:22.910  5819  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-07 06:41:22.911  5819  5936 I BluetoothAdapterState: Entering OffState
10-07 06:41:22.912   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-07 06:41:22.928  5819  5819 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-07 06:41:22.928  5819  5819 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-07 06:41:22.929  5819  5819 I BluetoothServiceJni: cleanupNative: return from cleanup
10-07 06:41:22.931  5819  5937 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-07 06:41:22.938  5819  5819 I art     : System.exit called, status: 0
,10-07 06:41:22.938  5819  5819 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-07 06:41:22.966   930  3916 I ActivityManager: Process com.android.bluetooth (pid 5819) has died
,10-07 06:41:27.476  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 06:41:27.477  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:41:27.481  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:41:27.482  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b54114 removed from the list
10-07 06:41:27.482  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 06:41:27.482  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:27.482  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:41:27.486  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:27.486  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@901cfb2 added. We now have 4 listener(s)
10-07 06:41:27.486  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:41:27.488  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:41:27.489  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@901cfb2 removed from the list
10-07 06:41:27.489  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 06:41:27.489  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:27.489  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:27.491  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:27.491  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b9db03 added. We now have 4 listener(s)
,10-07 06:41:27.491  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:41:32.503  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:32.536   930   947 I ActivityManager: Start proc 5982:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-07 06:41:32.618  5982  5982 D AdapterServiceConfig: Adding HeadsetService
,10-07 06:41:32.618  5982  5982 D AdapterServiceConfig: Adding A2dpService
10-07 06:41:32.619  5982  5982 D AdapterServiceConfig: Adding HidService
10-07 06:41:32.619  5982  5982 D AdapterServiceConfig: Adding HealthService
10-07 06:41:32.619  5982  5982 D AdapterServiceConfig: Adding PanService
10-07 06:41:32.619  5982  5982 D AdapterServiceConfig: Adding GattService
10-07 06:41:32.619  5982  5982 D AdapterServiceConfig: Adding BluetoothMapService
10-07 06:41:32.619  5982  5982 D AdapterServiceConfig: Adding SapService
,10-07 06:41:32.630   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5275c7a:true
,10-07 06:41:32.630  5982  5982 D BluetoothAdapterState: make() - Creating AdapterState
,10-07 06:41:32.645  5982  5982 I bt_bluedroid: init
,10-07 06:41:32.645  5982  5994 I BluetoothAdapterState: Entering OffState
10-07 06:41:32.647  5982  5995 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-07 06:41:32.648  5982  5995 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-07 06:41:32.648  5982  5995 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-07 06:41:32.648  5982  5995 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-07 06:41:32.649  5982  5982 I bt_bluedroid: get_profile_interface socket
,10-07 06:41:32.652  5982  5998 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 06:41:32.652  5982  5982 I bt_bluedroid: get_profile_interface sdp
,10-07 06:41:32.654  5982  5998 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 06:41:32.657  5982  5993 I bt_bluedroid: config_hci_snoop_log
,10-07 06:41:32.662   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-07 06:41:32.666  5982  5994 D BluetoothAdapterState: Current state: OFF, message: 0
10-07 06:41:32.666  5982  5994 D BluetoothAdapterProperties: Setting state to 14
10-07 06:41:32.666  5982  5994 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-07 06:41:32.668  5982  5994 D BluetoothBondStateMachine: make
,10-07 06:41:32.670  5982  5999 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-07 06:41:32.673  5982  5994 I BluetoothAdapterState: Entering PendingCommandState
,10-07 06:41:32.674  5982  5982 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-07 06:41:32.677  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:41:32.678  5982  5982 D BtGatt.DebugUtils: handleDebugAction() action=null
10-07 06:41:32.679  5982  5982 D BtGatt.GattService: Received start request. Starting profile...
10-07 06:41:32.679  5982  5982 D BtGatt.GattService: start()
10-07 06:41:32.679  5982  5982 I bt_bluedroid: get_profile_interface gatt
,10-07 06:41:32.680  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:32.680  5982  5982 D BtGatt.AdvertiseManager: advertise manager created
,10-07 06:41:32.686  5982  5982 V BluetoothAdapterState: isTurningOff()=false
,10-07 06:41:32.686  5982  5982 V BluetoothAdapterState: isTurningOn()=false
10-07 06:41:32.686  5982  5982 V BluetoothAdapterState: isBleTurningOn()=true
10-07 06:41:32.686  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:32.687  5982  5994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-07 06:41:32.688  5982  5994 I bt_bluedroid: bt_bluedroid
10-07 06:41:32.688  5982  5995 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-07 06:41:32.689  5982  5995 I bt_hci  : start_up
,10-07 06:41:32.694  5982  5995 I bt_vendor: alloc value 0xf3bf5871
,10-07 06:41:32.694  5982  5995 I bt_vendor: init
10-07 06:41:32.694  5982  5995 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-07 06:41:32.694  5982  5995 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-07 06:41:32.804  5982  5995 D bt_hci  : start_up starting async portion
10-07 06:41:32.805  5982  6002 I bt_hci  : event_finish_startup
10-07 06:41:32.805  5982  6002 I bt_hci_h4: hal_open
10-07 06:41:32.805  5982  6002 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-07 06:41:32.802  6003  6003 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-07 06:41:32.807  5982  6002 I bt_userial_vendor: device fd = 54 open
,10-07 06:41:32.822  5982  6002 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 06:41:32.827  5982  6002 D bt_hwcfg: Chipset BCM4358A3
,10-07 06:41:32.827  5982  6002 D bt_hwcfg: Target name = [BCM4358A3]
10-07 06:41:32.827  5982  6002 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-07 06:41:33.353  5982  6002 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-07 06:41:33.354  5982  6002 D bt_hwcfg: Settlement delay -- 100 ms
10-07 06:41:33.354  5982  6002 I bt_hwcfg: Setting fw settlement delay to 100 
,10-07 06:41:33.487  5982  6002 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 06:41:33.488  5982  6002 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-07 06:41:33.490  5982  6002 I bt_hwcfg: vendor lib fwcfg completed
10-07 06:41:33.490  5982  6002 I bt_vendor: firmware callback
,10-07 06:41:33.490  5982  6002 I bt_hci  : firmware_config_callback
,10-07 06:41:33.501  5982  6005 I bt_btu  : btu_task pending for preload complete event
,10-07 06:41:33.501  5982  6005 I bt_btu_task: Bluetooth chip preload is complete
10-07 06:41:33.501  5982  6005 I bt_btu  : btu_task received preload complete event
,10-07 06:41:33.509  5982  6005 I         : BTE_InitTraceLevels -- TRC_HCI
,10-07 06:41:33.510  5982  6005 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-07 06:41:33.511  5982  6005 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-07 06:41:33.511  5982  6005 I         : BTE_InitTraceLevels -- TRC_AVDT
10-07 06:41:33.511  5982  6005 I         : BTE_InitTraceLevels -- TRC_AVRC
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_A2D
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_BTM
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_GAP
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_PAN
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_SDP
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_GATT
10-07 06:41:33.512  5982  6005 I         : BTE_InitTraceLevels -- TRC_SMP
10-07 06:41:33.513  5982  6005 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-07 06:41:33.513  5982  6005 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-07 06:41:33.611  5982  6005 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b73549
10-07 06:41:33.611  5982  6005 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b73549 
,10-07 06:41:33.645  5982  5998 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-07 06:41:33.647  5982  5998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-07 06:41:33.648  5982  5998 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 06:41:33.651  5982  5998 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 06:41:33.653  5982  5998 D BluetoothAdapterProperties: Scan Mode:20
,10-07 06:41:33.654  5982  5998 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-07 06:41:33.654  5982  5998 D bt_hci  : do_postload posting postload work item
10-07 06:41:33.654  5982  6002 I bt_hci  : event_postload
,10-07 06:41:33.654  5982  6002 I bt_vendor: sco_config_cb
10-07 06:41:33.654  5982  6002 I bt_hci  : sco_config_callback postload finished.
10-07 06:41:33.657  5982  5998 D bt_bte_conf: Device ID record 1 : primary
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   vendorId            = 000f
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   vendorIdSource      = 0001
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   product             = 1200
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   version             = 1436
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   clientExecutableURL = 
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   serviceDescription  = 
10-07 06:41:33.657  5982  5998 D bt_bte_conf:   documentationURL    = 
10-07 06:41:33.657  5982  5998 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-07 06:41:33.658  5982  5995 D bt_stack_manager: event_start_up_stack finished
10-07 06:41:33.658  5982  5994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-07 06:41:33.659  5982  5994 D BluetoothAdapterProperties: Setting state to 15
10-07 06:41:33.659  5982  5994 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-07 06:41:33.659  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:33.663  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:33.663  5982  6002 I bt_vendor: low_power_mode_cb
10-07 06:41:33.664  5982  5994 I BluetoothAdapterState: Entering BleOnState
,10-07 06:41:33.666  5982  5994 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-07 06:41:33.666  5982  5994 D BluetoothAdapterProperties: Setting state to 11
10-07 06:41:33.666  5982  5994 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-07 06:41:33.674  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:33.675  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:41:33.675  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:33.676  5982  5982 D HeadsetService: Received start request. Starting profile...
,10-07 06:41:33.678  5982  5982 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-07 06:41:33.679  5982  5982 D HeadsetStateMachine: make
,10-07 06:41:33.684  5982  5994 I BluetoothAdapterState: Entering PendingCommandState
,10-07 06:41:33.686  5982  5982 D HeadsetStateMachine: max_hf_connections = 1
10-07 06:41:33.686  5982  5982 I bt_bluedroid: get_profile_interface handsfree
,10-07 06:41:33.687  5982  5998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-07 06:41:33.687  5982  5998 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-07 06:41:33.691  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:33.691  5982  5982 D A2dpService: Received start request. Starting profile...
10-07 06:41:33.692  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 06:41:33.692  5982  5982 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-07 06:41:33.692  5982  5982 I bt_bluedroid: get_profile_interface avrcp
,10-07 06:41:33.698  5982  5982 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-07 06:41:33.698  5982  5982 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-07 06:41:33.698  5982  5982 D A2dpStateMachine: make
,10-07 06:41:33.701  5982  5982 I bt_bluedroid: get_profile_interface a2dp
10-07 06:41:33.701  5982  5998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-07 06:41:33.703  5982  6014 D A2dpStateMachine: Enter Disconnected: -2
,10-07 06:41:33.703  5982  5982 I BluetoothHidServiceJni: classInitNative: succeeds
,10-07 06:41:33.704  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:33.705  5982  5982 D HidService: Received start request. Starting profile...
,10-07 06:41:33.705  5982  5982 I bt_bluedroid: get_profile_interface hidhost
10-07 06:41:33.705  5982  5998 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b5456d
10-07 06:41:33.705  5982  5982 D HidService: setHidService(): set to: null
10-07 06:41:33.705  5982  5998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-07 06:41:33.706  5982  5982 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-07 06:41:33.706  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:33.707  5982  5982 D HealthService: Received start request. Starting profile...
,10-07 06:41:33.709  5982  5982 I bt_bluedroid: get_profile_interface health
10-07 06:41:33.710  5982  5982 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-07 06:41:33.710  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:33.711  5982  5982 D PanService: Received start request. Starting profile...
,10-07 06:41:33.711  5982  5982 D BluetoothPanServiceJni: initializeNative(L110): pan
10-07 06:41:33.711  5982  5982 I bt_bluedroid: get_profile_interface pan
,10-07 06:41:33.713  5982  5998 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-07 06:41:33.714  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:41:33.714  5982  5982 D BluetoothMapService: Received start request. Starting profile...
10-07 06:41:33.714  5982  5982 D BluetoothMapService: start()
10-07 06:41:33.716  5982  5982 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-07 06:41:33.717  5982  5982 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-07 06:41:33.717  5982  5982 D BluetoothMapAppObserver: createReceiver()
,10-07 06:41:33.719  5982  5982 D BluetoothMapAppObserver: initObservers()
,10-07 06:41:33.719  5982  5982 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-07 06:41:33.725  5982  5982 V SapService: SapBinder()
,10-07 06:41:33.726  5982  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
10-07 06:41:33.726  5982  5982 D SapService: Received start request. Starting profile...
10-07 06:41:33.726  5982  5982 V SapService: start()
10-07 06:41:33.727  5982  5982 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:33.727  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.727  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:33.727  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:33.728  5982  6012 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isTurningOff()=false
,10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:33.728  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:33.729  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:33.730  5982  5982 V BluetoothAdapterState: isTurningOff()=false
10-07 06:41:33.730  5982  5982 V BluetoothAdapterState: isTurningOn()=true
10-07 06:41:33.730  5982  5982 V BluetoothAdapterState: isBleTurningOn()=false
10-07 06:41:33.730  5982  5982 V BluetoothAdapterState: isBleTurningOff()=false
10-07 06:41:33.730  5982  5994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-07 06:41:33.730  5982  5994 D BluetoothAdapterProperties: ScanMode =  20
10-07 06:41:33.730  5982  5994 D BluetoothAdapterProperties: State =  11
10-07 06:41:33.732  5982  5998 D BluetoothAdapterProperties: Scan Mode:21
10-07 06:41:33.732  5982  5994 D BluetoothAdapterProperties: Setting state to 12
10-07 06:41:33.732  5982  5994 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-07 06:41:33.732  5701  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 06:41:33.732  5982  5994 I BluetoothAdapterState: Entering OnState
10-07 06:41:33.732   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:33.732   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 06:41:33.733  3174  3404 D BluetoothMap: onBluetoothStateChange: up=true
10-07 06:41:33.734  5982  5998 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 06:41:33.735   930   930 D BluetoothA2dp: Proxy object connected
10-07 06:41:33.737  3174  3174 D BluetoothMap: Proxy object connected
10-07 06:41:33.737  5754  5766 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 06:41:33.737  3174  3174 D MapProfile: Bluetooth service connected
10-07 06:41:33.737  3174  3174 D BluetoothMap: getConnectedDevices()
,10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:33.738  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:33.739  5754  5769 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:33.740  3174  4010 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:33.740  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:33.740  5754  5766 D BluetoothMap: onBluetoothStateChange: up=true
10-07 06:41:33.742  3174  3188 D BluetoothPan: onBluetoothStateChange on: true
,10-07 06:41:33.744  5982  5982 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 06:41:33.744  5754  5769 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 06:41:33.744  5982  5982 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:33.745  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:33.745  3855  4046 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:33.746  5982  5982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 06:41:33.746  5754  5754 D BluetoothA2dp: Proxy object connected
10-07 06:41:33.746   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:33.746  3174  3187 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 06:41:33.747  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:33.748  5982  5982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:33.748  3174  3174 D BluetoothA2dp: Proxy object connected
10-07 06:41:33.748  3174  3404 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 06:41:33.749  5982  5982 D ObexServerSockets: Succeed to create listening sockets 
10-07 06:41:33.749  5982  5982 D ObexServerSockets0: startAccept()
10-07 06:41:33.749  5982  5982 D ObexServerSockets0: prepareForNewConnect()
10-07 06:41:33.750  5754  5766 D BluetoothPan: onBluetoothStateChange on: true
10-07 06:41:33.751  5982  5982 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-07 06:41:33.751  5982  5982 D BluetoothSdpJni: SDP Create record success - handle: 0
10-07 06:41:33.752  5982  6021 D ObexServerSockets0: Accepting socket connection...
10-07 06:41:33.752   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 06:41:33.752  5982  6022 D ObexServerSockets0: Accepting socket connection...
10-07 06:41:33.752  5754  5769 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 06:41:33.752  3174  3174 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 06:41:33.753  3174  3174 D PanProfile: Bluetooth service connected
10-07 06:41:33.754  3174  3188 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 06:41:33.756  3174  3174 D BluetoothInputDevice: Proxy object connected
10-07 06:41:33.756  3174  3174 D HidProfile: Bluetooth service connected
10-07 06:41:33.757   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-07 06:41:33.757  5701  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 06:41:33.758  5982  5982 D BluetoothMapService: onReceive
10-07 06:41:33.758  5982  5982 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 06:41:33.758  5982  5982 D BluetoothMapService: STATE_ON
10-07 06:41:33.759  5754  5754 D BluetoothMap: Proxy object connected
10-07 06:41:33.759  5754  5754 D MapProfile: Bluetooth service connected
,10-07 06:41:33.759  5754  5754 D BluetoothMap: getConnectedDevices()
10-07 06:41:33.759  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:33.761  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:33.761  5982  6024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:33.762  5754  5754 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 06:41:33.762  5754  5754 D PanProfile: Bluetooth service connected
10-07 06:41:33.762  5754  5754 D BluetoothInputDevice: Proxy object connected
,10-07 06:41:33.762  5754  5754 D HidProfile: Bluetooth service connected
10-07 06:41:33.762  5982  6024 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-07 06:41:33.763  5982  6024 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-07 06:41:33.767  5754  5754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 06:41:33.775  3629  3629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 06:41:33.775  5754  5754 D DockEventReceiver: finishStartingService: stopping service
,10-07 06:41:33.782  3174  3174 D BluetoothPbap: Proxy object connected
,10-07 06:41:33.782  3174  3174 D PbapServerProfile: Bluetooth service connected
10-07 06:41:33.782  5754  5754 D BluetoothPbap: Proxy object connected
10-07 06:41:33.782  5982  5982 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 06:41:33.782  5754  5754 D PbapServerProfile: Bluetooth service connected
10-07 06:41:33.782  5982  5982 D ObexServerSockets0: prepareForNewConnect()
,10-07 06:41:33.792  5982  6028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:33.808  5982  6032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 06:41:33.809  5982  6032 I BtOppRfcommListener: Accept thread started.
,10-07 06:41:33.835   930   930 D BluetoothHeadset: Proxy object connected
,10-07 06:41:33.835  3855  3879 D BluetoothHeadset: Proxy object connected
10-07 06:41:33.835  3174  3187 D BluetoothHeadset: Proxy object connected
10-07 06:41:33.835  3174  3174 D HeadsetProfile: Bluetooth service connected
10-07 06:41:33.835   930   930 D BluetoothHeadset: Proxy object connected
10-07 06:41:33.835   930   930 D BluetoothHeadset: Proxy object connected
,10-07 06:41:33.836  5754  5766 D BluetoothHeadset: Proxy object connected
,10-07 06:41:33.837  5754  5754 D HeadsetProfile: Bluetooth service connected
,10-07 06:41:33.840  5754  6020 D BluetoothHeadset: Proxy object connected
,10-07 06:41:33.840  3174  3188 D BluetoothHeadset: Proxy object connected
10-07 06:41:33.841  5754  5754 D HeadsetProfile: Bluetooth service connected
10-07 06:41:33.841  3174  3174 D HeadsetProfile: Bluetooth service connected
,10-07 06:41:33.847  3855  3876 D BluetoothHeadset: Proxy object connected
,10-07 06:41:33.847   930   947 D BluetoothHeadset: Proxy object connected
,10-07 06:41:33.852   930   947 D BluetoothHeadset: Proxy object connected
,10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:37.518  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:37.525  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:37.525  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:37.526  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b9db03 removed from the list
10-07 06:41:37.526  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:37.526  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:41:37.526  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:41:37.529  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:37.529  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2f5a80 added. We now have 4 listener(s)
10-07 06:41:37.529  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:41:37.533   930  3607 D WifiService: setWifiEnabled: false pid=5701, uid=10077
10-07 06:41:37.534   930  3607 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 06:41:38.891   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:39.892   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:40.894   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:41.895   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:42.544  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:42.545   930  3201 D WifiService: setWifiEnabled: true pid=5701, uid=10077
10-07 06:41:42.545   930  3201 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 06:41:42.554   508   921 D SoftapController: Softap fwReload - Ok
,10-07 06:41:42.559   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:42.560   508   921 D CommandListener: Trying to bring down wlan0
,10-07 06:41:42.562   508   921 D CommandListener: Clearing all IP addresses on wlan0
,10-07 06:41:42.569   930  3017 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 06:41:42.897   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:41:43.252   930  3017 D wifi    : set interface wlan0 flags (UP)
10-07 06:41:43.252   930  3017 I WifiHAL : Initializing wifi
10-07 06:41:43.252   930  3017 I WifiHAL : Creating socket
,10-07 06:41:43.258   930  3017 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-07 06:41:43.258   930  3017 D wifi    : Did set static halHandle = 0x7f91062e00
10-07 06:41:43.258   930  3017 D wifi    : halHandle = 0x7f91062e00, mVM = 0x7fad68d140, mCls = 0x2016b6
,10-07 06:41:43.259   930  3017 D wifi    : array field set
10-07 06:41:43.259   930  3017 I WifiNative-HAL: interface[0] = wlan0
10-07 06:41:43.261   930  6037 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547893947904
10-07 06:41:43.262   930  6037 D wifi    : waitForHalEvents called, vm = 0x7fad68d140, obj = 0x2016b6, env = 0x7fa2bdc780
10-07 06:41:43.265   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-07 06:41:43.318  6038  6038 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-07 06:41:43.338  6038  6038 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 06:41:43.364   930  3017 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-07 06:41:43.365   930  3017 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
10-07 06:41:43.373  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:43.375  6038  6038 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 06:41:43.375  6038  6038 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-07 06:41:43.381  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:43.898   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-07 06:41:44.384   930  3017 D WifiConfigStore: Loading config and enabling all networks 
,10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:44.389  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:44.393  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:44.400  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:44.404  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:44.412   930  3017 D WifiConfigStore: loaded 0 passpoint configs
,10-07 06:41:44.413   930  3017 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-07 06:41:44.413   930  3017 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-07 06:41:44.415   930  3017 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-07 06:41:44.416   930  3017 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-07 06:41:44.416   930  3017 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-07 06:41:44.416   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-07 06:41:44.417   930  3017 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-07 06:41:44.422   930  3017 D WifiNative-HAL: Setting external_sim to 1
,10-07 06:41:44.422  5069  5069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 06:41:44.422   930  3017 D wifi    : setting dfs flag to true, 0x7f948be140
10-07 06:41:44.423   930  3017 D WifiStateMachine: Setting OUI to DA-A1-19
10-07 06:41:44.423   930  3017 D wifi    : setting scan oui 0x7f948be140
10-07 06:41:44.424   930  3017 D WifiHAL : Sending mac address OUI
,10-07 06:41:44.429   930  3017 E native  : do suspend false
,10-07 06:41:44.442   930  3017 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-07 06:41:44.442   930   930 D RttService: SCAN_AVAILABLE : 3
10-07 06:41:44.442   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-07 06:41:44.443   930  3129 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-07 06:41:44.444   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:44.450   930  3016 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-07 06:41:44.450   930  3016 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-07 06:41:44.466   930  3016 D WifiNative-HAL: p2pGetDeviceAddress
,10-07 06:41:44.473   930  3016 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
10-07 06:41:44.473   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304512 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=24 mControllerEnergyUsed=91 }
,10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:47.564  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:47.571  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:47.571  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:41:47.572  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2f5a80 removed from the list
10-07 06:41:47.572  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:47.572  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.572  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:41:47.581  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-07 06:41:47.582  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-07 06:41:47.586  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@acc4a08 Bundle[{}]
,10-07 06:41:47.588  5701  5747 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-07 06:41:47.588  5701  5747 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-07 06:41:47.589  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-07 06:41:47.591  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-07 06:41:47.592  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-07 06:41:47.595  5701  5747 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-07 06:41:47.606  5701  5747 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-07 06:41:47.608  5701  5747 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-07 06:41:47.608  5701  5747 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
10-07 06:41:47.611  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.611  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bcb8b9 added. We now have 3 listener(s)
,10-07 06:41:47.615  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 06:41:47.615  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.615  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:41:47.615  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.615  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb934fe added. We now have 4 listener(s)
,10-07 06:41:47.616  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.617  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 06:41:47.617  6038  6038 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
10-07 06:41:47.619  6038  6038 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 06:41:47.622  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:41:47.624  6038  6038 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 06:41:47.627  6038  6038 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:47.630  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:47.633  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:47.633  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 06:41:47.633  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.633  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56f9eac added. We now have 4 listener(s)
,10-07 06:41:47.635  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.635  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.635  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.636  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:41:47.636  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.636  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e72775 added. We now have 5 listener(s)
10-07 06:41:47.636  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.636  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:41:47.636  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:41:47.636  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:41:47.636  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.636  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:41:47.637  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.637  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.637  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.637  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bcb8b9 removed from the list
,10-07 06:41:47.637  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.637  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb934fe removed from the list
,10-07 06:41:47.638  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.638  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:47.638  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.639  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:41:47.639  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 06:41:47.641  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 06:41:47.641  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.641  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.641  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb934fe not in the list
10-07 06:41:47.641  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.641  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.643  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.643  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 06:41:47.643  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.643  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e72775 removed from the list
10-07 06:41:47.643  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.643  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.643  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.643  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.643  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.643  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56f9eac removed from the list
,10-07 06:41:47.644  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.644  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4efa30a added. We now have 3 listener(s)
10-07 06:41:47.646  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.646  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.646  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 06:41:47.646  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.647  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171a77b added. We now have 4 listener(s)
10-07 06:41:47.647  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 06:41:47.647  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:41:47.651  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:47.655  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:47.657  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:47.658  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:41:47.658  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.658  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0fc5f1 added. We now have 4 listener(s)
10-07 06:41:47.659  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.659  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.659  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.659  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:41:47.659  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.660  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ce5d6 added. We now have 5 listener(s)
10-07 06:41:47.660  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.660  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:41:47.660  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 06:41:47.660  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 06:41:47.660  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:41:47.660  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 06:41:47.661  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:47.663  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-07 06:41:47.663  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 06:41:47.668  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 06:41:47.668  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 06:41:47.669  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 06:41:47.672  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 06:41:47.672  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 06:41:47.672  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 06:41:47.672  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 06:41:47.672  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 06:41:47.673  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:41:47.676  5982  6011 D BtGatt.GattService: registerClient() - UUID=379248fc-b231-4999-ba00-55e81ac2fde3
10-07 06:41:47.677  5982  5998 D BtGatt.GattService: onClientRegistered() - UUID=379248fc-b231-4999-ba00-55e81ac2fde3, clientIf=5
10-07 06:41:47.677  5701  5712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-07 06:41:47.678  5982  6019 D BtGatt.GattService: start scan with filters
,10-07 06:41:47.680   930  3017 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-07 06:41:47.681   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-07 06:41:47.681   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:47.681  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 06:41:47.681  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 06:41:47.682  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:41:47.682  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 06:41:47.682  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 06:41:47.682  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 06:41:47.682  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 06:41:47.682  5982  6001 D BtGatt.ScanManager: handling starting scan
,10-07 06:41:47.684  5982  6001 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@531ec25
,10-07 06:41:47.686  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:41:47.686  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 06:41:47.686  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:41:47.687  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 06:41:47.689  5701  5747 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-07 06:41:47.689  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 06:41:47.689  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 06:41:47.689  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.689  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 06:41:47.689  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.689  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 06:41:47.689  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 06:41:47.689  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 06:41:47.689  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 06:41:47.690  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 06:41:47.690  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-07 06:41:47.691  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:41:47.692  5982  6023 D BtGatt.GattService: stopScan() - queue size =1
10-07 06:41:47.692   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
10-07 06:41:47.693  5982  6011 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 06:41:47.693  5982  5998 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 06:41:47.693  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.693  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 06:41:47.693  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 06:41:47.693  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 06:41:47.693  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:41:47.693  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 06:41:47.693  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 06:41:47.694  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 06:41:47.694  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 06:41:47.694  5982  6001 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-07 06:41:47.695  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:41:47.695  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 06:41:47.695  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 06:41:47.695  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-07 06:41:47.695  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 06:41:47.695  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.697  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:41:47.697  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:41:47.697  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:41:47.699  5982  5998 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 06:41:47.699  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.699  5982  6001 D BtGatt.ScanManager: Starting BLE batch scan
10-07 06:41:47.699  5982  6001 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 06:41:47.701  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:41:47.701  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:41:47.701  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:41:47.701  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.701  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.701  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.701  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.701  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.701  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4efa30a removed from the list
10-07 06:41:47.701  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:41:47.701  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171a77b removed from the list
10-07 06:41:47.701  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:47.701  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.702  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.702  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.703  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.703  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.703  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.703  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171a77b not in the list
10-07 06:41:47.703  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 06:41:47.703  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.704  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.704  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.705  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.705  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ce5d6 removed from the list
10-07 06:41:47.705  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.705  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.705  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.705  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 06:41:47.705  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.706  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0fc5f1 removed from the list
10-07 06:41:47.706  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.706  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a98962 added. We now have 3 listener(s)
10-07 06:41:47.708  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.708  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.708  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 06:41:47.708  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.709  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d78af3 added. We now have 4 listener(s)
10-07 06:41:47.709  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.709  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:41:47.710  5982  5998 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 06:41:47.710  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.712  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:41:47.715  5982  5998 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 06:41:47.715  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:47.717  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:47.720  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:47.720  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:41:47.720  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.720  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a04229 added. We now have 4 listener(s)
10-07 06:41:47.721  5982  5998 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 06:41:47.721  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.721  5982  6001 D BtGatt.ScanManager: stopping BLe Batch
10-07 06:41:47.722  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.722  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.722  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.722  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 06:41:47.722  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.722  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51ad9ae added. We now have 5 listener(s)
10-07 06:41:47.722  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.722  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:41:47.723  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:41:47.723  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-07 06:41:47.723  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 06:41:47.723  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:41:47.723  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 06:41:47.723  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 06:41:47.726  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-07 06:41:47.727  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 06:41:47.727  5982  5998 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 06:41:47.727  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.727  5982  6001 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 06:41:47.727   930  3017 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
10-07 06:41:47.729  6038  6038 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
10-07 06:41:47.730  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 06:41:47.730  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 06:41:47.730  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 06:41:47.731  5982  5998 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 06:41:47.732  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.733  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 06:41:47.733  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 06:41:47.734  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 06:41:47.734  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 06:41:47.734  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-07 06:41:47.734  5701  5747 D BluetoothAdapter: STATE_ON
,10-07 06:41:47.736  5982  6009 D BtGatt.GattService: registerClient() - UUID=61b59d2e-926a-402d-862f-72287ae8d064
10-07 06:41:47.736  5982  5998 D BtGatt.GattService: onClientRegistered() - UUID=61b59d2e-926a-402d-862f-72287ae8d064, clientIf=5
,10-07 06:41:47.737  5701  5711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-07 06:41:47.737  5982  6023 D BtGatt.GattService: start scan with filters
10-07 06:41:47.739  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 06:41:47.739  5982  6001 D BtGatt.ScanManager: handling starting scan
10-07 06:41:47.739  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 06:41:47.739  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:41:47.739  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 06:41:47.739  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 06:41:47.739  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 06:41:47.739  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 06:41:47.741  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 06:41:47.741  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 06:41:47.741  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:41:47.742  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 06:41:47.745  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:41:47.745  5701  5747 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-07 06:41:47.745  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:41:47.745  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:41:47.745  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:41:47.745  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.745  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.745  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 06:41:47.745  5982  5998 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-07 06:41:47.745  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.745  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.745  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.745  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a98962 removed from the list
10-07 06:41:47.745  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.745  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d78af3 removed from the list
10-07 06:41:47.745  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:47.745  5982  6001 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 06:41:47.745  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.746  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.746  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-07 06:41:47.746  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.746  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.747  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.747  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.747  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.747  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d78af3 not in the list
,10-07 06:41:47.747  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 06:41:47.747  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 06:41:47.747  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 06:41:47.747  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 06:41:47.747  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-07 06:41:47.748  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:41:47.749  5982  6019 D BtGatt.GattService: stopScan() - queue size =1
10-07 06:41:47.749  5982  6011 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 06:41:47.750  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 06:41:47.750  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 06:41:47.750  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 06:41:47.750  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:41:47.750  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 06:41:47.750  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 06:41:47.750  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 06:41:47.750  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 06:41:47.751  5982  5998 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 06:41:47.751  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.751  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:41:47.751  5982  6001 D BtGatt.ScanManager: Starting BLE batch scan
,10-07 06:41:47.751  5982  6001 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 06:41:47.751  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 06:41:47.751  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 06:41:47.751  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 06:41:47.751  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 06:41:47.752  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.753  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.753  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.753  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.753  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:41:47.753  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51ad9ae removed from the list
10-07 06:41:47.753  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.753  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:41:47.753  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.753  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.753  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:41:47.753  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 06:41:47.753  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.753  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a04229 removed from the list
10-07 06:41:47.754  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.754  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3ee2ba added. We now have 3 listener(s)
10-07 06:41:47.755  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.755  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.755  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 06:41:47.755  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.755  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7656b added. We now have 4 listener(s)
10-07 06:41:47.755  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.755  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:41:47.757  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:41:47.760  5982  5998 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 06:41:47.760  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:47.761  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 06:41:47.764  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 06:41:47.764  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:41:47.764  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.764  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cd0d61 added. We now have 4 listener(s)
,10-07 06:41:47.764  5982  5998 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 06:41:47.765  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.765  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.766  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.766  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.766  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 06:41:47.766  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.766  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6687086 added. We now have 5 listener(s)
10-07 06:41:47.766  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.766  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.766  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:41:47.767  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 06:41:47.767  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 06:41:47.767  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 06:41:47.767  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-07 06:41:47.770  5701  5747 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-07 06:41:47.770  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 06:41:47.771  5982  5998 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 06:41:47.771  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.771  5982  6001 D BtGatt.ScanManager: stopping BLe Batch
,10-07 06:41:47.775  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 06:41:47.776  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 06:41:47.776  5982  5998 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 06:41:47.776  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.776  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 06:41:47.776  5982  6001 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 06:41:47.780  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 06:41:47.780  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-07 06:41:47.780  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 06:41:47.780  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 06:41:47.780  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 06:41:47.780  5982  5998 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 06:41:47.781  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:41:47.781  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.782  5982  6011 D BtGatt.GattService: registerClient() - UUID=a7819527-7b5f-4f5c-81da-74dee2843a22
,10-07 06:41:47.782  5982  5998 D BtGatt.GattService: onClientRegistered() - UUID=a7819527-7b5f-4f5c-81da-74dee2843a22, clientIf=5
10-07 06:41:47.783  5701  5711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 06:41:47.783  5982  5992 D BtGatt.GattService: start scan with filters
,10-07 06:41:47.785  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-07 06:41:47.785  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 06:41:47.785  5982  6001 D BtGatt.ScanManager: handling starting scan
10-07 06:41:47.785  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:41:47.785  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 06:41:47.785  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 06:41:47.785  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 06:41:47.785  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 06:41:47.787  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 06:41:47.787  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 06:41:47.787  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 06:41:47.788  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 06:41:47.789  5982  5998 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 06:41:47.789  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.789  5982  6001 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 06:41:47.791  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 06:41:47.791  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:41:47.791  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:41:47.791  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.791  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.791  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-07 06:41:47.791  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.791  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.791  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3ee2ba removed from the list
10-07 06:41:47.791  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 06:41:47.792  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7656b removed from the list
10-07 06:41:47.792  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:47.792  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.793  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.793  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-07 06:41:47.793  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.793  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.794  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.794  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.794  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.794  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7656b not in the list
10-07 06:41:47.794  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-07 06:41:47.794  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 06:41:47.794  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 06:41:47.794  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 06:41:47.794  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 06:41:47.795  5701  5747 D BluetoothAdapter: STATE_ON
10-07 06:41:47.795  5982  6009 D BtGatt.GattService: stopScan() - queue size =1
10-07 06:41:47.795  5982  5998 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 06:41:47.795  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.795  5982  6001 D BtGatt.ScanManager: Starting BLE batch scan
,10-07 06:41:47.795  5982  6001 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 06:41:47.795  5982  6023 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 06:41:47.796  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 06:41:47.796  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 06:41:47.796  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 06:41:47.796  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 06:41:47.796  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 06:41:47.796  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 06:41:47.796  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 06:41:47.796  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 06:41:47.797  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:41:47.797  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 06:41:47.797  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-07 06:41:47.797  5701  5747 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 06:41:47.797  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 06:41:47.797  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.798  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.798  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.798  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.798  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:41:47.798  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6687086 removed from the list
10-07 06:41:47.798  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 06:41:47.798  5701  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 06:41:47.798  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.798  5701  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 06:41:47.798  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.798  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.798  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.798  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cd0d61 removed from the list
10-07 06:41:47.799  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.799  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b0f12 added. We now have 3 listener(s)
,10-07 06:41:47.801  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.801  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.802  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 06:41:47.802  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.802  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7916e3 added. We now have 4 listener(s)
10-07 06:41:47.802  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.803  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 06:41:47.805  5982  5998 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 06:41:47.805  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.806  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 06:41:47.809  5701  5747 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 06:41:47.809  5982  5998 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 06:41:47.810  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:47.811  5701  5747 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 06:41:47.811  5701  5747 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 06:41:47.811  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 06:41:47.811  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f10799 added. We now have 4 listener(s)
,10-07 06:41:47.812  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.812  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 06:41:47.812  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 06:41:47.812  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 06:41:47.813  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 06:41:47.813  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8470a5e added. We now have 5 listener(s)
10-07 06:41:47.813  5701  5747 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 06:41:47.813  5701  5747 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 06:41:47.813  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:41:47.813  5701  5747 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 06:41:47.813  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 06:41:47.813  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.813  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 06:41:47.813  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 06:41:47.813  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.813  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b0f12 removed from the list
10-07 06:41:47.813  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.813  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 06:41:47.813  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7916e3 removed from the list
10-07 06:41:47.814  5701  5747 D io.jxcore.node.ConnectivityMonitor: stop
10-07 06:41:47.814  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.814  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.814  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.815  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.815  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.816  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.816  5701  5747 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7916e3 not in the list
10-07 06:41:47.816  5982  5998 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-07 06:41:47.816  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.816  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.816  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.816  5982  6001 D BtGatt.ScanManager: stopping BLe Batch
,10-07 06:41:47.817  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 06:41:47.817  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 06:41:47.817  5701  5747 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 06:41:47.817  5701  5747 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8470a5e removed from the list
10-07 06:41:47.817  5701  5747 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 06:41:47.817  5701  5747 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 06:41:47.817  5701  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 06:41:47.818  5701  5747 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 06:41:47.818  5701  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 06:41:47.818  5701  5747 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f10799 removed from the list
,10-07 06:41:47.818  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-07 06:41:47.819  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-07 06:41:47.819  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-07 06:41:47.819  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 06:41:47.819  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-07 06:41:47.819  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-07 06:41:47.820  5982  5998 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 06:41:47.820  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 06:41:47.820  5982  6001 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 06:41:47.824  5982  5998 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-07 06:41:47.824  5982  5998 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 06:41:48.196  6038  6038 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-07 06:41:48.198  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 06:41:48.233  6038  6038 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-07 06:41:48.234  6038  6038 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-07 06:41:48.243   930  3017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 06:41:48.243   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-07 06:41:48.243   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-07 06:41:48.254  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 06:41:48.260   930  3017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 06:41:48.274   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:48.280   930  3017 D WifiStateMachine: Start Dhcp Watchdog 3
,10-07 06:41:48.286   930  6043 D DhcpClient: Receive thread started
,10-07 06:41:48.291   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-07 06:41:48.291   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-07 06:41:48.291   930  3019 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
10-07 06:41:48.299  5701  5701 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 06:41:48.372   930  3017 E native  : do suspend false
,10-07 06:41:48.383   930  6042 D DhcpClient: Broadcasting DHCPDISCOVER
,10-07 06:41:48.394   930  6043 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,10-07 06:41:48.395   930  6042 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,10-07 06:41:48.396   930  6042 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-07 06:41:48.414   930  6043 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-07 06:41:48.414   930  6042 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-07 06:41:48.417   508   921 D CommandListener: Setting iface cfg
,10-07 06:41:48.421   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-07 06:41:48.429   930  6042 D DhcpClient: Scheduling renewal in 86399s
,10-07 06:41:48.439   930  3017 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-07 06:41:48.441   930  3017 D WifiConfigStore: No blacklist allowed without epno enabled
10-07 06:41:48.442   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-07 06:41:48.444   930  3019 D ConnectivityService: Adding iface wlan0 to network 102
,10-07 06:41:48.451   930  3017 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-07 06:41:48.494   930  3019 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-07 06:41:48.494   930  3019 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-07 06:41:48.498   930  3019 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-07 06:41:48.501   930  3019 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-07 06:41:48.504   930  3019 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-07 06:41:48.513   930  3019 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 06:41:48.518   930  3019 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-07 06:41:48.518   930  3019 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-07 06:41:48.518   930  3019 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-07 06:41:48.518   930  3019 D ConnectivityService:    accepting network in place of null
,10-07 06:41:48.518   930  3017 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-07 06:41:48.518   930  3017 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 06:41:48.519   930  3019 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 06:41:48.528   930  6041 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308568, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-07 06:41:48.542   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:48.563   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 06:41:48.567   930  3019 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-07 06:41:48.567  3820  3961 W QCNEJ   : |CORE| network available: 102
10-07 06:41:48.567   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-07 06:41:48.568   930  3019 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-07 06:41:48.570   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-07 06:41:48.570  3820  3961 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-07 06:41:48.572  3820  3961 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-07 06:41:48.572  3820  3961 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:48.578  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 06:41:48.580  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 06:41:48.584  5701  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 06:41:48.585  5095  5119 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-07 06:41:48.586  3795  3795 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 06:41:48.587  5701  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 06:41:48.585  5095  5119 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 06:41:48.587  5095  5119 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-07 06:41:48.587  5095  5119 E SarControlService: no key has been found,reset the power
10-07 06:41:48.587  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-07 06:41:48.588  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-07 06:41:48.588  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 06:41:48.588  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:48.588  5120  5120 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 06:41:48.589  5095  5132 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 06:41:48.590  5095  5132 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 06:41:48.590  5095  5132 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 06:41:48.590  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 06:41:48.590  5120  5120 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 06:41:48.595  4986  4986 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-07 06:41:48.596  3795  3795 D SystemUpdateService: onCreate
10-07 06:41:48.597  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000f003000000000000ffffffff]
10-07 06:41:48.597  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:48.597  5120  5134 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,10-07 06:41:48.598  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:48.598  5095  5105 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 06:41:48.602  3795  3795 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-07 06:41:48.603  5120  5134 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1466c84 HexData = [00000000f103000000000000ffffffff]
10-07 06:41:48.603  5120  5134 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 06:41:48.603  5120  5134 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-07 06:41:48.603   930  6040 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-07 06:41:48.604  5120  5120 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 06:41:48.604  5095  5106 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-07 06:41:48.617  3795  3795 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-07 06:41:48.621  3795  5458 I iu.UploadsManager: num queued entries: 0
,10-07 06:41:48.622  3795  5458 I iu.UploadsManager: num updated entries: 0
10-07 06:41:48.622  3795  5458 I iu.SyncManager: NEXT; no task
,10-07 06:41:48.624  3795  6053 I SystemUpdateService: active receiver: enabled
,10-07 06:41:48.626  3795  3795 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 06:41:48.628  3795  3795 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 06:41:48.629  5833  5833 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 06:41:48.633  5833  5833 D SprintDMHelper: simOperator: 
,10-07 06:41:48.633  5833  5833 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 06:41:48.655  3795  6053 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 06:41:48.657   930  6040 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 07 Oct 2016 10:41:48 GMT], X-Android-Received-Millis=[1475836908656], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475836908630]}
,10-07 06:41:48.658   930  3019 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-07 06:41:48.658   930  3019 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-07 06:41:48.658   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-07 06:41:48.659   930  3019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-07 06:41:48.669  3795  6053 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-07 06:41:48.669  3795  6053 I SystemUpdateService: now status is 0 (complete)
10-07 06:41:48.669  3795  6053 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 06:41:48.669  3795  6053 I SystemUpdateService: file has been verified
10-07 06:41:48.669  3795  6053 I SystemUpdateService: OTA package size = 21989297
,10-07 06:41:48.675  3795  6053 I SystemUpdateService: showing system update notification
,10-07 06:41:48.686  3795  3795 D SystemUpdateService: onDestroy
,10-07 06:41:48.755  5069  6057 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-07 06:41:49.962  5701  6065 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 06:41:49.962  5701  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:41:50.751  5701  6065 W !!      : call onHalfStreamCopied
,10-07 06:41:50.751  5701  6065 I testCopyDataAndClose: closing input stream
,10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].,
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 06:41:51.522  5701  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-07 06:41:55.235  5701  6066 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:41:55.235  5701  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:41:56.524   930  3019 D ConnectivityService: handlePromptUnvalidated 102
,10-07 06:41:57.236  5701  5747 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-07 06:41:57.236  5701  5747 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:41:57.236  5701  5747 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-07 06:41:57.373  5701  6067 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 06:41:57.373  5701  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:41:57.408  5701  6066 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-07 06:41:57.408  5701  6066 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:41:57.408  5701  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 06:41:59.012  5701  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-07 06:41:59.475   930  3017 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-07 06:42:02.727  5701  6068 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:42:02.727  5701  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 06:42:02.728  5701  6068 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 06:42:02.729  5701  6068 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-07 06:42:02.729  5701  6068 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:42:02.729  5701  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-07 06:42:02.730  5701  5747 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-07 06:42:02.733  5701  6069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:42:02.733  5701  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 06:42:02.733  5701  6069 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
10-07 06:42:02.734  5701  6069 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:42:02.734  5701  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-07 06:42:02.734  5701  6069 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-07 06:42:02.734  5701  6069 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 06:42:02.734  5701  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-07 06:42:02.738  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-07 06:42:02.738  5701  5747 I jxcore-log: 
10-07 06:42:02.738  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-07 06:42:02.738  5701  5747 I jxcore-log: 
10-07 06:42:02.738  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-07 06:42:02.738  5701  5747 I jxcore-log: 
10-07 06:42:02.739  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-07 06:42:02.739  5701  5747 I jxcore-log: 
10-07 06:42:02.739  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Total duration:  90693'
10-07 06:42:02.739  5701  5747 I jxcore-log: 
,10-07 06:42:02.741  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-07 06:42:02.741  5701  5747 I jxcore-log: 
,10-07 06:42:02.745  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.745  5701  5747 I jxcore-log: 
,10-07 06:42:02.746  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.746  5701  5747 I jxcore-log: 
10-07 06:42:02.747  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.747  5701  5747 I jxcore-log: 
10-07 06:42:02.747  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.747  5701  5747 I jxcore-log: 
10-07 06:42:02.747  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-07 06:42:02.747  5701  5747 I jxcore-log: 
10-07 06:42:02.748  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 06:42:02.748  5701  5747 I jxcore-log: 
,10-07 06:42:02.748  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.748  5701  5747 I jxcore-log: 
,10-07 06:42:02.748  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.748  5701  5747 I jxcore-log: 
10-07 06:42:02.749  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-07 06:42:02.749  5701  5747 I jxcore-log: 
,10-07 06:42:02.749  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 06:42:02.749  5701  5747 I jxcore-log: 
,10-07 06:42:02.749  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 06:42:02.749  5701  5747 I jxcore-log: 
10-07 06:42:02.749  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.749  5701  5747 I jxcore-log: 
10-07 06:42:02.750  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.750  5701  5747 I jxcore-log: 
10-07 06:42:02.750  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.750  5701  5747 I jxcore-log: 
10-07 06:42:02.750  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.750  5701  5747 I jxcore-log: 
,10-07 06:42:02.750  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.750  5701  5747 I jxcore-log: 
10-07 06:42:02.751  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.751  5701  5747 I jxcore-log: 
10-07 06:42:02.751  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.751  5701  5747 I jxcore-log: 
10-07 06:42:02.751  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.751  5701  5747 I jxcore-log: 
10-07 06:42:02.751  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.751  5701  5747 I jxcore-log: 
10-07 06:42:02.752  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.752  5701  5747 I jxcore-log: 
,10-07 06:42:02.752  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.752  5701  5747 I jxcore-log: 
10-07 06:42:02.752  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.752  5701  5747 I jxcore-log: 
10-07 06:42:02.754  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.754  5701  5747 I jxcore-log: 
,10-07 06:42:02.754  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.754  5701  5747 I jxcore-log: 
10-07 06:42:02.754  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.754  5701  5747 I jxcore-log: 
10-07 06:42:02.755  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.755  5701  5747 I jxcore-log: 
10-07 06:42:02.755  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.755  5701  5747 I jxcore-log: 
10-07 06:42:02.755  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.755  5701  5747 I jxcore-log: 
10-07 06:42:02.755  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.755  5701  5747 I jxcore-log: 
10-07 06:42:02.756  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.756  5701  5747 I jxcore-log: 
10-07 06:42:02.756  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.756  5701  5747 I jxcore-log: 
,10-07 06:42:02.756  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.756  5701  5747 I jxcore-log: 
10-07 06:42:02.756  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.756  5701  5747 I jxcore-log: 
10-07 06:42:02.757  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.757  5701  5747 I jxcore-log: 
10-07 06:42:02.757  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.757  5701  5747 I jxcore-log: 
10-07 06:42:02.757  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.757  5701  5747 I jxcore-log: 
10-07 06:42:02.757  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 06:42:02.757  5701  5747 I jxcore-log: 
10-07 06:42:02.757  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.757  5701  5747 I jxcore-log: 
,10-07 06:42:02.758  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.758  5701  5747 I jxcore-log: 
10-07 06:42:02.758  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.758  5701  5747 I jxcore-log: 
10-07 06:42:02.758  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.758  5701  5747 I jxcore-log: 
10-07 06:42:02.758  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.758  5701  5747 I jxcore-log: 
10-07 06:42:02.758  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 06:42:02.758  5701  5747 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-07 06:42:02.759  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.759  5701  5747 I jxcore-log: 
10-07 06:42:02.759  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.759  5701  5747 I jxcore-log: 
10-07 06:42:02.759  5701  5747 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 06:42:02.759  5701  5747 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-07 06:42:02.759  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 06:42:02.759  5701  5747 I jxcore-log: 
10-07 06:42:02.760  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 06:42:02.760  5701  5747 I jxcore-log: 
10-07 06:42:02.760  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 06:42:02.760  5701  5747 I jxcore-log: 
10-07 06:42:02.760  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 06:42:02.760  5701  5747 I jxcore-log: 
10-07 06:42:02.760  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.760  5701  5747 I jxcore-log: 
10-07 06:42:02.760  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 06:42:02.760  5701  5747 I jxcore-log: 
10-07 06:42:02.766  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-07 06:42:02.766  5701  5747 I jxcore-log: 
10-07 06:42:02.766  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - WARN testUtils: 'myNameCallback not set!'
10-07 06:42:02.766  5701  5747 I jxcore-log: 
10-07 06:42:02.767  5701  5747 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-07 06:42:02.768  5701  5747 I jxcore-log: 2016-10-07 10:42:02 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-07 06:42:02.768  5701  5747 I jxcore-log: 
,10-07 06:42:02.770  5701  5701 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-07 06:42:04.804  5701  5747 I jxcore-log: 2016-10-07 10:42:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-07 06:42:04.804  5701  5747 I jxcore-log: 
,10-07 06:42:05.141  5701  5747 I jxcore-log: 2016-10-07 10:42:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-07 06:42:05.141  5701  5747 I jxcore-log: 
,10-07 06:42:05.155  5701  5747 I jxcore-log: 2016-10-07 10:42:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-07 06:42:05.155  5701  5747 I jxcore-log: 
,10-07 06:42:06.258  5701  5747 I jxcore-log: 2016-10-07 10:42:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-07 06:42:06.258  5701  5747 I jxcore-log: 
,10-07 06:42:06.419  5701  5747 I jxcore-log: 2016-10-07 10:42:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-07 06:42:06.419  5701  5747 I jxcore-log: 
,10-07 06:42:06.423  5701  5747 I jxcore-log: 2016-10-07 10:42:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-07 06:42:06.423  5701  5747 I jxcore-log: 
,10-07 06:42:06.425   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 06:42:06.428  5701  5747 I jxcore-log: 2016-10-07 10:42:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-07 06:42:06.428  5701  5747 I jxcore-log: 
,10-07 06:42:06.966  5701  5747 I jxcore-log: 2016-10-07 10:42:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-07 06:42:06.966  5701  5747 I jxcore-log: 
,10-07 06:42:07.018  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-07 06:42:07.018  5701  5747 I jxcore-log: 
,10-07 06:42:07.030  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-07 06:42:07.030  5701  5747 I jxcore-log: 
,10-07 06:42:07.034  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-07 06:42:07.034  5701  5747 I jxcore-log: 
,10-07 06:42:07.312  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-07 06:42:07.312  5701  5747 I jxcore-log: 
,10-07 06:42:07.436  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-07 06:42:07.436  5701  5747 I jxcore-log: 
,10-07 06:42:07.670  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-07 06:42:07.670  5701  5747 I jxcore-log: 
,10-07 06:42:07.681  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-07 06:42:07.681  5701  5747 I jxcore-log: 
,10-07 06:42:07.685  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-07 06:42:07.685  5701  5747 I jxcore-log: 
,10-07 06:42:07.821  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-07 06:42:07.821  5701  5747 I jxcore-log: 
,10-07 06:42:07.828  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-07 06:42:07.828  5701  5747 I jxcore-log: 
,10-07 06:42:07.855  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-07 06:42:07.855  5701  5747 I jxcore-log: 
,10-07 06:42:07.889  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-07 06:42:07.889  5701  5747 I jxcore-log: 
,10-07 06:42:07.897  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-07 06:42:07.897  5701  5747 I jxcore-log: 
,10-07 06:42:07.903  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-07 06:42:07.903  5701  5747 I jxcore-log: 
,10-07 06:42:07.918  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-07 06:42:07.918  5701  5747 I jxcore-log: 
,10-07 06:42:07.923  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-07 06:42:07.923  5701  5747 I jxcore-log: 
,10-07 06:42:07.929  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-07 06:42:07.929  5701  5747 I jxcore-log: 
,10-07 06:42:07.934  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-07 06:42:07.934  5701  5747 I jxcore-log: 
,10-07 06:42:07.947  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-07 06:42:07.947  5701  5747 I jxcore-log: 
,10-07 06:42:07.968  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-07 06:42:07.968  5701  5747 I jxcore-log: 
,10-07 06:42:07.977  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-07 06:42:07.977  5701  5747 I jxcore-log: 
,10-07 06:42:07.988  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-07 06:42:07.988  5701  5747 I jxcore-log: 
,10-07 06:42:07.997  5701  5747 I jxcore-log: 2016-10-07 10:42:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-07 06:42:07.997  5701  5747 I jxcore-log: 
,10-07 06:42:08.009  5701  5747 I jxcore-log: 2016-10-07 10:42:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-07 06:42:08.009  5701  5747 I jxcore-log: 
,10-07 06:42:08.019  5701  5747 I jxcore-log: 2016-10-07 10:42:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-07 06:42:08.019  5701  5747 I jxcore-log: 
,10-07 06:42:08.024  5701  5747 I jxcore-log: 2016-10-07 10:42:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-07 06:42:08.024  5701  5747 I jxcore-log: 
,10-07 06:42:08.042  5701  5747 I jxcore-log: 2016-10-07 10:42:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUpdatingAdvertisingAndParallelDataTransferCoordinated.js'
10-07 06:42:08.042  5701  5747 I jxcore-log: 
,10-07 06:42:08.138  5701  5747 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-07 06:42:08.139  5701  5747 I jxcore-log: 2016-10-07 10:42:08 - INFO testUtils: 'BLE multiple advertisement supported'
10-07 06:42:08.139  5701  5747 I jxcore-log: 
,10-07 06:42:08.237  5701  5747 I jxcore-log: 2016-10-07 10:42:08 - DEBUG CoordinatedClient: 'connected to the test server'
10-07 06:42:08.237  5701  5747 I jxcore-log: 
,10-07 06:42:08.749  5701  5747 I jxcore-log: TAP version 13
10-07 06:42:08.749  5701  5747 I jxcore-log: 
,10-07 06:42:08.792  5701  5747 I jxcore-log: # setup
10-07 06:42:08.792  5701  5747 I jxcore-log: 
,10-07 06:42:08.899   545   545 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-07 06:42:08.899   545   545 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-07 06:42:09.444   930  3019 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 06:42:09.744  5701  5747 I jxcore-log: # calling createNativeListener directly rejects
10-07 06:42:09.744  5701  5747 I jxcore-log: 
,10-07 06:42:09.880  5701  5747 I jxcore-log: 2016-10-07 10:42:09 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:09.880  5701  5747 I jxcore-log: 
,10-07 06:42:09.886  5701  5747 I jxcore-log: 2016-10-07 10:42:09 - DEBUG createNativeListener: 'listening 45133'
10-07 06:42:09.886  5701  5747 I jxcore-log: 
,10-07 06:42:09.893  5701  5747 I jxcore-log: ok 1 Should throw
10-07 06:42:09.893  5701  5747 I jxcore-log: 
,10-07 06:42:09.903  5701  5747 I jxcore-log: # teardown
10-07 06:42:09.903  5701  5747 I jxcore-log: 
,10-07 06:42:10.055  5701  5747 I jxcore-log: # setup
10-07 06:42:10.055  5701  5747 I jxcore-log: 
,10-07 06:42:10.197  5701  5747 I jxcore-log: # emits incomingConnectionState
10-07 06:42:10.197  5701  5747 I jxcore-log: 
,10-07 06:42:10.678  5701  5747 I jxcore-log: 2016-10-07 10:42:10 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:10.678  5701  5747 I jxcore-log: 
,10-07 06:42:10.683  5701  5747 I jxcore-log: 2016-10-07 10:42:10 - DEBUG createNativeListener: 'listening 46687'
10-07 06:42:10.683  5701  5747 I jxcore-log: 
,10-07 06:42:10.694  5701  5747 I jxcore-log: 2016-10-07 10:42:10 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:10.694  5701  5747 I jxcore-log: 
,10-07 06:42:10.697  5701  5747 I jxcore-log: 2016-10-07 10:42:10 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:10.697  5701  5747 I jxcore-log: 
,10-07 06:42:10.707  5701  5747 I jxcore-log: 2016-10-07 10:42:10 - DEBUG createNativeListener: 'new mux'
10-07 06:42:10.707  5701  5747 I jxcore-log: 
,10-07 06:42:10.712  5701  5747 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-07 06:42:10.712  5701  5747 I jxcore-log: 
,10-07 06:42:10.729  5701  5747 I jxcore-log: 2016-10-07 10:42:10 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:10.729  5701  5747 I jxcore-log: 
,10-07 06:42:10.730  5701  5747 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-07 06:42:10.730  5701  5747 I jxcore-log: 
,10-07 06:42:10.737  5701  5747 I jxcore-log: # teardown
10-07 06:42:10.737  5701  5747 I jxcore-log: 
,10-07 06:42:12.444  5701  5747 I jxcore-log: # setup
10-07 06:42:12.444  5701  5747 I jxcore-log: 
,10-07 06:42:12.619  5701  5747 I jxcore-log: # emits routerPortConnectionFailed
10-07 06:42:12.619  5701  5747 I jxcore-log: 
,10-07 06:42:13.663  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:13.663  5701  5747 I jxcore-log: 
,10-07 06:42:13.668  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'listening 49424'
10-07 06:42:13.668  5701  5747 I jxcore-log: 
,10-07 06:42:13.676  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:13.676  5701  5747 I jxcore-log: 
,10-07 06:42:13.678  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:13.678  5701  5747 I jxcore-log: 
,10-07 06:42:13.680  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'new mux'
10-07 06:42:13.680  5701  5747 I jxcore-log: 
,10-07 06:42:13.708  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:13.708  5701  5747 I jxcore-log: 
,10-07 06:42:13.711  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:13.711  5701  5747 I jxcore-log: 
,10-07 06:42:13.715  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: ' $c@net.js:837:7
10-07 06:42:13.715  5701  5747 I jxcore-log: $09@net.js:829:13
10-07 06:42:13.715  5701  5747 I jxcore-log: '
10-07 06:42:13.715  5701  5747 I jxcore-log: 
10-07 06:42:13.716  5701  5747 I jxcore-log: ok 4 tried to connect to right port
10-07 06:42:13.716  5701  5747 I jxcore-log: 
,10-07 06:42:13.717  5701  5747 I jxcore-log: ok 5 failed due to refused connection
10-07 06:42:13.717  5701  5747 I jxcore-log: 
,10-07 06:42:13.718  5701  5747 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-07 06:42:13.718  5701  5747 I jxcore-log: 
10-07 06:42:13.723  5701  5747 I jxcore-log: # teardown
10-07 06:42:13.723  5701  5747 I jxcore-log: 
,10-07 06:42:13.725  5701  5747 I jxcore-log: 2016-10-07 10:42:13 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:13.725  5701  5747 I jxcore-log: 
,10-07 06:42:14.575  5701  5747 I jxcore-log: 2016-10-07 10:42:14 - DEBUG createNativeListener: 'mux close'
10-07 06:42:14.575  5701  5747 I jxcore-log: 
,10-07 06:42:14.584  5701  5747 I jxcore-log: 2016-10-07 10:42:14 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:14.584  5701  5747 I jxcore-log: 
,10-07 06:42:14.602  5701  5747 I jxcore-log: # setup
10-07 06:42:14.602  5701  5747 I jxcore-log: 
,10-07 06:42:14.776  5701  5747 I jxcore-log: # native server connections all up
10-07 06:42:14.776  5701  5747 I jxcore-log: 
,10-07 06:42:15.698  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:15.698  5701  5747 I jxcore-log: 
,10-07 06:42:15.703  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'listening 43193'
10-07 06:42:15.703  5701  5747 I jxcore-log: 
,10-07 06:42:15.712  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:15.712  5701  5747 I jxcore-log: 
,10-07 06:42:15.713  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:15.713  5701  5747 I jxcore-log: 
,10-07 06:42:15.715  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'new mux'
10-07 06:42:15.715  5701  5747 I jxcore-log: 
,10-07 06:42:15.741  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:15.741  5701  5747 I jxcore-log: 
,10-07 06:42:15.744  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:15.744  5701  5747 I jxcore-log: 
,10-07 06:42:15.747  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:15.747  5701  5747 I jxcore-log: 
,10-07 06:42:15.749  5701  5747 I jxcore-log: 2016-10-07 10:42:15 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:15.749  5701  5747 I jxcore-log: 
,10-07 06:42:15.769  5701  5747 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-07 06:42:15.769  5701  5747 I jxcore-log: 
,10-07 06:42:15.770  5701  5747 I jxcore-log: ok 8 Send/recvd #1 should be same
10-07 06:42:15.770  5701  5747 I jxcore-log: 
,10-07 06:42:15.773  5701  5747 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-07 06:42:15.773  5701  5747 I jxcore-log: 
,10-07 06:42:15.773  5701  5747 I jxcore-log: ok 10 Send/recvd #2 should be same
10-07 06:42:15.773  5701  5747 I jxcore-log: 
,10-07 06:42:15.776  5701  5747 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-07 06:42:15.776  5701  5747 I jxcore-log: 
,10-07 06:42:15.786  5701  5747 I jxcore-log: # teardown
10-07 06:42:15.786  5701  5747 I jxcore-log: 
,10-07 06:42:16.203  5701  5747 I jxcore-log: 2016-10-07 10:42:16 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:16.203  5701  5747 I jxcore-log: 
,10-07 06:42:16.206  5701  5747 I jxcore-log: 2016-10-07 10:42:16 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:16.206  5701  5747 I jxcore-log: 
,10-07 06:42:16.209  5701  5747 I jxcore-log: 2016-10-07 10:42:16 - DEBUG createNativeListener: 'mux close'
10-07 06:42:16.209  5701  5747 I jxcore-log: 
,10-07 06:42:16.216  5701  5747 I jxcore-log: 2016-10-07 10:42:16 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:16.216  5701  5747 I jxcore-log: 
,10-07 06:42:16.230  5701  5747 I jxcore-log: # setup
10-07 06:42:16.230  5701  5747 I jxcore-log: 
,10-07 06:42:17.131  5701  5747 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-07 06:42:17.131  5701  5747 I jxcore-log: 
,10-07 06:42:17.845  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:17.845  5701  5747 I jxcore-log: 
,10-07 06:42:17.851  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'listening 40742'
10-07 06:42:17.851  5701  5747 I jxcore-log: 
,10-07 06:42:17.858  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:17.858  5701  5747 I jxcore-log: 
,10-07 06:42:17.860  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:17.860  5701  5747 I jxcore-log: 
,10-07 06:42:17.864  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'new mux'
10-07 06:42:17.864  5701  5747 I jxcore-log: 
,10-07 06:42:17.876  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:17.876  5701  5747 I jxcore-log: 
,10-07 06:42:17.880  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:17.880  5701  5747 I jxcore-log: 
,10-07 06:42:17.892  5701  5747 I jxcore-log: 2016-10-07 10:42:17 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:17.892  5701  5747 I jxcore-log: 
,10-07 06:42:17.905  5701  5747 I jxcore-log: ok 12 socket shouldn't close until after stream
10-07 06:42:17.905  5701  5747 I jxcore-log: 
,10-07 06:42:17.905  5701  5747 I jxcore-log: ok 13 incoming remains open
10-07 06:42:17.905  5701  5747 I jxcore-log: 
,10-07 06:42:17.910  5701  5747 I jxcore-log: # teardown
10-07 06:42:17.910  5701  5747 I jxcore-log: 
,10-07 06:42:18.247  5701  5747 I jxcore-log: 2016-10-07 10:42:18 - DEBUG createNativeListener: 'mux close'
10-07 06:42:18.247  5701  5747 I jxcore-log: 
,10-07 06:42:18.255  5701  5747 I jxcore-log: 2016-10-07 10:42:18 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:18.255  5701  5747 I jxcore-log: 
,10-07 06:42:18.265  5701  5747 I jxcore-log: # setup
10-07 06:42:18.265  5701  5747 I jxcore-log: 
,10-07 06:42:19.085  5701  5747 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-07 06:42:19.085  5701  5747 I jxcore-log: 
,10-07 06:42:19.474  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:19.474  5701  5747 I jxcore-log: 
,10-07 06:42:19.480  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'listening 43321'
10-07 06:42:19.480  5701  5747 I jxcore-log: 
,10-07 06:42:19.489  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:19.489  5701  5747 I jxcore-log: 
,10-07 06:42:19.491  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:19.491  5701  5747 I jxcore-log: 
,10-07 06:42:19.493  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'new mux'
10-07 06:42:19.493  5701  5747 I jxcore-log: 
,10-07 06:42:19.506  5701  5747 I jxcore-log: ok 14 we should not have gotten an error
10-07 06:42:19.506  5701  5747 I jxcore-log: 
,10-07 06:42:19.512  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:19.512  5701  5747 I jxcore-log: 
,10-07 06:42:19.516  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:19.516  5701  5747 I jxcore-log: 
,10-07 06:42:19.525  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:19.525  5701  5747 I jxcore-log: 
,10-07 06:42:19.528  5701  5747 I jxcore-log: 2016-10-07 10:42:19 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:19.528  5701  5747 I jxcore-log: 
,10-07 06:42:19.536  5701  5747 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-07 06:42:19.536  5701  5747 I jxcore-log: 
,10-07 06:42:19.536  5701  5747 I jxcore-log: ok 16 incoming is cleaned up
10-07 06:42:19.536  5701  5747 I jxcore-log: 
,10-07 06:42:19.540  5701  5747 I jxcore-log: # teardown
10-07 06:42:19.540  5701  5747 I jxcore-log: 
,10-07 06:42:20.409  5701  5747 I jxcore-log: # setup
10-07 06:42:20.409  5701  5747 I jxcore-log: 
,10-07 06:42:20.813  5701  5747 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-07 06:42:20.813  5701  5747 I jxcore-log: 
,10-07 06:42:21.520  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:21.520  5701  5747 I jxcore-log: 
,10-07 06:42:21.525  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'listening 39182'
10-07 06:42:21.525  5701  5747 I jxcore-log: 
,10-07 06:42:21.534  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:21.534  5701  5747 I jxcore-log: 
,10-07 06:42:21.536  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:21.536  5701  5747 I jxcore-log: 
,10-07 06:42:21.539  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'new mux'
10-07 06:42:21.539  5701  5747 I jxcore-log: 
,10-07 06:42:21.553  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:21.553  5701  5747 I jxcore-log: 
,10-07 06:42:21.556  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:21.556  5701  5747 I jxcore-log: 
,10-07 06:42:21.569  5701  5747 I jxcore-log: 2016-10-07 10:42:21 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:21.569  5701  5747 I jxcore-log: 
,10-07 06:42:21.578  5701  5747 I jxcore-log: ok 17 stream was closed
10-07 06:42:21.578  5701  5747 I jxcore-log: 
,10-07 06:42:21.578  5701  5747 I jxcore-log: ok 18 incoming should survive
10-07 06:42:21.578  5701  5747 I jxcore-log: 
10-07 06:42:21.578  5701  5747 I jxcore-log: ok 19 mux should have no streams
10-07 06:42:21.578  5701  5747 I jxcore-log: 
,10-07 06:42:21.584  5701  5747 I jxcore-log: # teardown
10-07 06:42:21.584  5701  5747 I jxcore-log: 
,10-07 06:42:22.033  5701  5747 I jxcore-log: 2016-10-07 10:42:22 - DEBUG createNativeListener: 'mux close'
10-07 06:42:22.033  5701  5747 I jxcore-log: 
,10-07 06:42:22.051  5701  5747 I jxcore-log: 2016-10-07 10:42:22 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:22.051  5701  5747 I jxcore-log: 
,10-07 06:42:22.065  5701  5747 I jxcore-log: # setup
10-07 06:42:22.065  5701  5747 I jxcore-log: 
,10-07 06:42:22.971  5701  5747 I jxcore-log: # native server - closing the whole server cleans everything up
10-07 06:42:22.971  5701  5747 I jxcore-log: 
,10-07 06:42:23.216  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:23.216  5701  5747 I jxcore-log: 
,10-07 06:42:23.222  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'listening 44022'
10-07 06:42:23.222  5701  5747 I jxcore-log: 
,10-07 06:42:23.229  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:23.229  5701  5747 I jxcore-log: 
,10-07 06:42:23.234  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:23.234  5701  5747 I jxcore-log: 
,10-07 06:42:23.236  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'new mux'
10-07 06:42:23.236  5701  5747 I jxcore-log: 
,10-07 06:42:23.245  5701  5747 I jxcore-log: ok 20 we should not have gotten an error
10-07 06:42:23.245  5701  5747 I jxcore-log: 
,10-07 06:42:23.251  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:23.251  5701  5747 I jxcore-log: 
,10-07 06:42:23.254  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:23.254  5701  5747 I jxcore-log: 
,10-07 06:42:23.263  5701  5747 I jxcore-log: ok 21 Buffers are identical
10-07 06:42:23.263  5701  5747 I jxcore-log: 
,10-07 06:42:23.266  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:23.266  5701  5747 I jxcore-log: 
,10-07 06:42:23.269  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'mux close'
10-07 06:42:23.269  5701  5747 I jxcore-log: 
,10-07 06:42:23.271  5701  5747 I jxcore-log: ok 22 native server is nulled out
10-07 06:42:23.271  5701  5747 I jxcore-log: 
,10-07 06:42:23.271  5701  5747 I jxcore-log: ok 23 native server should be closed
10-07 06:42:23.271  5701  5747 I jxcore-log: 
10-07 06:42:23.271  5701  5747 I jxcore-log: ok 24 incoming has been removed
10-07 06:42:23.271  5701  5747 I jxcore-log: 
,10-07 06:42:23.272  5701  5747 I jxcore-log: ok 25 Incoming should be done
10-07 06:42:23.272  5701  5747 I jxcore-log: 
10-07 06:42:23.272  5701  5747 I jxcore-log: ok 26 The mux object should be closed
10-07 06:42:23.272  5701  5747 I jxcore-log: 
10-07 06:42:23.272  5701  5747 I jxcore-log: ok 27 The mux stream should be closed
10-07 06:42:23.272  5701  5747 I jxcore-log: 
10-07 06:42:23.273  5701  5747 I jxcore-log: 2016-10-07 10:42:23 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:23.273  5701  5747 I jxcore-log: 
,10-07 06:42:23.286  5701  5747 I jxcore-log: # teardown
10-07 06:42:23.286  5701  5747 I jxcore-log: 
,10-07 06:42:23.900   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:24.801  5701  5747 I jxcore-log: # setup
10-07 06:42:24.801  5701  5747 I jxcore-log: 
,10-07 06:42:24.901   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:25.642  5701  5747 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-07 06:42:25.642  5701  5747 I jxcore-log: 
,10-07 06:42:25.902   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:26.904   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:27.905   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:28.497   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 06:42:28.905   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-07 06:42:30.954  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:30.954  5701  5747 I jxcore-log: 
,10-07 06:42:30.959  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'listening 39936'
10-07 06:42:30.959  5701  5747 I jxcore-log: 
,10-07 06:42:30.985  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:30.985  5701  5747 I jxcore-log: 
,10-07 06:42:30.985  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:30.985  5701  5747 I jxcore-log: 
10-07 06:42:30.986  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'new mux'
10-07 06:42:30.986  5701  5747 I jxcore-log: 
,10-07 06:42:30.989  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:30.989  5701  5747 I jxcore-log: 
,10-07 06:42:30.990  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:30.990  5701  5747 I jxcore-log: 
10-07 06:42:30.991  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'new mux'
10-07 06:42:30.991  5701  5747 I jxcore-log: 
,10-07 06:42:30.994  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:30.994  5701  5747 I jxcore-log: 
,10-07 06:42:30.994  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:30.994  5701  5747 I jxcore-log: 
,10-07 06:42:30.996  5701  5747 I jxcore-log: 2016-10-07 10:42:30 - DEBUG createNativeListener: 'new mux'
10-07 06:42:30.996  5701  5747 I jxcore-log: 
,10-07 06:42:31.002  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.002  5701  5747 I jxcore-log: 
,10-07 06:42:31.003  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.003  5701  5747 I jxcore-log: 
,10-07 06:42:31.004  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.004  5701  5747 I jxcore-log: 
,10-07 06:42:31.008  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.008  5701  5747 I jxcore-log: 
,10-07 06:42:31.008  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.008  5701  5747 I jxcore-log: 
,10-07 06:42:31.009  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.009  5701  5747 I jxcore-log: 
,10-07 06:42:31.018  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.018  5701  5747 I jxcore-log: 
,10-07 06:42:31.019  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.019  5701  5747 I jxcore-log: 
,10-07 06:42:31.020  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.020  5701  5747 I jxcore-log: 
,10-07 06:42:31.022  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.022  5701  5747 I jxcore-log: 
,10-07 06:42:31.023  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.023  5701  5747 I jxcore-log: 
10-07 06:42:31.024  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.024  5701  5747 I jxcore-log: 
,10-07 06:42:31.026  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.026  5701  5747 I jxcore-log: 
,10-07 06:42:31.026  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.026  5701  5747 I jxcore-log: 
,10-07 06:42:31.027  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.027  5701  5747 I jxcore-log: 
,10-07 06:42:31.029  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.029  5701  5747 I jxcore-log: 
,10-07 06:42:31.030  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.030  5701  5747 I jxcore-log: 
,10-07 06:42:31.031  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.031  5701  5747 I jxcore-log: 
,10-07 06:42:31.032  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:31.032  5701  5747 I jxcore-log: 
,10-07 06:42:31.033  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:31.033  5701  5747 I jxcore-log: 
10-07 06:42:31.034  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new mux'
10-07 06:42:31.034  5701  5747 I jxcore-log: 
,10-07 06:42:31.091  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.091  5701  5747 I jxcore-log: 
,10-07 06:42:31.093  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.093  5701  5747 I jxcore-log: 
,10-07 06:42:31.095  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.095  5701  5747 I jxcore-log: 
10-07 06:42:31.096  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.096  5701  5747 I jxcore-log: 
,10-07 06:42:31.097  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.097  5701  5747 I jxcore-log: 
10-07 06:42:31.098  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.098  5701  5747 I jxcore-log: 
,10-07 06:42:31.099  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.099  5701  5747 I jxcore-log: 
,10-07 06:42:31.100  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.100  5701  5747 I jxcore-log: 
,10-07 06:42:31.102  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.102  5701  5747 I jxcore-log: 
,10-07 06:42:31.103  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.103  5701  5747 I jxcore-log: 
10-07 06:42:31.104  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.104  5701  5747 I jxcore-log: 
,10-07 06:42:31.104  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.104  5701  5747 I jxcore-log: 
,10-07 06:42:31.105  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.105  5701  5747 I jxcore-log: 
10-07 06:42:31.106  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.106  5701  5747 I jxcore-log: 
,10-07 06:42:31.107  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.107  5701  5747 I jxcore-log: 
10-07 06:42:31.108  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.108  5701  5747 I jxcore-log: 
,10-07 06:42:31.109  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.109  5701  5747 I jxcore-log: 
,10-07 06:42:31.110  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.110  5701  5747 I jxcore-log: 
10-07 06:42:31.111  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.111  5701  5747 I jxcore-log: 
,10-07 06:42:31.111  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.111  5701  5747 I jxcore-log: 
10-07 06:42:31.112  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.112  5701  5747 I jxcore-log: 
,10-07 06:42:31.113  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.113  5701  5747 I jxcore-log: 
10-07 06:42:31.114  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.114  5701  5747 I jxcore-log: 
,10-07 06:42:31.114  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.114  5701  5747 I jxcore-log: 
,10-07 06:42:31.116  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.116  5701  5747 I jxcore-log: 
,10-07 06:42:31.117  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.117  5701  5747 I jxcore-log: 
10-07 06:42:31.117  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.117  5701  5747 I jxcore-log: 
,10-07 06:42:31.118  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.118  5701  5747 I jxcore-log: 
10-07 06:42:31.119  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.119  5701  5747 I jxcore-log: 
10-07 06:42:31.119  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.119  5701  5747 I jxcore-log: 
,10-07 06:42:31.120  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.120  5701  5747 I jxcore-log: 
10-07 06:42:31.121  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.121  5701  5747 I jxcore-log: 
,10-07 06:42:31.122  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.122  5701  5747 I jxcore-log: 
,10-07 06:42:31.123  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.123  5701  5747 I jxcore-log: 
10-07 06:42:31.123  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.123  5701  5747 I jxcore-log: 
,10-07 06:42:31.124  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.124  5701  5747 I jxcore-log: 
10-07 06:42:31.125  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.125  5701  5747 I jxcore-log: 
10-07 06:42:31.126  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.126  5701  5747 I jxcore-log: 
,10-07 06:42:31.126  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.126  5701  5747 I jxcore-log: 
,10-07 06:42:31.127  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.127  5701  5747 I jxcore-log: 
10-07 06:42:31.128  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.128  5701  5747 I jxcore-log: 
,10-07 06:42:31.129  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.129  5701  5747 I jxcore-log: 
10-07 06:42:31.130  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.130  5701  5747 I jxcore-log: 
10-07 06:42:31.131  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.131  5701  5747 I jxcore-log: 
10-07 06:42:31.131  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.131  5701  5747 I jxcore-log: 
,10-07 06:42:31.132  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.132  5701  5747 I jxcore-log: 
10-07 06:42:31.132  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.132  5701  5747 I jxcore-log: 
,10-07 06:42:31.133  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.133  5701  5747 I jxcore-log: 
,10-07 06:42:31.140  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.140  5701  5747 I jxcore-log: 
,10-07 06:42:31.141  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.141  5701  5747 I jxcore-log: 
,10-07 06:42:31.142  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.142  5701  5747 I jxcore-log: 
10-07 06:42:31.143  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.143  5701  5747 I jxcore-log: 
10-07 06:42:31.144  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.144  5701  5747 I jxcore-log: 
,10-07 06:42:31.145  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.145  5701  5747 I jxcore-log: 
10-07 06:42:31.145  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.145  5701  5747 I jxcore-log: 
10-07 06:42:31.146  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.146  5701  5747 I jxcore-log: 
,10-07 06:42:31.147  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.147  5701  5747 I jxcore-log: 
10-07 06:42:31.148  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.148  5701  5747 I jxcore-log: 
10-07 06:42:31.149  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.149  5701  5747 I jxcore-log: 
10-07 06:42:31.149  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.149  5701  5747 I jxcore-log: 
,10-07 06:42:31.150  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.150  5701  5747 I jxcore-log: 
10-07 06:42:31.151  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.151  5701  5747 I jxcore-log: 
,10-07 06:42:31.151  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.151  5701  5747 I jxcore-log: 
10-07 06:42:31.152  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.152  5701  5747 I jxcore-log: 
,10-07 06:42:31.153  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.153  5701  5747 I jxcore-log: 
10-07 06:42:31.154  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.154  5701  5747 I jxcore-log: 
,10-07 06:42:31.154  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.154  5701  5747 I jxcore-log: 
10-07 06:42:31.155  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.155  5701  5747 I jxcore-log: 
10-07 06:42:31.155  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.155  5701  5747 I jxcore-log: 
,10-07 06:42:31.156  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.156  5701  5747 I jxcore-log: 
10-07 06:42:31.157  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.157  5701  5747 I jxcore-log: 
10-07 06:42:31.157  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.157  5701  5747 I jxcore-log: 
,10-07 06:42:31.158  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.158  5701  5747 I jxcore-log: 
10-07 06:42:31.159  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.159  5701  5747 I jxcore-log: 
,10-07 06:42:31.160  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.160  5701  5747 I jxcore-log: 
10-07 06:42:31.160  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.160  5701  5747 I jxcore-log: 
10-07 06:42:31.161  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.161  5701  5747 I jxcore-log: 
,10-07 06:42:31.162  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.162  5701  5747 I jxcore-log: 
10-07 06:42:31.162  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:31.162  5701  5747 I jxcore-log: 
,10-07 06:42:31.163  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:31.163  5701  5747 I jxcore-log: 
,10-07 06:42:31.207  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.207  5701  5747 I jxcore-log: 
,10-07 06:42:31.208  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.208  5701  5747 I jxcore-log: 
10-07 06:42:31.209  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.209  5701  5747 I jxcore-log: 
,10-07 06:42:31.210  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.210  5701  5747 I jxcore-log: 
10-07 06:42:31.210  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.210  5701  5747 I jxcore-log: 
10-07 06:42:31.211  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.211  5701  5747 I jxcore-log: 
10-07 06:42:31.212  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.212  5701  5747 I jxcore-log: 
,10-07 06:42:31.212  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.212  5701  5747 I jxcore-log: 
10-07 06:42:31.212  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.212  5701  5747 I jxcore-log: 
,10-07 06:42:31.213  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.213  5701  5747 I jxcore-log: 
10-07 06:42:31.213  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.213  5701  5747 I jxcore-log: 
10-07 06:42:31.214  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.214  5701  5747 I jxcore-log: 
,10-07 06:42:31.214  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.214  5701  5747 I jxcore-log: 
10-07 06:42:31.215  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.215  5701  5747 I jxcore-log: 
,10-07 06:42:31.215  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.215  5701  5747 I jxcore-log: 
10-07 06:42:31.216  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.216  5701  5747 I jxcore-log: 
10-07 06:42:31.216  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.216  5701  5747 I jxcore-log: 
10-07 06:42:31.217  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.217  5701  5747 I jxcore-log: 
10-07 06:42:31.217  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.217  5701  5747 I jxcore-log: 
,10-07 06:42:31.218  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.218  5701  5747 I jxcore-log: 
10-07 06:42:31.218  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.218  5701  5747 I jxcore-log: 
10-07 06:42:31.219  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.219  5701  5747 I jxcore-log: 
,10-07 06:42:31.219  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.219  5701  5747 I jxcore-log: 
,10-07 06:42:31.220  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.220  5701  5747 I jxcore-log: 
10-07 06:42:31.220  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.220  5701  5747 I jxcore-log: 
10-07 06:42:31.221  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.221  5701  5747 I jxcore-log: 
10-07 06:42:31.221  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.221  5701  5747 I jxcore-log: 
,10-07 06:42:31.222  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.222  5701  5747 I jxcore-log: 
10-07 06:42:31.222  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.222  5701  5747 I jxcore-log: 
10-07 06:42:31.223  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.223  5701  5747 I jxcore-log: 
,10-07 06:42:31.223  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.223  5701  5747 I jxcore-log: 
10-07 06:42:31.224  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.224  5701  5747 I jxcore-log: 
10-07 06:42:31.224  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.224  5701  5747 I jxcore-log: 
10-07 06:42:31.224  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.224  5701  5747 I jxcore-log: 
10-07 06:42:31.225  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.225  5701  5747 I jxcore-log: 
,10-07 06:42:31.225  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.225  5701  5747 I jxcore-log: 
10-07 06:42:31.226  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.226  5701  5747 I jxcore-log: 
,10-07 06:42:31.226  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.226  5701  5747 I jxcore-log: 
10-07 06:42:31.227  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.227  5701  5747 I jxcore-log: 
10-07 06:42:31.227  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.227  5701  5747 I jxcore-log: 
10-07 06:42:31.227  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.227  5701  5747 I jxcore-log: 
10-07 06:42:31.228  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.228  5701  5747 I jxcore-log: 
,10-07 06:42:31.228  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.228  5701  5747 I jxcore-log: 
10-07 06:42:31.229  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.229  5701  5747 I jxcore-log: 
,10-07 06:42:31.230  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.230  5701  5747 I jxcore-log: 
10-07 06:42:31.231  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.231  5701  5747 I jxcore-log: 
,10-07 06:42:31.231  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.231  5701  5747 I jxcore-log: 
10-07 06:42:31.232  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.232  5701  5747 I jxcore-log: 
,10-07 06:42:31.234  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:31.234  5701  5747 I jxcore-log: 
10-07 06:42:31.235  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'mux close'
10-07 06:42:31.235  5701  5747 I jxcore-log: 
,10-07 06:42:31.237  5701  5747 I jxcore-log: ok 28 native server is nulled out
10-07 06:42:31.237  5701  5747 I jxcore-log: 
10-07 06:42:31.237  5701  5747 I jxcore-log: ok 29 native server should be closed
10-07 06:42:31.237  5701  5747 I jxcore-log: 
,10-07 06:42:31.237  5701  5747 I jxcore-log: ok 30 incoming has been removed
10-07 06:42:31.237  5701  5747 I jxcore-log: 
10-07 06:42:31.238  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.238  5701  5747 I jxcore-log: 
10-07 06:42:31.239  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.239  5701  5747 I jxcore-log: 
,10-07 06:42:31.239  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.239  5701  5747 I jxcore-log: 
,10-07 06:42:31.239  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.239  5701  5747 I jxcore-log: 
10-07 06:42:31.239  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.239  5701  5747 I jxcore-log: 
10-07 06:42:31.240  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.240  5701  5747 I jxcore-log: 
10-07 06:42:31.240  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.240  5701  5747 I jxcore-log: 
,10-07 06:42:31.240  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.240  5701  5747 I jxcore-log: 
10-07 06:42:31.240  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.240  5701  5747 I jxcore-log: 
10-07 06:42:31.240  5701  5747 I jxcore-log: 2016-10-07 10:42:31 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:31.240  5701  5747 I jxcore-log: 
,10-07 06:42:31.314  5701  5747 I jxcore-log: # teardown
10-07 06:42:31.314  5701  5747 I jxcore-log: 
,10-07 06:42:33.282  5701  5747 I jxcore-log: # setup
10-07 06:42:33.282  5701  5747 I jxcore-log: 
,10-07 06:42:33.907   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:34.908   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:35.255  5701  5747 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-07 06:42:35.255  5701  5747 I jxcore-log: 
,10-07 06:42:35.909   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:35.966  5701  5747 I jxcore-log: 2016-10-07 10:42:35 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:35.966  5701  5747 I jxcore-log: 
,10-07 06:42:35.973  5701  5747 I jxcore-log: 2016-10-07 10:42:35 - DEBUG createNativeListener: 'listening 43012'
10-07 06:42:35.973  5701  5747 I jxcore-log: 
,10-07 06:42:35.982  5701  5747 I jxcore-log: 2016-10-07 10:42:35 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:35.982  5701  5747 I jxcore-log: 
,10-07 06:42:35.984  5701  5747 I jxcore-log: 2016-10-07 10:42:35 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:35.984  5701  5747 I jxcore-log: 
10-07 06:42:35.986  5701  5747 I jxcore-log: 2016-10-07 10:42:35 - DEBUG createNativeListener: 'new mux'
10-07 06:42:35.986  5701  5747 I jxcore-log: 
,10-07 06:42:35.996  5701  5747 I jxcore-log: ok 31 we should not have gotten an error
10-07 06:42:35.996  5701  5747 I jxcore-log: 
,10-07 06:42:36.000  5701  5747 I jxcore-log: 2016-10-07 10:42:35 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:36.000  5701  5747 I jxcore-log: 
,10-07 06:42:36.003  5701  5747 I jxcore-log: 2016-10-07 10:42:36 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:36.003  5701  5747 I jxcore-log: 
,10-07 06:42:36.011  5701  5747 I jxcore-log: ok 32 Buffers are identical
10-07 06:42:36.011  5701  5747 I jxcore-log: 
,10-07 06:42:36.012  5701  5747 I jxcore-log: 2016-10-07 10:42:36 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:36.012  5701  5747 I jxcore-log: 
,10-07 06:42:36.015  5701  5747 I jxcore-log: 2016-10-07 10:42:36 - DEBUG createNativeListener: 'mux close'
10-07 06:42:36.015  5701  5747 I jxcore-log: 
,10-07 06:42:36.027  5701  5747 I jxcore-log: 2016-10-07 10:42:36 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:36.027  5701  5747 I jxcore-log: 
,10-07 06:42:36.028  5701  5747 I jxcore-log: ok 33 server should be fine
10-07 06:42:36.028  5701  5747 I jxcore-log: 
10-07 06:42:36.028  5701  5747 I jxcore-log: ok 34 server should be open
10-07 06:42:36.028  5701  5747 I jxcore-log: 
10-07 06:42:36.028  5701  5747 I jxcore-log: ok 35 incoming has been removed
10-07 06:42:36.028  5701  5747 I jxcore-log: 
10-07 06:42:36.028  5701  5747 I jxcore-log: ok 36 The mux object should be closed
10-07 06:42:36.028  5701  5747 I jxcore-log: 
10-07 06:42:36.029  5701  5747 I jxcore-log: ok 37 The mux stream should be closed
10-07 06:42:36.029  5701  5747 I jxcore-log: 
,10-07 06:42:36.034  5701  5747 I jxcore-log: # teardown
10-07 06:42:36.034  5701  5747 I jxcore-log: 
,10-07 06:42:36.479  5701  5747 I jxcore-log: # setup
10-07 06:42:36.479  5701  5747 I jxcore-log: 
,10-07 06:42:36.911   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:37.304  5701  5747 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-07 06:42:37.304  5701  5747 I jxcore-log: 
,10-07 06:42:37.601  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'creating native server'
10-07 06:42:37.601  5701  5747 I jxcore-log: 
,10-07 06:42:37.605  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'listening 42539'
10-07 06:42:37.605  5701  5747 I jxcore-log: 
,10-07 06:42:37.612  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'new incoming socket'
10-07 06:42:37.612  5701  5747 I jxcore-log: 
,10-07 06:42:37.614  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'creating incoming mux'
10-07 06:42:37.614  5701  5747 I jxcore-log: 
,10-07 06:42:37.616  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'new mux'
10-07 06:42:37.616  5701  5747 I jxcore-log: 
,10-07 06:42:37.623  5701  5747 I jxcore-log: ok 38 we should not have gotten an error
10-07 06:42:37.623  5701  5747 I jxcore-log: 
,10-07 06:42:37.627  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'new stream: '
10-07 06:42:37.627  5701  5747 I jxcore-log: 
,10-07 06:42:37.630  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'new outgoing socket'
10-07 06:42:37.630  5701  5747 I jxcore-log: 
,10-07 06:42:37.638  5701  5747 I jxcore-log: ok 39 Buffers are identical
10-07 06:42:37.638  5701  5747 I jxcore-log: 
,10-07 06:42:37.642  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'incoming socket timeout'
10-07 06:42:37.642  5701  5747 I jxcore-log: 
,10-07 06:42:37.644  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'stream close:'
10-07 06:42:37.644  5701  5747 I jxcore-log: 
,10-07 06:42:37.646  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'mux close'
10-07 06:42:37.646  5701  5747 I jxcore-log: 
,10-07 06:42:37.652  5701  5747 I jxcore-log: 2016-10-07 10:42:37 - DEBUG createNativeListener: 'incoming socket close'
10-07 06:42:37.652  5701  5747 I jxcore-log: 
10-07 06:42:37.653  5701  5747 I jxcore-log: ok 40 server should be fine
10-07 06:42:37.653  5701  5747 I jxcore-log: 
10-07 06:42:37.653  5701  5747 I jxcore-log: ok 41 server should be open
10-07 06:42:37.653  5701  5747 I jxcore-log: 
,10-07 06:42:37.653  5701  5747 I jxcore-log: ok 42 incoming has been removed
10-07 06:42:37.653  5701  5747 I jxcore-log: 
10-07 06:42:37.654  5701  5747 I jxcore-log: ok 43 The mux object should be closed
10-07 06:42:37.654  5701  5747 I jxcore-log: 
10-07 06:42:37.654  5701  5747 I jxcore-log: ok 44 The mux stream should be closed
10-07 06:42:37.654  5701  5747 I jxcore-log: 
,10-07 06:42:37.660  5701  5747 I jxcore-log: # teardown
10-07 06:42:37.660  5701  5747 I jxcore-log: 
,10-07 06:42:37.912   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:38.529  5701  5747 I jxcore-log: # setup
10-07 06:42:38.529  5701  5747 I jxcore-log: 
,10-07 06:42:38.912   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-07 06:42:38.934  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-07 06:42:38.934  5701  5747 I jxcore-log: 
,10-07 06:42:39.775  5701  5747 I jxcore-log: 2016-10-07 10:42:39 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-07 06:42:39.775  5701  5747 I jxcore-log: 
,10-07 06:42:39.776  5701  5747 I jxcore-log: ok 45 Got right error
10-07 06:42:39.776  5701  5747 I jxcore-log: 
,10-07 06:42:39.781  5701  5747 I jxcore-log: # teardown
10-07 06:42:39.781  5701  5747 I jxcore-log: 
,10-07 06:42:40.269  5701  5747 I jxcore-log: # setup
10-07 06:42:40.269  5701  5747 I jxcore-log: 
,10-07 06:42:40.982  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-07 06:42:40.982  5701  5747 I jxcore-log: 
,10-07 06:42:41.448  5701  5747 I jxcore-log: 2016-10-07 10:42:41 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-07 06:42:41.448  5701  5747 I jxcore-log: 
,10-07 06:42:41.449  5701  5747 I jxcore-log: ok 46 Got socket hang up
10-07 06:42:41.449  5701  5747 I jxcore-log: 
,10-07 06:42:41.455  5701  5747 I jxcore-log: # teardown
10-07 06:42:41.455  5701  5747 I jxcore-log: 
,10-07 06:42:42.011  5701  5747 I jxcore-log: # setup
10-07 06:42:42.011  5701  5747 I jxcore-log: 
,10-07 06:42:42.621  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-07 06:42:42.621  5701  5747 I jxcore-log: 
,10-07 06:42:42.895  5701  5747 I jxcore-log: 2016-10-07 10:42:42 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-07 06:42:42.895  5701  5747 I jxcore-log: 
,10-07 06:42:42.896  5701  5747 I jxcore-log: ok 47 Got 500 as expected
10-07 06:42:42.896  5701  5747 I jxcore-log: 
,10-07 06:42:42.901  5701  5747 I jxcore-log: # teardown
10-07 06:42:42.901  5701  5747 I jxcore-log: 
,10-07 06:42:42.930  5701  5747 I jxcore-log: # setup
10-07 06:42:42.930  5701  5747 I jxcore-log: 
,10-07 06:42:42.975  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-07 06:42:42.975  5701  5747 I jxcore-log: 
,10-07 06:42:44.356  5701  5747 I jxcore-log: ok 48 should be equal
10-07 06:42:44.356  5701  5747 I jxcore-log: 
,10-07 06:42:44.356  5701  5747 I jxcore-log: ok 49 revs are equal
10-07 06:42:44.356  5701  5747 I jxcore-log: 
10-07 06:42:44.361  5701  5747 I jxcore-log: # teardown
10-07 06:42:44.361  5701  5747 I jxcore-log: 
,10-07 06:42:44.400  5701  5747 I jxcore-log: # setup
10-07 06:42:44.400  5701  5747 I jxcore-log: 
,10-07 06:42:45.296  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-07 06:42:45.296  5701  5747 I jxcore-log: 
,10-07 06:42:46.369  5701  5747 I jxcore-log: ok 50 should be equal
10-07 06:42:46.369  5701  5747 I jxcore-log: 
,10-07 06:42:46.369  5701  5747 I jxcore-log: ok 51 revs are equal
10-07 06:42:46.369  5701  5747 I jxcore-log: 
,10-07 06:42:46.375  5701  5747 I jxcore-log: # teardown
10-07 06:42:46.375  5701  5747 I jxcore-log: 
,10-07 06:42:47.274  5701  5747 I jxcore-log: # setup
10-07 06:42:47.274  5701  5747 I jxcore-log: 
,10-07 06:42:47.944  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-07 06:42:47.944  5701  5747 I jxcore-log: 
,10-07 06:42:48.500   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 06:42:48.914   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:49.055  5701  5747 I jxcore-log: ok 52 should be equal
10-07 06:42:49.055  5701  5747 I jxcore-log: 
,10-07 06:42:49.056  5701  5747 I jxcore-log: ok 53 revs are equal
10-07 06:42:49.056  5701  5747 I jxcore-log: 
,10-07 06:42:49.243  5701  5747 I jxcore-log: ok 54 should be equal
10-07 06:42:49.243  5701  5747 I jxcore-log: 
,10-07 06:42:49.244  5701  5747 I jxcore-log: ok 55 revs are equal
10-07 06:42:49.244  5701  5747 I jxcore-log: 
,10-07 06:42:49.425  5701  5747 I jxcore-log: ok 56 should be equal
10-07 06:42:49.425  5701  5747 I jxcore-log: 
,10-07 06:42:49.426  5701  5747 I jxcore-log: ok 57 revs are equal
10-07 06:42:49.426  5701  5747 I jxcore-log: 
,10-07 06:42:49.433  5701  5747 I jxcore-log: # teardown
10-07 06:42:49.433  5701  5747 I jxcore-log: 
,10-07 06:42:49.484  5701  5747 I jxcore-log: # setup
10-07 06:42:49.484  5701  5747 I jxcore-log: 
,10-07 06:42:49.788  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-07 06:42:49.788  5701  5747 I jxcore-log: 
,10-07 06:42:49.915   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:50.916   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:51.367  5701  5747 I jxcore-log: 2016-10-07 10:42:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-07 06:42:51.367  5701  5747 I jxcore-log: 
,10-07 06:42:51.368  5701  5747 I jxcore-log: ok 58 Our rev is old so we should fail
10-07 06:42:51.368  5701  5747 I jxcore-log: 
,10-07 06:42:51.371  5701  5747 I jxcore-log: # teardown
10-07 06:42:51.371  5701  5747 I jxcore-log: 
,10-07 06:42:51.410  5701  5747 I jxcore-log: # setup
10-07 06:42:51.410  5701  5747 I jxcore-log: 
,10-07 06:42:51.474  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-07 06:42:51.474  5701  5747 I jxcore-log: 
,10-07 06:42:51.580  5701  5747 I jxcore-log: ok 59 confirm stop caused failure
10-07 06:42:51.580  5701  5747 I jxcore-log: 
,10-07 06:42:51.593  5701  5747 I jxcore-log: # teardown
10-07 06:42:51.593  5701  5747 I jxcore-log: 
,10-07 06:42:51.624  5701  5747 I jxcore-log: # setup
10-07 06:42:51.624  5701  5747 I jxcore-log: 
,10-07 06:42:51.698  5701  5747 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-07 06:42:51.698  5701  5747 I jxcore-log: 
,10-07 06:42:51.917   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:51.991  5701  5747 I jxcore-log: 2016-10-07 10:42:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-07 06:42:51.991  5701  5747 I jxcore-log: 
,10-07 06:42:51.992  5701  5747 I jxcore-log: ok 60 stop caused us to fail
10-07 06:42:51.992  5701  5747 I jxcore-log: 
10-07 06:42:51.992  5701  5747 I jxcore-log: ok 61 We specifically failed on a stop before put
10-07 06:42:51.992  5701  5747 I jxcore-log: 
,10-07 06:42:51.997  5701  5747 I jxcore-log: # teardown
10-07 06:42:51.997  5701  5747 I jxcore-log: 
,10-07 06:42:52.039  5701  5747 I jxcore-log: # setup
10-07 06:42:52.039  5701  5747 I jxcore-log: 
,10-07 06:42:52.092  5701  5747 I jxcore-log: # #update - fail if stop is called
10-07 06:42:52.092  5701  5747 I jxcore-log: 
,10-07 06:42:52.253  5701  5747 I jxcore-log: ok 62 failed due to stop
10-07 06:42:52.253  5701  5747 I jxcore-log: 
,10-07 06:42:52.256  5701  5747 I jxcore-log: ok 63 failed due to stop
10-07 06:42:52.256  5701  5747 I jxcore-log: 
,10-07 06:42:52.268  5701  5747 I jxcore-log: # teardown
10-07 06:42:52.268  5701  5747 I jxcore-log: 
,10-07 06:42:52.325  5701  5747 I jxcore-log: # setup
10-07 06:42:52.325  5701  5747 I jxcore-log: 
,10-07 06:42:52.357  5701  5747 I jxcore-log: # #update - set seq for first time
10-07 06:42:52.357  5701  5747 I jxcore-log: 
,10-07 06:42:52.868  5701  5747 I jxcore-log: ok 64 should be equal
10-07 06:42:52.868  5701  5747 I jxcore-log: 
,10-07 06:42:52.874  5701  5747 I jxcore-log: # teardown
10-07 06:42:52.874  5701  5747 I jxcore-log: 
,10-07 06:42:52.917   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:42:52.994  5701  5747 I jxcore-log: # setup
10-07 06:42:52.994  5701  5747 I jxcore-log: 
,10-07 06:42:53.012  5701  5747 I jxcore-log: # #update - Fail on bad seq value
10-07 06:42:53.012  5701  5747 I jxcore-log: 
,10-07 06:42:53.754  5701  5747 I jxcore-log: 2016-10-07 10:42:53 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-07 06:42:53.754  5701  5747 I jxcore-log: 
10-07 06:42:53.756  5701  5747 I jxcore-log: ok 65 Expected bad seq error
10-07 06:42:53.756  5701  5747 I jxcore-log: 
,10-07 06:42:53.766  5701  5747 I jxcore-log: # teardown
10-07 06:42:53.766  5701  5747 I jxcore-log: 
,10-07 06:42:53.818  5701  5747 I jxcore-log: # setup
10-07 06:42:53.818  5701  5747 I jxcore-log: 
,10-07 06:42:53.918   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-07 06:42:54.908  5701  5747 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-07 06:42:54.908  5701  5747 I jxcore-log: 
,10-07 06:42:55.914  5701  5747 I jxcore-log: ok 66 Different promises
10-07 06:42:55.914  5701  5747 I jxcore-log: 
,10-07 06:42:55.916  5701  5747 I jxcore-log: ok 67 Timer was cancelled
10-07 06:42:55.916  5701  5747 I jxcore-log: 
,10-07 06:42:56.053  5701  5747 I jxcore-log: ok 68 should be equal
10-07 06:42:56.053  5701  5747 I jxcore-log: 
,10-07 06:42:56.060  5701  5747 I jxcore-log: # teardown
10-07 06:42:56.060  5701  5747 I jxcore-log: 
,10-07 06:42:57.085  5701  5747 I jxcore-log: # setup
10-07 06:42:57.085  5701  5747 I jxcore-log: 
,10-07 06:42:57.104  5701  5747 I jxcore-log: # #update - do we wait for blocked update
10-07 06:42:57.104  5701  5747 I jxcore-log: 
,10-07 06:42:57.200  5701  5747 I jxcore-log: ok 69 One go and one blocked
10-07 06:42:57.200  5701  5747 I jxcore-log: 
,10-07 06:42:57.201  5701  5747 I jxcore-log: ok 70 All blocked
10-07 06:42:57.201  5701  5747 I jxcore-log: 
10-07 06:42:57.201  5701  5747 I jxcore-log: ok 71 Still blocked
10-07 06:42:57.201  5701  5747 I jxcore-log: 
,10-07 06:42:57.639  5701  5747 I jxcore-log: ok 72 should be equal
10-07 06:42:57.639  5701  5747 I jxcore-log: 
,10-07 06:42:57.648  5701  5747 I jxcore-log: # teardown
10-07 06:42:57.648  5701  5747 I jxcore-log: 
,10-07 06:42:57.714  5701  5747 I jxcore-log: # setup
10-07 06:42:57.714  5701  5747 I jxcore-log: 
,10-07 06:42:57.906  5701  5747 I jxcore-log: # #update - test that we wait long enough
10-07 06:42:57.906  5701  5747 I jxcore-log: 
,10-07 06:42:59.123  5701  5747 I jxcore-log: ok 73 We waited long enough
10-07 06:42:59.123  5701  5747 I jxcore-log: 
,10-07 06:42:59.261  5701  5747 I jxcore-log: ok 74 should be equal
10-07 06:42:59.261  5701  5747 I jxcore-log: 
,10-07 06:42:59.267  5701  5747 I jxcore-log: # teardown
10-07 06:42:59.267  5701  5747 I jxcore-log: 
,10-07 06:42:59.308  5701  5747 I jxcore-log: # setup
10-07 06:42:59.308  5701  5747 I jxcore-log: 
,10-07 06:42:59.370  5701  5747 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-07 06:42:59.370  5701  5747 I jxcore-log: 
,10-07 06:42:59.765  5701  5747 I jxcore-log: ok 75 Should have gotten same timer promise
10-07 06:42:59.765  5701  5747 I jxcore-log: 
,10-07 06:42:59.765  5701  5747 I jxcore-log: ok 76 Still same timer promise
10-07 06:42:59.765  5701  5747 I jxcore-log: 
,10-07 06:43:00.569  5701  5747 I jxcore-log: ok 77 We waited long enough
10-07 06:43:00.569  5701  5747 I jxcore-log: 
,10-07 06:43:00.636  5701  5747 I jxcore-log: ok 78 should be equal
10-07 06:43:00.636  5701  5747 I jxcore-log: 
,10-07 06:43:00.643  5701  5747 I jxcore-log: # teardown
10-07 06:43:00.643  5701  5747 I jxcore-log: 
,10-07 06:43:00.703  5701  5747 I jxcore-log: # setup
10-07 06:43:00.703  5701  5747 I jxcore-log: 
,10-07 06:43:00.771  5701  5747 I jxcore-log: # Coordinated seq test
10-07 06:43:00.771  5701  5747 I jxcore-log: 
,10-07 06:43:00.950  5701  5747 I jxcore-log: 2016-10-07 10:43:00 - DEBUG thaliWifiInfrastructure: 'listening 45205'
10-07 06:43:00.950  5701  5747 I jxcore-log: 
,10-07 06:43:02.951  5701  5747 I jxcore-log: ok 79 should be equal
10-07 06:43:02.951  5701  5747 I jxcore-log: 
,10-07 06:43:02.972  5701  5747 I jxcore-log: ok 80 should be equal
10-07 06:43:02.972  5701  5747 I jxcore-log: 
,10-07 06:43:02.985  5701  5747 I jxcore-log: # teardown
10-07 06:43:02.985  5701  5747 I jxcore-log: 
,10-07 06:43:08.502   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 06:43:08.919   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:09.920   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:10.922   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:11.924   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:12.926   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:13.927   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-07 06:43:33.928   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:34.929   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:35.930   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:36.932   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:37.933   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 06:43:38.934   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-07 06:43:48.503   930  3017 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 06:44:03.001  5701  5747 I jxcore-log: 2016-10-07 10:44:02 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-07 06:44:03.001  5701  5747 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-07 06:44:03.001  5701  5747 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-07 06:44:03.001  5701  5747 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-07 06:44:03.001  5701  5747 I jxcore-log:     at $9@timers.js:120:1
10-07 06:44:03.001  5701  5747 I jxcore-log: ''
10-07 06:44:03.001  5701  5747 I jxcore-log: 
10-07 06:44:03.003  5701  5747 I jxcore-log: 2016-10-07 10:44:03 - DEBUG CoordinatedClient: 'test client failed'
10-07 06:44:03.003  5701  5747 I jxcore-log: 
,10-07 06:44:03.014  5701  5747 I jxcore-log: 2016-10-07 10:44:03 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-07 06:44:03.014  5701  5747 I jxcore-log: 
,10-07 06:44:03.021  5701  5747 I jxcore-log: 2016-10-07 10:44:03 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-07 06:44:03.021  5701  5747 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-07 06:44:03.021  5701  5747 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-07 06:44:03.021  5701  5747 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-07 06:44:03.021  5701  5747 I jxcore-log:     at $9@timers.js:120:1
10-07 06:44:03.021  5701  5747 I jxcore-log: ''
10-07 06:44:03.021  5701  5747 I jxcore-log: 
,10-07 06:44:03.022  5701  5747 I jxcore-log: 2016-10-07 10:44:03 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-07 06:44:03.022  5701  5747 I jxcore-log: 
,10-07 06:44:03.105   930  2957 W InputDispatcher: channel '48a7283 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-07 06:44:03.105   930  2957 E InputDispatcher: channel '48a7283 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-07 06:44:03.118   930  3916 I WindowState: WIN DEATH: Window{48a7283 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-07 06:44:03.118   930  3018 D WifiService: Client connection lost with reason: 4
10-07 06:44:03.118   930  3916 W InputDispatcher: Attempted to unregister already unregistered input channel '48a7283 com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-07 06:44:03.119   930   940 D GraphicsStats: Buffer count: 2
,10-07 06:44:03.135   930   941 I ActivityManager: Process com.test.thalitest (pid 5701) has died
,10-07 06:44:03.130   528   528 I Zygote  : Process 5701 exited cleanly (139)
,10-07 06:44:03.158   930   941 I ActivityManager: Start proc 6082:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-07 06:44:03.482   930  3646 I WindowManager: Screenshot max retries 4 of Token{931f85d ActivityRecord{d610234 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{48c4e4 u0 Starting com.test.thalitest} drawState=4
,10-07 06:44:03.547  6082  6082 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-07 06:44:03.570  6082  6082 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-07 06:44:03.576  6082  6082 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3613-3615)
10-07 06:44:03.576  6082  6082 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 06:44:03.584  6082  6082 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2249c6d}
,10-07 06:44:03.585  6082  6082 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-07 06:44:03.585  6082  6082 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-07 06:44:03.588  6082  6082 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-07 06:44:03.589  6082  6082 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-07 06:44:03.600  6082  6082 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-07 06:44:03.607  6080  6080 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-07 06:44:03.607  6082  6082 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 06:44:03.608  6082  6082 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 06:44:03.608  6082  6082 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-07 06:44:03.608  6082  6082 I Adreno  : Build Date                       : 12/06/15
10-07 06:44:03.608  6082  6082 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-07 06:44:03.608  6082  6082 I Adreno  : Local Branch                     : mybranch17112971
10-07 06:44:03.608  6082  6082 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-07 06:44:03.608  6082  6082 I Adreno  : Remote Branch                    : NONE
10-07 06:44:03.608  6082  6082 I Adreno  : Reconstruct Branch               : NOTHING
,10-07 06:44:03.621  6080  6080 D AndroidRuntime: CheckJNI is OFF
,10-07 06:44:03.639   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93e0905:true
,10-07 06:44:03.649  6080  6080 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-07 06:44:03.652   722   722 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33896]" dev="sockfs" ino=33896 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-07 06:44:03.652   722   722 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33896]" dev="sockfs" ino=33896 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 06:44:03.663  6082  6082 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-07 06:44:03.671  6082  6082 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-07 06:44:03.674  6080  6080 I Radio-JNI: register_android_hardware_Radio DONE
,10-07 06:44:03.689  6080  6080 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-07 06:44:03.695   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-07 06:44:03.695   930   943 I ActivityManager: Killing 6082:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-07 06:44:03.827   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-07 06:44:03.828   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-07 06:44:03.831   930   943 E ActivityManager: Failure starting process com.test.thalitest
10-07 06:44:03.831   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-07 06:44:03.831   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:03.831   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:03.831   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 06:44:03.831   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-07 06:44:03.832   930   953 I art     : Starting a blocking GC Explicit
,10-07 06:44:03.837   930   943 I ActivityManager:   Force finishing activity ActivityRecord{d610234 u0 com.test.thalitest/.MainActivity t2}
,10-07 06:44:03.849   930  3916 W ActivityManager: Spurious death for ProcessRecord{c83ad7b 0:com.test.thalitest/u0a77}, curProc for 6082: null
,10-07 06:44:03.859   930   948 W WindowManager: Failed looking up window
10-07 06:44:03.859   930   948 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@6aea077 does not exist
10-07 06:44:03.859   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-07 06:44:03.859   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-07 06:44:03.859   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-07 06:44:03.859   930   948 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-07 06:44:03.859   930   948 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-07 06:44:03.859   930   948 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-07 06:44:03.859   930   948 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-07 06:44:03.859   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:03.859   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:03.859   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 06:44:03.859   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-07 06:44:03.934   545   545 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-07 06:44:03.934   545   545 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-07 06:44:03.935   930   953 I art     : Explicit concurrent mark sweep GC freed 85901(6MB) AllocSpace objects, 43(1460KB) LOS objects, 33% free, 29MB/43MB, paused 1.478ms total 102.685ms
,10-07 06:44:03.957   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-07 06:44:03.961  6080  6080 I art     : System.exit called, status: 0
10-07 06:44:03.961  6080  6080 I AndroidRuntime: VM exiting with result code 0.
,10-07 06:44:03.975   930   953 I ActivityManager: Start proc 6126:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-07 06:44:03.975   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-07 06:44:03.981   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-07 06:44:03.985  5982  5982 D BluetoothMapAppObserver: onReceive
10-07 06:44:03.986  5982  5982 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-07 06:44:03.988  3701  3701 I Keyboard.Facilitator: resetDictionaries() : en_US
10-07 06:44:03.990   930  2958 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-07 06:44:03.994  4126  4234 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-07 06:44:04.017  3701  6137 I Keyboard.Facilitator.DecoderInitializer: run()
,10-07 06:44:04.020  3701  6137 I Decoder : createOrResetDecoder
,10-07 06:44:04.045  3855  3855 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
10-07 06:44:04.047  3442  6141 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-07 06:44:04.071  3629  3629 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-07 06:44:04.071  3629  3629 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
10-07 06:44:04.072   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-07 06:44:04.072    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 06:44:04.082    17    17 W kworker/2:0: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 06:44:04.101  3629  3629 I ConfigService: onCreate
,10-07 06:44:04.102  3795  6145 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-07 06:44:04.102  3795  6145 D AccountUtils: Clearing selected account for com.test.thalitest
,10-07 06:44:04.109  3886  3983 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-07 06:44:04.123   930  3201 I ActivityManager: Start proc 6149:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-07 06:44:04.123  3886  3983 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-07 06:44:04.123  3886  3983 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3886
10-07 06:44:04.123  3886  3983 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:04.123  3886  3983 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 06:44:04.119    17    17 W kworker/2:0: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 06:44:04.130   930  3607 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 06:44:04.137  3886  3983 I Process : Sending signal. PID: 3886 SIG: 9
10-07 06:44:04.140  3795  6145 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-07 06:44:04.156  3701  6137 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-07 06:44:04.211  3442  6141 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-07 06:44:04.212  3442  6141 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-07 06:44:04.212  3442  6141 E AndroidRuntime: Process: android.process.acore, PID: 3442
10-07 06:44:04.212  3442  6141 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:04.212  3442  6141 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-07 06:44:04.215   930  6166 E DropBoxManagerService: Can't write: system_app_crash
10-07 06:44:04.215   930  6166 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 06:44:04.215   930  6166 E DropBoxManagerService: 	... 5 more
,10-07 06:44:04.225  3442  6141 I Process : Sending signal. PID: 3442 SIG: 9
,10-07 06:44:04.246  3701  6137 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,10-07 06:44:04.248  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,10-07 06:44:04.248  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,10-07 06:44:04.254   930  2957 W InputDispatcher: channel '8c574ef com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-07 06:44:04.254   930  2957 E InputDispatcher: channel '8c574ef com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-07 06:44:04.255   930  3237 I WindowState: WIN DEATH: Window{8c574ef u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-07 06:44:04.255   930   941 D GraphicsStats: Buffer count: 1
10-07 06:44:04.255   930  3237 W InputDispatcher: Attempted to unregister already unregistered input channel '8c574ef com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-07 06:44:04.258  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
10-07 06:44:04.258  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
10-07 06:44:04.259  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
10-07 06:44:04.259  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,10-07 06:44:04.269  3701  6137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,10-07 06:44:04.269  3701  6137 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
10-07 06:44:04.269  3701  6137 I Keyboard.Facilitator.Delight2FileSweeper: run()
10-07 06:44:04.269  3701  6137 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,10-07 06:44:04.269  3701  6137 I StatsUtilsManager: startPeriodStatsRecorder() : Success
10-07 06:44:04.270  3701  6137 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
10-07 06:44:04.271   930  3607 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3886) has died
,10-07 06:44:04.272   930  3607 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-07 06:44:04.275   930  3607 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-07 06:44:04.293   930   943 I ActivityManager: Start proc 6168:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 06:44:04.318   930  3891 I ActivityManager: Process android.process.acore (pid 3442) has died
10-07 06:44:04.318   930  3891 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-07 06:44:04.337  6168  6168 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:44:04.337  6168  6168 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:44:04.338  6168  6168 D AndroidRuntime: Shutting down VM
,10-07 06:44:04.344  6168  6168 E AndroidRuntime: FATAL EXCEPTION: main
10-07 06:44:04.344  6168  6168 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6168
10-07 06:44:04.344  6168  6168 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 06:44:04.344  6168  6168 E AndroidRuntime: 	... 10 more
10-07 06:44:04.346   930  3607 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-07 06:44:04.347   930  6181 E DropBoxManagerService: Can't write: system_app_crash
10-07 06:44:04.347   930  6181 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 06:44:04.347   930  6181 E DropBoxManagerService: 	... 5 more
10-07 06:44:04.347  6168  6168 I Process : Sending signal. PID: 6168 SIG: 9
,10-07 06:44:04.361   930   941 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6168) has died
,10-07 06:44:04.363   930   941 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-07 06:44:04.378   930   943 I ActivityManager: Start proc 6182:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 06:44:04.427  6182  6182 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:44:04.427  6182  6182 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-07 06:44:04.428  6182  6182 D AndroidRuntime: Shutting down VM
,10-07 06:44:04.435  6182  6182 E AndroidRuntime: FATAL EXCEPTION: main
10-07 06:44:04.435  6182  6182 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6182
10-07 06:44:04.435  6182  6182 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 06:44:04.435  6182  6182 E AndroidRuntime: 	... 10 more
,10-07 06:44:04.438   930  3201 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 06:44:04.438   930  6194 E DropBoxManagerService: Can't write: system_app_crash
10-07 06:44:04.438   930  6194 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 06:44:04.438   930  6194 E DropBoxManagerService: 	... 5 more
10-07 06:44:04.439  6182  6182 I Process : Sending signal. PID: 6182 SIG: 9
,10-07 06:44:04.456   930   941 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6182) has died
,10-07 06:44:04.458   930   941 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-07 06:44:04.469   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
