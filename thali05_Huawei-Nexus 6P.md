#### Test 87460634ef5c251_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 05:50:01.126   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 05:50:01.127   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-30 05:50:01.599  5537  5537 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 05:50:01.605  5537  5537 D AndroidRuntime: CheckJNI is OFF
09-30 05:50:01.633  5537  5537 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 05:50:01.670  5537  5537 I Radio-JNI: register_android_hardware_Radio DONE
09-30 05:50:01.687  5537  5537 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 05:50:01.693   930  3467 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 05:50:01.737   930  3467 I ActivityManager: Start proc 5547:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 05:50:01.759  5537  5537 D AndroidRuntime: Shutting down VM
,09-30 05:50:02.069   930   940 I WindowManager: Screenshot max retries 4 of Token{a481d96 ActivityRecord{37a04b1 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{5bb98e9 u0 Starting com.test.thalitest} drawState=2
,09-30 05:50:02.142  5547  5547 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 05:50:02.175  5547  5547 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 05:50:02.197  5547  5547 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 591-609)
09-30 05:50:02.197  5547  5547 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 05:50:02.216  5547  5547 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7230fd8}
,09-30 05:50:02.217  5547  5547 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 05:50:02.217  5547  5547 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 05:50:02.222  5547  5547 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 05:50:02.224  5547  5547 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 05:50:02.257  5547  5547 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 05:50:02.272  5547  5547 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 05:50:02.272  5547  5547 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 05:50:02.272  5547  5547 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 05:50:02.272  5547  5547 I Adreno  : Build Date                       : 12/06/15
09-30 05:50:02.272  5547  5547 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 05:50:02.272  5547  5547 I Adreno  : Local Branch                     : mybranch17112971
09-30 05:50:02.272  5547  5547 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 05:50:02.272  5547  5547 I Adreno  : Remote Branch                    : NONE
09-30 05:50:02.272  5547  5547 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 05:50:02.320   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e952734:true
,09-30 05:50:02.346   397   397 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[31222]" dev="sockfs" ino=31222 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 05:50:02.346   397   397 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31222]" dev="sockfs" ino=31222 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 05:50:02.358  5547  5547 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 05:50:02.366  5547  5547 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 05:50:02.386   401   401 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32367]" dev="sockfs" ino=32367 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 05:50:02.386   401   401 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32367]" dev="sockfs" ino=32367 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 05:50:02.390  5547  5584 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-30 05:50:02.390  3713  3713 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13923]" dev="sockfs" ino=13923 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 05:50:02.390  3713  3713 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[13923]" dev="sockfs" ino=13923 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 05:50:02.395  5547  5571 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 05:50:02.419  5547  5584 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 05:50:02.479   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +405ms (total +770ms)
,09-30 05:50:02.514  5547  5547 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5547
,09-30 05:50:02.596  5547  5547 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 05:50:02.714  5547  5586 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -584058576
,09-30 05:50:02.719  5547  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 05:50:02.719  5547  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 05:50:02.719  5547  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 05:50:02.719  5547  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 05:50:02.719  5547  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-30 05:50:02.719  5547  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bbe129 added. We now have 1 listener(s)
,09-30 05:50:02.722  5547  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 05:50:02.723  5547  5586 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:50:02.723  5547  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:50:02.723  5547  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-30 05:50:02.725  5547  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3975dc added. We now have 1 listener(s)
09-30 05:50:02.726  5547  5586 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:50:02.729   930  2870 D WifiService: New client listening to asynchronous messages
,09-30 05:50:02.730  5547  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:50:02.730  5547  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-30 05:50:02.730  5547  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 05:50:02.730  5547  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 05:50:02.730  5547  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-30 05:50:02.732  5547  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:02.732  5547  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 05:50:02.736  5547  5586 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:02.736  5547  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:02.736  5547  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 05:50:02.736  5547  5586 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:02.736  5547  5586 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 05:50:02.740  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:02.742  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:02.863  5547  5547 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 05:50:03.093  5547  5593 W jxcore-log: Initializing JXcore engine
09-30 05:50:03.093  5547  5593 W jxcore-log: JXcore engine is ready
,09-30 05:50:03.090  5593  5593 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1196 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-30 05:50:03.090  5593  5593 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14443]" dev="sockfs" ino=14443 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 05:50:03.090  5593  5593 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 05:50:03.090  5593  5593 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32343]" dev="sockfs" ino=32343 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 05:50:03.132  5547  5593 W jxcore-log: Starting JXcore engine
,09-30 05:50:03.176   930  2869 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:50:03.199  5547  5593 W jxcore-log: Platform android
09-30 05:50:03.199  5547  5593 W jxcore-log: 
,09-30 05:50:03.199  5547  5593 W jxcore-log: Process ARCH arm
09-30 05:50:03.199  5547  5593 W jxcore-log: 
,09-30 05:50:03.314  5547  5593 I jxcore-log: JXcore Cordova bridge is ready!
09-30 05:50:03.314  5547  5593 I jxcore-log: 
,09-30 05:50:03.314  5547  5593 W jxcore-log: JXcore engine is started
,09-30 05:50:03.326  5547  5586 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 05:50:03.331  5547  5547 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 05:50:06.999  5547  5593 I jxcore-log: 2016-09-30 09:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 05:50:06.999  5547  5593 I jxcore-log: 
,09-30 05:50:07.000  5547  5593 I jxcore-log: 2016-09-30 09:50:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 05:50:07.000  5547  5593 I jxcore-log: 
,09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:07.003  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:50:07.004  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:07.005  5547  5593 I jxcore-log: 2016-09-30 09:50:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 05:50:07.005  5547  5593 I jxcore-log: 
,09-30 05:50:07.006  5547  5593 I jxcore-log: 2016-09-30 09:50:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 05:50:07.006  5547  5593 I jxcore-log: 
,09-30 05:50:07.099  5547  5593 I jxcore-log: 2016-09-30 09:50:07 - DEBUG UnitTest_app: 'Running unit tests'
09-30 05:50:07.099  5547  5593 I jxcore-log: 
,09-30 05:50:07.099  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:50:07.099  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3d57a2 added. We now have 2 listener(s)
,09-30 05:50:07.100  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 05:50:07.100  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:50:07.100  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:50:07.100  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:50:07.100  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ddc33 added. We now have 2 listener(s)
09-30 05:50:07.100  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:50:07.101  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:50:07.102  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:07.104  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:07.105  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:07.105  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:07.106  5547  5593 D executeNativeTests: Running unit tests
,09-30 05:50:07.112  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:07.124  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:07.142  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:50:07.142  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 added. We now have 3 listener(s)
09-30 05:50:07.142  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 05:50:07.143  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:50:07.143  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:50:07.143  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:50:07.143  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e added. We now have 3 listener(s)
,09-30 05:50:07.143  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:50:07.143  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:50:07.148  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:07.155  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:50:07.159  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:07.160  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:07.162  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 05:50:07.162  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:50:07.162  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:50:07.162  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:50:07.162  5547  5593 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-30 05:50:07.162  5547  5593 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 05:50:07.163  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 05:50:07.163  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-30 05:50:07.163  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:50:07.163  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:50:07.163  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:07.163  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:07.163  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:07.163  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:07.163  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.163  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:50:07.164  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:07.164  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:50:07.164  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 removed from the list
09-30 05:50:07.164  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:07.164  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e removed from the list
,09-30 05:50:07.166  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:07.167  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:07.167  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.167  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.167  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.168  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:07.168  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:07.168  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:07.168  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:07.169  5547  5593 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 05:50:07.169  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:07.169  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:50:07.169  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:07.169  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:07.170  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.170  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.170  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:07.170  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:07.170  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:07.170  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:07.172  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:07.172  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:07.172  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.172  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.172  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.172  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.173  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:07.173  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:07.173  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:07.173  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 05:50:07.175  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 05:50:07.176  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 05:50:07.176  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:07.176  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:07.176  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:07.176  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:07.176  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.176  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.176  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:07.176  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:07.177  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:07.177  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:07.177  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:07.177  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.177  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.177  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:07.177  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:07.177  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:07.177  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:07.177  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:07.177  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:07.178  5547  5593 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 05:50:07.179  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:07.181  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:07.182  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:07.182  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:07.182  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:50:07.182  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:50:07.182  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:50:07.182  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:07.182  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:50:07.184  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:07.185  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:50:07.185  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 05:50:07.185  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:07.187  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:50:07.188  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:50:07.188  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 05:50:07.189  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 05:50:07.190  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 05:50:07.190  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:50:07.190  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:50:07.190  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:50:07.191  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:50:07.191  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:50:07.191  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:50:07.193  4490  4732 D BtGatt.GattService: registerClient() - UUID=6b29f3e2-ac29-4ceb-b82d-bab619fa68c4
09-30 05:50:07.194  4490  4573 D BtGatt.GattService: onClientRegistered() - UUID=6b29f3e2-ac29-4ceb-b82d-bab619fa68c4, clientIf=5
09-30 05:50:07.195  5547  5557 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:50:07.198  4490  4512 D BtGatt.GattService: start scan with filters
09-30 05:50:07.202  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:50:07.202  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:50:07.202  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:50:07.202  4490  4579 D BtGatt.ScanManager: handling starting scan
09-30 05:50:07.202  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:50:07.202  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:50:07.202  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:50:07.202  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 05:50:07.203  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:50:07.203  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:50:07.204  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:50:07.204  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:50:07.204  4490  4579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:50:07.205  5547  5593 I io.jxcore.node.ConnectionHelper: start: OK
09-30 05:50:07.211  4490  4573 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:50:07.212  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:07.212  4490  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 05:50:07.220  4490  4573 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:50:07.220  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:07.220  4490  4579 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:50:07.220  4490  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:50:07.232  4490  4573 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:50:07.232  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:07.238  4490  4573 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:50:07.238  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:50:07.705  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 05:50:07.706  5547  5547 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:50:07.706  5547  5547 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 05:50:07.938   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:50:07.943   930  2871 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-30 05:50:10.960   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:50:10.967   930  2871 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 05:50:11.128   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:12.129   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:12.210  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:12.210  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:50:12.210  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:50:12.210  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:12.210  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:50:12.211  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:12.211  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:50:12.211  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 05:50:12.211  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 05:50:12.211  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:50:12.212  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:50:12.212  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:50:12.213  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:50:12.214  4490  4512 D BtGatt.GattService: stopScan() - queue size =1
,09-30 05:50:12.215  4490  4711 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:50:12.215  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:50:12.215  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:50:12.216  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:50:12.216  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 05:50:12.216  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:50:12.216  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:50:12.216  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:50:12.216  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:50:12.217  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:12.218  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:50:12.218  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:50:12.218  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:50:12.219  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:50:12.220  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:50:12.225  4490  4490 D BtGatt.ScanManager: awakened up at time 230637
09-30 05:50:12.225  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:12.225  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:12.225  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:12.225  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:12.225  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:50:12.225  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:12.225  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:12.226  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:12.226  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:12.226  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:12.226  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:12.226  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:12.235  4490  4573 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:50:12.235  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:12.236  4490  4579 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:50:12.244  4490  4573 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 05:50:12.244  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:12.245  4490  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:50:12.266  4490  4573 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 05:50:12.267  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:12.267  4490  4573 D BtGatt.GattService: current time is 230679531878
09-30 05:50:12.267  4490  4573 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -74, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -71, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -73, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -78, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -77, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 05:50:12.269  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 05:50:12.270  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 05:50:12.270  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 05:50:12.271  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-30 05:50:12.271  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 05:50:12.272  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-30 05:50:12.726  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:50:13.130   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:14.131   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:15.132   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:16.133   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 05:50:17.235  5547  5593 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 05:50:17.240  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:17.250  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:50:17.256  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:17.256  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:17.256  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 05:50:17.257  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:50:17.257  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:50:17.257  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:17.257  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:50:17.263  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:17.265  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 05:50:17.265  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 05:50:17.268  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:17.273  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 05:50:17.275  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 05:50:17.275  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:50:17.280  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 05:50:17.280  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:50:17.280  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:50:17.280  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:50:17.281  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:50:17.281  5547  5593 D BluetoothAdapter: STATE_ON
,09-30 05:50:17.284  4490  4512 D BtGatt.GattService: registerClient() - UUID=adeccb49-8047-4ddc-8386-d99b7954d48f
,09-30 05:50:17.285  4490  4573 D BtGatt.GattService: onClientRegistered() - UUID=adeccb49-8047-4ddc-8386-d99b7954d48f, clientIf=5
,09-30 05:50:17.285  5547  5558 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 05:50:17.286  4490  4711 D BtGatt.GattService: start scan with filters
09-30 05:50:17.289  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:50:17.289  4490  4579 D BtGatt.ScanManager: handling starting scan
09-30 05:50:17.289  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:50:17.289  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 05:50:17.289  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:50:17.289  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:50:17.289  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:50:17.289  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:50:17.292  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:50:17.292  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:50:17.292  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:50:17.294  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:50:17.296  4490  4573 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:50:17.296  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:17.296  4490  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:50:17.297  5547  5593 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 05:50:17.299  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:17.300  5547  5593 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 05:50:17.300  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:17.300  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:50:17.300  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:50:17.300  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:50:17.300  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:17.300  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:50:17.300  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:50:17.300  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 05:50:17.300  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:50:17.300  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:50:17.300  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:50:17.301  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:50:17.302  4490  4512 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:50:17.303  4490  4711 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 05:50:17.303  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:50:17.303  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:50:17.303  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:50:17.303  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:50:17.303  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:50:17.303  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:50:17.303  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:50:17.303  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:50:17.304  4490  4573 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:50:17.304  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:17.305  4490  4579 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:50:17.305  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:17.305  4490  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:50:17.305  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:50:17.305  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-30 05:50:17.305  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:50:17.305  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:50:17.306  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:50:17.307  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:17.307  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:17.307  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:17.307  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:17.307  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:50:17.307  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:17.307  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:17.308  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:17.308  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:17.308  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:17.308  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:17.308  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:17.309  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:17.309  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:17.310  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:17.310  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:17.310  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:17.310  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:17.311  5547  5593 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 05:50:17.313  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:17.318  4490  4573 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:50:17.318  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:17.320  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:50:17.324  4490  4573 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 05:50:17.324  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:17.324  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:17.324  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:17.324  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:50:17.324  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:50:17.325  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:50:17.325  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:17.325  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 05:50:17.327  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 05:50:17.328  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:50:17.328  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:17.331  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:17.331  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:50:17.332  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 05:50:17.332  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 05:50:17.332  4490  4573 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:50:17.332  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:17.332  4490  4579 D BtGatt.ScanManager: stopping BLe Batch
09-30 05:50:17.335  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:50:17.335  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:50:17.335  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:50:17.335  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:50:17.335  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:50:17.336  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:50:17.336  4490  4573 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:50:17.337  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:17.337  4490  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:50:17.338  4490  4512 D BtGatt.GattService: registerClient() - UUID=8d531850-2efc-4ff9-afef-8def8ecf2a2b
,09-30 05:50:17.341  4490  4573 D BtGatt.GattService: onClientRegistered() - UUID=8d531850-2efc-4ff9-afef-8def8ecf2a2b, clientIf=5
,09-30 05:50:17.341  5547  5557 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:50:17.342  4490  4711 D BtGatt.GattService: start scan with filters
09-30 05:50:17.342  4490  4573 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:50:17.342  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:50:17.344  4490  4579 D BtGatt.ScanManager: handling starting scan
,09-30 05:50:17.344  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:50:17.344  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:50:17.344  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:50:17.344  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:50:17.344  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:50:17.344  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:50:17.344  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:50:17.346  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:50:17.347  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:50:17.347  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:50:17.348  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:50:17.349  4490  4573 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:50:17.349  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:17.349  4490  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:50:17.350  5547  5593 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 05:50:17.354  4490  4573 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:50:17.355  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:50:17.355  4490  4579 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:50:17.355  4490  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 05:50:17.363  4490  4573 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:50:17.363  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:50:17.368  4490  4573 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 05:50:17.368  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:50:17.849  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 05:50:17.850  5547  5547 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 05:50:17.850  5547  5547 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 05:50:21.134   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:22.118   930  5281 D NetlinkSocketObserver: NeighborEvent{elapsedMs=240530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-30 05:50:22.134   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:22.350  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:50:22.351  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:22.351  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-30 05:50:22.351  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:22.351  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 05:50:22.351  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 05:50:22.352  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:50:22.352  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:50:22.352  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:50:22.352  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 05:50:22.352  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:50:22.353  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:50:22.355  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:50:22.357  4490  4732 D BtGatt.GattService: stopScan() - queue size =1
,09-30 05:50:22.359  4490  4510 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 05:50:22.359  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:50:22.360  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:50:22.360  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:50:22.360  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:50:22.360  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:50:22.360  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:50:22.361  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:50:22.361  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:50:22.364  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:22.365  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:50:22.365  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:50:22.365  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-30 05:50:22.365  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 05:50:22.367  4490  4490 D BtGatt.ScanManager: awakened up at time 240779
09-30 05:50:22.370  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:50:22.372  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:22.372  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:22.372  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 05:50:22.375  4490  4573 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:50:22.375  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:22.375  4490  4579 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:50:22.384  4490  4573 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 05:50:22.384  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:22.384  4490  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:50:22.405  4490  4573 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-30 05:50:22.406  4490  4573 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:50:22.406  4490  4573 D BtGatt.GattService: current time is 240818501234
,09-30 05:50:22.406  4490  4573 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -74, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -76, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -72, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 05:50:22.406  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 05:50:22.407  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 05:50:22.407  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 05:50:22.407  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 05:50:22.408  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 05:50:22.408  4490  4573 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 05:50:22.873  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:50:22.874  5547  5547 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:22.874  5547  5547 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 05:50:23.135   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:24.137   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:25.139   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:26.139   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 05:50:27.373  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:50:27.374  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:50:27.374  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.374  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.374  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:50:27.375  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:50:27.375  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.375  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.375  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:27.375  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.375  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.376  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.377  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.377  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.380  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:50:27.381  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.381  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.381  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.383  5547  5593 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-30 05:50:27.386  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.386  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:50:27.386  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.386  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.387  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.387  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.387  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.388  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.388  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.388  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.388  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:50:27.388  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.388  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.389  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.389  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.392  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.392  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.392  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.392  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:27.394  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-30 05:50:27.394  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.394  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.394  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.394  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.395  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.395  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.395  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.395  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
,09-30 05:50:27.395  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.395  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.395  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.395  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.395  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.395  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.395  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.397  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.397  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.397  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:27.397  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:27.398  5547  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 05:50:27.399  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.399  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.399  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.399  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.399  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.399  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.399  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.399  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.399  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.400  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:27.400  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.400  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.400  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.400  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.400  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.401  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.401  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.401  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.402  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.403  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 05:50:27.403  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.403  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.403  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.403  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 05:50:27.403  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.403  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.403  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.403  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.404  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.404  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.404  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.404  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.404  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.404  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.404  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:27.405  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.406  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.406  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.406  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:27.407  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 05:50:27.407  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:50:27.407  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:50:27.407  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 05:50:27.408  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:50:27.408  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:50:27.408  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 05:50:27.408  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-30 05:50:27.408  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:50:27.408  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.408  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.409  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.409  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.409  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.409  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.409  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.409  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.409  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.409  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.409  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:50:27.409  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.409  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.409  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.410  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.411  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.411  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.411  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.411  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:27.412  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:50:27.412  5547  5593 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 05:50:27.413  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-30 05:50:27.416  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:50:27.416  5547  5593 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 05:50:27.416  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 05:50:27.417  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 05:50:27.418  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 05:50:27.418  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 05:50:27.418  5547  5593 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 05:50:27.418  5547  5593 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 05:50:27.418  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:50:27.418  5547  5593 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-30 05:50:27.418  5547  5593 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 05:50:27.418  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:50:27.418  5547  5593 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 05:50:27.418  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-30 05:50:27.422  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-30 05:50:27.423  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-30 05:50:27.423  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-30 05:50:27.424  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-30 05:50:27.425  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 05:50:27.425  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 05:50:27.425  5547  5593 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:50:27.425  5547  5593 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 05:50:27.425  5547  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-30 05:50:27.426  5547  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 05:50:27.426  5547  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 05:50:27.426  5547  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-30 05:50:27.426  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.426  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.426  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.426  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.426  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.426  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.426  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 05:50:27.426  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 05:50:27.427  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.427  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.427  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.427  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.427  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.428  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.428  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.428  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:27.428  5547  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-30 05:50:27.428  5547  5596 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 05:50:27.429  5547  5596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:50:27.430  4512  4512 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30502]" dev="sockfs" ino=30502 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:50:27.430  4512  4512 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30502]" dev="sockfs" ino=30502 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:50:27.430  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.430  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.430  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.430  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.431  5547  5593 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 05:50:27.431  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.431  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.431  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.432  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.432  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.432  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.432  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.432  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.432  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.432  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.432  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.432  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.432  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.432  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.432  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.433  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.433  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.433  5547,  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.433  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.435  5547  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 05:50:27.435  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.435  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.435  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.435  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.435  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.435  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.435  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.435  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.435  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.435  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.435  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.435  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.435  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.436  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.436  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:27.436  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.436  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.437  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.437  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.437  5547  5593 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 05:50:27.437  5547  5593 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 05:50:27.438  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 05:50:27.438  5547  5593 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 05:50:27.438  5547  5593 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 05:50:27.438  5547  5593 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 05:50:27.438  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 05:50:27.438  5547  5593 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 05:50:27.438  5547  5593 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-30 05:50:27.438  5547  5593 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 05:50:27.438  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 05:50:27.438  5547  5593 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 05:50:27.438  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:27.438  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:27.438  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:27.438  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.438  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.438  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.439  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.439  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.439  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.439  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.439  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.439  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:50:27.439  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.439  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.439  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.440  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:27.440  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:27.440  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.440  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.441  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:27.441  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.441  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:27.441  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:27.441  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:27.441  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:27.441  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:27.441  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:27.441  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:27.442  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:32.442  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:32.443  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.443  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.443  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.443  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:32.443  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.443  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:32.444  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:50:32.444  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:32.444  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:32.444  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.444  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:50:32.445  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.445  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.445  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:32.445  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:32.445  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:32.446  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:32.446  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.446  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:32.446  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.446  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.449  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:50:32.449  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:32.449  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.449  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:32.453  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-30 05:50:32.454  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:32.456  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 05:50:32.458  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-30 05:50:32.458  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-30 05:50:32.458  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-30 05:50:32.459  5547  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-30 05:50:32.459  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 05:50:32.459  5547  5547 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 05:50:32.459  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 05:50:32.460  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.460  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-30 05:50:32.460  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 05:50:32.461  5547  5598 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:50:32.461  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 05:50:32.462  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.462  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 05:50:32.462  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 05:50:32.462  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:32.462  5547  5547 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 05:50:32.462  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.462  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 05:50:32.462  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:50:32.463  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:50:32.463  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.463  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.460  4510  4510 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30507]" dev="sockfs" ino=30507 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:50:32.460  4510  4510 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30507]" dev="sockfs" ino=30507 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:50:32.464  5547  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-30 05:50:32.464  5547  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 05:50:32.464  5547  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-30 05:50:32.465  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:32.465  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.465  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:32.465  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:50:32.465  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:50:32.465  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:32.466  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:32.466  5547  5547 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 05:50:32.466  5547  5547 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.466  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.466  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:50:32.466  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.466  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.466  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.466  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:32.466  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:32.466  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.466  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:32.466  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.467  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.467  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.467  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:32.468  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:32.468  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:32.468  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.469  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.470  5547  5593 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-30 05:50:32.470  5547  5593 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-30 05:50:32.471  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 05:50:32.471  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:50:32.471  5547  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:50:32.472  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:32.472  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:32.472  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:50:32.472  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.472  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.472  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.472  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.472  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
,09-30 05:50:32.472  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.473  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.473  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:32.473  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.473  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.473  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.473  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:32.474  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:32.475  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:32.475  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.475  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:32.481  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:50:32.481  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:32.481  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:32.481  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.481  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.481  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.481  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.481  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:32.481  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:32.482  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.482  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:32.482  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.482  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.482  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.482  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.483  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:32.483  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:32.483  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.483  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:32.484  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:50:32.485  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:50:32.485  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:50:32.485  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:50:32.485  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.485  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.485  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:50:32.485  5547  5593 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b642ad9 not in the list
09-30 05:50:32.485  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.485  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
09-30 05:50:32.485  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:32.485  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:32.485  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.485  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:50:32.485  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:32.486  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:50:32.486  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:50:32.487  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:50:32.487  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a8c9e not in the list
,09-30 05:50:32.488  5547  5593 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 05:50:32.488  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 05:50:32.488  5547  5593 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-30 05:50:32.488  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 05:50:32.488  5547  5593 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 05:50:32.489  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-30 05:50:32.491  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-30 05:50:32.491  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-30 05:50:32.492  5547  5593 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 05:50:32.492  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 05:50:32.492  5547  5593 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-30 05:50:32.492  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 05:50:32.493  5547  5593 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 05:50:32.493  5547  5593 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-30 05:50:32.493  5547  5593 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-30 05:50:32.493  5547  5593 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 05:50:32.493  5547  5593 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-30 05:50:32.493  5547  5593 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 05:50:32.494  5547  5593 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-30 05:50:32.494  5547  5593 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-30 05:50:32.494  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:50:32.495  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@978b250 added. We now have 3 listener(s)
09-30 05:50:32.495  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:50:32.497  5547  5593 D BluetoothAdapter: enable(): BT is already enabled..!
09-30 05:50:32.497   930   940 D WifiService: setWifiEnabled: true pid=5547, uid=10077
09-30 05:50:32.497   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:50:32.557  4490  4678 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-30 05:50:32.558  4490  4707 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-30 05:50:32.558  5547  5596 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-30 05:50:32.558  5547  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 05:50:32.558  5547  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,09-30 05:50:32.966  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:50:36.141   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:37.142   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:37.502  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:50:37.503  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8987c49 added. We now have 4 listener(s)
09-30 05:50:37.503  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:50:37.515  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:37.515  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8987c49 removed from the list
,09-30 05:50:37.516  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:37.516  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:37.516  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:50:37.518  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:50:37.518  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@841594e added. We now have 4 listener(s)
09-30 05:50:37.518  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:50:37.522  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:50:37.522  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@841594e removed from the list
09-30 05:50:37.522  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:50:37.522  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:50:37.522  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:50:37.524  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:50:37.524  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5cfa6f added. We now have 4 listener(s)
09-30 05:50:37.524  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:50:37.528   930  3713 D WifiService: setWifiEnabled: false pid=5547, uid=10077
,09-30 05:50:37.529   930  3713 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:50:37.536   930  2869 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 05:50:37.536   930  2869 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-30 05:50:37.536   930  2869 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 05:50:37.536   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:50:37.544  4490  4569 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 05:50:37.544  4490  4569 D BluetoothAdapterProperties: Setting state to 13
09-30 05:50:37.544  4490  4569 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 05:50:37.545  4490  4569 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 05:50:37.546  4490  4569 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:50:37.546  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:50:37.549  4490  4490 D BluetoothMapService: onReceive
09-30 05:50:37.549  4490  4490 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:50:37.549  4490  4490 D BluetoothMapService: STATE_TURNING_OFF
09-30 05:50:37.550  4490  4490 D BluetoothMapService: MAP Service closeService in
09-30 05:50:37.551  4490  4490 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 05:50:37.551  4490  4490 D ObexServerSockets0: shutdown(block = true)
,09-30 05:50:37.552  4490  4490 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-30 05:50:37.552  4490  4490 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:50:37.552  4490  4707 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 05:50:37.552  4490  4735 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 05:50:37.553  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:37.553  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:37.553  4490  4734 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-30 05:50:37.555  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.555  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:37.556  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:50:37.559   930  5282 D DhcpClient: Clearing IP address
09-30 05:50:37.560   507   924 D CommandListener: Clearing all IP addresses on wlan0
09-30 05:50:37.561  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.562  4490  4490 I BtOppRfcommListener: stopping Accept Thread
,09-30 05:50:37.563  4490  5207 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-30 05:50:37.563  4490  5207 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 05:50:37.565  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.568  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:37.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:37.569   930   943 I ActivityManager: Start proc 5602:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-30 05:50:37.570  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.570  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:37.570  4490  4573 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:50:37.571  4490  4569 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 05:50:37.572   507   924 D CommandListener: Setting iface cfg
,09-30 05:50:37.574  4490  4490 D HeadsetService: Received stop request...Stopping profile...
09-30 05:50:37.576   930   930 D BluetoothHeadset: Proxy object disconnected
,09-30 05:50:37.576   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:37.576  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:37.577  3037  5546 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:37.577  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:50:37.577  3037  3037 D HeadsetProfile: Bluetooth service disconnected
09-30 05:50:37.577   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:37.579  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.579  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:37.579  3674  5083 D BluetoothHeadset: Proxy object disconnected
,09-30 05:50:37.582  3468  5336 V NativeCrypto: Read error: ssl=0x7f844c5480: I/O error during system call, Connection timed out
,09-30 05:50:37.583  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.583  4490  4490 D A2dpService: Received stop request...Stopping profile...
09-30 05:50:37.583  3468  5336 V NativeCrypto: SSL shutdown failed: ssl=0x7f844c5480: I/O error during system call, Broken pipe
,09-30 05:50:37.584  4490  4717 D A2dpStateMachine: Exit Disconnected: -1
09-30 05:50:37.585   930  3034 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-30 05:50:37.586   930  5280 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-30 05:50:37.586   930  5283 D DhcpClient: Receive thread stopped
09-30 05:50:37.586   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 05:50:37.586   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 05:50:37.586  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.589   536   536 E Parcel  : Reading a NULL string not supported here.
,09-30 05:50:37.590   930   930 D BluetoothA2dp: Proxy object disconnected
09-30 05:50:37.590  3037  3037 D BluetoothA2dp: Proxy object disconnected
09-30 05:50:37.591  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.591  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:37.591  4490  4490 D HidService: Received stop request...Stopping profile...
09-30 05:50:37.591  4490  4490 D HidService: Stopping Bluetooth HidService
09-30 05:50:37.592  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:37.592  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:37.592   930   930 D RttService: SCAN_AVAILABLE : 1
09-30 05:50:37.593  3037  3037 D BluetoothInputDevice: Proxy object disconnected
09-30 05:50:37.593   930  2979 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 05:50:37.593  3037  3037 D HidProfile: Bluetooth service disconnected
09-30 05:50:37.593  4490  4490 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:37.593  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.593  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:37.593  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.595   930  5280 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-30 05:50:37.595  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.596  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:37.597  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.597  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:50:37.599   930  2871 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-30 05:50:37.600  4490  4490 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 05:50:37.600  4490  4490 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 05:50:37.601  4490  4573 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 05:50:37.601  4490  4678 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:37.601  4490  4678 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:37.601  4490  4678 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 05:50:37.601  4490  4573 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 05:50:37.602  3644  3790 W QCNEJ   : |CORE| network lost: 100
09-30 05:50:37.602  3644  3790 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 05:50:37.603  4490  4490 D HealthService: Received stop request...Stopping profile...
09-30 05:50:37.605  4490  4490 D PanService: Received stop request...Stopping profile...
,09-30 05:50:37.607  4490  4490 D BluetoothMapService: Received stop request...Stopping profile...
09-30 05:50:37.607   930  2869 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 05:50:37.607  4490  4490 D BluetoothMapService: stop()
09-30 05:50:37.608  4490  4490 D BluetoothMapAppObserver: deinitObservers()
09-30 05:50:37.608  4490  4490 D BluetoothMapAppObserver: removeReceiver()
09-30 05:50:37.610  4490  4490 D SapService: Received stop request...Stopping profile...
09-30 05:50:37.610  4490  4490 V SapService: stop()
09-30 05:50:37.611  4490  4490 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:37.611  4490  4490 V BluetoothAdapterState: isTurningOn()=false
,09-30 05:50:37.612  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 05:50:37.612  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.614  4490  4573 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 05:50:37.614  4490  4678 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:37.614  4490  4678 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:37.614  4490  4490 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:37.614  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.614  4490  4678 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:50:37.614  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:37.614  4490  4678 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:50:37.614  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.615  4490  4678 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:50:37.615  4490  4678 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:50:37.615  4490  4490 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-30 05:50:37.615  4490  4490 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 05:50:37.615  4490  4490 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:37.615  4490  4573 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 05:50:37.615  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.615  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:37.615  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.616  4490  4490 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 05:50:37.616   930  2869 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 05:50:37.616  4490  4490 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 05:50:37.616  4490  4490 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:37.616  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.616  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:37.616  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.616  4490  4490 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 05:50:37.617  4490  4490 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 05:50:37.617  4490  4573 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 05:50:37.617  3037  3037 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 05:50:37.617  3037  3037 D PanProfile: Bluetooth service disconnected
09-30 05:50:37.617  4490  4490 D BluetoothMapService: MAP Service closeService in
09-30 05:50:37.617  3037  3037 D BluetoothMap: Proxy object disconnected
09-30 05:50:37.617  3037  3037 D MapProfile: Bluetooth service disconnected
09-30 05:50:37.617  4490  4490 V BluetoothAdapterState: isTurningOff()=true
,09-30 05:50:37.617  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.618  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:37.618  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.618  4490  4490 D BluetoothMapService: cleanup()
09-30 05:50:37.618  4490  4490 D BluetoothMapService: MAP Service closeService in
09-30 05:50:37.618  4490  4490 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:37.618  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.618  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:37.618  4490  4490 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:37.618  4490  4569 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 05:50:37.618  4490  4569 D BluetoothAdapterProperties: Setting state to 15
09-30 05:50:37.618  4490  4569 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 05:50:37.619  3037  5546 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 05:50:37.620  4490  4569 I BluetoothAdapterState: Entering BleOnState
09-30 05:50:37.620  3037  3861 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:37.621   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:37.621  3037  3051 D BluetoothMap: onBluetoothStateChange: up=false
09-30 05:50:37.621  3037  3050 D BluetoothPan: onBluetoothStateChange on: false
09-30 05:50:37.622  3037  5546 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:50:37.627   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:50:37.627   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:37.628   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:37.628  3674  3702 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 05:50:37.628  3037  3051 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 05:50:37.629  4490  4569 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-30 05:50:37.629  4490  4569 D BluetoothAdapterProperties: Setting state to 16
09-30 05:50:37.629  4490  4569 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 05:50:37.630   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 05:50:37.631  4490  4569 D BluetoothAdapterProperties: onBleDisable
09-30 05:50:37.631  4490  4569 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:50:37.631  4490  4570 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 05:50:37.632  4490  4573 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:50:37.633  4490  4678 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 05:50:37.633  4490  4678 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:37.634  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.634  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:50:37.636  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:37.636  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:37.638  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.639  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:37.641  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.641  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:37.643  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:37.644  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.646  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:37.650   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:50:37.650   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-30 05:50:37.650   507   924 D TetherController: Setting IP forward enable = 0
09-30 05:50:37.651   930  2871 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-30 05:50:37.652   930  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:50:37.654   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-30 05:50:37.655  5192  5192 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@34a2244 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 05:50:37.656  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.657   930  2869 D DhcpClient: doQuit
09-30 05:50:37.657   930  2869 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 05:50:37.657  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.658   930  5282 D DhcpClient: onQuitting
09-30 05:50:37.658  3362  3362 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 05:50:37.659  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.662  4945  4968 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:50:37.662  4945  4968 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:50:37.662  4945  4968 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 05:50:37.662  4945  4968 E SarControlService: no key has been found,reset the power
09-30 05:50:37.662  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:50:37.663  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:50:37.663  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-30 05:50:37.663  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:50:37.663  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.663  4970  4970 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:37.665  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.665  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:37.667  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.667  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:37.668  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.668  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:37.670  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:  ,   - BSSID name: null
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:37.670  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:37.670  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:50:37.670  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:50:37.670  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:50:37.670  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:37.670  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:50:37.674  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000ea03000000000000ffffffff]
,09-30 05:50:37.674  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:50:37.674  4970  4984 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 05:50:37.675  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:50:37.675  4970  4970 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:50:37.676  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:50:37.676  4945  4956 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 05:50:37.681  5602  5602 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-30 05:50:37.682  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000eb03000000000000ffffffff]
09-30 05:50:37.682  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:50:37.682  4970  4984 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 05:50:37.682  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:50:37.683  4945  4955 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 05:50:37.683  3362  3362 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-30 05:50:37.688  3362  3362 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 05:50:37.694  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:50:37.699   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8d095c:true
,09-30 05:50:37.700  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:50:37.712  3362  3362 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 05:50:37.713   930  3920 I ActivityManager: Start proc 5630:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 05:50:37.714  3362  3362 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 05:50:37.723   930  2869 D wifi    : In wifi stop Hal
,09-30 05:50:37.725   930  2869 D wifi    : halHandle = 0x7f82ce7400, mVM = 0x7f9f2cd140, mCls = 0x100a02
09-30 05:50:37.725   930  3360 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 05:50:37.725   930  3360 D WifiHAL : Got a signal to exit!!!
09-30 05:50:37.725   930  3360 I WifiHAL : Exit wifi_event_loop
09-30 05:50:37.726  4919  4919 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 05:50:37.727   930  2869 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 05:50:37.727   930  2869 E WifiHAL : Event processing terminated
09-30 05:50:37.727   930  2869 D wifi    : In wifi cleaned up handler
09-30 05:50:37.727   930  2869 I WifiHAL : Internal cleanup completed
,09-30 05:50:37.729  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.731  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.732  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:37.735  4024  4136 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 05:50:37.740  5602  5602 D LocalBluetoothProfileManager: Adding local MAP profile
,09-30 05:50:37.743  5602  5602 D BluetoothMap: Create BluetoothMap proxy object
,09-30 05:50:37.750   930  3360 D wifi    : set interface wlan0 flags (DOWN)
,09-30 05:50:37.750   930  2869 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 05:50:37.755  5602  5602 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 05:50:37.763  5630  5630 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 05:50:37.774  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:50:37.777   930  3483 I ActivityManager: Killing 4884:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 05:50:37.837  4490  4573 I bt_hci  : shut_down
,09-30 05:50:37.841  4490  4580 D bt_hwcfg: hw_epilog_process
,09-30 05:50:37.841  4490  4580 I bt_vendor: low_power_mode_cb
,09-30 05:50:37.843  4490  4580 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-30 05:50:37.843  4490  4580 I bt_vendor: epilog_cb
09-30 05:50:37.843  4490  4580 I bt_hci  : epilog_finished_callback
,09-30 05:50:37.846  4490  4573 I bt_hci_h4: hal_close
,09-30 05:50:37.847  4490  4573 I bt_userial_vendor: device fd = 54 close
,09-30 05:50:37.953   930   947 D Tethering: InitialState.processMessage what=4
,09-30 05:50:37.953  4490  4570 D bt_stack_manager: event_shut_down_stack finished.
09-30 05:50:37.954  4490  4569 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 05:50:37.956  4490  4569 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 05:50:37.956  4490  4490 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 05:50:37.956   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-30 05:50:37.957  4490  4490 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 05:50:37.957  4490  4490 D BtGatt.GattService: stop()
09-30 05:50:37.957  4490  4490 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 05:50:37.959  4490  4490 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:50:37.959  4490  4490 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:37.959  4490  4490 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 05:50:37.959  4490  4490 V BluetoothAdapterState: isBleTurningOff()=true
09-30 05:50:37.960  4490  4569 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 05:50:37.960  4490  4569 D BluetoothAdapterProperties: Setting state to 10
09-30 05:50:37.960  4490  4569 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-30 05:50:37.960  4490  4569 I BluetoothAdapterState: Entering OffState
,09-30 05:50:37.961   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-30 05:50:37.968  4490  4490 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 05:50:37.969  4490  4490 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 05:50:37.969  4490  4490 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 05:50:37.970  4490  4570 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 05:50:37.973  4490  4490 I art     : System.exit called, status: 0
,09-30 05:50:37.973  4490  4490 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 05:50:38.012  5630  5630 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.012  5630  5630 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.012  5630  5630 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.012  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.013  5630  5630 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.013  5630  5630 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.013  5630  5630 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.013  5630  5630 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.013  5630  5630 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:50:38.013  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:50:38.017  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 05:50:38.021   930  3034 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-30 05:50:38.022   930  3034 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-30 05:50:38.023   930  3034 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-30 05:50:38.023   930  3034 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-30 05:50:38.023   930  3034 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-30 05:50:38.036   930  3034 I ActivityManager: Start proc 5662:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-30 05:50:38.037   930  3713 W ActivityManager: Spurious death for ProcessRecord{918588b 5662:com.android.bluetooth/1002}, curProc for 4490: null
09-30 05:50:38.040  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-30 05:50:38.041   930   941 I ActivityManager: Killing 5018:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-30 05:50:38.129  5662  5662 D AdapterServiceConfig: Adding HeadsetService
,09-30 05:50:38.129  5662  5662 D AdapterServiceConfig: Adding A2dpService
09-30 05:50:38.129  5662  5662 D AdapterServiceConfig: Adding HidService
09-30 05:50:38.129  5662  5662 D AdapterServiceConfig: Adding HealthService
09-30 05:50:38.129  5662  5662 D AdapterServiceConfig: Adding PanService
09-30 05:50:38.130  5662  5662 D AdapterServiceConfig: Adding GattService
09-30 05:50:38.130  5662  5662 D AdapterServiceConfig: Adding BluetoothMapService
,09-30 05:50:38.130  5662  5662 D AdapterServiceConfig: Adding SapService
,09-30 05:50:38.142   930  3112 I ActivityManager: Killing 5356:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-30 05:50:38.143   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:38.165  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:50:38.180  3817  3817 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 05:50:38.183  3817  3817 D SystemUpdateService: onCreate
,09-30 05:50:38.186  3817  3817 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 05:50:38.195  3817  3817 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 05:50:38.199  3817  5306 I iu.UploadsManager: num queued entries: 0
,09-30 05:50:38.199  3817  5306 I iu.UploadsManager: num updated entries: 0
09-30 05:50:38.200  3817  5306 I iu.SyncManager: NEXT; no task
,09-30 05:50:38.202  3817  3817 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:50:38.204  3817  3817 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 05:50:38.208  3817  5675 I SystemUpdateService: active receiver: enabled
,09-30 05:50:38.216   930   941 I ActivityManager: Start proc 5677:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 05:50:38.220  3817  5675 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:50:38.223  3817  5675 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 05:50:38.225  3817  5675 I SystemUpdateService: now status is 0 (complete)
09-30 05:50:38.226  3817  5675 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:50:38.226  3817  5675 I SystemUpdateService: file has been verified
09-30 05:50:38.226  3817  5675 I SystemUpdateService: OTA package size = 21989297
,09-30 05:50:38.251  3817  5675 I SystemUpdateService: showing system update notification
,09-30 05:50:38.258  5677  5677 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 05:50:38.261  5677  5677 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:50:38.268  5677  5677 D SprintDMHelper: simOperator: 
,09-30 05:50:38.268  5677  5677 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:50:38.280   930   940 I ActivityManager: Start proc 5689:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 05:50:38.292  3817  3817 D SystemUpdateService: onDestroy
,09-30 05:50:38.294   930   941 I ActivityManager: Killing 5340:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-30 05:50:38.377  4919  5703 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 05:50:38.386   930   941 I ActivityManager: Start proc 5704:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-30 05:50:38.388   930  3034 I ActivityManager: Killing 5192:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 05:50:38.450  5704  5704 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-30 05:50:38.628   930  3034 I ActivityManager: Killing 4584:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 05:50:38.648  5630  5650 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 05:50:38.659   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@55f5daf:true
,09-30 05:50:38.665   930   941 I ActivityManager: Start proc 5717:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 05:50:38.697  5717  5717 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 05:50:38.702   507   924 E Netd    : netlink response contains error (No such file or directory)
,09-30 05:50:38.703   930  2871 E NetdConnector: NDC Command {113 network destroy 100} took too long (1051ms)
09-30 05:50:38.703   930  2871 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 05:50:38.703   930  2871 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 05:50:38.704   930  2867 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1047ms)
09-30 05:50:38.705   930  2866 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (747ms)
09-30 05:50:38.705   507   924 D TetherController: Setting IP forward enable = 0
,09-30 05:50:38.710   930  3920 I ActivityManager: Killing 5408:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 05:50:39.144   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:40.144   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:41.145   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 05:50:42.559   930  3467 D WifiService: setWifiEnabled: true pid=5547, uid=10077
,09-30 05:50:42.559   930  3467 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:50:42.570   507   924 D SoftapController: Softap fwReload - Ok
,09-30 05:50:42.575   507   924 D CommandListener: Setting iface cfg
,09-30 05:50:42.575   507   924 D CommandListener: Trying to bring down wlan0
,09-30 05:50:42.576   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-30 05:50:42.582   930  2869 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 05:50:43.154   930  2869 D wifi    : set interface wlan0 flags (UP)
,09-30 05:50:43.156   930  2869 I WifiHAL : Initializing wifi
,09-30 05:50:43.156   930  2869 I WifiHAL : Creating socket
09-30 05:50:43.158   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 05:50:43.161   930  2869 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 05:50:43.162   930  2869 D wifi    : Did set static halHandle = 0x7f82ce7400
09-30 05:50:43.162   930  2869 D wifi    : halHandle = 0x7f82ce7400, mVM = 0x7f9f2cd140, mCls = 0x1018ca
09-30 05:50:43.162   930  2869 D wifi    : array field set
09-30 05:50:43.162   930  2869 I WifiNative-HAL: interface[0] = wlan0
09-30 05:50:43.163   930  5740 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547655414784
09-30 05:50:43.163   930  5740 D wifi    : waitForHalEvents called, vm = 0x7f9f2cd140, obj = 0x1018ca, env = 0x7f94752380
,09-30 05:50:43.230  5741  5741 I wpa_supplicant: Successfully initialized wpa_supplicant
09-30 05:50:43.247  5741  5741 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-30 05:50:43.265   930  2869 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 05:50:43.270  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:43.273  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:43.276  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:43.293  5741  5741 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-30 05:50:43.293  5741  5741 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 05:50:43.308   930  2869 D WifiConfigStore: Loading config and enabling all networks 
,09-30 05:50:43.308  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:43.308  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:43.308  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:43.308  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:50:43.310  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:43.310  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:43.310  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:43.310  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:43.312  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:43.312  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:43.312  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:43.312  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:50:43.317   930  2869 D WifiConfigStore: loaded 0 passpoint configs
,09-30 05:50:43.318   930  2869 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 05:50:43.318   930  2869 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 05:50:43.319   930  2869 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-30 05:50:43.320   930  2869 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 05:50:43.320   930  2869 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 05:50:43.320   930  2869 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 05:50:43.320   930  2869 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-30 05:50:43.323  4919  4919 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 05:50:43.323   930  2869 D WifiNative-HAL: Setting external_sim to 1
09-30 05:50:43.323   930  2869 D wifi    : setting dfs flag to true, 0x7f854974e0
09-30 05:50:43.324   930  2869 D WifiStateMachine: Setting OUI to DA-A1-19
,09-30 05:50:43.324   930  2869 D wifi    : setting scan oui 0x7f854974e0
09-30 05:50:43.324   930  2869 D WifiHAL : Sending mac address OUI
,09-30 05:50:43.329   930  2869 E native  : do suspend false
,09-30 05:50:43.337   930  2869 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-30 05:50:43.337   930   930 D RttService: SCAN_AVAILABLE : 3
09-30 05:50:43.337   507   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 05:50:43.337   930  2979 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 05:50:43.338   507   924 D CommandListener: Setting iface cfg
,09-30 05:50:43.342   930  2868 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-30 05:50:43.342   930  2868 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 05:50:43.351   930  2868 D WifiNative-HAL: p2pGetDeviceAddress
09-30 05:50:43.352   930  2868 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 05:50:43.358   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=261771 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,09-30 05:50:46.561  5741  5741 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:50:46.572  5741  5741 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:50:46.578  5741  5741 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:50:46.584  5741  5741 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:50:46.612   930  2869 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 05:50:46.613   930  2869 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 05:50:46.614   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:50:46.626   930  2869 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 05:50:46.661   930  2869 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 05:50:46.663  5741  5741 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 05:50:47.103  5741  5741 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 05:50:47.144  5741  5741 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 05:50:47.146  5741  5741 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 05:50:47.155   930  2869 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:50:47.155   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:50:47.155   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 05:50:47.175   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:50:47.189   507   924 D CommandListener: Setting iface cfg
,09-30 05:50:47.195   930  2869 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 05:50:47.203   930  5747 D DhcpClient: Receive thread started
,09-30 05:50:47.209   930  2869 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-30 05:50:47.209   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-30 05:50:47.209   930  2871 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 05:50:47.301   930  2869 E native  : do suspend false
,09-30 05:50:47.324   930  5746 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 05:50:47.339   930  5747 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172576, domain null
,09-30 05:50:47.340   930  5746 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172576 seconds
,09-30 05:50:47.344   930  5746 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 05:50:47.376   930  5747 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 05:50:47.377   930  5746 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 05:50:47.380   507   924 D CommandListener: Setting iface cfg
09-30 05:50:47.386   930  2869 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 05:50:47.390   930  5746 D DhcpClient: Scheduling renewal in 86399s
,09-30 05:50:47.405   930  2869 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 05:50:47.405   930  2869 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 05:50:47.406   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 05:50:47.410   930  2871 D ConnectivityService: Adding iface wlan0 to network 101
,09-30 05:50:47.413   930  2869 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 05:50:47.462   930  2871 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 05:50:47.462   930  2871 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 05:50:47.468   930  2871 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 05:50:47.470   930  2871 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 05:50:47.472   930  2871 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 05:50:47.480   930  2871 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 05:50:47.484   930  2871 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 05:50:47.485   930  2871 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 05:50:47.485   930  2871 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 05:50:47.485   930  2871 D ConnectivityService:    accepting network in place of null
09-30 05:50:47.485   930  2869 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 05:50:47.485   930  2869 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:50:47.485   930  2871 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:50:47.504   930  5745 D NetlinkSocketObserver: NeighborEvent{elapsedMs=265916, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 05:50:47.510   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:50:47.531   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:50:47.534   930  2871 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-30 05:50:47.534  3644  3790 W QCNEJ   : |CORE| network available: 101
09-30 05:50:47.534   930  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 05:50:47.535   930  2871 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-30 05:50:47.536  3644  3790 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 05:50:47.537   930   947 D Tethering: MasterInitialState.processMessage what=3
09-30 05:50:47.538  3644  3790 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 05:50:47.538  3644  3790 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 05:50:47.540  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:47.540  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:47.540  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.540  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:47.545  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:47.545  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:47.545  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.545  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:47.547  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:50:47.547  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:50:47.547  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.547  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:50:47.549  4945  4968 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:50:47.549  4945  4968 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:50:47.549  4945  4968 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 05:50:47.549  4945  4968 E SarControlService: no key has been found,reset the power
,09-30 05:50:47.549  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:50:47.549  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:50:47.550  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 05:50:47.550  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:50:47.550  4970  4970 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-30 05:50:47.553  3817  3817 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 05:50:47.556  3817  3817 D SystemUpdateService: onCreate
09-30 05:50:47.557  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:50:47.557  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:50:47.557  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:50:47.558  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000ec03000000000000ffffffff]
09-30 05:50:47.558  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:50:47.558  4970  4984 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 05:50:47.559  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:50:47.559  4970  4970 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:50:47.560  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:50:47.560  4945  4956 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 05:50:47.563  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000ed03000000000000ffffffff]
09-30 05:50:47.563  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:50:47.563  4970  4984 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-30 05:50:47.564  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 05:50:47.564  4945  4955 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 05:50:47.565  3817  3817 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 05:50:47.569   930   941 D WifiService: setWifiEnabled: false pid=5547, uid=10077
09-30 05:50:47.569   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:50:47.570   930  2869 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 05:50:47.571   930  2869 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 05:50:47.571   930  2869 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:50:47.571   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:50:47.574   930  5744 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,09-30 05:50:47.579  3817  3817 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 05:50:47.582   930  5746 D DhcpClient: Clearing IP address
09-30 05:50:47.582   507   924 D CommandListener: Clearing all IP addresses on wlan0
09-30 05:50:47.584   507   924 D CommandListener: Setting iface cfg
09-30 05:50:47.587  3817  5306 I iu.UploadsManager: num queued entries: 0
09-30 05:50:47.588  3817  5306 I iu.UploadsManager: num updated entries: 0
09-30 05:50:47.588  3817  5306 I iu.SyncManager: NEXT; no task
,09-30 05:50:47.590  3817  5757 I SystemUpdateService: active receiver: enabled
,09-30 05:50:47.590   930  5744 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:800::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-30 05:50:47.591   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-30 05:50:47.591  3817  3817 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:50:47.593  3817  3817 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 05:50:47.593   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 05:50:47.593   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-30 05:50:47.596  5677  5677 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 05:50:47.596   536   536 E Parcel  : Reading a NULL string not supported here.
09-30 05:50:47.599   930  2871 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-30 05:50:47.600  3644  3790 W QCNEJ   : |CORE| network lost: 101
,09-30 05:50:47.600  3644  3790 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 05:50:47.602   930   930 D RttService: SCAN_AVAILABLE : 1
09-30 05:50:47.603   930  2979 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 05:50:47.605   930  2869 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 05:50:47.605  5677  5677 D SprintDMHelper: simOperator: 
09-30 05:50:47.605  5677  5677 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:50:47.610   930  2869 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 05:50:47.612   930  5747 D DhcpClient: Receive thread stopped
,09-30 05:50:47.626   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:50:47.628  3817  5757 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:50:47.639  3817  5757 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 05:50:47.639  3817  5757 I SystemUpdateService: now status is 0 (complete)
09-30 05:50:47.639  3817  5757 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:50:47.639  3817  5757 I SystemUpdateService: file has been verified
09-30 05:50:47.639  3817  5757 I SystemUpdateService: OTA package size = 21989297
,09-30 05:50:47.645  3817  5757 I SystemUpdateService: showing system update notification
,09-30 05:50:47.648   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:50:47.648   507   924 D CommandListener: Clearing all IP addresses on wlan0
09-30 05:50:47.649   930  2871 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 05:50:47.649   930  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 05:50:47.652   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-30 05:50:47.653  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:47.653  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:47.653  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.654  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:47.655  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:47.656  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:47.656  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.656  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:47.657  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:47.657  5547  5547 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-30 05:50:47.657  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.657  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:47.659   930  2869 D DhcpClient: doQuit
09-30 05:50:47.659   930  2869 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 05:50:47.659   930  5746 D DhcpClient: onQuitting
09-30 05:50:47.660  5741  5741 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-30 05:50:47.661  3817  3817 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 05:50:47.662  4945  4968 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:50:47.662  4945  4968 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:50:47.662  4945  4968 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 05:50:47.662  4945  4968 E SarControlService: no key has been found,reset the power
09-30 05:50:47.663  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:47.663  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:47.663  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:50:47.663  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:50:47.663  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.663  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-30 05:50:47.663  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:47.663  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:50:47.663  4970  4970 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 05:50:47.664  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:47.664  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:47.665  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.665  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:50:47.665  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:47.665  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:50:47.665  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:50:47.665  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:50:47.665  4970  4970 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:50:47.666  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:47.666  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:47.666  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:47.666  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:47.668  3817  3817 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 05:50:47.671  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000ee03000000000000ffffffff]
09-30 05:50:47.671  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:50:47.671  4970  4984 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,09-30 05:50:47.672  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 05:50:47.672  4945  4955 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 05:50:47.674  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000ef03000000000000ffffffff]
,09-30 05:50:47.674  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 05:50:47.675  4970  4984 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 05:50:47.675  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:50:47.676  4945  4956 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 05:50:47.677  3817  3817 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 05:50:47.679  5741  5741 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 05:50:47.679  3817  5306 I iu.UploadsManager: num queued entries: 0
,09-30 05:50:47.680  3817  5306 I iu.UploadsManager: num updated entries: 0
,09-30 05:50:47.684  5741  5741 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 05:50:47.688  3817  3817 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:50:47.689  3817  3817 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 05:50:47.691  5677  5677 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:50:47.695  5677  5677 D SprintDMHelper: simOperator: 
09-30 05:50:47.695  5677  5677 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:50:47.704   507   924 E Netd    : netlink response contains error (No such file or directory)
,09-30 05:50:47.706   930  2871 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 05:50:47.706   930  2871 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 05:50:47.713  3817  5306 I iu.SyncManager: NEXT; no task
,09-30 05:50:47.721  3817  5776 I SystemUpdateService: active receiver: enabled
,09-30 05:50:47.726  3817  5776 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:50:47.728  3817  5776 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 05:50:47.728  3817  5776 I SystemUpdateService: now status is 0 (complete)
09-30 05:50:47.728  3817  5776 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:50:47.728  3817  5776 I SystemUpdateService: file has been verified
09-30 05:50:47.728  3817  5776 I SystemUpdateService: OTA package size = 21989297
,09-30 05:50:47.733  3817  5776 I SystemUpdateService: showing system update notification
,09-30 05:50:47.737  5741  5741 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 05:50:47.743  3817  3817 D SystemUpdateService: onDestroy
,09-30 05:50:47.748  5741  5741 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 05:50:47.850   930  2869 D wifi    : In wifi stop Hal
,09-30 05:50:47.850   930  2869 D wifi    : halHandle = 0x7f82ce7400, mVM = 0x7f9f2cd140, mCls = 0x1018ca
,09-30 05:50:47.850   930  5740 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 05:50:47.850   930  5740 D WifiHAL : Got a signal to exit!!!
09-30 05:50:47.850   930  5740 I WifiHAL : Exit wifi_event_loop
,09-30 05:50:47.852   930  2869 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 05:50:47.852   930  2869 E WifiHAL : Event processing terminated
09-30 05:50:47.855  4919  4919 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 05:50:47.855   930  2869 D wifi    : In wifi cleaned up handler
09-30 05:50:47.856   930  2869 I WifiHAL : Internal cleanup completed
09-30 05:50:47.860  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:47.862  4024  4136 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 05:50:47.862  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:47.863  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:47.877   930  5740 D wifi    : set interface wlan0 flags (DOWN)
09-30 05:50:47.877   930  2869 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 05:50:48.083   930   947 D Tethering: InitialState.processMessage what=4
,09-30 05:50:48.090   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 05:50:48.535   930  2871 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 05:50:52.607   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@748a81:true
,09-30 05:50:52.608  5662  5662 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 05:50:52.614  5662  5662 I bt_bluedroid: init
,09-30 05:50:52.614  5662  5778 I BluetoothAdapterState: Entering OffState
,09-30 05:50:52.617  5662  5779 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 05:50:52.618  5662  5779 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 05:50:52.618  5662  5779 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 05:50:52.618  5662  5779 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-30 05:50:52.619  5662  5662 I bt_bluedroid: get_profile_interface socket
,09-30 05:50:52.621  5662  5782 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 05:50:52.622  5662  5662 I bt_bluedroid: get_profile_interface sdp
,09-30 05:50:52.625  5662  5782 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:50:52.632  5662  5673 I bt_bluedroid: config_hci_snoop_log
,09-30 05:50:52.633   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 05:50:52.639  5662  5778 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 05:50:52.640  5662  5778 D BluetoothAdapterProperties: Setting state to 14
09-30 05:50:52.640  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-30 05:50:52.642  5662  5778 D BluetoothBondStateMachine: make
,09-30 05:50:52.645  5662  5783 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 05:50:52.650  5662  5778 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:50:52.651  5662  5662 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 05:50:52.656  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:50:52.657  5662  5662 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 05:50:52.657  5662  5662 D BtGatt.GattService: Received start request. Starting profile...
09-30 05:50:52.658  5662  5662 D BtGatt.GattService: start()
,09-30 05:50:52.658  5662  5662 I bt_bluedroid: get_profile_interface gatt
09-30 05:50:52.659  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:50:52.659  5662  5662 D BtGatt.AdvertiseManager: advertise manager created
,09-30 05:50:52.665  5662  5662 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:50:52.666  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:52.666  5662  5662 V BluetoothAdapterState: isBleTurningOn()=true
09-30 05:50:52.666  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:52.666  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 05:50:52.668  5662  5778 I bt_bluedroid: bt_bluedroid
09-30 05:50:52.669  5662  5779 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 05:50:52.669  5662  5779 I bt_hci  : start_up
,09-30 05:50:52.676  5662  5779 I bt_vendor: alloc value 0xf3b38871
,09-30 05:50:52.676  5662  5779 I bt_vendor: init
09-30 05:50:52.676  5662  5779 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 05:50:52.676  5662  5779 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 05:50:52.790  5662  5779 D bt_hci  : start_up starting async portion
,09-30 05:50:52.791  5662  5786 I bt_hci  : event_finish_startup
,09-30 05:50:52.791  5662  5786 I bt_hci_h4: hal_open
09-30 05:50:52.791  5662  5786 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 05:50:52.790  5787  5787 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 05:50:52.793  5662  5786 I bt_userial_vendor: device fd = 54 open
,09-30 05:50:52.808  5662  5786 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 05:50:52.810  5662  5786 D bt_hwcfg: Chipset BCM4358A3
,09-30 05:50:52.810  5662  5786 D bt_hwcfg: Target name = [BCM4358A3]
09-30 05:50:52.811  5662  5786 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 05:50:53.204  5662  5786 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 05:50:53.205  5662  5786 D bt_hwcfg: Settlement delay -- 100 ms
09-30 05:50:53.205  5662  5786 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 05:50:53.339  5662  5786 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 05:50:53.339  5662  5786 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 05:50:53.341  5662  5786 I bt_hwcfg: vendor lib fwcfg completed
09-30 05:50:53.341  5662  5786 I bt_vendor: firmware callback
09-30 05:50:53.341  5662  5786 I bt_hci  : firmware_config_callback
,09-30 05:50:53.350  5662  5789 I bt_btu  : btu_task pending for preload complete event
,09-30 05:50:53.351  5662  5789 I bt_btu_task: Bluetooth chip preload is complete
09-30 05:50:53.351  5662  5789 I bt_btu  : btu_task received preload complete event
,09-30 05:50:53.358  5662  5789 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 05:50:53.358  5662  5789 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 05:50:53.358  5662  5789 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-30 05:50:53.358  5662  5789 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_SDP
,09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 05:50:53.359  5662  5789 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 05:50:53.360  5662  5789 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 05:50:53.360  5662  5789 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 05:50:53.442  5662  5789 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ab6549
,09-30 05:50:53.442  5662  5789 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ab6549 
,09-30 05:50:53.459  5662  5782 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 05:50:53.460  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 05:50:53.460  5662  5782 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 05:50:53.463  5662  5782 D BluetoothAdapterProperties: Name is: Nexus 6P
09-30 05:50:53.467  5662  5782 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:50:53.467  5662  5782 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 05:50:53.468  5662  5782 D bt_hci  : do_postload posting postload work item
09-30 05:50:53.468  5662  5786 I bt_hci  : event_postload
09-30 05:50:53.468  5662  5786 I bt_vendor: sco_config_cb
,09-30 05:50:53.468  5662  5786 I bt_hci  : sco_config_callback postload finished.
09-30 05:50:53.472  5662  5782 D bt_bte_conf: Device ID record 1 : primary
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   vendorId            = 000f
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   vendorIdSource      = 0001
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   product             = 1200
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   version             = 1436
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   clientExecutableURL = 
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   serviceDescription  = 
09-30 05:50:53.472  5662  5782 D bt_bte_conf:   documentationURL    = 
09-30 05:50:53.473  5662  5782 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-30 05:50:53.473  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:53.473  5662  5779 D bt_stack_manager: event_start_up_stack finished
09-30 05:50:53.475  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 05:50:53.475  5662  5778 D BluetoothAdapterProperties: Setting state to 15
09-30 05:50:53.476  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 05:50:53.476  5662  5778 I BluetoothAdapterState: Entering BleOnState
09-30 05:50:53.477  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:53.477  5662  5786 I bt_vendor: low_power_mode_cb
09-30 05:50:53.482  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:53.484  5662  5778 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 05:50:53.485  5662  5778 D BluetoothAdapterProperties: Setting state to 11
09-30 05:50:53.485  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 05:50:53.493  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:53.494  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:53.496  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:53.496  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:50:53.497  5662  5662 D HeadsetService: Received start request. Starting profile...
,09-30 05:50:53.500  5662  5662 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 05:50:53.500  5662  5662 D HeadsetStateMachine: make
,09-30 05:50:53.510  5662  5778 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:50:53.510  5662  5662 D HeadsetStateMachine: max_hf_connections = 1
09-30 05:50:53.511  5662  5662 I bt_bluedroid: get_profile_interface handsfree
09-30 05:50:53.511  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 05:50:53.511  5662  5782 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-30 05:50:53.514  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:50:53.515  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:50:53.515  5662  5662 D A2dpService: Received start request. Starting profile...
,09-30 05:50:53.516  5662  5662 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 05:50:53.516  5662  5662 I bt_bluedroid: get_profile_interface avrcp
,09-30 05:50:53.522  5662  5662 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 05:50:53.522  5662  5662 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 05:50:53.522  5662  5662 D A2dpStateMachine: make
09-30 05:50:53.523  5662  5662 I bt_bluedroid: get_profile_interface a2dp
,09-30 05:50:53.525  5662  5798 D A2dpStateMachine: Enter Disconnected: -2
,09-30 05:50:53.525  5662  5662 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 05:50:53.526  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:50:53.527  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-30 05:50:53.528  5602  5602 D BluetoothInputDevice: Proxy object connected
,09-30 05:50:53.528  5602  5602 D HidProfile: Bluetooth service connected
,09-30 05:50:53.529  5662  5662 D HidService: Received start request. Starting profile...
09-30 05:50:53.530  5662  5662 I bt_bluedroid: get_profile_interface hidhost
09-30 05:50:53.530  5662  5662 D HidService: setHidService(): set to: null
09-30 05:50:53.530  5662  5782 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a9756d
09-30 05:50:53.530  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 05:50:53.530  5662  5662 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 05:50:53.531  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:50:53.532  5662  5662 D HealthService: Received start request. Starting profile...
,09-30 05:50:53.533  5662  5662 I bt_bluedroid: get_profile_interface health
09-30 05:50:53.534  5662  5662 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-30 05:50:53.534  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:50:53.535  5602  5602 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:50:53.536  5662  5662 D PanService: Received start request. Starting profile...
09-30 05:50:53.536  5662  5662 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 05:50:53.536  5662  5662 I bt_bluedroid: get_profile_interface pan
09-30 05:50:53.536  5602  5602 D PanProfile: Bluetooth service connected
09-30 05:50:53.536  5662  5782 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 05:50:53.539  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:50:53.541  5602  5602 D BluetoothMap: Proxy object connected
,09-30 05:50:53.541  5602  5602 D MapProfile: Bluetooth service connected
09-30 05:50:53.541  5602  5602 D BluetoothMap: getConnectedDevices()
09-30 05:50:53.542  5662  5662 D BluetoothMapService: Received start request. Starting profile...
09-30 05:50:53.542  5602  5602 D BluetoothMap: Bluetooth is Not enabled
09-30 05:50:53.542  5662  5662 D BluetoothMapService: start()
,09-30 05:50:53.545  5662  5662 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 05:50:53.545  5662  5662 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 05:50:53.545  5662  5662 D BluetoothMapAppObserver: createReceiver()
09-30 05:50:53.547  5662  5662 D BluetoothMapAppObserver: initObservers()
09-30 05:50:53.547  5662  5662 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 05:50:53.552  5662  5662 V SapService: SapBinder()
,09-30 05:50:53.552  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:50:53.553  5662  5662 D SapService: Received start request. Starting profile...
09-30 05:50:53.553  5662  5662 V SapService: start()
,09-30 05:50:53.554  5662  5662 V BluetoothAdapterState: isTurningOff()=false
09-30 05:50:53.554  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:50:53.555  5662  5796 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isTurningOff()=false
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isTurningOff()=false
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.555  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isTurningOff()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isTurningOff()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.556  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:53.557  5662  5662 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:50:53.557  5662  5662 V BluetoothAdapterState: isTurningOn()=true
09-30 05:50:53.557  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:53.557  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:50:53.557  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 05:50:53.557  5662  5778 D BluetoothAdapterProperties: ScanMode =  20
09-30 05:50:53.557  5662  5778 D BluetoothAdapterProperties: State =  11
,09-30 05:50:53.559  5662  5782 D BluetoothAdapterProperties: Scan Mode:21
09-30 05:50:53.559  5662  5778 D BluetoothAdapterProperties: Setting state to 12
09-30 05:50:53.559  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 05:50:53.559  5662  5782 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 05:50:53.560  5547  5547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:50:53.560  5662  5778 I BluetoothAdapterState: Entering OnState
09-30 05:50:53.560  3037  3861 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:53.563  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:53.564  3037  3037 D BluetoothInputDevice: Proxy object connected
09-30 05:50:53.564  3037  3037 D HidProfile: Bluetooth service connected
09-30 05:50:53.564  3037  3051 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:50:53.565  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 05:50:53.565   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:50:53.565  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:53.565  5602  5615 D BluetoothMap: onBluetoothStateChange: up=true
09-30 05:50:53.565  3037  5546 D BluetoothMap: onBluetoothStateChange: up=true
09-30 05:50:53.567  3037  3050 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:50:53.567  3037  3037 D BluetoothMap: Proxy object connected
09-30 05:50:53.567  3037  3037 D MapProfile: Bluetooth service connected
09-30 05:50:53.567  3037  3037 D BluetoothMap: getConnectedDevices()
09-30 05:50:53.569  3037  5546 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:53.569  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:50:53.571  5662  5662 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 05:50:53.571   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 05:50:53.572  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:53.572   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 05:50:53.572  5662  5662 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-30 05:50:53.572  5602  5613 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:50:53.573   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:50:53.573  3674  3896 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:50:53.573  3037  3037 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:50:53.573  3037  3051 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 05:50:53.573  3037  3037 D PanProfile: Bluetooth service connected
09-30 05:50:53.574  5662  5662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:50:53.575  5602  5615 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 05:50:53.576  5662  5662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:53.576  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:53.577   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 05:50:53.579  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:53.579  5547  5547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:50:53.580  5602  5602 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-30 05:50:53.581  5662  5662 D ObexServerSockets: Succeed to create listening sockets 
09-30 05:50:53.581  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:53.581  5662  5662 D ObexServerSockets0: startAccept()
09-30 05:50:53.581  5662  5662 D ObexServerSockets0: prepareForNewConnect()
,09-30 05:50:53.583  5602  5602 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-30 05:50:53.583  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:53.586  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:53.586  5662  5662 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 05:50:53.586  5662  5662 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 05:50:53.587  5662  5804 D ObexServerSockets0: Accepting socket connection...
09-30 05:50:53.587  5662  5805 D ObexServerSockets0: Accepting socket connection...
,09-30 05:50:53.587   930   930 D BluetoothA2dp: Proxy object connected
09-30 05:50:53.588  5662  5662 D BluetoothMapService: onReceive
09-30 05:50:53.588  5662  5662 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:50:53.588  5662  5662 D BluetoothMapService: STATE_ON
09-30 05:50:53.591  5662  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:50:53.592  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:50:53.593  5662  5806 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 05:50:53.593  5662  5806 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 05:50:53.595  5602  5602 D BluetoothA2dp: Proxy object connected
,09-30 05:50:53.600  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:50:53.600  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-30 05:50:53.601  3037  3037 D BluetoothA2dp: Proxy object connected
,09-30 05:50:53.606  3037  3037 D BluetoothPbap: Proxy object connected
09-30 05:50:53.606  3037  3037 D PbapServerProfile: Bluetooth service connected
,09-30 05:50:53.606  5602  5602 D BluetoothPbap: Proxy object connected
,09-30 05:50:53.607  5602  5602 D PbapServerProfile: Bluetooth service connected
,09-30 05:50:53.608  5662  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:50:53.612  5662  5662 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 05:50:53.612  5662  5662 D ObexServerSockets0: prepareForNewConnect()
,09-30 05:50:53.628  5662  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:50:53.630  5662  5814 I BtOppRfcommListener: Accept thread started.
,09-30 05:50:53.666   930   930 D BluetoothHeadset: Proxy object connected
,09-30 05:50:53.666   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:50:53.666  3037  3050 D BluetoothHeadset: Proxy object connected
09-30 05:50:53.666  3037  3037 D HeadsetProfile: Bluetooth service connected
09-30 05:50:53.666   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:50:53.666  3674  3702 D BluetoothHeadset: Proxy object connected
,09-30 05:50:53.672   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:50:53.673   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:50:53.673  3674  5083 D BluetoothHeadset: Proxy object connected
,09-30 05:50:53.686  5602  5613 D BluetoothHeadset: Proxy object connected
09-30 05:50:53.687  5602  5602 D HeadsetProfile: Bluetooth service connected
,09-30 05:50:55.492   930  2871 D ConnectivityService: handlePromptUnvalidated 101
,09-30 05:50:56.146   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:57.147   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:57.585  5662  5778 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 05:50:57.586  5662  5778 D BluetoothAdapterProperties: Setting state to 13
09-30 05:50:57.586  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 05:50:57.587  5662  5778 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 05:50:57.588  5662  5778 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:50:57.593  5662  5662 D BluetoothMapService: onReceive
,09-30 05:50:57.593  5662  5662 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:50:57.593  5662  5662 D BluetoothMapService: STATE_TURNING_OFF
,09-30 05:50:57.594  5662  5662 D BluetoothMapService: MAP Service closeService in
,09-30 05:50:57.595  5662  5662 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 05:50:57.595  5662  5782 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:50:57.595  5662  5662 D ObexServerSockets0: shutdown(block = true)
09-30 05:50:57.596  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 05:50:57.596  5662  5804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 05:50:57.597  5662  5662 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:50:57.598  5662  5662 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:50:57.599  5662  5791 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 05:50:57.600  5662  5805 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 05:50:57.602  5662  5662 I BtOppRfcommListener: stopping Accept Thread
09-30 05:50:57.602  5662  5814 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 05:50:57.603  5662  5814 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-30 05:50:57.603  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:50:57.604  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:57.604  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:50:57.605  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:57.605  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:57.606  5662  5662 D HeadsetService: Received stop request...Stopping profile...
09-30 05:50:57.608  5602  5613 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:57.608   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:57.608   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:57.609  3037  5546 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:57.609   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:50:57.609  3674  3695 D BluetoothHeadset: Proxy object disconnected
,09-30 05:50:57.610  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:57.611  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:50:57.611  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:50:57.611  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:57.613  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.613  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.613  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 05:50:57.613  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.613  5662  5662 D A2dpService: Received stop request...Stopping profile...
09-30 05:50:57.613  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:50:57.614  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:50:57.614  5662  5798 D A2dpStateMachine: Exit Disconnected: -1
09-30 05:50:57.615  5547  5547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:50:57.615   930   930 D BluetoothA2dp: Proxy object disconnected
09-30 05:50:57.615  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:50:57.617  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:57.618  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-30 05:50:57.619  5602  5602 D HeadsetProfile: Bluetooth service disconnected
09-30 05:50:57.619  5662  5662 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 05:50:57.620  5602  5602 D BluetoothA2dp: Proxy object disconnected
09-30 05:50:57.620  5662  5662 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 05:50:57.620  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:57.621  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 05:50:57.621  5662  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:57.621  5662  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:57.621  5662  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 05:50:57.621  5662  5782 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-30 05:50:57.623  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:57.625  3037  3037 D HeadsetProfile: Bluetooth service disconnected
09-30 05:50:57.625  3037  3037 D BluetoothA2dp: Proxy object disconnected
09-30 05:50:57.627  5662  5662 D HidService: Received stop request...Stopping profile...
09-30 05:50:57.627  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:50:57.627  5662  5662 D HidService: Stopping Bluetooth HidService
09-30 05:50:57.628  3037  3037 D BluetoothInputDevice: Proxy object disconnected
09-30 05:50:57.628  3037  3037 D HidProfile: Bluetooth service disconnected
,09-30 05:50:57.629  5662  5662 D HealthService: Received stop request...Stopping profile...
09-30 05:50:57.630  5602  5602 D BluetoothInputDevice: Proxy object disconnected
09-30 05:50:57.630  5602  5602 D HidProfile: Bluetooth service disconnected
,09-30 05:50:57.632  5662  5662 D PanService: Received stop request...Stopping profile...
09-30 05:50:57.632  3037  3037 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-30 05:50:57.632  3037  3037 D PanProfile: Bluetooth service disconnected
09-30 05:50:57.633  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.633  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.633  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:57.633  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.633  5602  5602 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 05:50:57.633  5602  5602 D PanProfile: Bluetooth service disconnected
,09-30 05:50:57.634  5662  5662 D BluetoothMapService: Received stop request...Stopping profile...
,09-30 05:50:57.634  5662  5662 D BluetoothMapService: stop()
,09-30 05:50:57.635  5662  5662 D BluetoothMapAppObserver: deinitObservers()
,09-30 05:50:57.635  5662  5662 D BluetoothMapAppObserver: removeReceiver()
09-30 05:50:57.636  5662  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:57.636  5662  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:57.636  5602  5602 D BluetoothMap: Proxy object disconnected
09-30 05:50:57.636  5602  5602 D MapProfile: Bluetooth service disconnected
09-30 05:50:57.636  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 05:50:57.636  5662  5789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:50:57.636  5662  5789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:50:57.636  3037  3037 D BluetoothMap: Proxy object disconnected
09-30 05:50:57.637  3037  3037 D MapProfile: Bluetooth service disconnected
09-30 05:50:57.637  5662  5789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:50:57.637  5662  5789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:50:57.637  5662  5662 D SapService: Received stop request...Stopping profile...
,09-30 05:50:57.637  5662  5662 V SapService: stop()
,09-30 05:50:57.641  3037  3037 D BluetoothPbap: Proxy object disconnected
,09-30 05:50:57.641  3037  3037 D PbapServerProfile: Bluetooth service disconnected
09-30 05:50:57.641  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.641  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.642  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:57.642  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.642  5662  5662 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 05:50:57.642  5662  5662 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 05:50:57.642  5662  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 05:50:57.642  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.642  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.642  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:57.642  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.642  5602  5602 D BluetoothPbap: Proxy object disconnected
09-30 05:50:57.643  5602  5602 D PbapServerProfile: Bluetooth service disconnected
09-30 05:50:57.643  5662  5662 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 05:50:57.643  5662  5782 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 05:50:57.643  5662  5662 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-30 05:50:57.644  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.644  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.644  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:57.644  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.644  5662  5662 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 05:50:57.644  5662  5662 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 05:50:57.645  5662  5662 D BluetoothMapService: MAP Service closeService in
09-30 05:50:57.645  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.645  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.645  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:57.645  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.645  5662  5662 D BluetoothMapService: cleanup()
09-30 05:50:57.645  5662  5662 D BluetoothMapService: MAP Service closeService in
09-30 05:50:57.646  5662  5662 V BluetoothAdapterState: isTurningOff()=true
09-30 05:50:57.646  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:57.646  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:57.646  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:50:57.646  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 05:50:57.646  5662  5778 D BluetoothAdapterProperties: Setting state to 15
09-30 05:50:57.646  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 05:50:57.647  3037  5546 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 05:50:57.647  5662  5778 I BluetoothAdapterState: Entering BleOnState
09-30 05:50:57.648  3037  3050 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:57.648  5602  5615 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 05:50:57.649   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:57.649  5602  5613 D BluetoothMap: onBluetoothStateChange: up=false
09-30 05:50:57.649  3037  3861 D BluetoothMap: onBluetoothStateChange: up=false
09-30 05:50:57.650  3037  3051 D BluetoothPan: onBluetoothStateChange on: false
09-30 05:50:57.650  3037  5546 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:50:57.651   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:50:57.651   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:57.651  5602  5615 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:50:57.653  5602  5613 D BluetoothPan: onBluetoothStateChange on: false
09-30 05:50:57.653   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:57.654  3674  3896 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:57.654  5602  5615 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:50:57.655  3037  3051 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 05:50:57.655  5602  5613 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 05:50:57.656  5662  5778 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-30 05:50:57.656  5662  5778 D BluetoothAdapterProperties: Setting state to 16
,09-30 05:50:57.665  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 05:50:57.665  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:57.666  5662  5778 D BluetoothAdapterProperties: onBleDisable
09-30 05:50:57.666  5662  5778 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:50:57.666  5662  5779 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 05:50:57.666  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:57.667  5662  5782 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:50:57.667  5662  5789 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 05:50:57.667  5662  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:50:57.668  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:57.670  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:57.670  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 05:50:57.672  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:50:57.673  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:50:57.680  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:50:57.682  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:50:57.876  5662  5782 I bt_hci  : shut_down
,09-30 05:50:57.887  5662  5786 D bt_hwcfg: hw_epilog_process
,09-30 05:50:57.888  5662  5786 I bt_vendor: low_power_mode_cb
,09-30 05:50:57.891  5662  5786 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 05:50:57.891  5662  5786 I bt_vendor: epilog_cb
09-30 05:50:57.891  5662  5786 I bt_hci  : epilog_finished_callback
,09-30 05:50:57.895  5662  5782 I bt_hci_h4: hal_close
,09-30 05:50:57.896  5662  5782 I bt_userial_vendor: device fd = 54 close
,09-30 05:50:58.013  5662  5779 D bt_stack_manager: event_shut_down_stack finished.
,09-30 05:50:58.014  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 05:50:58.019  5662  5662 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 05:50:58.019  5662  5778 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-30 05:50:58.020  5662  5662 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 05:50:58.020  5662  5662 D BtGatt.GattService: stop()
09-30 05:50:58.020  5662  5662 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 05:50:58.026  5662  5662 V BluetoothAdapterState: isTurningOff()=false
09-30 05:50:58.026  5662  5662 V BluetoothAdapterState: isTurningOn()=false
09-30 05:50:58.026  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:50:58.026  5662  5662 V BluetoothAdapterState: isBleTurningOff()=true
09-30 05:50:58.027  5662  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 05:50:58.028  5662  5778 D BluetoothAdapterProperties: Setting state to 10
,09-30 05:50:58.028  5662  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 05:50:58.029  5662  5778 I BluetoothAdapterState: Entering OffState
,09-30 05:50:58.030   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 05:50:58.045  5662  5662 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 05:50:58.046  5662  5662 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 05:50:58.046  5662  5662 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-30 05:50:58.048  5662  5779 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 05:50:58.058  5662  5662 I art     : System.exit called, status: 0
,09-30 05:50:58.058  5662  5662 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 05:50:58.090   930  3034 I ActivityManager: Process com.android.bluetooth (pid 5662) has died
,09-30 05:50:58.148   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:50:59.149   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:00.149   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:01.150   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 05:51:02.583  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:51:02.583  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:51:02.589  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:51:02.590  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5cfa6f removed from the list
09-30 05:51:02.590  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:51:02.590  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:02.590  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:02.593  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:02.594  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e39405 added. We now have 4 listener(s)
09-30 05:51:02.594  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:51:02.595  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:02.596  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e39405 removed from the list
09-30 05:51:02.596  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:51:02.596  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:02.596  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:02.598  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:02.598  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ddbc5a added. We now have 4 listener(s)
,09-30 05:51:02.598  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:51:07.609  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:07.639   930   947 I ActivityManager: Start proc 5822:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 05:51:07.712  5822  5822 D AdapterServiceConfig: Adding HeadsetService
,09-30 05:51:07.712  5822  5822 D AdapterServiceConfig: Adding A2dpService
09-30 05:51:07.712  5822  5822 D AdapterServiceConfig: Adding HidService
09-30 05:51:07.712  5822  5822 D AdapterServiceConfig: Adding HealthService
09-30 05:51:07.713  5822  5822 D AdapterServiceConfig: Adding PanService
09-30 05:51:07.713  5822  5822 D AdapterServiceConfig: Adding GattService
09-30 05:51:07.713  5822  5822 D AdapterServiceConfig: Adding BluetoothMapService
09-30 05:51:07.713  5822  5822 D AdapterServiceConfig: Adding SapService
,09-30 05:51:07.724   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c792041:true
,09-30 05:51:07.725  5822  5822 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 05:51:07.728  5822  5822 I bt_bluedroid: init
,09-30 05:51:07.729  5822  5834 I BluetoothAdapterState: Entering OffState
,09-30 05:51:07.732  5822  5835 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 05:51:07.732  5822  5835 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 05:51:07.732  5822  5835 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 05:51:07.732  5822  5835 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 05:51:07.733  5822  5822 I bt_bluedroid: get_profile_interface socket
,09-30 05:51:07.734  5822  5838 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 05:51:07.735  5822  5822 I bt_bluedroid: get_profile_interface sdp
09-30 05:51:07.736  5822  5838 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:51:07.739  5822  5833 I bt_bluedroid: config_hci_snoop_log
09-30 05:51:07.740   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 05:51:07.745  5822  5834 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 05:51:07.745  5822  5834 D BluetoothAdapterProperties: Setting state to 14
09-30 05:51:07.746  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-30 05:51:07.747  5822  5834 D BluetoothBondStateMachine: make
,09-30 05:51:07.749  5822  5839 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 05:51:07.751  5822  5834 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:51:07.753  5822  5822 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-30 05:51:07.755  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:51:07.756  5822  5822 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 05:51:07.756  5822  5822 D BtGatt.GattService: Received start request. Starting profile...
09-30 05:51:07.756  5822  5822 D BtGatt.GattService: start()
09-30 05:51:07.756  5822  5822 I bt_bluedroid: get_profile_interface gatt
,09-30 05:51:07.757  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:51:07.758  5822  5822 D BtGatt.AdvertiseManager: advertise manager created
,09-30 05:51:07.764  5822  5822 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:51:07.764  5822  5822 V BluetoothAdapterState: isTurningOn()=false
09-30 05:51:07.764  5822  5822 V BluetoothAdapterState: isBleTurningOn()=true
09-30 05:51:07.764  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:51:07.764  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 05:51:07.766  5822  5834 I bt_bluedroid: bt_bluedroid
09-30 05:51:07.766  5822  5835 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 05:51:07.766  5822  5835 I bt_hci  : start_up
,09-30 05:51:07.771  5822  5835 I bt_vendor: alloc value 0xf3bb1871
,09-30 05:51:07.771  5822  5835 I bt_vendor: init
09-30 05:51:07.771  5822  5835 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 05:51:07.771  5822  5835 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 05:51:07.878  5822  5835 D bt_hci  : start_up starting async portion
,09-30 05:51:07.878  5822  5842 I bt_hci  : event_finish_startup
09-30 05:51:07.878  5822  5842 I bt_hci_h4: hal_open
09-30 05:51:07.879  5822  5842 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 05:51:07.876  5843  5843 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:51:07.882  5822  5842 I bt_userial_vendor: device fd = 54 open
,09-30 05:51:07.896  5822  5842 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 05:51:07.899  5822  5842 D bt_hwcfg: Chipset BCM4358A3
,09-30 05:51:07.899  5822  5842 D bt_hwcfg: Target name = [BCM4358A3]
09-30 05:51:07.899  5822  5842 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 05:51:08.410  5822  5842 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-30 05:51:08.411  5822  5842 D bt_hwcfg: Settlement delay -- 100 ms
,09-30 05:51:08.411  5822  5842 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 05:51:08.545  5822  5842 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 05:51:08.546  5822  5842 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 05:51:08.547  5822  5842 I bt_hwcfg: vendor lib fwcfg completed
09-30 05:51:08.548  5822  5842 I bt_vendor: firmware callback
09-30 05:51:08.548  5822  5842 I bt_hci  : firmware_config_callback
,09-30 05:51:08.556  5822  5845 I bt_btu  : btu_task pending for preload complete event
09-30 05:51:08.556  5822  5845 I bt_btu_task: Bluetooth chip preload is complete
,09-30 05:51:08.557  5822  5845 I bt_btu  : btu_task received preload complete event
,09-30 05:51:08.565  5822  5845 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 05:51:08.565  5822  5845 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 05:51:08.566  5822  5845 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 05:51:08.567  5822  5845 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 05:51:08.567  5822  5845 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 05:51:08.567  5822  5845 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 05:51:08.567  5822  5845 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 05:51:08.661  5822  5845 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b2f549
,09-30 05:51:08.661  5822  5845 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b2f549 
,09-30 05:51:08.686  5822  5838 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 05:51:08.688  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 05:51:08.689  5822  5838 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 05:51:08.691  5822  5838 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:51:08.692  5822  5838 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:51:08.693  5822  5838 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 05:51:08.693  5822  5838 D bt_hci  : do_postload posting postload work item
,09-30 05:51:08.693  5822  5842 I bt_hci  : event_postload
09-30 05:51:08.693  5822  5842 I bt_vendor: sco_config_cb
09-30 05:51:08.693  5822  5842 I bt_hci  : sco_config_callback postload finished.
,09-30 05:51:08.695  5822  5838 D bt_bte_conf: Device ID record 1 : primary
,09-30 05:51:08.695  5822  5838 D bt_bte_conf:   vendorId            = 000f
09-30 05:51:08.695  5822  5838 D bt_bte_conf:   vendorIdSource      = 0001
,09-30 05:51:08.695  5822  5838 D bt_bte_conf:   product             = 1200
09-30 05:51:08.695  5822  5838 D bt_bte_conf:   version             = 1436
09-30 05:51:08.695  5822  5838 D bt_bte_conf:   clientExecutableURL = 
09-30 05:51:08.695  5822  5838 D bt_bte_conf:   serviceDescription  = 
,09-30 05:51:08.695  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:08.695  5822  5838 D bt_bte_conf:   documentationURL    = 
09-30 05:51:08.695  5822  5838 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 05:51:08.696  5822  5835 D bt_stack_manager: event_start_up_stack finished
09-30 05:51:08.696  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 05:51:08.697  5822  5834 D BluetoothAdapterProperties: Setting state to 15
09-30 05:51:08.697  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-30 05:51:08.698  5822  5834 I BluetoothAdapterState: Entering BleOnState
09-30 05:51:08.699  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:08.700  5822  5834 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 05:51:08.701  5822  5834 D BluetoothAdapterProperties: Setting state to 11
09-30 05:51:08.701  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-30 05:51:08.703  5822  5842 I bt_vendor: low_power_mode_cb
09-30 05:51:08.706  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:51:08.707  5822  5822 D HeadsetService: Received start request. Starting profile...
,09-30 05:51:08.708  5822  5822 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 05:51:08.708  5822  5822 D HeadsetStateMachine: make
,09-30 05:51:08.714  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:08.715  5822  5834 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:51:08.719  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:08.722  5822  5822 D HeadsetStateMachine: max_hf_connections = 1
09-30 05:51:08.722  5822  5822 I bt_bluedroid: get_profile_interface handsfree
,09-30 05:51:08.723  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 05:51:08.723  5822  5838 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 05:51:08.726  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:51:08.727  5822  5822 D A2dpService: Received start request. Starting profile...
09-30 05:51:08.728  5822  5822 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 05:51:08.728  5822  5822 I bt_bluedroid: get_profile_interface avrcp
,09-30 05:51:08.733  5822  5822 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 05:51:08.733  5822  5822 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 05:51:08.733  5822  5822 D A2dpStateMachine: make
09-30 05:51:08.735  5822  5822 I bt_bluedroid: get_profile_interface a2dp
,09-30 05:51:08.736  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 05:51:08.737  5822  5854 D A2dpStateMachine: Enter Disconnected: -2
,09-30 05:51:08.737  5822  5822 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 05:51:08.738  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
09-30 05:51:08.738  5822  5822 D HidService: Received start request. Starting profile...
09-30 05:51:08.739  5822  5822 I bt_bluedroid: get_profile_interface hidhost
09-30 05:51:08.739  5822  5822 D HidService: setHidService(): set to: null
09-30 05:51:08.739  5822  5838 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b1056d
09-30 05:51:08.739  5822  5838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 05:51:08.739  5822  5822 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 05:51:08.740  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:51:08.740  5822  5822 D HealthService: Received start request. Starting profile...
09-30 05:51:08.742  5822  5822 I bt_bluedroid: get_profile_interface health
,09-30 05:51:08.743  5822  5822 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 05:51:08.743  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:51:08.744  5822  5822 D PanService: Received start request. Starting profile...
,09-30 05:51:08.744  5822  5822 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 05:51:08.744  5822  5822 I bt_bluedroid: get_profile_interface pan
09-30 05:51:08.745  5822  5838 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 05:51:08.746  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:51:08.747  5822  5822 D BluetoothMapService: Received start request. Starting profile...
09-30 05:51:08.747  5822  5822 D BluetoothMapService: start()
,09-30 05:51:08.749  5822  5822 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 05:51:08.750  5822  5822 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 05:51:08.750  5822  5822 D BluetoothMapAppObserver: createReceiver()
,09-30 05:51:08.751  5822  5822 D BluetoothMapAppObserver: initObservers()
09-30 05:51:08.751  5822  5822 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 05:51:08.757  5822  5822 V SapService: SapBinder()
09-30 05:51:08.757  5822  5822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:51:08.758  5822  5822 D SapService: Received start request. Starting profile...
09-30 05:51:08.758  5822  5822 V SapService: start()
,09-30 05:51:08.761  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.761  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:51:08.761  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.761  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.761  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:51:08.762  5822  5851 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.762  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.763  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:51:08.764  5822  5822 V BluetoothAdapterState: isTurningOff()=false
09-30 05:51:08.764  5822  5822 V BluetoothAdapterState: isTurningOn()=true
09-30 05:51:08.764  5822  5822 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:51:08.764  5822  5822 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:51:08.765  5822  5834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 05:51:08.765  5822  5834 D BluetoothAdapterProperties: ScanMode =  20
,09-30 05:51:08.765  5822  5834 D BluetoothAdapterProperties: State =  11
,09-30 05:51:08.765  5822  5834 D BluetoothAdapterProperties: Setting state to 12
,09-30 05:51:08.765  5822  5834 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 05:51:08.766  3037  3051 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 05:51:08.766  5822  5834 I BluetoothAdapterState: Entering OnState
09-30 05:51:08.766  5822  5838 D BluetoothAdapterProperties: Scan Mode:21
09-30 05:51:08.767  5822  5838 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 05:51:08.768  5547  5547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:51:08.770  3037  3037 D BluetoothInputDevice: Proxy object connected
09-30 05:51:08.771  3037  3037 D HidProfile: Bluetooth service connected
09-30 05:51:08.771  3037  5546 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:51:08.772  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:08.773  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:51:08.774   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:51:08.774  5602  5615 D BluetoothMap: onBluetoothStateChange: up=true
09-30 05:51:08.775  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:51:08.776  3037  3050 D BluetoothMap: onBluetoothStateChange: up=true
09-30 05:51:08.776  5822  5822 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 05:51:08.777  5822  5822 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 05:51:08.777  3037  3861 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:08.778  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:51:08.778  5822  5822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:51:08.779  3037  3051 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:51:08.780  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:51:08.780  5822  5822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:51:08.780   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:51:08.781  5602  5602 D BluetoothInputDevice: Proxy object connected
09-30 05:51:08.781  5602  5602 D HidProfile: Bluetooth service connected
09-30 05:51:08.781  5822  5822 D ObexServerSockets: Succeed to create listening sockets 
09-30 05:51:08.781  5822  5822 D ObexServerSockets0: startAccept()
09-30 05:51:08.781  5822  5822 D ObexServerSockets0: prepareForNewConnect()
,09-30 05:51:08.782   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:51:08.782  5602  5613 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:51:08.783  5822  5822 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 05:51:08.783  5822  5822 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 05:51:08.783  5602  5615 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:51:08.784  5822  5860 D ObexServerSockets0: Accepting socket connection...
09-30 05:51:08.784  5822  5861 D ObexServerSockets0: Accepting socket connection...
09-30 05:51:08.785  3037  3037 D BluetoothMap: Proxy object connected
09-30 05:51:08.785   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:51:08.785  3037  3037 D MapProfile: Bluetooth service connected
09-30 05:51:08.785  3037  3037 D BluetoothMap: getConnectedDevices()
09-30 05:51:08.785  3674  3896 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:51:08.786  5602  5615 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 05:51:08.786   930   930 D BluetoothA2dp: Proxy object connected
09-30 05:51:08.787  3037  5546 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 05:51:08.788  3037  3037 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:51:08.788  3037  3037 D PanProfile: Bluetooth service connected
09-30 05:51:08.788  3037  3037 D BluetoothA2dp: Proxy object connected
09-30 05:51:08.789  5602  5613 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 05:51:08.791  5602  5602 D BluetoothMap: Proxy object connected
09-30 05:51:08.791  5602  5602 D MapProfile: Bluetooth service connected
09-30 05:51:08.791  5602  5602 D BluetoothMap: getConnectedDevices()
09-30 05:51:08.792  5822  5822 D BluetoothMapService: onReceive
09-30 05:51:08.792  5822  5822 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:51:08.792  5547  5547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:51:08.792  5822  5822 D BluetoothMapService: STATE_ON
09-30 05:51:08.792   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 05:51:08.792  5602  5602 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:51:08.793  5602  5602 D PanProfile: Bluetooth service connected
09-30 05:51:08.793  5602  5602 D BluetoothA2dp: Proxy object connected
09-30 05:51:08.794  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:08.795  5822  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:51:08.796  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:08.796  5822  5862 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 05:51:08.796  5822  5862 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 05:51:08.802  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:51:08.809  3468  3468 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:51:08.809  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:51:08.815  5602  5602 D BluetoothPbap: Proxy object connected
,09-30 05:51:08.815  5602  5602 D PbapServerProfile: Bluetooth service connected
,09-30 05:51:08.816  5822  5822 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 05:51:08.816  5822  5822 D ObexServerSockets0: prepareForNewConnect()
,09-30 05:51:08.820  3037  3037 D BluetoothPbap: Proxy object connected
09-30 05:51:08.820  3037  3037 D PbapServerProfile: Bluetooth service connected
,09-30 05:51:08.825  5822  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:51:08.836  5822  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:51:08.837  5822  5870 I BtOppRfcommListener: Accept thread started.
,09-30 05:51:08.872  5602  5615 D BluetoothHeadset: Proxy object connected
,09-30 05:51:08.873   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:51:08.873   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:51:08.873  3037  3050 D BluetoothHeadset: Proxy object connected
09-30 05:51:08.873  3037  3037 D HeadsetProfile: Bluetooth service connected
09-30 05:51:08.873   930   930 D BluetoothHeadset: Proxy object connected
,09-30 05:51:08.873  3674  3702 D BluetoothHeadset: Proxy object connected
09-30 05:51:08.875  5602  5602 D HeadsetProfile: Bluetooth service connected
09-30 05:51:08.875   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:51:08.882   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:51:08.886   930   947 D BluetoothHeadset: Proxy object connected
09-30 05:51:08.886  3674  5083 D BluetoothHeadset: Proxy object connected
,09-30 05:51:08.887  5602  5613 D BluetoothHeadset: Proxy object connected
09-30 05:51:08.888  5602  5602 D HeadsetProfile: Bluetooth service connected
,09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:12.624  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:12.630  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:51:12.631  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:12.631  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ddbc5a removed from the list
09-30 05:51:12.631  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:51:12.631  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:12.632  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:12.633  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:12.634  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a68ce8b added. We now have 4 listener(s)
09-30 05:51:12.634  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:51:12.638   930  3467 D WifiService: setWifiEnabled: false pid=5547, uid=10077
09-30 05:51:12.638   930  3467 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:51:17.650  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:17.651   930  3112 D WifiService: setWifiEnabled: true pid=5547, uid=10077
09-30 05:51:17.651   930  3112 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:51:17.661   507   924 D SoftapController: Softap fwReload - Ok
,09-30 05:51:17.666   507   924 D CommandListener: Setting iface cfg
,09-30 05:51:17.666   507   924 D CommandListener: Trying to bring down wlan0
,09-30 05:51:17.668   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-30 05:51:17.673   930  2869 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 05:51:18.342   930  2869 D wifi    : set interface wlan0 flags (UP)
,09-30 05:51:18.344   930  2869 I WifiHAL : Initializing wifi
,09-30 05:51:18.344   930  2869 I WifiHAL : Creating socket
,09-30 05:51:18.351   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 05:51:18.355   930  2869 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 05:51:18.356   930  2869 D wifi    : Did set static halHandle = 0x7f82ce7400
,09-30 05:51:18.356   930  2869 D wifi    : halHandle = 0x7f82ce7400, mVM = 0x7f9f2cd140, mCls = 0x20156a
,09-30 05:51:18.356   930  2869 D wifi    : array field set
09-30 05:51:18.356   930  2869 I WifiNative-HAL: interface[0] = wlan0
09-30 05:51:18.358   930  5875 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547655414784
09-30 05:51:18.359   930  5875 D wifi    : waitForHalEvents called, vm = 0x7f9f2cd140, obj = 0x20156a, env = 0x7f94753ac0
,09-30 05:51:18.425  5876  5876 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 05:51:18.448  5876  5876 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 05:51:18.459  5876  5876 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-30 05:51:18.459  5876  5876 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
09-30 05:51:18.460   930  2869 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 05:51:18.469  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:18.473  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:18.481   930  2869 D WifiConfigStore: Loading config and enabling all networks 
,09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:18.485  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:51:18.487  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:18.490  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:18.493  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:51:18.496   930  2869 D WifiConfigStore: loaded 0 passpoint configs
,09-30 05:51:18.497   930  2869 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 05:51:18.497   930  2869 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 05:51:18.498   930  2869 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 05:51:18.500   930  2869 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 05:51:18.500   930  2869 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 05:51:18.500   930  2869 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 05:51:18.500   930  2869 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 05:51:18.504   930  2869 D WifiNative-HAL: Setting external_sim to 1
,09-30 05:51:18.505  4919  4919 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 05:51:18.505   930  2869 D wifi    : setting dfs flag to true, 0x7f851b0660
,09-30 05:51:18.505   930  2869 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 05:51:18.505   930  2869 D wifi    : setting scan oui 0x7f851b0660
09-30 05:51:18.505   930  2869 D WifiHAL : Sending mac address OUI
,09-30 05:51:18.510   930  2869 E native  : do suspend false
,09-30 05:51:18.518   930  2869 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 05:51:18.518   930   930 D RttService: SCAN_AVAILABLE : 3
09-30 05:51:18.518   507   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 05:51:18.518   930  2979 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 05:51:18.519   507   924 D CommandListener: Setting iface cfg
,09-30 05:51:18.524   930  2868 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-30 05:51:18.524   930  2868 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 05:51:18.532   930  2868 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 05:51:18.538   930  2868 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 05:51:18.538   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=296950 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-30 05:51:21.151   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:21.687  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:51:21.692  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:51:21.699  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:51:21.702  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:51:22.152   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:22.674  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:22.680  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:51:22.681  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:22.681  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a68ce8b removed from the list
,09-30 05:51:22.681  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:51:22.681  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:51:22.681  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:51:22.691  5547  5878 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-30 05:51:22.691  5547  5878 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 05:51:23.153   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:24.154   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:25.155   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:51:25.702  5547  5879 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 05:51:25.703  5547  5879 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 05:51:25.704  5547  5879 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:51:25.705  5547  5879 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:51:25.706  5547  5879 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-30 05:51:25.707  5547  5878 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-30 05:51:25.707  5547  5878 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 05:51:25.708  5547  5881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:25.708  5547  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:51:25.708  5547  5878 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:51:25.710  5547  5882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:25.710  5547  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:51:25.710  5547  5878 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:51:25.711  5547  5882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:25.711  5547  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:51:25.712  5547  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:25.712  5547  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:51:25.712  5547  5878 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-30 05:51:25.712  5547  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:51:25.712  5547  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:25.712  5547  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:25.713  5547  5882 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 05:51:25.713  5547  5882 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:25.713  5547  5882 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 05:51:25.713  5547  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:25.713  5547  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:25.713  5547  5882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:25.713  5547  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:51:25.714  5547  5884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:25.714  5547  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:51:25.714  5547  5883 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:25.714  5547  5883 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-30 05:51:25.714  5547  5881 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: IncomingSocketThread/Sender): Socket closed
09-30 05:51:25.715  5547  5881 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:25.715  5547  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:51:25.715  5547  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:25.715  5547  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:25.715  5547  5881 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:25.715  5547  5881 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:25.715  5547  5881 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:25.715  5547  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:25.715  5547  5884 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:51:25.716  5547  5884 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:25.716  5547  5884 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 05:51:25.716  5547  5884 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-30 05:51:25.716  5547  5884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:25.716  5547  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 05:51:26.156   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 05:51:28.702  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-30 05:51:28.704  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 05:51:28.709  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@60f41ee Bundle[{}]
,09-30 05:51:28.710  5547  5593 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 05:51:28.711  5547  5593 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-30 05:51:28.712  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-30 05:51:28.713  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-30 05:51:28.714  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-30 05:51:28.715  5547  5593 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 05:51:28.722  5547  5593 I System.out: Running OutgoingSocketThread
,09-30 05:51:28.725  5547  5885 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 05:51:28.725  5547  5885 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 05:51:31.736  5547  5886 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-30 05:51:31.736  5547  5886 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 05:51:31.737  5547  5886 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:51:31.737  5547  5885 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-30 05:51:31.737  5547  5885 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 05:51:31.737  5547  5885 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:51:31.738  5547  5886 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:51:31.738  5547  5885 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:51:31.741  5547  5888 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:31.741  5547  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:51:31.742  5547  5886 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 05:51:31.746  5547  5885 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 05:51:31.749  5547  5889 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:31.749  5547  5889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:31.751  5547  5890 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:31.751  5547  5890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:51:31.752  5547  5891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:31.752  5547  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:31.752  5547  5891 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:31.752  5547  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 05:51:31.753  5547  5890 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:31.753  5547  5890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:51:31.753  5547  5890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:31.753  5547  5890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 05:51:31.753  5547  5890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:51:31.753  5547  5891 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:31.753  5547  5891 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 05:51:31.754  5547  5890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:31.754  5547  5891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:31.754  5547  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:51:31.754  5547  5889 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 170, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 05:51:31.754  5547  5888 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: IncomingSocketThread/Sender): Socket closed
,09-30 05:51:31.755  5547  5890 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:31.755  5547  5889 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 170, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:31.755  5547  5889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:51:31.755  5547  5888 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:31.755  5547  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:51:31.755  5547  5888 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 05:51:31.755  5547  5889 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-30 05:51:31.755  5547  5888 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 05:51:31.755  5547  5889 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 05:51:31.755  5547  5889 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:31.755  5547  5889 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:51:31.755  5547  5888 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:51:31.755  5547  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:51:31.755  5547  5890 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:51:31.755  5547  5890 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:31.756  5547  5890 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-30 05:51:31.756  5547  5890 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:51:31.756  5547  5890 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 05:51:34.736  5547  5593 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-30 05:51:34.737  5547  5593 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-30 05:51:34.737  5547  5593 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-30 05:51:34.744  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:51:34.744  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8107b68 added. We now have 3 listener(s)
,09-30 05:51:34.747  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 05:51:34.747  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:51:34.748  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.748  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.748  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0e6b81 added. We now have 4 listener(s)
09-30 05:51:34.748  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:51:34.750  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:51:34.755  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:34.762  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:34.764  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:51:34.765  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 05:51:34.765  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.765  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@713c867 added. We now have 4 listener(s)
,09-30 05:51:34.767  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.767  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:51:34.767  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.767  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:34.767  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.767  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125e614 added. We now have 5 listener(s)
09-30 05:51:34.767  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.767  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:51:34.768  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:51:34.768  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:51:34.768  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.768  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.768  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.768  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 05:51:34.768  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.768  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8107b68 removed from the list
09-30 05:51:34.768  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.768  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0e6b81 removed from the list
09-30 05:51:34.769  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.770  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:51:34.770  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:51:34.770  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:51:34.771  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.772  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.772  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.772  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.772  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0e6b81 not in the list
09-30 05:51:34.772  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.772  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.774  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.774  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.774  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.774  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125e614 removed from the list
,09-30 05:51:34.774  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.774  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.774  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.774  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.774  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.774  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@713c867 removed from the list
09-30 05:51:34.775  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.775  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53ebd added. We now have 3 listener(s)
,09-30 05:51:34.777  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.777  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:51:34.778  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.778  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.778  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9777cb2 added. We now have 4 listener(s)
09-30 05:51:34.778  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:51:34.779  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:51:34.782  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:34.786  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:34.789  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:51:34.790  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 05:51:34.790  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.790  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3854f80 added. We now have 4 listener(s)
09-30 05:51:34.792  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.793  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.793  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:51:34.793  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.793  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.793  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc09b9 added. We now have 5 listener(s)
09-30 05:51:34.793  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.793  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:51:34.793  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:51:34.794  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-30 05:51:34.794  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:51:34.794  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:51:34.794  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:51:34.797  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:51:34.798  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:51:34.801  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 05:51:34.802  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:51:34.802  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:51:34.805  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:51:34.805  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-30 05:51:34.806  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:51:34.806  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:51:34.806  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:51:34.806  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:51:34.809  5822  5832 D BtGatt.GattService: registerClient() - UUID=842b263b-ea22-461e-89b6-dce1a5c01f96
09-30 05:51:34.810  5822  5838 D BtGatt.GattService: onClientRegistered() - UUID=842b263b-ea22-461e-89b6-dce1a5c01f96, clientIf=5
,09-30 05:51:34.810  5547  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:51:34.811  5822  5849 D BtGatt.GattService: start scan with filters
,09-30 05:51:34.816  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 05:51:34.816  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:51:34.816  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:51:34.816  5822  5841 D BtGatt.ScanManager: handling starting scan
09-30 05:51:34.816  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:51:34.816  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:51:34.816  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:51:34.816  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:51:34.819  5822  5841 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ba33
,09-30 05:51:34.819  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:51:34.820  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:51:34.820  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:51:34.821  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:51:34.824  5547  5593 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-30 05:51:34.824  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:51:34.824  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:51:34.824  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.824  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:51:34.824  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.824  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:51:34.824  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 05:51:34.824  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:51:34.824  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:51:34.825  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:51:34.825  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:51:34.825  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:51:34.826  5822  5849 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:51:34.826  5822  5838 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 05:51:34.826  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.827  5822  5841 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:51:34.827  5822  5833 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 05:51:34.828  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 05:51:34.828  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:51:34.828  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:51:34.828  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:51:34.828  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:51:34.828  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-30 05:51:34.828  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:51:34.828  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:51:34.829  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:51:34.830  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:51:34.830  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:51:34.830  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:51:34.830  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:51:34.830  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.832  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:51:34.832  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:51:34.832  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:51:34.833  5822  5838 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:51:34.833  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:51:34.833  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.833  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:51:34.833  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:51:34.833  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.833  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.833  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.834  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.834  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.834  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53ebd removed from the list
09-30 05:51:34.834  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.834  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9777cb2 removed from the list
09-30 05:51:34.834  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:51:34.834  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.834  5822  5841 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:51:34.834  5822  5841 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:51:34.835  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.835  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.836  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.836  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.836  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.836  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9777cb2 not in the list
09-30 05:51:34.836  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.836  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.837  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.837  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.837  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.837  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc09b9 removed from the list
09-30 05:51:34.837  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.837  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:51:34.837  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.837  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.837  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.837  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3854f80 removed from the list
09-30 05:51:34.838  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:51:34.838  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24a8875 added. We now have 3 listener(s)
,09-30 05:51:34.840  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.840  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:51:34.840  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.840  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.840  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecdf00a added. We now have 4 listener(s)
09-30 05:51:34.840  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.840  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:51:34.843  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:51:34.845  5822  5838 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:51:34.845  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:34.847  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:34.850  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:51:34.850  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:51:34.850  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.850  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d8e98 added. We now have 4 listener(s)
09-30 05:51:34.851  5822  5838 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:51:34.851  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.851  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.851  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:51:34.851  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.852  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.852  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:51:34.852  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc836f1 added. We now have 5 listener(s)
09-30 05:51:34.852  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.852  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:51:34.853  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:51:34.853  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:51:34.853  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:51:34.853  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:51:34.853  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:51:34.853  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.856  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:51:34.856  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:51:34.859  5822  5838 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:51:34.859  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.859  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:51:34.859  5822  5841 D BtGatt.ScanManager: stopping BLe Batch
09-30 05:51:34.859  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:51:34.860  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 05:51:34.863  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:51:34.863  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:51:34.864  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:51:34.864  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-30 05:51:34.864  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-30 05:51:34.865  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:51:34.865  5822  5838 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:51:34.865  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.865  5822  5841 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:51:34.867  5822  5832 D BtGatt.GattService: registerClient() - UUID=74e3582f-db88-40f5-a45c-aadba4549c3c
09-30 05:51:34.868  5822  5838 D BtGatt.GattService: onClientRegistered() - UUID=74e3582f-db88-40f5-a45c-aadba4549c3c, clientIf=5
,09-30 05:51:34.868  5547  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 05:51:34.869  5822  5852 D BtGatt.GattService: start scan with filters
09-30 05:51:34.870  5822  5838 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:51:34.870  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:51:34.871  5822  5841 D BtGatt.ScanManager: handling starting scan
09-30 05:51:34.872  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:51:34.872  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:51:34.872  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:51:34.872  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:51:34.872  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-30 05:51:34.872  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:51:34.872  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:51:34.878  5822  5838 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 05:51:34.878  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.878  5822  5841 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:51:34.879  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:51:34.879  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:51:34.879  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:51:34.881  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 05:51:34.883  5822  5838 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 05:51:34.883  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.884  5822  5841 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:51:34.884  5822  5841 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 05:51:34.885  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 05:51:34.885  5547  5593 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 05:51:34.885  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:51:34.885  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:51:34.885  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:51:34.885  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.885  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.885  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:51:34.885  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.885  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.885  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24a8875 removed from the list
09-30 05:51:34.886  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:51:34.886  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecdf00a removed from the list
09-30 05:51:34.886  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:51:34.886  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.886  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.887  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 05:51:34.887  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.887  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:51:34.888  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.888  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.888  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.888  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecdf00a not in the list
,09-30 05:51:34.888  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:51:34.888  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:51:34.888  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:51:34.888  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:51:34.888  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:51:34.889  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:51:34.889  5822  5849 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:51:34.890  5822  5833 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:51:34.890  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:51:34.890  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:51:34.890  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:51:34.890  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 05:51:34.890  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:51:34.890  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:51:34.890  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:51:34.890  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:51:34.892  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:51:34.892  5822  5838 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:51:34.892  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:51:34.892  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:51:34.892  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.892  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:51:34.892  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 05:51:34.892  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.893  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.894  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:51:34.894  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.894  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:51:34.894  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc836f1 removed from the list
09-30 05:51:34.894  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.894  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:51:34.894  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.894  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:51:34.894  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.894  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.894  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.894  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d8e98 removed from the list
09-30 05:51:34.895  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.895  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d98512d added. We now have 3 listener(s)
,09-30 05:51:34.896  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.896  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:51:34.896  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.896  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.896  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8647662 added. We now have 4 listener(s)
09-30 05:51:34.896  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.897  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:51:34.897  5822  5838 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:51:34.897  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:51:34.900  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:51:34.902  5822  5838 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:51:34.902  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.902  5822  5841 D BtGatt.ScanManager: stopping BLe Batch
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:34.903  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:51:34.904  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:51:34.904  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:51:34.904  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.904  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24b98b0 added. We now have 4 listener(s)
09-30 05:51:34.906  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.906  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.906  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:51:34.906  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.906  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.906  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad5d329 added. We now have 5 listener(s)
09-30 05:51:34.906  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.906  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:51:34.906  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:51:34.906  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:51:34.906  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:51:34.906  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:51:34.907  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.907  5822  5838 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:51:34.907  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.907  5822  5841 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:51:34.908  5547  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:51:34.909  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:51:34.911  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:51:34.911  5822  5838 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:51:34.911  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:51:34.912  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:51:34.912  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:51:34.914  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:51:34.915  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:51:34.915  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 05:51:34.915  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:51:34.915  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:51:34.915  5547  5593 D BluetoothAdapter: STATE_ON
09-30 05:51:34.917  5822  5832 D BtGatt.GattService: registerClient() - UUID=6a922a42-d024-4fea-ae51-0c14497b9d03
,09-30 05:51:34.917  5822  5838 D BtGatt.GattService: onClientRegistered() - UUID=6a922a42-d024-4fea-ae51-0c14497b9d03, clientIf=5
09-30 05:51:34.917  5547  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:51:34.918  5822  5852 D BtGatt.GattService: start scan with filters
,09-30 05:51:34.920  5822  5841 D BtGatt.ScanManager: handling starting scan
09-30 05:51:34.920  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:51:34.920  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-30 05:51:34.920  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:51:34.920  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:51:34.920  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:51:34.921  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:51:34.921  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:51:34.925  5822  5838 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 05:51:34.925  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.925  5822  5841 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:51:34.926  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:51:34.926  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:51:34.926  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:51:34.927  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 05:51:34.929  5822  5838 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 05:51:34.930  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.930  5822  5841 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:51:34.930  5822  5841 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 05:51:34.933  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:51:34.933  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:51:34.933  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:51:34.933  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.933  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.933  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:51:34.933  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.933  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.933  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d98512d removed from the list
,09-30 05:51:34.933  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.933  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8647662 removed from the list
09-30 05:51:34.933  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:51:34.933  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.934  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.934  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 05:51:34.934  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.934  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.935  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:51:34.935  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.935  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.935  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8647662 not in the list
09-30 05:51:34.935  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:51:34.935  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:51:34.935  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:51:34.935  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:51:34.935  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:51:34.936  5547  5593 D BluetoothAdapter: STATE_ON
,09-30 05:51:34.936  5822  5852 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:51:34.937  5822  5849 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:51:34.938  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:51:34.938  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:51:34.938  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:51:34.938  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:51:34.938  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:51:34.938  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:51:34.938  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 05:51:34.938  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:51:34.938  5822  5838 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:51:34.938  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:51:34.939  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:51:34.939  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:51:34.939  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:51:34.939  5547  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:51:34.939  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 05:51:34.940  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.941  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.941  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.941  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.941  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad5d329 removed from the list
09-30 05:51:34.941  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 05:51:34.941  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.941  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.941  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.941  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.941  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24b98b0 removed from the list
09-30 05:51:34.941  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:51:34.941  5547  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:51:34.941  5547  5547 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:51:34.942  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.942  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f78e5 added. We now have 3 listener(s)
09-30 05:51:34.943  5822  5838 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:51:34.943  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.943  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.943  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:51:34.943  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:51:34.943  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.943  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca6fba added. We now have 4 listener(s)
09-30 05:51:34.943  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.943  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:51:34.946  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:51:34.949  5822  5838 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:51:34.949  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.949  5822  5841 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:51:34.951  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:51:34.953  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:51:34.954  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:51:34.954  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:51:34.954  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cdcdc8 added. We now have 4 listener(s)
,09-30 05:51:34.955  5822  5838 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:51:34.955  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.955  5822  5841 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 05:51:34.955  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.955  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:51:34.956  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:51:34.956  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 05:51:34.956  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:51:34.956  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@703be61 added. We now have 5 listener(s)
09-30 05:51:34.956  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:51:34.956  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:51:34.956  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:51:34.956  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:51:34.957  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.957  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.957  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:51:34.957  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.957  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.957  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f78e5 removed from the list
09-30 05:51:34.957  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.957  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:51:34.957  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca6fba removed from the list
09-30 05:51:34.957  5547  5593 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:51:34.957  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.958  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.958  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:51:34.959  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.959  5822  5838 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:51:34.959  5822  5838 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:51:34.959  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.960  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:51:34.960  5547  5593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca6fba not in the list
09-30 05:51:34.960  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:51:34.960  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:51:34.961  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:51:34.961  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:51:34.961  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:51:34.961  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@703be61 removed from the list
09-30 05:51:34.961  5547  5593 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:51:34.961  5547  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:51:34.961  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:51:34.961  5547  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:51:34.961  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:51:34.961  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cdcdc8 removed from the list
09-30 05:51:34.962  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 05:51:34.962  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-30 05:51:34.962  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-30 05:51:34.962  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:51:34.962  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 05:51:34.962  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:51:35.332  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:51:35.395  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:51:35.443  5547  5547 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:51:36.484   930  2869 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-30 05:51:36.485   930  2869 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-30 05:51:36.486   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:51:36.498   930  2869 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 05:51:36.530   930  2869 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 05:51:36.532  5876  5876 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 05:51:36.993  5876  5876 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 05:51:37.018  5876  5876 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 05:51:37.019  5876  5876 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 05:51:37.024   930  2869 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:51:37.024   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 05:51:37.024   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 05:51:37.035   930  2869 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:51:37.045   507   924 D CommandListener: Setting iface cfg
,09-30 05:51:37.048   930  2869 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 05:51:37.055   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:51:37.056   930  2869 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 05:51:37.056   930  2871 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 05:51:37.078   930  5895 D DhcpClient: Receive thread started
,09-30 05:51:37.099  5547  5896 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 05:51:37.099  5547  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:37.157   930  2869 E native  : do suspend false
,09-30 05:51:37.165   930  5894 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 05:51:37.178   930  5895 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172750, domain null
,09-30 05:51:37.179   930  5894 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172750 seconds
09-30 05:51:37.179   930  5894 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 05:51:37.192   930  5895 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 05:51:37.193   930  5894 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 05:51:37.194   507   924 D CommandListener: Setting iface cfg
09-30 05:51:37.196   930  2869 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 05:51:37.198   930  5894 D DhcpClient: Scheduling renewal in 86399s
,09-30 05:51:37.202   930  2869 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 05:51:37.203   930  2869 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 05:51:37.203   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 05:51:37.204   930  2869 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 05:51:37.208   930  2871 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 05:51:37.233   930  2871 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 05:51:37.233   930  2871 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 05:51:37.235   930  2871 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 05:51:37.236   930  2871 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 05:51:37.238   930  2871 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 05:51:37.245   930  2871 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:51:37.250   930  2871 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 05:51:37.250   930  2871 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 05:51:37.250   930  2871 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 05:51:37.250   930  2871 D ConnectivityService:    accepting network in place of null
09-30 05:51:37.250   930  2869 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 05:51:37.250   930  2869 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:51:37.251   930  2871 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:51:37.260   930  5893 D NetlinkSocketObserver: NeighborEvent{elapsedMs=315672, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 05:51:37.273   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:51:37.294   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:51:37.298   930  2871 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-30 05:51:37.298  3644  3790 W QCNEJ   : |CORE| network available: 102
09-30 05:51:37.298   930  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:51:37.300  3644  3790 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-30 05:51:37.300   930  2871 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-30 05:51:37.302  3644  3790 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 05:51:37.302   930   947 D Tethering: MasterInitialState.processMessage what=3
09-30 05:51:37.302  3644  3790 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:51:37.306  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:51:37.307  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:51:37.313  3817  3817 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:51:37.314  5547  5547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:51:37.315  4945  4968 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:51:37.315  4945  4968 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:51:37.315  4945  4968 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-30 05:51:37.315  4945  4968 E SarControlService: no key has been found,reset the power
09-30 05:51:37.315  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:51:37.315  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:51:37.315  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 05:51:37.316  5547  5547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:51:37.316  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:51:37.316  4970  4970 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 05:51:37.317  4945  4981 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:51:37.318  4945  4981 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:51:37.318  4945  4981 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:51:37.319  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:51:37.319  4970  4970 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 05:51:37.321  3817  3817 D SystemUpdateService: onCreate
,09-30 05:51:37.324  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000f003000000000000ffffffff]
09-30 05:51:37.325  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:51:37.325  4970  4984 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-30 05:51:37.325  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:51:37.325  4945  4955 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 05:51:37.325  4970  4984 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@42bf4a HexData = [00000000f103000000000000ffffffff]
09-30 05:51:37.325  4970  4984 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:51:37.325  4970  4984 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 05:51:37.326  4970  4970 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:51:37.326  4945  4956 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 05:51:37.327  3817  3817 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 05:51:37.331   930  5892 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-30 05:51:37.339  3817  3817 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 05:51:37.343  3817  5306 I iu.UploadsManager: num queued entries: 0
,09-30 05:51:37.343  3817  5306 I iu.UploadsManager: num updated entries: 0
09-30 05:51:37.344  3817  5306 I iu.SyncManager: NEXT; no task
,09-30 05:51:37.347  3817  5906 I SystemUpdateService: active receiver: enabled
,09-30 05:51:37.349  3817  3817 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:51:37.350  3817  3817 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 05:51:37.352  5677  5677 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:51:37.355  5677  5677 D SprintDMHelper: simOperator: 
09-30 05:51:37.355  5677  5677 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:51:37.377  3817  5906 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:51:37.385   930  5892 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 09:51:37 GMT], X-Android-Received-Millis=[1475229097385], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475229097363]}
,09-30 05:51:37.386   930  2871 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 05:51:37.386   930  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-30 05:51:37.386   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 05:51:37.387   930  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 05:51:37.392  3817  5906 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 05:51:37.392  3817  5906 I SystemUpdateService: now status is 0 (complete)
09-30 05:51:37.392  3817  5906 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:51:37.392  3817  5906 I SystemUpdateService: file has been verified
09-30 05:51:37.392  3817  5906 I SystemUpdateService: OTA package size = 21989297
,09-30 05:51:37.397  3817  5906 I SystemUpdateService: showing system update notification
,09-30 05:51:37.406  3817  3817 D SystemUpdateService: onDestroy
,09-30 05:51:37.476  4919  5911 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 05:51:37.904  5547  5896 W !!      : call onHalfStreamCopied
,09-30 05:51:37.904  5547  5896 I testCopyDataAndClose: closing input stream
,09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:38.685  5547  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:38.686  5547  5896 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:51:38.686  5547  5896 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:38.686  5547  5896 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 05:51:38.686  5547  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 05:51:40.077   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:51:42.384  5547  5918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:42.384  5547  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:44.383  5547  5593 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-30 05:51:44.383  5547  5593 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:44.383  5547  5593 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-30 05:51:44.411  5547  5918 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 05:51:44.411  5547  5918 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:44.411  5547  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-30 05:51:44.529  5547  5920 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 05:51:44.529  5547  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:45.255   930  2871 D ConnectivityService: handlePromptUnvalidated 102
,09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 05:51:46.113  5547  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 05:51:46.126   930  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:51:48.548   930  2869 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 05:51:49.765  5547  5921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:49.765  5547  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:51:49.765  5547  5921 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:49.765  5547  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:49.766  5547  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-30 05:51:49.768  5547  5593 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:51:49.771  5547  5922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:49.771  5547  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:51:49.772  5547  5922 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
,09-30 05:51:49.772  5547  5922 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:49.772  5547  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 05:51:49.772  5547  5922 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-30 05:51:49.772  5547  5922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:51:49.772  5547  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-30 05:51:49.776  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 05:51:49.776  5547  5593 I jxcore-log: 
,09-30 05:51:49.777  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-30 05:51:49.777  5547  5593 I jxcore-log: 
09-30 05:51:49.777  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-30 05:51:49.777  5547  5593 I jxcore-log: 
09-30 05:51:49.777  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 05:51:49.777  5547  5593 I jxcore-log: 
09-30 05:51:49.777  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Total duration:  102633'
09-30 05:51:49.777  5547  5593 I jxcore-log: 
,09-30 05:51:49.777  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Failures: 
09-30 05:51:49.777  5547  5593 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-30 05:51:49.777  5547  5593 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 05:51:49.777  5547  5593 I jxcore-log:      but: was ""
09-30 05:51:49.777  5547  5593 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 05:51:49.777  5547  5593 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 05:51:49.777  5547  5593 I jxcore-log:      but: was ""
09-30 05:51:49.777  5547  5593 I jxcore-log: '
09-30 05:51:49.777  5547  5593 I jxcore-log: 
09-30 05:51:49.778  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 05:51:49.778  5547  5593 I jxcore-log: 
09-30 05:51:49.779  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 05:51:49.779  5547  5593 I jxcore-log: 
,09-30 05:51:49.782  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.782  5547  5593 I jxcore-log: 
09-30 05:51:49.783  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.783  5547  5593 I jxcore-log: 
09-30 05:51:49.783  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.783  5547  5593 I jxcore-log: 
09-30 05:51:49.784  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.784  5547  5593 I jxcore-log: 
09-30 05:51:49.784  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 05:51:49.784  5547  5593 I jxcore-log: 
,09-30 05:51:49.784  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:51:49.784  5547  5593 I jxcore-log: 
,09-30 05:51:49.784  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.784  5547  5593 I jxcore-log: 
09-30 05:51:49.785  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.785  5547  5593 I jxcore-log: 
,09-30 05:51:49.785  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 05:51:49.785  5547  5593 I jxcore-log: 
09-30 05:51:49.785  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:51:49.785  5547  5593 I jxcore-log: 
09-30 05:51:49.785  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:51:49.785  5547  5593 I jxcore-log: 
,09-30 05:51:49.785  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.785  5547  5593 I jxcore-log: 
09-30 05:51:49.786  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.786  5547  5593 I jxcore-log: 
09-30 05:51:49.786  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.786  5547  5593 I jxcore-log: 
,09-30 05:51:49.786  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.786  5547  5593 I jxcore-log: 
09-30 05:51:49.786  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.786  5547  5593 I jxcore-log: 
09-30 05:51:49.786  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.786  5547  5593 I jxcore-log: 
09-30 05:51:49.787  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.787  5547  5593 I jxcore-log: 
09-30 05:51:49.787  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.787  5547  5593 I jxcore-log: 
,09-30 05:51:49.787  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.787  5547  5593 I jxcore-log: 
09-30 05:51:49.787  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.787  5547  5593 I jxcore-log: 
09-30 05:51:49.787  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.787  5547  5593 I jxcore-log: 
09-30 05:51:49.788  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.788  5547  5593 I jxcore-log: 
09-30 05:51:49.788  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.788  5547  5593 I jxcore-log: 
,09-30 05:51:49.788  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.788  5547  5593 I jxcore-log: 
09-30 05:51:49.788  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.788  5547  5593 I jxcore-log: 
09-30 05:51:49.788  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.788  5547  5593 I jxcore-log: 
09-30 05:51:49.789  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.789  5547  5593 I jxcore-log: 
09-30 05:51:49.789  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.789  5547  5593 I jxcore-log: 
09-30 05:51:49.790  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.790  5547  5593 I jxcore-log: 
,09-30 05:51:49.790  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.790  5547  5593 I jxcore-log: 
09-30 05:51:49.790  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.790  5547  5593 I jxcore-log: 
09-30 05:51:49.790  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.790  5547  5593 I jxcore-log: 
09-30 05:51:49.791  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.791  5547  5593 I jxcore-log: 
09-30 05:51:49.791  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.791  5547  5593 I jxcore-log: 
09-30 05:51:49.791  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.791  5547  5593 I jxcore-log: 
09-30 05:51:49.791  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.791  5547  5593 I jxcore-log: 
,09-30 05:51:49.792  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.792  5547  5593 I jxcore-log: 
09-30 05:51:49.792  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.792  5547  5593 I jxcore-log: 
09-30 05:51:49.792  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.792  5547  5593 I jxcore-log: 
09-30 05:51:49.792  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:51:49.792  5547  5593 I jxcore-log: 
,09-30 05:51:49.792  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.792  5547  5593 I jxcore-log: 
09-30 05:51:49.793  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.793  5547  5593 I jxcore-log: 
09-30 05:51:49.793  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.793  5547  5593 I jxcore-log: 
,09-30 05:51:49.793  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.793  5547  5593 I jxcore-log: 
09-30 05:51:49.793  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.793  5547  5593 I jxcore-log: 
09-30 05:51:49.793  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:51:49.793  5547  5593 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-30 05:51:49.794  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.794  5547  5593 I jxcore-log: 
,09-30 05:51:49.794  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.794  5547  5593 I jxcore-log: 
09-30 05:51:49.794  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:51:49.794  5547  5593 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 05:51:49.794  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:51:49.794  5547  5593 I jxcore-log: 
,09-30 05:51:49.794  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:51:49.794  5547  5593 I jxcore-log: 
09-30 05:51:49.795  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:51:49.795  5547  5593 I jxcore-log: 
09-30 05:51:49.795  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:51:49.795  5547  5593 I jxcore-log: 
09-30 05:51:49.795  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.795  5547  5593 I jxcore-log: 
,09-30 05:51:49.795  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:51:49.795  5547  5593 I jxcore-log: 
09-30 05:51:49.798  5547  5547 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-30 05:51:49.799  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 05:51:49.799  5547  5593 I jxcore-log: 
09-30 05:51:49.800  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - WARN testUtils: 'myNameCallback not set!'
09-30 05:51:49.800  5547  5593 I jxcore-log: 
,09-30 05:51:49.802  5547  5593 I jxcore-log: 2016-09-30 09:51:49 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 05:51:49.802  5547  5593 I jxcore-log: 
,09-30 05:51:50.432  5547  5593 I jxcore-log: 2016-09-30 09:51:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 05:51:50.432  5547  5593 I jxcore-log: 
,09-30 05:51:50.548  5547  5593 I jxcore-log: 2016-09-30 09:51:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 05:51:50.548  5547  5593 I jxcore-log: 
,09-30 05:51:50.557  5547  5593 I jxcore-log: 2016-09-30 09:51:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 05:51:50.557  5547  5593 I jxcore-log: 
,09-30 05:51:50.948  5547  5593 I jxcore-log: 2016-09-30 09:51:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 05:51:50.948  5547  5593 I jxcore-log: 
,09-30 05:51:51.041  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 05:51:51.041  5547  5593 I jxcore-log: 
,09-30 05:51:51.044  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 05:51:51.044  5547  5593 I jxcore-log: 
,09-30 05:51:51.048  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 05:51:51.048  5547  5593 I jxcore-log: 
,09-30 05:51:51.157   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 05:51:51.157   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 05:51:51.431  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 05:51:51.431  5547  5593 I jxcore-log: 
,09-30 05:51:51.466  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 05:51:51.466  5547  5593 I jxcore-log: 
,09-30 05:51:51.473  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 05:51:51.473  5547  5593 I jxcore-log: 
,09-30 05:51:51.475  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 05:51:51.475  5547  5593 I jxcore-log: 
,09-30 05:51:51.649  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 05:51:51.649  5547  5593 I jxcore-log: 
,09-30 05:51:51.695  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 05:51:51.695  5547  5593 I jxcore-log: 
,09-30 05:51:51.796  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 05:51:51.796  5547  5593 I jxcore-log: 
,09-30 05:51:51.802  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 05:51:51.802  5547  5593 I jxcore-log: 
,09-30 05:51:51.805  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 05:51:51.805  5547  5593 I jxcore-log: 
,09-30 05:51:51.809  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 05:51:51.809  5547  5593 I jxcore-log: 
,09-30 05:51:51.812  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 05:51:51.812  5547  5593 I jxcore-log: 
,09-30 05:51:51.823  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 05:51:51.823  5547  5593 I jxcore-log: 
,09-30 05:51:51.851  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 05:51:51.851  5547  5593 I jxcore-log: 
,09-30 05:51:51.855  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 05:51:51.855  5547  5593 I jxcore-log: 
,09-30 05:51:51.859  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 05:51:51.859  5547  5593 I jxcore-log: 
,09-30 05:51:51.866  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 05:51:51.866  5547  5593 I jxcore-log: 
,09-30 05:51:51.868  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 05:51:51.868  5547  5593 I jxcore-log: 
,09-30 05:51:51.871  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 05:51:51.871  5547  5593 I jxcore-log: 
,09-30 05:51:51.874  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 05:51:51.874  5547  5593 I jxcore-log: 
,09-30 05:51:51.879  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 05:51:51.879  5547  5593 I jxcore-log: 
,09-30 05:51:51.890  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 05:51:51.890  5547  5593 I jxcore-log: 
,09-30 05:51:51.897  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 05:51:51.897  5547  5593 I jxcore-log: 
,09-30 05:51:51.905  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 05:51:51.905  5547  5593 I jxcore-log: 
,09-30 05:51:51.912  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 05:51:51.912  5547  5593 I jxcore-log: 
,09-30 05:51:51.917  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 05:51:51.917  5547  5593 I jxcore-log: 
,09-30 05:51:51.923  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 05:51:51.923  5547  5593 I jxcore-log: 
,09-30 05:51:51.925  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 05:51:51.925  5547  5593 I jxcore-log: 
,09-30 05:51:51.936  5547  5593 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 05:51:51.937  5547  5593 I jxcore-log: 2016-09-30 09:51:51 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 05:51:51.937  5547  5593 I jxcore-log: 
,09-30 05:51:51.954  5547  5593 W jxcore-log: Warning: a promise was created in a handler at node.js:898:9 but was not returned from it, see http://goo.gl/rRqMUw
09-30 05:51:51.954  5547  5593 W jxcore-log:     at new Promise (/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:77:14)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at Object.module.exports.hasRequiredHardware (/data/data/com.test.thalitest/files/www/jxcore/lib/testUtils.js:143:10)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at Object.<anonymous> (/data/data/com.test.thalitest/files/www/jxcore/runTests.js:72:11)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at $w._compile (module.js:619:12)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at Object.$w._extensions..js (module.js:649:8)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at $w.load (module.js:440:20)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at Function.$w._load (module.js:405:8)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at $w.require (module.js:475:11)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at require (module.js:493:12)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at /data/data/com.test.thalitest/files/www/jxcore/app.js:76:13
09-30 05:51:51.954  5547  5593 W jxcore-log: From previous event:
09-30 05:51:51.954  5547  5593 W jxcore-log:     at /data/data/com.test.thalitest/files/www/jxcore/app.js:73:12
09-30 05:51:51.954  5547  5593 W jxcore-log:     at Array.reduce (native)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at /data/data/com.test.thalitest/files/www/jxcore/app.js:71:20
09-30 05:51:51.954  5547  5593 W jxcore-log:     at WrapFunction.callback (main.js:54:22)
09-30 05:51:51.954  5547  5593 W jxcore-log:     at JXMobile.ping (main.js:89:30)
09-30 05:51:51.954  5547  5593 W jxcore-log:     
,09-30 05:51:52.047  5547  5593 I jxcore-log: 2016-09-30 09:51:52 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 05:51:52.047  5547  5593 I jxcore-log: 
,09-30 05:51:52.481  5547  5593 I jxcore-log: TAP version 13
09-30 05:51:52.481  5547  5593 I jxcore-log: 
,09-30 05:51:52.484  5547  5593 I jxcore-log: # setup
09-30 05:51:52.484  5547  5593 I jxcore-log: 
,09-30 05:51:53.316  5547  5593 I jxcore-log: # calling createNativeListener directly rejects
09-30 05:51:53.316  5547  5593 I jxcore-log: 
,09-30 05:51:53.698  5547  5593 I jxcore-log: 2016-09-30 09:51:53 - DEBUG createNativeListener: 'creating native server'
09-30 05:51:53.698  5547  5593 I jxcore-log: 
,09-30 05:51:53.707  5547  5593 I jxcore-log: 2016-09-30 09:51:53 - DEBUG createNativeListener: 'listening 40982'
09-30 05:51:53.707  5547  5593 I jxcore-log: 
,09-30 05:51:53.716  5547  5593 I jxcore-log: ok 1 Should throw
09-30 05:51:53.716  5547  5593 I jxcore-log: 
,09-30 05:51:53.721  5547  5593 I jxcore-log: # teardown
09-30 05:51:53.721  5547  5593 I jxcore-log: 
,09-30 05:51:54.117  5547  5593 I jxcore-log: # setup
09-30 05:51:54.117  5547  5593 I jxcore-log: 
,09-30 05:51:54.822  5547  5593 I jxcore-log: # emits incomingConnectionState
09-30 05:51:54.822  5547  5593 I jxcore-log: 
,09-30 05:51:55.224  5547  5593 I jxcore-log: 2016-09-30 09:51:55 - DEBUG createNativeListener: 'creating native server'
09-30 05:51:55.224  5547  5593 I jxcore-log: 
,09-30 05:51:55.230  5547  5593 I jxcore-log: 2016-09-30 09:51:55 - DEBUG createNativeListener: 'listening 49213'
09-30 05:51:55.230  5547  5593 I jxcore-log: 
,09-30 05:51:55.248  5547  5593 I jxcore-log: 2016-09-30 09:51:55 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:51:55.248  5547  5593 I jxcore-log: 
,09-30 05:51:55.255  5547  5593 I jxcore-log: 2016-09-30 09:51:55 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:51:55.255  5547  5593 I jxcore-log: 
,09-30 05:51:55.268  5547  5593 I jxcore-log: 2016-09-30 09:51:55 - DEBUG createNativeListener: 'new mux'
09-30 05:51:55.268  5547  5593 I jxcore-log: 
,09-30 05:51:55.277  5547  5593 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 05:51:55.277  5547  5593 I jxcore-log: 
,09-30 05:51:55.302  5547  5593 I jxcore-log: 2016-09-30 09:51:55 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:51:55.302  5547  5593 I jxcore-log: 
,09-30 05:51:55.303  5547  5593 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 05:51:55.303  5547  5593 I jxcore-log: 
,09-30 05:51:55.312  5547  5593 I jxcore-log: # teardown
09-30 05:51:55.312  5547  5593 I jxcore-log: 
,09-30 05:51:56.153  5547  5593 I jxcore-log: # setup
09-30 05:51:56.153  5547  5593 I jxcore-log: 
,09-30 05:51:56.334  5547  5593 I jxcore-log: # emits routerPortConnectionFailed
09-30 05:51:56.334  5547  5593 I jxcore-log: 
,09-30 05:51:57.206   930  2869 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:51:57.266  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'creating native server'
09-30 05:51:57.266  5547  5593 I jxcore-log: 
,09-30 05:51:57.272  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'listening 37667'
09-30 05:51:57.272  5547  5593 I jxcore-log: 
,09-30 05:51:57.281  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:51:57.281  5547  5593 I jxcore-log: 
,09-30 05:51:57.283  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:51:57.283  5547  5593 I jxcore-log: 
,09-30 05:51:57.290  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'new mux'
09-30 05:51:57.290  5547  5593 I jxcore-log: 
,09-30 05:51:57.321  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'new stream: '
09-30 05:51:57.321  5547  5593 I jxcore-log: 
,09-30 05:51:57.324  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:51:57.324  5547  5593 I jxcore-log: 
,09-30 05:51:57.328  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
09-30 05:51:57.328  5547  5593 I jxcore-log:     at $c (net.js:837:7)
09-30 05:51:57.328  5547  5593 I jxcore-log:     at Object.$09 [as oncomplete] (net.js:829:13)'
09-30 05:51:57.328  5547  5593 I jxcore-log: 
,09-30 05:51:57.329  5547  5593 I jxcore-log: ok 4 tried to connect to right port
09-30 05:51:57.329  5547  5593 I jxcore-log: 
,09-30 05:51:57.330  5547  5593 I jxcore-log: ok 5 failed due to refused connection
09-30 05:51:57.330  5547  5593 I jxcore-log: 
09-30 05:51:57.330  5547  5593 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 05:51:57.330  5547  5593 I jxcore-log: 
,09-30 05:51:57.335  5547  5593 I jxcore-log: # teardown
09-30 05:51:57.335  5547  5593 I jxcore-log: 
,09-30 05:51:57.339  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'stream close:'
09-30 05:51:57.339  5547  5593 I jxcore-log: 
,09-30 05:51:57.624  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'mux close'
09-30 05:51:57.624  5547  5593 I jxcore-log: 
,09-30 05:51:57.633  5547  5593 I jxcore-log: # setup
09-30 05:51:57.633  5547  5593 I jxcore-log: 
,09-30 05:51:57.639  5547  5593 I jxcore-log: 2016-09-30 09:51:57 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:51:57.639  5547  5593 I jxcore-log: 
,09-30 05:51:59.333  5547  5593 I jxcore-log: # native server connections all up
09-30 05:51:59.333  5547  5593 I jxcore-log: 
,09-30 05:51:59.363  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'creating native server'
09-30 05:51:59.363  5547  5593 I jxcore-log: 
,09-30 05:51:59.369  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'listening 43672'
09-30 05:51:59.369  5547  5593 I jxcore-log: 
,09-30 05:51:59.375  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:51:59.375  5547  5593 I jxcore-log: 
,09-30 05:51:59.376  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:51:59.376  5547  5593 I jxcore-log: 
09-30 05:51:59.377  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'new mux'
09-30 05:51:59.377  5547  5593 I jxcore-log: 
,09-30 05:51:59.408  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'new stream: '
09-30 05:51:59.408  5547  5593 I jxcore-log: 
,09-30 05:51:59.411  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:51:59.411  5547  5593 I jxcore-log: 
,09-30 05:51:59.412  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'new stream: '
09-30 05:51:59.412  5547  5593 I jxcore-log: 
,09-30 05:51:59.415  5547  5593 I jxcore-log: 2016-09-30 09:51:59 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:51:59.415  5547  5593 I jxcore-log: 
,09-30 05:51:59.432  5547  5593 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 05:51:59.432  5547  5593 I jxcore-log: 
,09-30 05:51:59.433  5547  5593 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 05:51:59.433  5547  5593 I jxcore-log: 
09-30 05:51:59.433  5547  5593 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 05:51:59.433  5547  5593 I jxcore-log: 
09-30 05:51:59.433  5547  5593 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 05:51:59.433  5547  5593 I jxcore-log: 
,09-30 05:51:59.434  5547  5593 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 05:51:59.434  5547  5593 I jxcore-log: 
,09-30 05:51:59.438  5547  5593 I jxcore-log: # teardown
09-30 05:51:59.438  5547  5593 I jxcore-log: 
,09-30 05:52:00.043  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:00.043  5547  5593 I jxcore-log: 
,09-30 05:52:00.046  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:00.046  5547  5593 I jxcore-log: 
09-30 05:52:00.048  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'mux close'
09-30 05:52:00.048  5547  5593 I jxcore-log: 
,09-30 05:52:00.062  5547  5593 I jxcore-log: # setup
09-30 05:52:00.062  5547  5593 I jxcore-log: 
,09-30 05:52:00.065  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:00.065  5547  5593 I jxcore-log: 
,09-30 05:52:00.113  5547  5593 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 05:52:00.113  5547  5593 I jxcore-log: 
,09-30 05:52:00.167  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:00.167  5547  5593 I jxcore-log: 
,09-30 05:52:00.170  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'listening 39545'
09-30 05:52:00.170  5547  5593 I jxcore-log: 
,09-30 05:52:00.176  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:00.176  5547  5593 I jxcore-log: 
,09-30 05:52:00.177  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:00.177  5547  5593 I jxcore-log: 
,09-30 05:52:00.178  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new mux'
09-30 05:52:00.178  5547  5593 I jxcore-log: 
,09-30 05:52:00.187  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:00.187  5547  5593 I jxcore-log: 
,09-30 05:52:00.190  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:00.190  5547  5593 I jxcore-log: 
,09-30 05:52:00.210  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:00.210  5547  5593 I jxcore-log: 
,09-30 05:52:00.218  5547  5593 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 05:52:00.218  5547  5593 I jxcore-log: 
,09-30 05:52:00.219  5547  5593 I jxcore-log: ok 13 incoming remains open
09-30 05:52:00.219  5547  5593 I jxcore-log: 
,09-30 05:52:00.222  5547  5593 I jxcore-log: # teardown
09-30 05:52:00.222  5547  5593 I jxcore-log: 
,09-30 05:52:00.268  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'mux close'
09-30 05:52:00.268  5547  5593 I jxcore-log: 
,09-30 05:52:00.272  5547  5593 I jxcore-log: # setup
09-30 05:52:00.272  5547  5593 I jxcore-log: 
,09-30 05:52:00.275  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:00.275  5547  5593 I jxcore-log: 
,09-30 05:52:00.318  5547  5593 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 05:52:00.318  5547  5593 I jxcore-log: 
,09-30 05:52:00.350  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:00.350  5547  5593 I jxcore-log: 
,09-30 05:52:00.355  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'listening 47813'
09-30 05:52:00.355  5547  5593 I jxcore-log: 
,09-30 05:52:00.363  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:00.363  5547  5593 I jxcore-log: 
,09-30 05:52:00.364  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:00.364  5547  5593 I jxcore-log: 
,09-30 05:52:00.366  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new mux'
09-30 05:52:00.366  5547  5593 I jxcore-log: 
,09-30 05:52:00.373  5547  5593 I jxcore-log: ok 14 we should not have gotten an error
09-30 05:52:00.373  5547  5593 I jxcore-log: 
,09-30 05:52:00.377  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:00.377  5547  5593 I jxcore-log: 
,09-30 05:52:00.379  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:00.379  5547  5593 I jxcore-log: 
,09-30 05:52:00.386  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:00.386  5547  5593 I jxcore-log: 
,09-30 05:52:00.388  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:00.388  5547  5593 I jxcore-log: 
,09-30 05:52:00.393  5547  5593 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 05:52:00.393  5547  5593 I jxcore-log: 
,09-30 05:52:00.394  5547  5593 I jxcore-log: ok 16 incoming is cleaned up
09-30 05:52:00.394  5547  5593 I jxcore-log: 
,09-30 05:52:00.398  5547  5593 I jxcore-log: # teardown
09-30 05:52:00.398  5547  5593 I jxcore-log: 
,09-30 05:52:00.447  5547  5593 I jxcore-log: # setup
09-30 05:52:00.447  5547  5593 I jxcore-log: 
,09-30 05:52:00.509  5547  5593 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 05:52:00.509  5547  5593 I jxcore-log: 
,09-30 05:52:00.556  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:00.556  5547  5593 I jxcore-log: 
,09-30 05:52:00.561  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'listening 41819'
09-30 05:52:00.561  5547  5593 I jxcore-log: 
,09-30 05:52:00.569  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:00.569  5547  5593 I jxcore-log: 
,09-30 05:52:00.570  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:00.570  5547  5593 I jxcore-log: 
,09-30 05:52:00.573  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new mux'
09-30 05:52:00.573  5547  5593 I jxcore-log: 
,09-30 05:52:00.582  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:00.582  5547  5593 I jxcore-log: 
,09-30 05:52:00.586  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:00.586  5547  5593 I jxcore-log: 
,09-30 05:52:00.598  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:00.598  5547  5593 I jxcore-log: 
,09-30 05:52:00.606  5547  5593 I jxcore-log: ok 17 stream was closed
09-30 05:52:00.606  5547  5593 I jxcore-log: 
,09-30 05:52:00.607  5547  5593 I jxcore-log: ok 18 incoming should survive
09-30 05:52:00.607  5547  5593 I jxcore-log: 
09-30 05:52:00.607  5547  5593 I jxcore-log: ok 19 mux should have no streams
09-30 05:52:00.607  5547  5593 I jxcore-log: 
,09-30 05:52:00.615  5547  5593 I jxcore-log: # teardown
09-30 05:52:00.615  5547  5593 I jxcore-log: 
,09-30 05:52:00.638  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'mux close'
09-30 05:52:00.638  5547  5593 I jxcore-log: 
,09-30 05:52:00.641  5547  5593 I jxcore-log: # setup
09-30 05:52:00.641  5547  5593 I jxcore-log: 
,09-30 05:52:00.643  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:00.643  5547  5593 I jxcore-log: 
,09-30 05:52:00.724  5547  5593 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 05:52:00.724  5547  5593 I jxcore-log: 
,09-30 05:52:00.801  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:00.801  5547  5593 I jxcore-log: 
,09-30 05:52:00.806  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'listening 39623'
09-30 05:52:00.806  5547  5593 I jxcore-log: 
,09-30 05:52:00.814  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:00.814  5547  5593 I jxcore-log: 
,09-30 05:52:00.815  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:00.815  5547  5593 I jxcore-log: 
,09-30 05:52:00.816  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new mux'
09-30 05:52:00.816  5547  5593 I jxcore-log: 
,09-30 05:52:00.825  5547  5593 I jxcore-log: ok 20 we should not have gotten an error
09-30 05:52:00.825  5547  5593 I jxcore-log: 
,09-30 05:52:00.828  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:00.828  5547  5593 I jxcore-log: 
,09-30 05:52:00.831  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:00.831  5547  5593 I jxcore-log: 
,09-30 05:52:00.839  5547  5593 I jxcore-log: ok 21 Buffers are identical
09-30 05:52:00.839  5547  5593 I jxcore-log: 
,09-30 05:52:00.840  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:00.840  5547  5593 I jxcore-log: 
,09-30 05:52:00.842  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'mux close'
09-30 05:52:00.842  5547  5593 I jxcore-log: 
,09-30 05:52:00.844  5547  5593 I jxcore-log: ok 22 native server is nulled out
09-30 05:52:00.844  5547  5593 I jxcore-log: 
09-30 05:52:00.844  5547  5593 I jxcore-log: ok 23 native server should be closed
09-30 05:52:00.844  5547  5593 I jxcore-log: 
,09-30 05:52:00.844  5547  5593 I jxcore-log: ok 24 incoming has been removed
09-30 05:52:00.844  5547  5593 I jxcore-log: 
09-30 05:52:00.844  5547  5593 I jxcore-log: ok 25 Incoming should be done
09-30 05:52:00.844  5547  5593 I jxcore-log: 
09-30 05:52:00.845  5547  5593 I jxcore-log: ok 26 The mux object should be closed
09-30 05:52:00.845  5547  5593 I jxcore-log: 
09-30 05:52:00.845  5547  5593 I jxcore-log: ok 27 The mux stream should be closed
09-30 05:52:00.845  5547  5593 I jxcore-log: 
,09-30 05:52:00.845  5547  5593 I jxcore-log: 2016-09-30 09:52:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:00.845  5547  5593 I jxcore-log: 
,09-30 05:52:00.857  5547  5593 I jxcore-log: # teardown
09-30 05:52:00.857  5547  5593 I jxcore-log: 
,09-30 05:52:00.927  5547  5593 I jxcore-log: # setup
09-30 05:52:00.927  5547  5593 I jxcore-log: 
,09-30 05:52:00.949  5547  5593 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 05:52:00.949  5547  5593 I jxcore-log: 
,09-30 05:52:01.046  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:01.046  5547  5593 I jxcore-log: 
,09-30 05:52:01.051  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'listening 48479'
09-30 05:52:01.051  5547  5593 I jxcore-log: 
,09-30 05:52:01.079  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.079  5547  5593 I jxcore-log: 
,09-30 05:52:01.080  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.080  5547  5593 I jxcore-log: 
,09-30 05:52:01.081  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.081  5547  5593 I jxcore-log: 
,09-30 05:52:01.084  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.084  5547  5593 I jxcore-log: 
09-30 05:52:01.084  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.084  5547  5593 I jxcore-log: 
09-30 05:52:01.085  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.085  5547  5593 I jxcore-log: 
09-30 05:52:01.086  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.086  5547  5593 I jxcore-log: 
09-30 05:52:01.087  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.087  5547  5593 I jxcore-log: 
09-30 05:52:01.089  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.089  5547  5593 I jxcore-log: 
,09-30 05:52:01.091  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.091  5547  5593 I jxcore-log: 
,09-30 05:52:01.091  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.091  5547  5593 I jxcore-log: 
09-30 05:52:01.092  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.092  5547  5593 I jxcore-log: 
09-30 05:52:01.094  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.094  5547  5593 I jxcore-log: 
09-30 05:52:01.094  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.094  5547  5593 I jxcore-log: 
,09-30 05:52:01.095  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.095  5547  5593 I jxcore-log: 
,09-30 05:52:01.096  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.096  5547  5593 I jxcore-log: 
09-30 05:52:01.097  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.097  5547  5593 I jxcore-log: 
09-30 05:52:01.097  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.097  5547  5593 I jxcore-log: 
,09-30 05:52:01.101  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.101  5547  5593 I jxcore-log: 
,09-30 05:52:01.101  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.101  5547  5593 I jxcore-log: 
,09-30 05:52:01.102  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.102  5547  5593 I jxcore-log: 
,09-30 05:52:01.103  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.103  5547  5593 I jxcore-log: 
,09-30 05:52:01.104  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.104  5547  5593 I jxcore-log: 
09-30 05:52:01.104  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.104  5547  5593 I jxcore-log: 
,09-30 05:52:01.105  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.105  5547  5593 I jxcore-log: 
,09-30 05:52:01.106  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.106  5547  5593 I jxcore-log: 
,09-30 05:52:01.106  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.106  5547  5593 I jxcore-log: 
,09-30 05:52:01.107  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:01.107  5547  5593 I jxcore-log: 
09-30 05:52:01.107  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:01.107  5547  5593 I jxcore-log: 
,09-30 05:52:01.108  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new mux'
09-30 05:52:01.108  5547  5593 I jxcore-log: 
,09-30 05:52:01.156  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.156  5547  5593 I jxcore-log: 
,09-30 05:52:01.158  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.158  5547  5593 I jxcore-log: 
,09-30 05:52:01.158  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.158  5547  5593 I jxcore-log: 
,09-30 05:52:01.159  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.159  5547  5593 I jxcore-log: 
,09-30 05:52:01.159  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.159  5547  5593 I jxcore-log: 
09-30 05:52:01.160  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.160  5547  5593 I jxcore-log: 
,09-30 05:52:01.160  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.160  5547  5593 I jxcore-log: 
,09-30 05:52:01.161  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.161  5547  5593 I jxcore-log: 
,09-30 05:52:01.161  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.161  5547  5593 I jxcore-log: 
,09-30 05:52:01.164  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.164  5547  5593 I jxcore-log: 
,09-30 05:52:01.164  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.164  5547  5593 I jxcore-log: 
09-30 05:52:01.165  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.165  5547  5593 I jxcore-log: 
,09-30 05:52:01.166  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.166  5547  5593 I jxcore-log: 
,09-30 05:52:01.166  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.166  5547  5593 I jxcore-log: 
,09-30 05:52:01.167  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.167  5547  5593 I jxcore-log: 
,09-30 05:52:01.167  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.167  5547  5593 I jxcore-log: 
09-30 05:52:01.168  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.168  5547  5593 I jxcore-log: 
,09-30 05:52:01.169  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.169  5547  5593 I jxcore-log: 
09-30 05:52:01.169  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.169  5547  5593 I jxcore-log: 
,09-30 05:52:01.169  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.169  5547  5593 I jxcore-log: 
09-30 05:52:01.170  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.170  5547  5593 I jxcore-log: 
09-30 05:52:01.170  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.170  5547  5593 I jxcore-log: 
,09-30 05:52:01.170  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.170  5547  5593 I jxcore-log: 
09-30 05:52:01.171  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.171  5547  5593 I jxcore-log: 
,09-30 05:52:01.172  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.172  5547  5593 I jxcore-log: 
,09-30 05:52:01.172  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.172  5547  5593 I jxcore-log: 
09-30 05:52:01.173  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.173  5547  5593 I jxcore-log: 
,09-30 05:52:01.173  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.173  5547  5593 I jxcore-log: 
09-30 05:52:01.174  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.174  5547  5593 I jxcore-log: 
,09-30 05:52:01.178  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.178  5547  5593 I jxcore-log: 
,09-30 05:52:01.178  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.178  5547  5593 I jxcore-log: 
,09-30 05:52:01.181  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.181  5547  5593 I jxcore-log: 
,09-30 05:52:01.182  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.182  5547  5593 I jxcore-log: 
,09-30 05:52:01.182  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.182  5547  5593 I jxcore-log: 
09-30 05:52:01.183  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.183  5547  5593 I jxcore-log: 
,09-30 05:52:01.183  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.183  5547  5593 I jxcore-log: 
09-30 05:52:01.183  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.183  5547  5593 I jxcore-log: 
,09-30 05:52:01.184  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.184  5547  5593 I jxcore-log: 
09-30 05:52:01.184  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.184  5547  5593 I jxcore-log: 
09-30 05:52:01.185  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.185  5547  5593 I jxcore-log: 
,09-30 05:52:01.185  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.185  5547  5593 I jxcore-log: 
,09-30 05:52:01.186  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.186  5547  5593 I jxcore-log: 
09-30 05:52:01.186  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.186  5547  5593 I jxcore-log: 
,09-30 05:52:01.187  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.187  5547  5593 I jxcore-log: 
09-30 05:52:01.187  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.187  5547  5593 I jxcore-log: 
09-30 05:52:01.188  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.188  5547  5593 I jxcore-log: 
,09-30 05:52:01.188  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.188  5547  5593 I jxcore-log: 
09-30 05:52:01.188  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.188  5547  5593 I jxcore-log: 
,09-30 05:52:01.189  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.189  5547  5593 I jxcore-log: 
09-30 05:52:01.189  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.189  5547  5593 I jxcore-log: 
09-30 05:52:01.190  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.190  5547  5593 I jxcore-log: 
,09-30 05:52:01.191  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.191  5547  5593 I jxcore-log: 
,09-30 05:52:01.191  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.191  5547  5593 I jxcore-log: 
09-30 05:52:01.192  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.192  5547  5593 I jxcore-log: 
,09-30 05:52:01.192  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.192  5547  5593 I jxcore-log: 
09-30 05:52:01.192  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.192  5547  5593 I jxcore-log: 
,09-30 05:52:01.193  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.193  5547  5593 I jxcore-log: 
09-30 05:52:01.194  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.194  5547  5593 I jxcore-log: 
09-30 05:52:01.194  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.194  5547  5593 I jxcore-log: 
,09-30 05:52:01.194  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.194  5547  5593 I jxcore-log: 
09-30 05:52:01.195  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.195  5547  5593 I jxcore-log: 
09-30 05:52:01.195  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.195  5547  5593 I jxcore-log: 
09-30 05:52:01.195  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.195  5547  5593 I jxcore-log: 
,09-30 05:52:01.196  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.196  5547  5593 I jxcore-log: 
,09-30 05:52:01.197  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.197  5547  5593 I jxcore-log: 
,09-30 05:52:01.198  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.198  5547  5593 I jxcore-log: 
09-30 05:52:01.199  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.199  5547  5593 I jxcore-log: 
09-30 05:52:01.199  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.199  5547  5593 I jxcore-log: 
,09-30 05:52:01.199  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.199  5547  5593 I jxcore-log: 
09-30 05:52:01.200  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.200  5547  5593 I jxcore-log: 
09-30 05:52:01.200  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.200  5547  5593 I jxcore-log: 
,09-30 05:52:01.202  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.202  5547  5593 I jxcore-log: 
,09-30 05:52:01.203  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.203  5547  5593 I jxcore-log: 
,09-30 05:52:01.203  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.203  5547  5593 I jxcore-log: 
09-30 05:52:01.204  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.204  5547  5593 I jxcore-log: 
,09-30 05:52:01.204  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.204  5547  5593 I jxcore-log: 
09-30 05:52:01.205  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.205  5547  5593 I jxcore-log: 
,09-30 05:52:01.205  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.205  5547  5593 I jxcore-log: 
09-30 05:52:01.206  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:01.206  5547  5593 I jxcore-log: 
,09-30 05:52:01.206  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:01.206  5547  5593 I jxcore-log: 
,09-30 05:52:01.242  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.242  5547  5593 I jxcore-log: 
,09-30 05:52:01.243  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.243  5547  5593 I jxcore-log: 
09-30 05:52:01.243  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.243  5547  5593 I jxcore-log: 
09-30 05:52:01.243  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.243  5547  5593 I jxcore-log: 
,09-30 05:52:01.244  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.244  5547  5593 I jxcore-log: 
09-30 05:52:01.244  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.244  5547  5593 I jxcore-log: 
09-30 05:52:01.246  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.246  5547  5593 I jxcore-log: 
,09-30 05:52:01.246  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.246  5547  5593 I jxcore-log: 
09-30 05:52:01.246  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.246  5547  5593 I jxcore-log: 
09-30 05:52:01.247  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.247  5547  5593 I jxcore-log: 
09-30 05:52:01.247  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.247  5547  5593 I jxcore-log: 
,09-30 05:52:01.247  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.247  5547  5593 I jxcore-log: 
09-30 05:52:01.248  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.248  5547  5593 I jxcore-log: 
09-30 05:52:01.248  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.248  5547  5593 I jxcore-log: 
09-30 05:52:01.248  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.248  5547  5593 I jxcore-log: 
09-30 05:52:01.248  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.248  5547  5593 I jxcore-log: 
,09-30 05:52:01.249  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.249  5547  5593 I jxcore-log: 
09-30 05:52:01.249  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.249  5547  5593 I jxcore-log: 
,09-30 05:52:01.249  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.249  5547  5593 I jxcore-log: 
09-30 05:52:01.249  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.249  5547  5593 I jxcore-log: 
09-30 05:52:01.249  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.249  5547  5593 I jxcore-log: 
,09-30 05:52:01.250  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.250  5547  5593 I jxcore-log: 
09-30 05:52:01.250  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.250  5547  5593 I jxcore-log: 
09-30 05:52:01.250  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.250  5547  5593 I jxcore-log: 
09-30 05:52:01.250  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.250  5547  5593 I jxcore-log: 
,09-30 05:52:01.250  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.250  5547  5593 I jxcore-log: 
09-30 05:52:01.251  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.251  5547  5593 I jxcore-log: 
09-30 05:52:01.251  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.251  5547  5593 I jxcore-log: 
09-30 05:52:01.251  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.251  5547  5593 I jxcore-log: 
,09-30 05:52:01.251  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.251  5547  5593 I jxcore-log: 
09-30 05:52:01.252  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.252  5547  5593 I jxcore-log: 
09-30 05:52:01.252  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.252  5547  5593 I jxcore-log: 
09-30 05:52:01.252  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.252  5547  5593 I jxcore-log: 
09-30 05:52:01.252  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.252  5547  5593 I jxcore-log: 
,09-30 05:52:01.252  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.252  5547  5593 I jxcore-log: 
09-30 05:52:01.253  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.253  5547  5593 I jxcore-log: 
09-30 05:52:01.253  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.253  5547  5593 I jxcore-log: 
09-30 05:52:01.256  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.256  5547  5593 I jxcore-log: 
09-30 05:52:01.256  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.256  5547  5593 I jxcore-log: 
,09-30 05:52:01.257  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.257  5547  5593 I jxcore-log: 
09-30 05:52:01.257  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.257  5547  5593 I jxcore-log: 
09-30 05:52:01.257  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.257  5547  5593 I jxcore-log: 
09-30 05:52:01.257  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.257  5547  5593 I jxcore-log: 
09-30 05:52:01.259  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.259  5547  5593 I jxcore-log: 
09-30 05:52:01.260  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.260  5547  5593 I jxcore-log: 
09-30 05:52:01.260  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.260  5547  5593 I jxcore-log: 
09-30 05:52:01.260  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.260  5547  5593 I jxcore-log: 
09-30 05:52:01.260  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.260  5547  5593 I jxcore-log: 
09-30 05:52:01.261  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:01.261  5547  5593 I jxcore-log: 
09-30 05:52:01.262  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'mux close'
09-30 05:52:01.262  5547  5593 I jxcore-log: 
09-30 05:52:01.263  5547  5593 I jxcore-log: ok 28 native server is nulled out
09-30 05:52:01.263  5547  5593 I jxcore-log: 
09-30 05:52:01.263  5547  5593 I jxcore-log: ok 29 native server should be closed
09-30 05:52:01.263  5547  5593 I jxcore-log: 
09-30 05:52:01.263  5547  5593 I jxcore-log: ok 30 incoming has been removed
09-30 05:52:01.263  5547  5593 I jxcore-log: 
09-30 05:52:01.263  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.263  5547  5593 I jxcore-log: 
09-30 05:52:01.264  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.264  5547  5593 I jxcore-log: 
09-30 05:52:01.264  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.264  5547  5593 I jxcore-log: 
09-30 05:52:01.264  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.264  5547  5593 I jxcore-log: 
09-30 05:52:01.264  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.264  5547  5593 I jxcore-log: 
09-30 05:52:01.264  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.264  5547  5593 I jxcore-log: 
09-30 05:52:01.264  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.264  5547  5593 I jxcore-log: 
09-30 05:52:01.265  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.265  5547  5593 I jxcore-log: 
09-30 05:52:01.265  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.265  5547  5593 I jxcore-log: 
09-30 05:52:01.265  5547  5593 I jxcore-log: 2016-09-30 09:52:01 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:01.265  5547  5593 I jxcore-log: 
,09-30 05:52:01.322  5547  5593 I jxcore-log: # teardown
09-30 05:52:01.322  5547  5593 I jxcore-log: 
,09-30 05:52:01.419  5547  5593 I jxcore-log: # setup
09-30 05:52:01.419  5547  5593 I jxcore-log: 
,09-30 05:52:03.220  5547  5593 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 05:52:03.220  5547  5593 I jxcore-log: 
,09-30 05:52:04.133  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:04.133  5547  5593 I jxcore-log: 
,09-30 05:52:04.142  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'listening 48002'
09-30 05:52:04.142  5547  5593 I jxcore-log: 
,09-30 05:52:04.149  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:04.149  5547  5593 I jxcore-log: 
,09-30 05:52:04.150  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:04.150  5547  5593 I jxcore-log: 
09-30 05:52:04.151  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'new mux'
09-30 05:52:04.151  5547  5593 I jxcore-log: 
,09-30 05:52:04.156  5547  5593 I jxcore-log: ok 31 we should not have gotten an error
09-30 05:52:04.156  5547  5593 I jxcore-log: 
,09-30 05:52:04.159  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:04.159  5547  5593 I jxcore-log: 
,09-30 05:52:04.162  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:04.162  5547  5593 I jxcore-log: 
,09-30 05:52:04.168  5547  5593 I jxcore-log: ok 32 Buffers are identical
09-30 05:52:04.168  5547  5593 I jxcore-log: 
,09-30 05:52:04.169  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:04.169  5547  5593 I jxcore-log: 
09-30 05:52:04.170  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'mux close'
09-30 05:52:04.170  5547  5593 I jxcore-log: 
,09-30 05:52:04.179  5547  5593 I jxcore-log: 2016-09-30 09:52:04 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:04.179  5547  5593 I jxcore-log: 
,09-30 05:52:04.179  5547  5593 I jxcore-log: ok 33 server should be fine
09-30 05:52:04.179  5547  5593 I jxcore-log: 
09-30 05:52:04.180  5547  5593 I jxcore-log: ok 34 server should be open
09-30 05:52:04.180  5547  5593 I jxcore-log: 
09-30 05:52:04.180  5547  5593 I jxcore-log: ok 35 incoming has been removed
09-30 05:52:04.180  5547  5593 I jxcore-log: 
,09-30 05:52:04.180  5547  5593 I jxcore-log: ok 36 The mux object should be closed
09-30 05:52:04.180  5547  5593 I jxcore-log: 
,09-30 05:52:04.182  5547  5593 I jxcore-log: ok 37 The mux stream should be closed
09-30 05:52:04.182  5547  5593 I jxcore-log: 
,09-30 05:52:04.199  5547  5593 I jxcore-log: # teardown
09-30 05:52:04.199  5547  5593 I jxcore-log: 
,09-30 05:52:04.574  5547  5593 I jxcore-log: # setup
09-30 05:52:04.574  5547  5593 I jxcore-log: 
,09-30 05:52:05.366  5547  5593 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 05:52:05.366  5547  5593 I jxcore-log: 
,09-30 05:52:05.891  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'creating native server'
09-30 05:52:05.891  5547  5593 I jxcore-log: 
,09-30 05:52:05.898  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'listening 40446'
09-30 05:52:05.898  5547  5593 I jxcore-log: 
,09-30 05:52:05.906  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:52:05.906  5547  5593 I jxcore-log: 
,09-30 05:52:05.907  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:52:05.907  5547  5593 I jxcore-log: 
,09-30 05:52:05.909  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'new mux'
09-30 05:52:05.909  5547  5593 I jxcore-log: 
,09-30 05:52:05.916  5547  5593 I jxcore-log: ok 38 we should not have gotten an error
09-30 05:52:05.916  5547  5593 I jxcore-log: 
,09-30 05:52:05.919  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'new stream: '
09-30 05:52:05.919  5547  5593 I jxcore-log: 
,09-30 05:52:05.923  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:52:05.923  5547  5593 I jxcore-log: 
,09-30 05:52:05.930  5547  5593 I jxcore-log: ok 39 Buffers are identical
09-30 05:52:05.930  5547  5593 I jxcore-log: 
,09-30 05:52:05.939  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 05:52:05.939  5547  5593 I jxcore-log: 
,09-30 05:52:05.941  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'stream close:'
09-30 05:52:05.941  5547  5593 I jxcore-log: 
,09-30 05:52:05.952  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'mux close'
09-30 05:52:05.952  5547  5593 I jxcore-log: 
,09-30 05:52:05.956  5547  5593 I jxcore-log: 2016-09-30 09:52:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:52:05.956  5547  5593 I jxcore-log: 
,09-30 05:52:05.957  5547  5593 I jxcore-log: ok 40 server should be fine
09-30 05:52:05.957  5547  5593 I jxcore-log: 
,09-30 05:52:05.958  5547  5593 I jxcore-log: ok 41 server should be open
09-30 05:52:05.958  5547  5593 I jxcore-log: 
09-30 05:52:05.958  5547  5593 I jxcore-log: ok 42 incoming has been removed
09-30 05:52:05.958  5547  5593 I jxcore-log: 
,09-30 05:52:05.959  5547  5593 I jxcore-log: ok 43 The mux object should be closed
09-30 05:52:05.959  5547  5593 I jxcore-log: 
,09-30 05:52:05.959  5547  5593 I jxcore-log: ok 44 The mux stream should be closed
09-30 05:52:05.959  5547  5593 I jxcore-log: 
,09-30 05:52:05.967  5547  5593 I jxcore-log: # teardown
09-30 05:52:05.967  5547  5593 I jxcore-log: 
,09-30 05:52:06.158   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:06.604  5547  5593 I jxcore-log: # setup
09-30 05:52:06.604  5547  5593 I jxcore-log: 
,09-30 05:52:07.000  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 05:52:07.000  5547  5593 I jxcore-log: 
,09-30 05:52:07.159   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:07.547  5547  5593 I jxcore-log: 2016-09-30 09:52:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 05:52:07.547  5547  5593 I jxcore-log: 
,09-30 05:52:07.548  5547  5593 I jxcore-log: ok 45 Got right error
09-30 05:52:07.548  5547  5593 I jxcore-log: 
,09-30 05:52:07.552  5547  5593 I jxcore-log: # teardown
09-30 05:52:07.552  5547  5593 I jxcore-log: 
,09-30 05:52:08.160   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:08.339  5547  5593 I jxcore-log: # setup
09-30 05:52:08.339  5547  5593 I jxcore-log: 
,09-30 05:52:09.162   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:09.500  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 05:52:09.500  5547  5593 I jxcore-log: 
,09-30 05:52:09.551  5547  5593 I jxcore-log: 2016-09-30 09:52:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 05:52:09.551  5547  5593 I jxcore-log: 
,09-30 05:52:09.552  5547  5593 I jxcore-log: ok 46 Got socket hang up
09-30 05:52:09.552  5547  5593 I jxcore-log: 
09-30 05:52:09.553  5547  5593 I jxcore-log: # teardown
09-30 05:52:09.553  5547  5593 I jxcore-log: 
,09-30 05:52:10.163   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:10.175  5547  5593 I jxcore-log: # setup
09-30 05:52:10.175  5547  5593 I jxcore-log: 
,09-30 05:52:10.786  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 05:52:10.786  5547  5593 I jxcore-log: 
,09-30 05:52:11.163   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 05:52:12.447  5547  5593 I jxcore-log: 2016-09-30 09:52:12 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 05:52:12.447  5547  5593 I jxcore-log: 
,09-30 05:52:12.448  5547  5593 I jxcore-log: ok 47 Got 500 as expected
09-30 05:52:12.448  5547  5593 I jxcore-log: 
,09-30 05:52:12.451  5547  5593 I jxcore-log: # teardown
09-30 05:52:12.451  5547  5593 I jxcore-log: 
,09-30 05:52:12.478  5547  5593 I jxcore-log: # setup
09-30 05:52:12.478  5547  5593 I jxcore-log: 
,09-30 05:52:13.343  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 05:52:13.343  5547  5593 I jxcore-log: 
,09-30 05:52:14.761  5547  5593 I jxcore-log: ok 48 should be equal
09-30 05:52:14.761  5547  5593 I jxcore-log: 
,09-30 05:52:14.762  5547  5593 I jxcore-log: ok 49 revs are equal
09-30 05:52:14.762  5547  5593 I jxcore-log: 
09-30 05:52:14.765  5547  5593 I jxcore-log: # teardown
09-30 05:52:14.765  5547  5593 I jxcore-log: 
,09-30 05:52:15.417  5547  5593 I jxcore-log: # setup
09-30 05:52:15.417  5547  5593 I jxcore-log: 
,09-30 05:52:15.928  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 05:52:15.928  5547  5593 I jxcore-log: 
,09-30 05:52:16.164   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:16.963  5547  5593 I jxcore-log: ok 50 should be equal
09-30 05:52:16.963  5547  5593 I jxcore-log: 
,09-30 05:52:16.964  5547  5593 I jxcore-log: ok 51 revs are equal
09-30 05:52:16.964  5547  5593 I jxcore-log: 
09-30 05:52:16.967  5547  5593 I jxcore-log: # teardown
09-30 05:52:16.967  5547  5593 I jxcore-log: 
,09-30 05:52:17.166   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:17.207   930  2869 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:52:17.626  5547  5593 I jxcore-log: # setup
09-30 05:52:17.626  5547  5593 I jxcore-log: 
,09-30 05:52:18.167   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:18.370  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 05:52:18.370  5547  5593 I jxcore-log: 
,09-30 05:52:19.168   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:19.504  5547  5593 I jxcore-log: ok 52 should be equal
09-30 05:52:19.504  5547  5593 I jxcore-log: 
09-30 05:52:19.505  5547  5593 I jxcore-log: ok 53 revs are equal
09-30 05:52:19.505  5547  5593 I jxcore-log: 
,09-30 05:52:19.604  5547  5593 I jxcore-log: ok 54 should be equal
09-30 05:52:19.604  5547  5593 I jxcore-log: 
,09-30 05:52:19.605  5547  5593 I jxcore-log: ok 55 revs are equal
09-30 05:52:19.605  5547  5593 I jxcore-log: 
,09-30 05:52:19.704  5547  5593 I jxcore-log: ok 56 should be equal
09-30 05:52:19.704  5547  5593 I jxcore-log: 
,09-30 05:52:19.704  5547  5593 I jxcore-log: ok 57 revs are equal
09-30 05:52:19.704  5547  5593 I jxcore-log: 
,09-30 05:52:19.708  5547  5593 I jxcore-log: # teardown
09-30 05:52:19.708  5547  5593 I jxcore-log: 
,09-30 05:52:20.143  5547  5593 I jxcore-log: # setup
09-30 05:52:20.143  5547  5593 I jxcore-log: 
,09-30 05:52:20.169   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:20.413  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 05:52:20.413  5547  5593 I jxcore-log: 
,09-30 05:52:20.945  5547  5593 I jxcore-log: 2016-09-30 09:52:20 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 05:52:20.945  5547  5593 I jxcore-log: 
,09-30 05:52:20.945  5547  5593 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 05:52:20.945  5547  5593 I jxcore-log: 
09-30 05:52:20.947  5547  5593 I jxcore-log: # teardown
09-30 05:52:20.947  5547  5593 I jxcore-log: 
,09-30 05:52:21.105  5547  5593 I jxcore-log: # setup
09-30 05:52:21.105  5547  5593 I jxcore-log: 
,09-30 05:52:21.150  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 05:52:21.150  5547  5593 I jxcore-log: 
,09-30 05:52:21.169   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 05:52:21.224  5547  5593 I jxcore-log: ok 59 confirm stop caused failure
09-30 05:52:21.224  5547  5593 I jxcore-log: 
,09-30 05:52:21.230  5547  5593 I jxcore-log: # teardown
09-30 05:52:21.230  5547  5593 I jxcore-log: 
,09-30 05:52:21.270  5547  5593 I jxcore-log: # setup
09-30 05:52:21.270  5547  5593 I jxcore-log: 
,09-30 05:52:21.295  5547  5593 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 05:52:21.295  5547  5593 I jxcore-log: 
,09-30 05:52:21.569  5547  5593 I jxcore-log: 2016-09-30 09:52:21 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 05:52:21.569  5547  5593 I jxcore-log: 
,09-30 05:52:21.569  5547  5593 I jxcore-log: ok 60 stop caused us to fail
09-30 05:52:21.569  5547  5593 I jxcore-log: 
09-30 05:52:21.570  5547  5593 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 05:52:21.570  5547  5593 I jxcore-log: 
,09-30 05:52:21.572  5547  5593 I jxcore-log: # teardown
09-30 05:52:21.572  5547  5593 I jxcore-log: 
,09-30 05:52:21.656  5547  5593 I jxcore-log: # setup
09-30 05:52:21.656  5547  5593 I jxcore-log: 
,09-30 05:52:21.709  5547  5593 I jxcore-log: # #update - fail if stop is called
09-30 05:52:21.709  5547  5593 I jxcore-log: 
,09-30 05:52:21.785  5547  5593 I jxcore-log: ok 62 failed due to stop
09-30 05:52:21.785  5547  5593 I jxcore-log: 
,09-30 05:52:21.785  5547  5593 I jxcore-log: ok 63 failed due to stop
09-30 05:52:21.785  5547  5593 I jxcore-log: 
,09-30 05:52:21.792  5547  5593 I jxcore-log: # teardown
09-30 05:52:21.792  5547  5593 I jxcore-log: 
,09-30 05:52:21.844  5547  5593 I jxcore-log: # setup
09-30 05:52:21.844  5547  5593 I jxcore-log: 
,09-30 05:52:21.871  5547  5593 I jxcore-log: # #update - set seq for first time
09-30 05:52:21.871  5547  5593 I jxcore-log: 
,09-30 05:52:22.249  5547  5593 I jxcore-log: ok 64 should be equal
09-30 05:52:22.249  5547  5593 I jxcore-log: 
,09-30 05:52:22.258  5547  5593 I jxcore-log: # teardown
09-30 05:52:22.258  5547  5593 I jxcore-log: 
,09-30 05:52:22.353  5547  5593 I jxcore-log: # setup
09-30 05:52:22.353  5547  5593 I jxcore-log: 
,09-30 05:52:22.386  5547  5593 I jxcore-log: # #update - Fail on bad seq value
09-30 05:52:22.386  5547  5593 I jxcore-log: 
,09-30 05:52:22.695  5547  5593 I jxcore-log: 2016-09-30 09:52:22 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 05:52:22.695  5547  5593 I jxcore-log: 
,09-30 05:52:22.696  5547  5593 I jxcore-log: ok 65 Expected bad seq error
09-30 05:52:22.696  5547  5593 I jxcore-log: 
,09-30 05:52:22.699  5547  5593 I jxcore-log: # teardown
09-30 05:52:22.699  5547  5593 I jxcore-log: 
,09-30 05:52:22.876  5547  5593 I jxcore-log: # setup
09-30 05:52:22.876  5547  5593 I jxcore-log: 
,09-30 05:52:22.920  5547  5593 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 05:52:22.920  5547  5593 I jxcore-log: 
,09-30 05:52:23.239  5547  5593 I jxcore-log: ok 66 Different promises
09-30 05:52:23.239  5547  5593 I jxcore-log: 
,09-30 05:52:23.240  5547  5593 I jxcore-log: ok 67 Timer was cancelled
09-30 05:52:23.240  5547  5593 I jxcore-log: 
,09-30 05:52:23.360  5547  5593 I jxcore-log: ok 68 should be equal
09-30 05:52:23.360  5547  5593 I jxcore-log: 
,09-30 05:52:23.369  5547  5593 I jxcore-log: # teardown
09-30 05:52:23.369  5547  5593 I jxcore-log: 
,09-30 05:52:23.453  5547  5593 I jxcore-log: # setup
09-30 05:52:23.453  5547  5593 I jxcore-log: 
,09-30 05:52:23.493  5547  5593 I jxcore-log: # #update - do we wait for blocked update
09-30 05:52:23.493  5547  5593 I jxcore-log: 
,09-30 05:52:23.599  5547  5593 I jxcore-log: ok 69 One go and one blocked
09-30 05:52:23.599  5547  5593 I jxcore-log: 
,09-30 05:52:23.599  5547  5593 I jxcore-log: ok 70 All blocked
09-30 05:52:23.599  5547  5593 I jxcore-log: 
09-30 05:52:23.599  5547  5593 I jxcore-log: ok 71 Still blocked
09-30 05:52:23.599  5547  5593 I jxcore-log: 
,09-30 05:52:23.870  5547  5593 I jxcore-log: ok 72 should be equal
09-30 05:52:23.870  5547  5593 I jxcore-log: 
,09-30 05:52:23.873  5547  5593 I jxcore-log: # teardown
09-30 05:52:23.873  5547  5593 I jxcore-log: 
,09-30 05:52:23.979  5547  5593 I jxcore-log: # setup
09-30 05:52:23.979  5547  5593 I jxcore-log: 
,09-30 05:52:24.045  5547  5593 I jxcore-log: # #update - test that we wait long enough
09-30 05:52:24.045  5547  5593 I jxcore-log: 
,09-30 05:52:25.207  5547  5593 I jxcore-log: ok 73 We waited long enough
09-30 05:52:25.207  5547  5593 I jxcore-log: 
,09-30 05:52:25.268  5547  5593 I jxcore-log: ok 74 should be equal
09-30 05:52:25.268  5547  5593 I jxcore-log: 
,09-30 05:52:25.272  5547  5593 I jxcore-log: # teardown
09-30 05:52:25.272  5547  5593 I jxcore-log: 
,09-30 05:52:25.411  5547  5593 I jxcore-log: # setup
09-30 05:52:25.411  5547  5593 I jxcore-log: 
,09-30 05:52:25.455  5547  5593 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-30 05:52:25.455  5547  5593 I jxcore-log: 
,09-30 05:52:25.789  5547  5593 I jxcore-log: ok 75 Should have gotten same timer promise
09-30 05:52:25.789  5547  5593 I jxcore-log: 
,09-30 05:52:25.790  5547  5593 I jxcore-log: ok 76 Still same timer promise
09-30 05:52:25.790  5547  5593 I jxcore-log: 
,09-30 05:52:26.698  5547  5593 I jxcore-log: ok 77 We waited long enough
09-30 05:52:26.698  5547  5593 I jxcore-log: 
,09-30 05:52:26.743  5547  5593 I jxcore-log: ok 78 should be equal
09-30 05:52:26.743  5547  5593 I jxcore-log: 
,09-30 05:52:26.746  5547  5593 I jxcore-log: # teardown
09-30 05:52:26.746  5547  5593 I jxcore-log: 
,09-30 05:52:27.289  5547  5593 I jxcore-log: # setup
09-30 05:52:27.289  5547  5593 I jxcore-log: 
,09-30 05:52:27.729  5547  5593 I jxcore-log: # Coordinated seq test
09-30 05:52:27.729  5547  5593 I jxcore-log: 
,09-30 05:52:27.731  5547  5593 I jxcore-log: 2016-09-30 09:52:27 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-30 05:52:27.731  5547  5593 I jxcore-log: 
,09-30 05:52:27.776  5547  5593 I jxcore-log: # teardown
09-30 05:52:27.776  5547  5593 I jxcore-log: 
,09-30 05:52:27.843  5547  5593 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-30 05:52:27.844  5547  5593 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:52:27.844  5547  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:52:27.844  5547  5593 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:52:27.860  5547  5593 I jxcore-log: # setup
09-30 05:52:27.860  5547  5593 I jxcore-log: 
,09-30 05:52:27.890  5547  5593 I jxcore-log: # closeAll can close even when connections open
09-30 05:52:27.890  5547  5593 I jxcore-log: 
,09-30 05:52:28.040  5547  5593 I jxcore-log: ok 79 not possible to connect to the server anymore
09-30 05:52:28.040  5547  5593 I jxcore-log: 
,09-30 05:52:28.050  5547  5593 I jxcore-log: # teardown
09-30 05:52:28.050  5547  5593 I jxcore-log: 
,09-30 05:52:28.086  5547  5593 I jxcore-log: # setup
09-30 05:52:28.086  5547  5593 I jxcore-log: 
,09-30 05:52:28.130  5547  5593 I jxcore-log: # closeAll with promise
09-30 05:52:28.130  5547  5593 I jxcore-log: 
,09-30 05:52:28.285  5547  5593 I jxcore-log: ok 80 not possible to connect to the server anymore
09-30 05:52:28.285  5547  5593 I jxcore-log: 
,09-30 05:52:28.290  5547  5593 I jxcore-log: # teardown
09-30 05:52:28.290  5547  5593 I jxcore-log: 
,09-30 05:52:28.326  5547  5593 I jxcore-log: # setup
09-30 05:52:28.326  5547  5593 I jxcore-log: 
,09-30 05:52:28.370  5547  5593 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-30 05:52:28.370  5547  5593 I jxcore-log: 
,09-30 05:52:28.501  5547  5593 I jxcore-log: ok 81 Got the right error
09-30 05:52:28.501  5547  5593 I jxcore-log: 
,09-30 05:52:28.508  5547  5593 I jxcore-log: # teardown
09-30 05:52:28.508  5547  5593 I jxcore-log: 
,09-30 05:52:28.547  5547  5593 I jxcore-log: # setup
09-30 05:52:28.547  5547  5593 I jxcore-log: 
,09-30 05:52:28.579  5547  5593 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-30 05:52:28.579  5547  5593 I jxcore-log: 
,09-30 05:52:28.751  5547  5593 I jxcore-log: # teardown
09-30 05:52:28.751  5547  5593 I jxcore-log: 
,09-30 05:52:28.779  5547  5593 I jxcore-log: # setup
09-30 05:52:28.779  5547  5593 I jxcore-log: 
,09-30 05:52:28.824  5547  5593 I jxcore-log: # onPeerLost calls jxcore
09-30 05:52:28.824  5547  5593 I jxcore-log: 
,09-30 05:52:28.853  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:52:28.853  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fcd86 added. We now have 3 listener(s)
,09-30 05:52:28.856  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:52:28.856  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:52:28.856  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:52:28.857  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:52:28.857  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d8647 added. We now have 4 listener(s)
09-30 05:52:28.857  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:52:28.858  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:52:28.864  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:52:28.871  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:52:28.875  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:52:28.876  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:52:28.876  5547  5593 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-30 05:52:28.876  5547  5593 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-30 05:52:28.880  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:52:28.883  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:52:30.879  5547  5593 I jxcore-log: onPeerLost
09-30 05:52:30.879  5547  5593 I jxcore-log: 
,09-30 05:52:30.882  5547  5593 I jxcore-log: 2016-09-30 09:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:52:30.882  5547  5593 I jxcore-log: 
,09-30 05:52:30.889  5547  5593 I jxcore-log: # teardown
09-30 05:52:30.889  5547  5593 I jxcore-log: 
,09-30 05:52:30.894  5547  5593 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-30 05:52:30.894  5547  5593 I jxcore-log: 
,09-30 05:52:30.895  5547  5593 I jxcore-log: ok 83 check if peerAvailable is false
09-30 05:52:30.895  5547  5593 I jxcore-log: 
,09-30 05:52:30.967  5547  5593 I jxcore-log: 2016-09-30 09:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 05:52:30.967  5547  5593 I jxcore-log: 
,09-30 05:52:30.970  5547  5593 I jxcore-log: 2016-09-30 09:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 05:52:30.970  5547  5593 I jxcore-log: 
,09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:52:30.980  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:52:30.984  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:52:30.986  5547  5593 I jxcore-log: 2016-09-30 09:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 05:52:30.986  5547  5593 I jxcore-log: 
,09-30 05:52:30.988  5547  5593 I jxcore-log: 2016-09-30 09:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 05:52:30.988  5547  5593 I jxcore-log: 
09-30 05:52:30.991  5547  5593 I jxcore-log: # setup
09-30 05:52:30.991  5547  5593 I jxcore-log: 
09-30 05:52:30.993  5547  5593 I jxcore-log: 2016-09-30 09:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:52:30.993  5547  5593 I jxcore-log: 
,09-30 05:52:31.051  5547  5593 I jxcore-log: # onPeerDiscovered calls jxcore
09-30 05:52:31.051  5547  5593 I jxcore-log: 
,09-30 05:52:31.090  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:52:31.090  5547  5593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5cdf9d added. We now have 4 listener(s)
,09-30 05:52:31.092  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 05:52:31.093  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:52:31.093  5547  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:52:31.093  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:52:31.093  5547  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b3c12 added. We now have 5 listener(s)
,09-30 05:52:31.093  5547  5593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:52:31.095  5547  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:52:31.100  5547  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:52:31.108  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:52:31.112  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:52:31.113  5547  5593 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:52:31.113  5547  5593 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-30 05:52:31.118  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:52:31.122  5547  5547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:52:31.170   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:32.171   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:33.115  5547  5593 I jxcore-log: onPeerDiscovered
09-30 05:52:33.115  5547  5593 I jxcore-log: 
,09-30 05:52:33.117  5547  5593 I jxcore-log: 2016-09-30 09:52:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:52:33.117  5547  5593 I jxcore-log: 
,09-30 05:52:33.121  5547  5593 I jxcore-log: # teardown
09-30 05:52:33.121  5547  5593 I jxcore-log: 
,09-30 05:52:33.126  5547  5593 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-30 05:52:33.126  5547  5593 I jxcore-log: 
09-30 05:52:33.127  5547  5593 I jxcore-log: ok 85 check if peerAvailable is true
09-30 05:52:33.127  5547  5593 I jxcore-log: 
,09-30 05:52:33.172   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:33.209  5547  5593 I jxcore-log: 2016-09-30 09:52:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 05:52:33.209  5547  5593 I jxcore-log: 
,09-30 05:52:33.212  5547  5593 I jxcore-log: 2016-09-30 09:52:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 05:52:33.212  5547  5593 I jxcore-log: 
,09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:52:33.219  5547  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:52:33.222  5547  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:52:33.223  5547  5593 I jxcore-log: 2016-09-30 09:52:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 05:52:33.223  5547  5593 I jxcore-log: 
,09-30 05:52:33.225  5547  5593 I jxcore-log: 2016-09-30 09:52:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 05:52:33.225  5547  5593 I jxcore-log: 
,09-30 05:52:33.228  5547  5593 I jxcore-log: # setup
09-30 05:52:33.228  5547  5593 I jxcore-log: 
,09-30 05:52:33.234  5547  5593 I jxcore-log: 2016-09-30 09:52:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:52:33.234  5547  5593 I jxcore-log: 
,09-30 05:52:33.296  5547  5593 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-30 05:52:33.296  5547  5593 I jxcore-log: 
,09-30 05:52:33.642  5547  5593 I jxcore-log: # teardown
09-30 05:52:33.642  5547  5593 I jxcore-log: 
,09-30 05:52:33.749  5547  5593 I jxcore-log: # setup
09-30 05:52:33.749  5547  5593 I jxcore-log: 
,09-30 05:52:33.786  5547  5593 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-30 05:52:33.786  5547  5593 I jxcore-log: 
,09-30 05:52:34.104  5547  5593 I jxcore-log: # teardown
09-30 05:52:34.104  5547  5593 I jxcore-log: 
,09-30 05:52:34.155  5547  5593 I jxcore-log: # setup
09-30 05:52:34.155  5547  5593 I jxcore-log: 
,09-30 05:52:34.173   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:34.188  5547  5593 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-30 05:52:34.188  5547  5593 I jxcore-log: 
,09-30 05:52:35.174   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:52:35.491  5547  5593 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-30 05:52:35.491  5547  5593 I jxcore-log: 
,09-30 05:52:35.500  5547  5593 I jxcore-log: # teardown
09-30 05:52:35.500  5547  5593 I jxcore-log: 
,09-30 05:52:35.583  5547  5593 I jxcore-log: # setup
09-30 05:52:35.583  5547  5593 I jxcore-log: 
,09-30 05:52:35.616  5547  5593 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-30 05:52:35.616  5547  5593 I jxcore-log: 
,09-30 05:52:36.175   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 05:52:36.215  5547  5593 I jxcore-log: # teardown
09-30 05:52:36.215  5547  5593 I jxcore-log: 
,09-30 05:52:36.248  5547  5593 I jxcore-log: # setup
09-30 05:52:36.248  5547  5593 I jxcore-log: 
,09-30 05:52:36.270  5547  5593 I jxcore-log: # test defaultDirectory
09-30 05:52:36.270  5547  5593 I jxcore-log: 
,09-30 05:52:36.314  5547  5593 I jxcore-log: ok 87 should be equal
09-30 05:52:36.314  5547  5593 I jxcore-log: 
,09-30 05:52:36.317  5547  5593 I jxcore-log: ok 88 should be equal
09-30 05:52:36.317  5547  5593 I jxcore-log: 
,09-30 05:52:36.321  5547  5593 I jxcore-log: ok 89 should be equal
09-30 05:52:36.321  5547  5593 I jxcore-log: 
,09-30 05:52:36.325  5547  5593 I jxcore-log: # teardown
09-30 05:52:36.325  5547  5593 I jxcore-log: 
,09-30 05:52:36.369  5547  5593 I jxcore-log: # setup
09-30 05:52:36.369  5547  5593 I jxcore-log: 
,09-30 05:52:36.397  5547  5593 I jxcore-log: # test defaultAdapter
09-30 05:52:36.397  5547  5593 I jxcore-log: 
,09-30 05:52:36.433  5547  5593 I jxcore-log: ok 90 should be equal
09-30 05:52:36.433  5547  5593 I jxcore-log: 
,09-30 05:52:36.433  5547  5593 I jxcore-log: ok 91 should be equal
09-30 05:52:36.433  5547  5593 I jxcore-log: 
,09-30 05:52:36.436  5547  5593 I jxcore-log: ok 92 should be equal
09-30 05:52:36.436  5547  5593 I jxcore-log: 
09-30 05:52:36.437  5547  5593 I jxcore-log: ok 93 should be equal
09-30 05:52:36.437  5547  5593 I jxcore-log: 
,09-30 05:52:36.439  5547  5593 I jxcore-log: ok 94 should be equal
09-30 05:52:36.439  5547  5593 I jxcore-log: 
,09-30 05:52:36.440  5547  5593 I jxcore-log: ok 95 should be equal
09-30 05:52:36.440  5547  5593 I jxcore-log: 
,09-30 05:52:36.537  5547  5593 I jxcore-log: ok 96 should be equal
09-30 05:52:36.537  5547  5593 I jxcore-log: 
09-30 05:52:36.537  5547  5593 I jxcore-log: ok 97 should be equal
09-30 05:52:36.537  5547  5593 I jxcore-log: 
,09-30 05:52:36.538  5547  5593 I jxcore-log: # teardown
09-30 05:52:36.538  5547  5593 I jxcore-log: 
,09-30 05:52:36.575  5547  5593 I jxcore-log: # setup
09-30 05:52:36.575  5547  5593 I jxcore-log: 
,09-30 05:52:36.619  5547  5593 I jxcore-log: # enqueue and run in order
09-30 05:52:36.619  5547  5593 I jxcore-log: 
,09-30 05:52:36.757  5547  5593 I jxcore-log: ok 98 firstPromise setTimeout
09-30 05:52:36.757  5547  5593 I jxcore-log: 
,09-30 05:52:36.759  5547  5593 I jxcore-log: ok 99 firstPromise result
09-30 05:52:36.759  5547  5593 I jxcore-log: 
09-30 05:52:36.759  5547  5593 I jxcore-log: ok 100 firstPromise testValue
09-30 05:52:36.759  5547  5593 I jxcore-log: 
,09-30 05:52:36.863  5547  5593 I jxcore-log: ok 101 secondPromise setTimeout
09-30 05:52:36.863  5547  5593 I jxcore-log: 
,09-30 05:52:36.864  5547  5593 I jxcore-log: ok 102 secondPromise result
09-30 05:52:36.864  5547  5593 I jxcore-log: 
09-30 05:52:36.865  5547  5593 I jxcore-log: ok 103 secondPromise testValue
09-30 05:52:36.865  5547  5593 I jxcore-log: 
09-30 05:52:36.866  5547  5593 I jxcore-log: ok 104 thirdPromise in promise
09-30 05:52:36.866  5547  5593 I jxcore-log: 
,09-30 05:52:36.867  5547  5593 I jxcore-log: ok 105 thirdPromise result
09-30 05:52:36.867  5547  5593 I jxcore-log: 
09-30 05:52:36.868  5547  5593 I jxcore-log: ok 106 thirdPromise testValue
09-30 05:52:36.868  5547  5593 I jxcore-log: 
,09-30 05:52:36.881  5547  5593 I jxcore-log: # teardown
09-30 05:52:36.881  5547  5593 I jxcore-log: 
,09-30 05:52:36.942  5547  5593 I jxcore-log: # setup
09-30 05:52:36.942  5547  5593 I jxcore-log: 
,09-30 05:52:37.026  5547  5593 I jxcore-log: # enqueueAtTop and run backwards
09-30 05:52:37.026  5547  5593 I jxcore-log: 
,09-30 05:52:37.087  5547  5593 I jxcore-log: ok 107 thirdPromise - first to run
09-30 05:52:37.087  5547  5593 I jxcore-log: 
,09-30 05:52:37.089  5547  5593 I jxcore-log: ok 108 thirdPromise - in resolve
09-30 05:52:37.089  5547  5593 I jxcore-log: 
,09-30 05:52:37.092  5547  5593 I jxcore-log: ok 109 secondPromise - second to run
09-30 05:52:37.092  5547  5593 I jxcore-log: 
,09-30 05:52:37.093  5547  5593 I jxcore-log: ok 110 secondPromise - in catch
09-30 05:52:37.093  5547  5593 I jxcore-log: 
09-30 05:52:37.093  5547  5593 I jxcore-log: ok 111 firstPromise - third to run
09-30 05:52:37.093  5547  5593 I jxcore-log: 
,09-30 05:52:37.094  5547  5593 I jxcore-log: ok 112 firstPromise - in then
09-30 05:52:37.094  5547  5593 I jxcore-log: 
,09-30 05:52:37.095  5547  5593 I jxcore-log: ok 113 testing promises
09-30 05:52:37.095  5547  5593 I jxcore-log: 
,09-30 05:52:37.098  5547  5593 I jxcore-log: # teardown
09-30 05:52:37.098  5547  5593 I jxcore-log: 
,09-30 05:52:37.161  5547  5593 I jxcore-log: # setup
09-30 05:52:37.161  5547  5593 I jxcore-log: 
,09-30 05:52:37.210   930  2869 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:52:37.223  5547  5593 I jxcore-log: # mix enqueue and enqueueAtTop
09-30 05:52:37.223  5547  5593 I jxcore-log: 
,09-30 05:52:37.305  5547  5593 I jxcore-log: ok 114 fourth
09-30 05:52:37.305  5547  5593 I jxcore-log: 
,09-30 05:52:37.306  5547  5593 I jxcore-log: ok 115 fourth
09-30 05:52:37.306  5547  5593 I jxcore-log: 
09-30 05:52:37.306  5547  5593 I jxcore-log: ok 116 second
09-30 05:52:37.306  5547  5593 I jxcore-log: 
09-30 05:52:37.307  5547  5593 I jxcore-log: ok 117 secondPromise - in then
09-30 05:52:37.307  5547  5593 I jxcore-log: 
,09-30 05:52:37.410  5547  5593 I jxcore-log: ok 118 first
09-30 05:52:37.410  5547  5593 I jxcore-log: 
,09-30 05:52:37.412  5547  5593 I jxcore-log: ok 119 firstPromise - in catch
09-30 05:52:37.412  5547  5593 I jxcore-log: 
,09-30 05:52:37.415  5547  5593 I jxcore-log: ok 120 third
09-30 05:52:37.415  5547  5593 I jxcore-log: 
,09-30 05:52:37.420  5547  5593 I jxcore-log: ok 121 thirdPromise - in then
09-30 05:52:37.420  5547  5593 I jxcore-log: 
,09-30 05:52:37.421  5547  5593 I jxcore-log: ok 122 testingPromises
09-30 05:52:37.421  5547  5593 I jxcore-log: 
09-30 05:52:37.425  5547  5593 I jxcore-log: # teardown
09-30 05:52:37.425  5547  5593 I jxcore-log: 
,09-30 05:52:37.470  5547  5593 I jxcore-log: # setup
09-30 05:52:37.470  5547  5593 I jxcore-log: 
,09-30 05:52:37.521  5547  5593 I jxcore-log: # queues handled independently
09-30 05:52:37.521  5547  5593 I jxcore-log: 
,09-30 05:52:37.646  5547  5593 I jxcore-log: ok 123 all short operations completed before the long resolves
09-30 05:52:37.646  5547  5593 I jxcore-log: 
,09-30 05:52:37.657  5547  5593 I jxcore-log: # teardown
09-30 05:52:37.657  5547  5593 I jxcore-log: 
,09-30 05:52:37.707  5547  5593 I jxcore-log: # setup
09-30 05:52:37.707  5547  5593 I jxcore-log: 
,09-30 05:52:37.749  5547  5593 I jxcore-log: # basic
09-30 05:52:37.749  5547  5593 I jxcore-log: 
,09-30 05:52:37.798  5547  5593 I jxcore-log: ok 124 sane
09-30 05:52:37.798  5547  5593 I jxcore-log: 
,09-30 05:52:37.811  5547  5593 I jxcore-log: # teardown
09-30 05:52:37.811  5547  5593 I jxcore-log: 
,09-30 05:52:37.842  5547  5593 I jxcore-log: # setup
09-30 05:52:37.842  5547  5593 I jxcore-log: 
,09-30 05:52:37.960  5547  5593 I jxcore-log: # another
09-30 05:52:37.960  5547  5593 I jxcore-log: 
,09-30 05:52:38.008  5547  5593 I jxcore-log: ok 125 sane
09-30 05:52:38.008  5547  5593 I jxcore-log: 
,09-30 05:52:38.012  5547  5593 I jxcore-log: # teardown
09-30 05:52:38.012  5547  5593 I jxcore-log: 
,09-30 05:52:38.055  5547  5593 I jxcore-log: # setup
09-30 05:52:38.055  5547  5593 I jxcore-log: 
,09-30 05:52:38.092  5547  5593 I jxcore-log: # can pass data in setup
09-30 05:52:38.092  5547  5593 I jxcore-log: 
,09-30 05:52:38.132  5547  5593 I jxcore-log: ok 126 test participant has uuid
09-30 05:52:38.132  5547  5593 I jxcore-log: 
,09-30 05:52:38.133  5547  5593 I jxcore-log: ok 127 participant data matches
09-30 05:52:38.133  5547  5593 I jxcore-log: 
,09-30 05:52:38.133  5547  5593 I jxcore-log: ok 128 test participant has uuid
09-30 05:52:38.133  5547  5593 I jxcore-log: 
09-30 05:52:38.134  5547  5593 I jxcore-log: ok 129 participant data matches
09-30 05:52:38.134  5547  5593 I jxcore-log: 
09-30 05:52:38.134  5547  5593 I jxcore-log: ok 130 test participant has uuid
09-30 05:52:38.134  5547  5593 I jxcore-log: 
,09-30 05:52:38.135  5547  5593 I jxcore-log: ok 131 participant data matches
09-30 05:52:38.135  5547  5593 I jxcore-log: 
,09-30 05:52:38.139  5547  5593 I jxcore-log: ok 132 own UUID is found from the participants list
09-30 05:52:38.139  5547  5593 I jxcore-log: 
,09-30 05:52:38.142  5547  5593 I jxcore-log: # teardown
09-30 05:52:38.142  5547  5593 I jxcore-log: 
,09-30 05:52:38.180  5547  5593 I jxcore-log: # setup
09-30 05:52:38.180  5547  5593 I jxcore-log: 
,09-30 05:52:38.220  5547  5593 I jxcore-log: # test thali manager spies
09-30 05:52:38.220  5547  5593 I jxcore-log: 
,09-30 05:52:38.458  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 05:52:38.458  5547  5593 I jxcore-log: 
,09-30 05:52:38.468  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 05:52:38.468  5547  5593 I jxcore-log: 
,09-30 05:52:38.473  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 05:52:38.473  5547  5593 I jxcore-log: 
,09-30 05:52:38.488  5547  5593 I jxcore-log: ok 133 expressPouchDB was called once
09-30 05:52:38.488  5547  5593 I jxcore-log: 
,09-30 05:52:38.489  5547  5593 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-30 05:52:38.489  5547  5593 I jxcore-log: 
09-30 05:52:38.490  5547  5593 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-30 05:52:38.490  5547  5593 I jxcore-log: 
,09-30 05:52:38.490  5547  5593 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-30 05:52:38.490  5547  5593 I jxcore-log: 
09-30 05:52:38.490  5547  5593 I jxcore-log: ok 137 PouchDB was called once
09-30 05:52:38.490  5547  5593 I jxcore-log: 
,09-30 05:52:38.490  5547  5593 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-30 05:52:38.490  5547  5593 I jxcore-log: 
09-30 05:52:38.491  5547  5593 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-30 05:52:38.491  5547  5593 I jxcore-log: 
09-30 05:52:38.491  5547  5593 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-30 05:52:38.491  5547  5593 I jxcore-log: 
09-30 05:52:38.491  5547  5593 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-30 05:52:38.491  5547  5593 I jxcore-log: 
,09-30 05:52:38.491  5547  5593 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-30 05:52:38.491  5547  5593 I jxcore-log: 
09-30 05:52:38.491  5547  5593 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-30 05:52:38.491  5547  5593 I jxcore-log: 
09-30 05:52:38.492  5547  5593 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-30 05:52:38.492  5547  5593 I jxcore-log: 
09-30 05:52:38.492  5547  5593 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-30 05:52:38.492  5547  5593 I jxcore-log: 
,09-30 05:52:38.492  5547  5593 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-30 05:52:38.492  5547  5593 I jxcore-log: 
09-30 05:52:38.492  5547  5593 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-30 05:52:38.492  5547  5593 I jxcore-log: 
09-30 05:52:38.492  5547  5593 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-30 05:52:38.492  5547  5593 I jxcore-log: 
09-30 05:52:38.494  5547  5593 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-30 05:52:38.494  5547  5593 I jxcore-log: 
,09-30 05:52:38.495  5547  5593 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-30 05:52:38.495  5547  5593 I jxcore-log: 
09-30 05:52:38.495  5547  5593 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-30 05:52:38.495  5547  5593 I jxcore-log: 
09-30 05:52:38.495  5547  5593 I jxcore-log: ok 152 Salti was called once
09-30 05:52:38.495  5547  5593 I jxcore-log: 
09-30 05:52:38.495  5547  5593 I jxcore-log: ok 153 Salti was called with 4 arguments
09-30 05:52:38.495  5547  5593 I jxcore-log: 
,09-30 05:52:38.495  5547  5593 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-30 05:52:38.495  5547  5593 I jxcore-log: 
09-30 05:52:38.496  5547  5593 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-30 05:52:38.496  5547  5593 I jxcore-log: 
09-30 05:52:38.496  5547  5593 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-30 05:52:38.496  5547  5593 I jxcore-log: 
,09-30 05:52:38.496  5547  5593 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-30 05:52:38.496  5547  5593 I jxcore-log: 
09-30 05:52:38.496  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 05:52:38.496  5547  5593 I jxcore-log: 
09-30 05:52:38.498  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 05:52:38.498  5547  5593 I jxcore-log: 
,09-30 05:52:38.502  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 05:52:38.502  5547  5593 I jxcore-log: 
,09-30 05:52:38.513  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start listening for advertisements'
09-30 05:52:38.513  5547  5593 I jxcore-log: 
,09-30 05:52:38.518  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start update advertising and listening'
09-30 05:52:38.518  5547  5593 I jxcore-log: 
,09-30 05:52:38.529  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliWifiInfrastructure: 'listening 40217'
09-30 05:52:38.529  5547  5593 I jxcore-log: 
,09-30 05:52:38.533  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 05:52:38.533  5547  5593 I jxcore-log: 
,09-30 05:52:38.549  5547  5593 I jxcore-log: ok 158 ThaliMobile.start was called once
09-30 05:52:38.549  5547  5593 I jxcore-log: 
,09-30 05:52:38.549  5547  5593 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-30 05:52:38.549  5547  5593 I jxcore-log: 
09-30 05:52:38.550  5547  5593 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 05:52:38.550  5547  5593 I jxcore-log: 
09-30 05:52:38.550  5547  5593 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 05:52:38.550  5547  5593 I jxcore-log: 
09-30 05:52:38.550  5547  5593 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-30 05:52:38.550  5547  5593 I jxcore-log: 
,09-30 05:52:38.551  5547  5593 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 05:52:38.551  5547  5593 I jxcore-log: 
,09-30 05:52:38.551  5547  5593 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 05:52:38.551  5547  5593 I jxcore-log: 
09-30 05:52:38.551  5547  5593 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 05:52:38.551  5547  5593 I jxcore-log: 
,09-30 05:52:38.551  5547  5593 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 05:52:38.551  5547  5593 I jxcore-log: 
,09-30 05:52:38.551  5547  5593 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 05:52:38.551  5547  5593 I jxcore-log: 
,09-30 05:52:38.552  5547  5593 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 05:52:38.552  5547  5593 I jxcore-log: 
,09-30 05:52:38.552  5547  5593 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 05:52:38.552  5547  5593 I jxcore-log: 
,09-30 05:52:38.552  5547  5593 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 05:52:38.552  5547  5593 I jxcore-log: 
09-30 05:52:38.552  5547  5593 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 05:52:38.552  5547  5593 I jxcore-log: 
,09-30 05:52:38.553  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 05:52:38.553  5547  5593 I jxcore-log: 
,09-30 05:52:38.554  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 05:52:38.554  5547  5593 I jxcore-log: 
09-30 05:52:38.556  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 05:52:38.556  5547  5593 I jxcore-log: 
,09-30 05:52:38.558  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 05:52:38.558  5547  5593 I jxcore-log: 
09-30 05:52:38.561  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 05:52:38.561  5547  5593 I jxcore-log: 
,09-30 05:52:38.563  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 05:52:38.563  5547  5593 I jxcore-log: 
09-30 05:52:38.565  5547  5593 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-30 05:52:38.565  5547  5593 I jxcore-log: 
,09-30 05:52:38.566  5547  5593 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-30 05:52:38.566  5547  5593 I jxcore-log: 
09-30 05:52:38.566  5547  5593 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-30 05:52:38.566  5547  5593 I jxcore-log: 
,09-30 05:52:38.566  5547  5593 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-30 05:52:38.566  5547  5593 I jxcore-log: 
09-30 05:52:38.566  5547  5593 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-30 05:52:38.566  5547  5593 I jxcore-log: 
09-30 05:52:38.566  5547  5593 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-30 05:52:38.566  5547  5593 I jxcore-log: 
09-30 05:52:38.566  5547  5593 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-30 05:52:38.566  5547  5593 I jxcore-log: 
,09-30 05:52:38.566  5547  5593 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-30 05:52:38.566  5547  5593 I jxcore-log: 
09-30 05:52:38.567  5547  5593 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-30 05:52:38.567  5547  5593 I jxcore-log: 
09-30 05:52:38.568  5547  5593 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-30 05:52:38.568  5547  5593 I jxcore-log: 
,09-30 05:52:38.575  5547  5593 I jxcore-log: # teardown
09-30 05:52:38.575  5547  5593 I jxcore-log: 
,09-30 05:52:38.595  5547  5593 I jxcore-log: # setup
09-30 05:52:38.595  5547  5593 I jxcore-log: 
,09-30 05:52:38.617  5547  5593 I jxcore-log: # test thali manager multiple starts and stops
09-30 05:52:38.617  5547  5593 I jxcore-log: 
,09-30 05:52:38.818  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 05:52:38.818  5547  5593 I jxcore-log: 
,09-30 05:52:38.828  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 05:52:38.828  5547  5593 I jxcore-log: 
,09-30 05:52:38.832  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 05:52:38.832  5547  5593 I jxcore-log: 
,09-30 05:52:38.867  5547  5593 I jxcore-log: ok 182 expressPouchDB was called once
09-30 05:52:38.867  5547  5593 I jxcore-log: 
,09-30 05:52:38.867  5547  5593 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-30 05:52:38.867  5547  5593 I jxcore-log: 
09-30 05:52:38.867  5547  5593 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-30 05:52:38.867  5547  5593 I jxcore-log: 
09-30 05:52:38.867  5547  5593 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-30 05:52:38.867  5547  5593 I jxcore-log: 
09-30 05:52:38.867  5547  5593 I jxcore-log: ok 186 PouchDB was called once
09-30 05:52:38.867  5547  5593 I jxcore-log: 
,09-30 05:52:38.868  5547  5593 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-30 05:52:38.868  5547  5593 I jxcore-log: 
09-30 05:52:38.868  5547  5593 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-30 05:52:38.868  5547  5593 I jxcore-log: 
09-30 05:52:38.868  5547  5593 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-30 05:52:38.868  5547  5593 I jxcore-log: 
09-30 05:52:38.868  5547  5593 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-30 05:52:38.868  5547  5593 I jxcore-log: 
,09-30 05:52:38.868  5547  5593 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-30 05:52:38.868  5547  5593 I jxcore-log: 
09-30 05:52:38.868  5547  5593 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-30 05:52:38.868  5547  5593 I jxcore-log: 
09-30 05:52:38.868  5547  5593 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-30 05:52:38.868  5547  5593 I jxcore-log: 
09-30 05:52:38.869  5547  5593 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-30 05:52:38.869  5547  5593 I jxcore-log: 
,09-30 05:52:38.869  5547  5593 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-30 05:52:38.869  5547  5593 I jxcore-log: 
09-30 05:52:38.869  5547  5593 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-30 05:52:38.869  5547  5593 I jxcore-log: 
09-30 05:52:38.869  5547  5593 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-30 05:52:38.869  5547  5593 I jxcore-log: 
09-30 05:52:38.869  5547  5593 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-30 05:52:38.869  5547  5593 I jxcore-log: 
,09-30 05:52:38.870  5547  5593 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-30 05:52:38.870  5547  5593 I jxcore-log: 
09-30 05:52:38.870  5547  5593 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-30 05:52:38.870  5547  5593 I jxcore-log: 
09-30 05:52:38.870  5547  5593 I jxcore-log: ok 201 Salti was called once
09-30 05:52:38.870  5547  5593 I jxcore-log: 
09-30 05:52:38.870  5547  5593 I jxcore-log: ok 202 Salti was called with 4 arguments
09-30 05:52:38.870  5547  5593 I jxcore-log: 
,09-30 05:52:38.870  5547  5593 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-30 05:52:38.870  5547  5593 I jxcore-log: 
09-30 05:52:38.870  5547  5593 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-30 05:52:38.870  5547  5593 I jxcore-log: 
09-30 05:52:38.870  5547  5593 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-30 05:52:38.870  5547  5593 I jxcore-log: 
09-30 05:52:38.870  5547  5593 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-30 05:52:38.870  5547  5593 I jxcore-log: 
,09-30 05:52:38.872  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 05:52:38.872  5547  5593 I jxcore-log: 
09-30 05:52:38.872  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 05:52:38.872  5547  5593 I jxcore-log: 
,09-30 05:52:38.876  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 05:52:38.876  5547  5593 I jxcore-log: 
,09-30 05:52:38.884  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start listening for advertisements'
09-30 05:52:38.884  5547  5593 I jxcore-log: 
,09-30 05:52:38.887  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start update advertising and listening'
09-30 05:52:38.887  5547  5593 I jxcore-log: 
,09-30 05:52:38.892  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliWifiInfrastructure: 'listening 46726'
09-30 05:52:38.892  5547  5593 I jxcore-log: 
,09-30 05:52:38.894  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 05:52:38.894  5547  5593 I jxcore-log: 
,09-30 05:52:38.907  5547  5593 I jxcore-log: ok 207 ThaliMobile.start was called once
09-30 05:52:38.907  5547  5593 I jxcore-log: 
,09-30 05:52:38.908  5547  5593 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-30 05:52:38.908  5547  5593 I jxcore-log: 
,09-30 05:52:38.908  5547  5593 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 05:52:38.908  5547  5593 I jxcore-log: 
09-30 05:52:38.908  5547  5593 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 05:52:38.908  5547  5593 I jxcore-log: 
,09-30 05:52:38.908  5547  5593 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-30 05:52:38.908  5547  5593 I jxcore-log: 
,09-30 05:52:38.908  5547  5593 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 05:52:38.908  5547  5593 I jxcore-log: 
09-30 05:52:38.908  5547  5593 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 05:52:38.908  5547  5593 I jxcore-log: 
09-30 05:52:38.908  5547  5593 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 05:52:38.908  5547  5593 I jxcore-log: 
09-30 05:52:38.909  5547  5593 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 05:52:38.909  5547  5593 I jxcore-log: 
,09-30 05:52:38.909  5547  5593 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 05:52:38.909  5547  5593 I jxcore-log: 
09-30 05:52:38.909  5547  5593 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 05:52:38.909  5547  5593 I jxcore-log: 
09-30 05:52:38.909  5547  5593 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 05:52:38.909  5547  5593 I jxcore-log: 
09-30 05:52:38.909  5547  5593 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 05:52:38.909  5547  5593 I jxcore-log: 
,09-30 05:52:38.909  5547  5593 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 05:52:38.909  5547  5593 I jxcore-log: 
09-30 05:52:38.910  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 05:52:38.910  5547  5593 I jxcore-log: 
09-30 05:52:38.912  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 05:52:38.912  5547  5593 I jxcore-log: 
09-30 05:52:38.916  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 05:52:38.916  5547  5593 I jxcore-log: 
,09-30 05:52:38.916  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 05:52:38.916  5547  5593 I jxcore-log: 
,09-30 05:52:38.920  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 05:52:38.920  5547  5593 I jxcore-log: 
,09-30 05:52:38.922  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 05:52:38.922  5547  5593 I jxcore-log: 
,09-30 05:52:38.924  5547  5593 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-30 05:52:38.924  5547  5593 I jxcore-log: 
,09-30 05:52:38.924  5547  5593 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-30 05:52:38.924  5547  5593 I jxcore-log: 
09-30 05:52:38.924  5547  5593 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-30 05:52:38.924  5547  5593 I jxcore-log: 
09-30 05:52:38.924  5547  5593 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-30 05:52:38.924  5547  5593 I jxcore-log: 
09-30 05:52:38.924  5547  5593 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-30 05:52:38.924  5547  5593 I jxcore-log: 
,09-30 05:52:38.925  5547  5593 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-30 05:52:38.925  5547  5593 I jxcore-log: 
09-30 05:52:38.925  5547  5593 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-30 05:52:38.925  5547  5593 I jxcore-log: 
09-30 05:52:38.925  5547  5593 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-30 05:52:38.925  5547  5593 I jxcore-log: 
,09-30 05:52:38.925  5547  5593 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-30 05:52:38.925  5547  5593 I jxcore-log: 
09-30 05:52:38.925  5547  5593 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-30 05:52:38.925  5547  5593 I jxcore-log: 
09-30 05:52:38.926  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 05:52:38.926  5547  5593 I jxcore-log: 
09-30 05:52:38.926  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 05:52:38.926  5547  5593 I jxcore-log: 
,09-30 05:52:38.928  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 05:52:38.928  5547  5593 I jxcore-log: 
,09-30 05:52:38.932  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start listening for advertisements'
09-30 05:52:38.932  5547  5593 I jxcore-log: 
,09-30 05:52:38.934  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start update advertising and listening'
09-30 05:52:38.934  5547  5593 I jxcore-log: 
,09-30 05:52:38.939  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliWifiInfrastructure: 'listening 46835'
09-30 05:52:38.939  5547  5593 I jxcore-log: 
,09-30 05:52:38.940  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 05:52:38.940  5547  5593 I jxcore-log: 
,09-30 05:52:38.942  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 05:52:38.942  5547  5593 I jxcore-log: 
,09-30 05:52:38.943  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 05:52:38.943  5547  5593 I jxcore-log: 
09-30 05:52:38.944  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 05:52:38.944  5547  5593 I jxcore-log: 
09-30 05:52:38.945  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 05:52:38.945  5547  5593 I jxcore-log: 
,09-30 05:52:38.950  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 05:52:38.950  5547  5593 I jxcore-log: 
,09-30 05:52:38.951  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 05:52:38.951  5547  5593 I jxcore-log: 
,09-30 05:52:38.954  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 05:52:38.954  5547  5593 I jxcore-log: 
,09-30 05:52:38.954  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 05:52:38.954  5547  5593 I jxcore-log: 
,09-30 05:52:38.958  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 05:52:38.958  5547  5593 I jxcore-log: 
,09-30 05:52:38.963  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start listening for advertisements'
09-30 05:52:38.963  5547  5593 I jxcore-log: 
,09-30 05:52:38.965  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start update advertising and listening'
09-30 05:52:38.965  5547  5593 I jxcore-log: 
,09-30 05:52:38.969  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliWifiInfrastructure: 'listening 40458'
09-30 05:52:38.969  5547  5593 I jxcore-log: 
,09-30 05:52:38.971  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 05:52:38.971  5547  5593 I jxcore-log: 
,09-30 05:52:38.973  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 05:52:38.973  5547  5593 I jxcore-log: 
,09-30 05:52:38.975  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 05:52:38.975  5547  5593 I jxcore-log: 
,09-30 05:52:38.976  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 05:52:38.976  5547  5593 I jxcore-log: 
,09-30 05:52:38.977  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 05:52:38.977  5547  5593 I jxcore-log: 
,09-30 05:52:38.982  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 05:52:38.982  5547  5593 I jxcore-log: 
,09-30 05:52:38.984  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 05:52:38.984  5547  5593 I jxcore-log: 
,09-30 05:52:38.985  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 05:52:38.985  5547  5593 I jxcore-log: 
,09-30 05:52:38.986  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 05:52:38.986  5547  5593 I jxcore-log: 
,09-30 05:52:38.989  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 05:52:38.989  5547  5593 I jxcore-log: 
,09-30 05:52:38.994  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start listening for advertisements'
09-30 05:52:38.994  5547  5593 I jxcore-log: 
,09-30 05:52:38.996  5547  5593 I jxcore-log: 2016-09-30 09:52:38 - DEBUG thaliManager: 'start update advertising and listening'
09-30 05:52:38.996  5547  5593 I jxcore-log: 
,09-30 05:52:39.000  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliWifiInfrastructure: 'listening 45916'
09-30 05:52:39.000  5547  5593 I jxcore-log: 
,09-30 05:52:39.001  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 05:52:39.001  5547  5593 I jxcore-log: 
,09-30 05:52:39.003  5547  5593 I jxcore-log: ok 231 ThaliMobile.start was called once
09-30 05:52:39.003  5547  5593 I jxcore-log: 
,09-30 05:52:39.003  5547  5593 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-30 05:52:39.003  5547  5593 I jxcore-log: 
,09-30 05:52:39.003  5547  5593 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 05:52:39.003  5547  5593 I jxcore-log: 
,09-30 05:52:39.003  5547  5593 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 05:52:39.003  5547  5593 I jxcore-log: 
09-30 05:52:39.003  5547  5593 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-30 05:52:39.003  5547  5593 I jxcore-log: 
,09-30 05:52:39.004  5547  5593 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 05:52:39.004  5547  5593 I jxcore-log: 
09-30 05:52:39.004  5547  5593 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 05:52:39.004  5547  5593 I jxcore-log: 
09-30 05:52:39.004  5547  5593 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 05:52:39.004  5547  5593 I jxcore-log: 
,09-30 05:52:39.004  5547  5593 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 05:52:39.004  5547  5593 I jxcore-log: 
09-30 05:52:39.004  5547  5593 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 05:52:39.004  5547  5593 I jxcore-log: 
,09-30 05:52:39.004  5547  5593 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 05:52:39.004  5547  5593 I jxcore-log: 
09-30 05:52:39.004  5547  5593 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 05:52:39.004  5547  5593 I jxcore-log: 
,09-30 05:52:39.005  5547  5593 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 05:52:39.005  5547  5593 I jxcore-log: 
09-30 05:52:39.005  5547  5593 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 05:52:39.005  5547  5593 I jxcore-log: 
09-30 05:52:39.005  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 05:52:39.005  5547  5593 I jxcore-log: 
,09-30 05:52:39.008  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 05:52:39.008  5547  5593 I jxcore-log: 
,09-30 05:52:39.011  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 05:52:39.011  5547  5593 I jxcore-log: 
,09-30 05:52:39.011  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 05:52:39.011  5547  5593 I jxcore-log: 
,09-30 05:52:39.015  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 05:52:39.015  5547  5593 I jxcore-log: 
,09-30 05:52:39.016  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 05:52:39.016  5547  5593 I jxcore-log: 
,09-30 05:52:39.026  5547  5593 I jxcore-log: # teardown
09-30 05:52:39.026  5547  5593 I jxcore-log: 
,09-30 05:52:39.089  5547  5593 I jxcore-log: # setup
09-30 05:52:39.089  5547  5593 I jxcore-log: 
,09-30 05:52:39.133  5547  5593 I jxcore-log: # test write
09-30 05:52:39.133  5547  5593 I jxcore-log: 
,09-30 05:52:39.296  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 05:52:39.296  5547  5593 I jxcore-log: 
,09-30 05:52:39.298  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 05:52:39.298  5547  5593 I jxcore-log: 
,09-30 05:52:39.299  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 05:52:39.299  5547  5593 I jxcore-log: 
,09-30 05:52:39.316  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 05:52:39.316  5547  5593 I jxcore-log: 
,09-30 05:52:39.318  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 05:52:39.318  5547  5593 I jxcore-log: 
,09-30 05:52:39.318  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 05:52:39.318  5547  5593 I jxcore-log: 
09-30 05:52:39.319  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'start listening for advertisements'
09-30 05:52:39.319  5547  5593 I jxcore-log: 
,09-30 05:52:39.326  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'start update advertising and listening'
09-30 05:52:39.326  5547  5593 I jxcore-log: 
,09-30 05:52:39.331  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliWifiInfrastructure: 'listening 48336'
09-30 05:52:39.331  5547  5593 I jxcore-log: 
,09-30 05:52:39.334  5547  5593 I jxcore-log: 2016-09-30 09:52:39 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 05:52:39.334  5547  5593 I jxcore-log: 
,09-30 05:52:40.432  5547  5593 I jxcore-log: 2016-09-30 09:52:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-30 05:52:40.432  5547  5593 I jxcore-log: 
,09-30 05:52:40.614  5547  5593 I jxcore-log: 2016-09-30 09:52:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-30 05:52:40.614  5547  5593 I jxcore-log: 
,09-30 05:52:40.893  5547  5593 I jxcore-log: 2016-09-30 09:52:40 - ERROR thaliSendNotificationBasedOnReplication: 'Got an error on the replication change listener - {"name":"AssertionError","actual":null,"expected":true,"operator":"==","message":"If beacons werepreviously updated then there has to be a refresh timer for them."}'
09-30 05:52:40.893  5547  5593 I jxcore-log: 
,09-30 05:52:40.908  5547  5593 I jxcore-log: 2016-09-30 09:52:40 - ERROR TestsProcess: 'uncaught promise rejection, error: 'AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.', stack: 'AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.
09-30 05:52:40.908  5547  5593 I jxcore-log:     at Changes.<anonymous> (/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9)
09-30 05:52:40.908  5547  5593 I jxcore-log:     at Changes.<anonymous> (/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:18)
09-30 05:52:40.908  5547  5593 I jxcore-log:     at Changes.emit (events.js:82:4)
09-30 05:52:40.908  5547  5593 I jxcore-log:     at tryCatchInChangeListener (/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb/lib/index.js:1411:10)
09-30 05:52:40.908  5547  5593 I jxcore-log:     at Object.Changes.opts.onChange (/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb/lib/index.js:1449:5)
09-30 05:52:40.908  5547  5593 I jxcore-log:     at Changes.db.changes.on.on.inprogress (/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb/lib/index.js:423:14)
09-30 05:52:40.908  5547  5593 I jxcore-log:     at 
,09-30 05:52:40.909  5547  5593 I jxcore-log: 2016-09-30 09:52:40 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 05:52:40.909  5547  5593 I jxcore-log: 
,09-30 05:52:40.910  5547  5593 E jxcore-log: 
09-30 05:52:40.911  5547  5593 E jxcore-log: main.js:542
09-30 05:52:40.912  5547  5593 E jxcore-log:   Error.captureStackTrace(e);
09-30 05:52:40.912  5547  5593 E jxcore-log: illegal access
,09-30 05:52:41.461  5932  5932 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 05:52:41.468  5932  5932 D AndroidRuntime: CheckJNI is OFF
,09-30 05:52:41.501  5932  5932 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 05:52:41.534  5932  5932 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 05:52:41.550  5932  5932 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 05:52:41.558   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-30 05:52:41.559   930   943 I ActivityManager: Killing 5547:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 05:52:41.653   930  3482 I WindowState: WIN DEATH: Window{66ac564 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-30 05:52:41.653   930  3112 D GraphicsStats: Buffer count: 2
09-30 05:52:41.654   930  2870 D WifiService: Client connection lost with reason: 4
,09-30 05:52:41.719   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-30 05:52:41.720   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-30 05:52:41.720   930   953 I art     : Starting a blocking GC Explicit
,09-30 05:52:41.721   930   943 E ActivityManager: Failure starting process com.test.thalitest
09-30 05:52:41.721   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 05:52:41.721   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:52:41.721   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:52:41.721   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 05:52:41.721   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 05:52:41.722   930   943 I ActivityManager:   Force finishing activity ActivityRecord{37a04b1 u0 com.test.thalitest/.MainActivity t2}
,09-30 05:52:41.733   930  3483 W ActivityManager: Spurious death for ProcessRecord{bdca233 0:com.test.thalitest/u0a77}, curProc for 5547: null
,09-30 05:52:41.737   930   948 W WindowManager: Attempted to add application window with unknown token Token{a481d96 ActivityRecord{37a04b1 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 05:52:41.737   930   948 W WindowManager: Token{a481d96 ActivityRecord{37a04b1 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{a481d96 ActivityRecord{37a04b1 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 05:52:41.737   930   948 W WindowManager: view not successfully added to wm, removing view
09-30 05:52:41.738   930   948 W WindowManager: Exception when adding starting window
09-30 05:52:41.738   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{82216fa V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 05:52:41.738   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 05:52:41.738   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 05:52:41.738   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 05:52:41.738   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 05:52:41.738   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 05:52:41.738   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:52:41.738   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:52:41.738   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 05:52:41.738   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 05:52:41.812   930   953 I art     : Explicit concurrent mark sweep GC freed 77223(5MB) AllocSpace objects, 38(1676KB) LOS objects, 33% free, 29MB/43MB, paused 1.735ms total 91.376ms
,09-30 05:52:41.833   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 05:52:41.836  5932  5932 I art     : System.exit called, status: 0
,09-30 05:52:41.836  5932  5932 I AndroidRuntime: VM exiting with result code 0.
,09-30 05:52:41.850   930   953 I ActivityManager: Start proc 5942:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-30 05:52:41.851   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 05:52:41.857   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-30 05:52:41.863  5822  5822 D BluetoothMapAppObserver: onReceive
09-30 05:52:41.863  5822  5822 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-30 05:52:41.869   930  2861 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-30 05:52:41.869  3580  3580 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-30 05:52:41.871  4024  4093 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 05:52:41.890  3580  5953 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 05:52:41.897  4845  4854 W art     : Suspending all threads took: 7.037ms
,09-30 05:52:41.913  3674  3674 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 05:52:41.928  3580  5953 I Decoder : createOrResetDecoder
,09-30 05:52:41.945   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 05:52:41.946  3468  3468 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-30 05:52:41.946  3468  3468 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-30 05:52:41.950  3292  5957 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 05:52:41.960  3468  3468 I ConfigService: onCreate
,09-30 05:52:41.964  3817  5961 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-30 05:52:41.965  3817  5961 D AccountUtils: Clearing selected account for com.test.thalitest
,09-30 05:52:41.976    13    13 W kworker/1:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:52:41.980    13    13 W kworker/1:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:52:41.993    13    13 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:52:41.995  3580  5953 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-30 05:52:42.022  3292  3313 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj5C840E90E) - 
,09-30 05:52:42.048  3817  5961 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-30 05:52:42.064  3817  5961 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:52:42.064  3817  5961 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:52:42.065  3817  5961 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 05:52:42.065  3817  5961 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
09-30 05:52:42.091  3292  3313 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-30 05:52:42.091  3292  3313 E AndroidRuntime: Process: android.process.acore, PID: 3292
09-30 05:52:42.091  3292  3313 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:52:42.091  3292  3313 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 05:52:42.108  3817  3817 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-30 05:52:42.110  3817  3817 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-30 05:52:42.122  3817  3817 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-30 05:52:42.122  3817  3817 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-30 05:52:42.143  4845  5971 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-30 05:52:42.157   930  3467 I ActivityManager: Start proc 5975:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-30 05:52:42.180  3292  3313 I Process : Sending signal. PID: 3292 SIG: 9
,09-30 05:52:42.185  4845  5971 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-30 05:52:42.213  3817  5980 I GMPM-SVC: App measurement is starting up
,09-30 05:52:42.216  3817  5980 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-30 05:52:42.218  3817  5980 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-30 05:52:42.219   930  3112 I ActivityManager: Start proc 5982:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-30 05:52:42.223  3817  5970 W BaseAppContext: Using Auth Proxy for data requests.
,09-30 05:52:42.230  3817  3817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-30 05:52:42.236  3817  5970 W BaseAppContext: Using Auth Proxy for data requests.
,09-30 05:52:42.378   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
