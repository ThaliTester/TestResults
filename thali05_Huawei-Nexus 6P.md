#### Test 8691870194a743c_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 08:42:11.055   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 08:42:11.055   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-27 08:42:11.551  5584  5584 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 08:42:11.557  5584  5584 D AndroidRuntime: CheckJNI is OFF
09-27 08:42:11.591  5584  5584 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 08:42:11.627  5584  5584 I Radio-JNI: register_android_hardware_Radio DONE
09-27 08:42:11.643  5584  5584 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-27 08:42:11.647   927  3838 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 08:42:11.686   927  3838 I ActivityManager: Start proc 5593:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 08:42:11.709  5584  5584 D AndroidRuntime: Shutting down VM
,09-27 08:42:12.025   927  3111 I WindowManager: Screenshot max retries 4 of Token{5425518 ActivityRecord{21840fb u0 com.test.thalitest/.MainActivity t2}} appWin=Window{87d473 u0 Starting com.test.thalitest} drawState=2
,09-27 08:42:12.089  5593  5593 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 08:42:12.127  5593  5593 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 08:42:12.150  5593  5593 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 519-537)
,09-27 08:42:12.150  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 08:42:12.169  5593  5593 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {347f5f1}
,09-27 08:42:12.169  5593  5593 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 08:42:12.170  5593  5593 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-27 08:42:12.175  5593  5593 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-27 08:42:12.176  5593  5593 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 08:42:12.210  5593  5593 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 08:42:12.223  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-27 08:42:12.223  5593  5593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 08:42:12.223  5593  5593 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 08:42:12.223  5593  5593 I Adreno  : Build Date                       : 12/06/15
09-27 08:42:12.223  5593  5593 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 08:42:12.223  5593  5593 I Adreno  : Local Branch                     : mybranch17112971
09-27 08:42:12.223  5593  5593 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 08:42:12.223  5593  5593 I Adreno  : Remote Branch                    : NONE
09-27 08:42:12.223  5593  5593 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 08:42:12.272   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5dd806:true
,09-27 08:42:12.298   407   407 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16161]" dev="sockfs" ino=16161 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:12.298   407   407 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[16161]" dev="sockfs" ino=16161 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:12.308  5593  5593 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 08:42:12.316  5593  5593 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 08:42:12.338  2896  2896 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33482]" dev="sockfs" ino=33482 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:12.340  5593  5630 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-27 08:42:12.338  2896  2896 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33482]" dev="sockfs" ino=33482 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:12.341  3847  3847 W Binder_D: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24367]" dev="sockfs" ino=24367 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:12.341  3847  3847 W Binder_D: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24367]" dev="sockfs" ino=24367 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:12.346  5593  5617 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 08:42:12.369  5593  5630 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 08:42:12.449   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +421ms (total +789ms)
,09-27 08:42:12.474  5593  5593 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5593
,09-27 08:42:12.564  5593  5593 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 08:42:12.688  5593  5633 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -579860176
,09-27 08:42:12.692  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 08:42:12.692  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 08:42:12.692  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 08:42:12.692  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 08:42:12.692  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-27 08:42:12.692  5593  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@633546e added. We now have 1 listener(s)
,09-27 08:42:12.694  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 08:42:12.694  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:42:12.695  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 08:42:12.695  5593  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-27 08:42:12.697  5593  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@505a1a5 added. We now have 1 listener(s)
09-27 08:42:12.697  5593  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:42:12.702   927  2933 D WifiService: New client listening to asynchronous messages
,09-27 08:42:12.703  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 08:42:12.703  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-27 08:42:12.703  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 08:42:12.704  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 08:42:12.704  5593  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-27 08:42:12.705  5593  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:12.705  5593  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-27 08:42:12.710  5593  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:12.711  5593  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:12.711  5593  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 08:42:12.711  5593  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:42:12.711  5593  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 08:42:12.714  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:12.719  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:12.730  5593  5593 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 08:42:13.049  5593  5639 W jxcore-log: Initializing JXcore engine
09-27 08:42:13.049  5593  5639 W jxcore-log: JXcore engine is ready
,09-27 08:42:13.075  5639  5639 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12493 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-27 08:42:13.075  5639  5639 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14430]" dev="sockfs" ino=14430 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-27 08:42:13.075  5639  5639 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 08:42:13.075  5639  5639 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33458]" dev="sockfs" ino=33458 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 08:42:13.082  5593  5639 W jxcore-log: Starting JXcore engine
,09-27 08:42:13.141  5593  5639 W jxcore-log: Platform android
09-27 08:42:13.141  5593  5639 W jxcore-log: 
,09-27 08:42:13.141  5593  5639 W jxcore-log: Process ARCH arm
09-27 08:42:13.141  5593  5639 W jxcore-log: 
,09-27 08:42:13.241  5593  5639 I jxcore-log: JXcore Cordova bridge is ready!
09-27 08:42:13.241  5593  5639 I jxcore-log: 
,09-27 08:42:13.241  5593  5639 W jxcore-log: JXcore engine is started
,09-27 08:42:13.245  5593  5633 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 08:42:13.248  5593  5593 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 08:42:13.943   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:42:21.057   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:22.058   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:23.059   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:23.070  5593  5639 I jxcore-log: 2016-09-27 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-27 08:42:23.070  5593  5639 I jxcore-log: 
,09-27 08:42:23.071  5593  5639 I jxcore-log: 2016-09-27 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-27 08:42:23.071  5593  5639 I jxcore-log: 
,09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:23.075  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:23.077  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:42:23.079  5593  5639 I jxcore-log: 2016-09-27 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-27 08:42:23.079  5593  5639 I jxcore-log: 
,09-27 08:42:23.081  5593  5639 I jxcore-log: 2016-09-27 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-27 08:42:23.081  5593  5639 I jxcore-log: 
,09-27 08:42:23.338  5593  5639 I jxcore-log: 2016-09-27 12:42:23 - DEBUG UnitTest_app: 'Running unit tests'
09-27 08:42:23.338  5593  5639 I jxcore-log: 
,09-27 08:42:23.339  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:42:23.339  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f806429 added. We now have 2 listener(s)
09-27 08:42:23.340  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:42:23.340  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 08:42:23.340  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:42:23.340  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:42:23.340  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e553ae added. We now have 2 listener(s)
,09-27 08:42:23.340  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:42:23.341  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 08:42:23.343  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:23.346  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:23.351  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:42:23.353  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:42:23.353  5593  5639 D executeNativeTests: Running unit tests
,09-27 08:42:23.359  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:23.363  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:23.390  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 08:42:23.390  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c added. We now have 3 listener(s)
,09-27 08:42:23.390  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 08:42:23.390  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 08:42:23.390  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:42:23.390  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 08:42:23.390  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 added. We now have 3 listener(s)
,09-27 08:42:23.391  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:42:23.391  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 08:42:23.396  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:23.404  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:23.408  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:23.408  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:42:23.410  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 08:42:23.410  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 08:42:23.410  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:42:23.410  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:42:23.411  5593  5639 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-27 08:42:23.411  5593  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-27 08:42:23.411  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 08:42:23.411  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:23.411  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:23.411  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:23.412  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:23.412  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:23.412  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:23.412  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:23.412  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.412  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:23.412  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:42:23.413  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c removed from the list
09-27 08:42:23.413  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:23.413  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 removed from the list
09-27 08:42:23.413  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:23.419  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:23.419  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:42:23.419  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:23.420  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.420  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:23.420  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:23.420  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:42:23.420  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:23.420  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:23.421  5593  5639 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-27 08:42:23.421  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:23.421  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:23.422  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:23.422  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:23.422  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:42:23.422  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:23.422  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:23.422  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:23.422  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list,
09-27 08:42:23.422  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:42:23.422  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.422  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:23.422  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.422  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:23.422  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:23.422  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:23.423  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:23.423  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
,09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 08:42:23.425  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 08:42:23.426  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:23.426  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:23.426  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 08:42:23.426  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:23.426  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.426  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:23.426  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:23.426  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:23.426  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:23.426  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:42:23.426  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.426  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:23.426  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:23.426  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:23.427  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:23.427  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:23.427  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:23.427  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:23.427  5593  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-27 08:42:23.428  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:23.431  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:23.432  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:23.432  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:42:23.432  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:42:23.432  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-27 08:42:23.432  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 08:42:23.432  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:23.432  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:23.434  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:23.434  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:42:23.435  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:23.438  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:23.438  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:42:23.440  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:42:23.440  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 08:42:23.441  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-27 08:42:23.442  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-27 08:42:23.442  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 08:42:23.442  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 08:42:23.442  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 08:42:23.443  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:42:23.445  4553  4777 D BtGatt.GattService: registerClient() - UUID=9deb0baa-6edd-4d89-96d6-9dc4f70ac862
,09-27 08:42:23.445  4553  4627 D BtGatt.GattService: onClientRegistered() - UUID=9deb0baa-6edd-4d89-96d6-9dc4f70ac862, clientIf=5
,09-27 08:42:23.446  5593  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 08:42:23.447  4553  4796 D BtGatt.GattService: start scan with filters
,09-27 08:42:23.451  4553  4630 D BtGatt.ScanManager: handling starting scan
,09-27 08:42:23.451  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 08:42:23.451  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 08:42:23.451  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 08:42:23.451  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 08:42:23.452  4553  4630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:42:23.452  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 08:42:23.452  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:42:23.452  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 08:42:23.453  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:42:23.454  5593  5639 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 08:42:23.459  4553  4627 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-27 08:42:23.459  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:23.460  4553  4630 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 08:42:23.466  4553  4627 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 08:42:23.466  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:23.466  4553  4630 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:42:23.466  4553  4630 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 08:42:23.477  4553  4627 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 08:42:23.477  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:23.483  4553  4627 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 08:42:23.483  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:23.955  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-27 08:42:23.955  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:42:23.955  5593  5593 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:42:24.060   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:24.760   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 08:42:25.061   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:26.062   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 08:42:27.785   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 08:42:28.460  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:28.460  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:28.460  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 08:42:28.461  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:42:28.461  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:42:28.461  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:42:28.461  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-27 08:42:28.461  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:42:28.461  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:42:28.463  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:42:28.463  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 08:42:28.464  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:28.464  4553  4568 D BtGatt.GattService: stopScan() - queue size =1
,09-27 08:42:28.466  4553  4797 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:42:28.468  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:28.469  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 08:42:28.469  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 08:42:28.469  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 08:42:28.469  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 08:42:28.472  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:42:28.472  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:28.472  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:42:28.473  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:28.473  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:42:28.475  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:28.475  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:28.475  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:28.475  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:28.475  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:28.475  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:28.475  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:28.475  4553  4553 D BtGatt.ScanManager: awakened up at time 236863
09-27 08:42:28.475  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:28.476  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:28.476  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:28.476  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:28.481  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:28.481  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:42:28.484  4553  4627 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-27 08:42:28.484  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:28.485  4553  4630 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:42:28.486  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:42:28.489  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:42:28.489  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:42:28.489  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:28.490  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:28.494  4553  4627 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 08:42:28.494  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:28.494  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:28.494  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:42:28.494  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:28.495  4553  4630 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 08:42:28.499  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:42:28.499  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:28.500  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:28.503  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:42:28.517  4553  4627 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-27 08:42:28.517  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:28.518  4553  4627 D BtGatt.GattService: current time is 236905862914
09-27 08:42:28.518  4553  4627 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -75, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -75, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -73, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -77, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 08:42:28.521  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 08:42:28.522  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 08:42:28.522  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 08:42:28.523  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-27 08:42:28.523  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 08:42:28.523  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-27 08:42:29.003  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:42:30.817   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 08:42:31.063   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:32.065   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:33.066   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:33.480  5593  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-27 08:42:33.487  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:33.497  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:33.502  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:42:33.502  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:42:33.503  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:42:33.503  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 08:42:33.503  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-27 08:42:33.503  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:33.503  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:33.508  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:33.510  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:42:33.514  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:33.518  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 08:42:33.518  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 08:42:33.518  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 08:42:33.519  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:42:33.524  4553  4777 D BtGatt.GattService: registerClient() - UUID=cba62c81-051e-4bd8-ad6a-d791758f17df
,09-27 08:42:33.525  4553  4627 D BtGatt.GattService: onClientRegistered() - UUID=cba62c81-051e-4bd8-ad6a-d791758f17df, clientIf=5
09-27 08:42:33.525  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 08:42:33.526  4553  4568 D BtGatt.GattService: start scan with filters
,09-27 08:42:33.530  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-27 08:42:33.530  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 08:42:33.530  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 08:42:33.530  4553  4630 D BtGatt.ScanManager: handling starting scan
09-27 08:42:33.530  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 08:42:33.534  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 08:42:33.534  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:42:33.536  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 08:42:33.537  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 08:42:33.542  5593  5639 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 08:42:33.542  4553  4627 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 08:42:33.542  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:33.543  4553  4630 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 08:42:33.545  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:33.545  5593  5639 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-27 08:42:33.545  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:42:33.545  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 08:42:33.545  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:33.545  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:42:33.545  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:42:33.545  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-27 08:42:33.545  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:42:33.545  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:42:33.546  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:42:33.546  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 08:42:33.546  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:33.547  4553  4797 D BtGatt.GattService: stopScan() - queue size =1
09-27 08:42:33.548  4553  4777 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 08:42:33.548  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:33.548  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-27 08:42:33.548  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 08:42:33.548  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 08:42:33.548  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 08:42:33.550  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:42:33.550  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:33.550  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:42:33.550  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:33.550  4553  4627 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 08:42:33.550  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:33.551  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:33.551  4553  4630 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:42:33.551  4553  4630 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 08:42:33.552  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:33.552  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:33.552  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:33.552  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:33.552  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:33.552  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:42:33.552  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:33.552  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:33.552  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:33.552  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:33.552  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:33.556  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:33.556  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:42:33.561  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:42:33.561  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:42:33.561  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:42:33.562  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:33.562  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:33.564  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:42:33.565  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:33.565  4553  4627 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 08:42:33.565  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:33.566  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 08:42:33.566  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:33.566  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:33.567  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:33.567  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:33.567  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:33.567  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:33.567  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 08:42:33.567  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:33.567  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:33.567  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:33.568  5593  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-27 08:42:33.569  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:33.571  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:33.571  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:42:33.572  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:33.573  4553  4627 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 08:42:33.573  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:33.574  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:33.577  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:42:33.578  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:42:33.578  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:42:33.578  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:42:33.579  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 08:42:33.579  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 08:42:33.579  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:33.579  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:33.580  4553  4627 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 08:42:33.580  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:33.580  4553  4630 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:42:33.581  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:33.583  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:42:33.586  4553  4627 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 08:42:33.587  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:33.587  4553  4630 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 08:42:33.587  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:33.589  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 08:42:33.589  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 08:42:33.590  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 08:42:33.590  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:42:33.592  4553  4570 D BtGatt.GattService: registerClient() - UUID=9c6fa18d-f374-48ea-bb88-8092c3860e1c
09-27 08:42:33.592  4553  4627 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-27 08:42:33.592  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:33.593  4553  4627 D BtGatt.GattService: onClientRegistered() - UUID=9c6fa18d-f374-48ea-bb88-8092c3860e1c, clientIf=5
,09-27 08:42:33.594  5593  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 08:42:33.594  4553  4777 D BtGatt.GattService: start scan with filters
,09-27 08:42:33.596  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 08:42:33.596  4553  4630 D BtGatt.ScanManager: handling starting scan
09-27 08:42:33.597  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 08:42:33.597  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 08:42:33.597  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 08:42:33.601  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 08:42:33.601  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:42:33.601  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 08:42:33.602  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:42:33.603  4553  4627 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 08:42:33.603  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:33.603  4553  4630 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-27 08:42:33.604  5593  5639 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 08:42:33.607  4553  4627 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 08:42:33.608  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:33.608  4553  4630 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:42:33.608  4553  4630 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 08:42:33.616  4553  4627 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 08:42:33.616  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:33.621  4553  4627 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 08:42:33.621  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:42:34.067   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:34.102  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 08:42:34.103  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:42:34.103  5593  5593 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:42:35.068   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:36.069   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 08:42:36.870   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 08:42:38.605  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:38.605  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:38.605  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 08:42:38.606  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:38.606  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:42:38.606  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:42:38.606  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:42:38.606  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:42:38.606  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 08:42:38.607  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:42:38.607  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-27 08:42:38.609  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:38.610  4553  4777 D BtGatt.GattService: stopScan() - queue size =1
,09-27 08:42:38.613  4553  4797 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:42:38.613  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:42:38.613  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 08:42:38.614  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 08:42:38.614  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 08:42:38.614  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 08:42:38.617  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:42:38.617  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:38.617  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:42:38.617  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:38.618  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:38.621  4553  4553 D BtGatt.ScanManager: awakened up at time 247008
09-27 08:42:38.621  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:38.621  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:42:38.621  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 08:42:38.626  4553  4627 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 08:42:38.626  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:38.626  4553  4630 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:42:38.628  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:38.628  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:42:38.632  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:42:38.633  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:42:38.633  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:42:38.633  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:42:38.634  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:42:38.634  4553  4627 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 08:42:38.635  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:38.635  4553  4630 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 08:42:38.637  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:38.637  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:38.637  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:38.641  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:38.641  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:38.641  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:42:38.645  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:42:38.651  4553  4627 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-27 08:42:38.651  4553  4627 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:42:38.651  4553  4627 D BtGatt.GattService: current time is 247039455124
09-27 08:42:38.651  4553  4627 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -73, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -75, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -75, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -70, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 08:42:38.652  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 08:42:38.652  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 08:42:38.652  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 08:42:38.652  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 08:42:38.653  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 08:42:38.653  4553  4627 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-27 08:42:39.146  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:42:39.146  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:39.146  5593  5593 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:42:43.622  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:43.622  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.623  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.623  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.623  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.623  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:43.623  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
,09-27 08:42:43.624  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.624  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.624  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.624  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.626  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:42:43.626  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.630  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.630  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.630  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:42:43.633  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:42:43.633  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.634  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.634  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.634  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
,09-27 08:42:43.636  5593  5639 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-27 08:42:43.637  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:43.638  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.638  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.638  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.638  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.639  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.639  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.639  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.639  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.639  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.639  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.639  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.640  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.640  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.642  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.642  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.643  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:42:43.644  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:42:43.644  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.644  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.644  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.645  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.647  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 08:42:43.647  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:43.647  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.647  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 08:42:43.647  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.647  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.648  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.648  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.648  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.648  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
,09-27 08:42:43.648  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.648  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.648  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.648  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.648  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.650  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.650  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.651  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:43.652  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.652  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.652  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:42:43.652  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.653  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.654  5593  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-27 08:42:43.654  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.654  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.654  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.655  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.655  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.655  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.655  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.655  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.655  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.655  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.656  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.656  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.656  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.656  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.658  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.658  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 08:42:43.658  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:43.659  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.659  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.659  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.660  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.660  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.661  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-27 08:42:43.661  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.661  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.662  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 08:42:43.662  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.663  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.663  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.663  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.663  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.663  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.663  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.663  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.663  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.663  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.663  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.665  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.665  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.665  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:42:43.667  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.667  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.667  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.667  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:43.667  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.668  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 08:42:43.668  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:42:43.669  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:42:43.669  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 08:42:43.669  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:43.669  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:43.669  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 08:42:43.669  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:42:43.669  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 08:42:43.669  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.669  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.670  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.670  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.670  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.670  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.670  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.670  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.670  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.670  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:42:43.670  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.670  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.670  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.670  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.674  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.674  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 08:42:43.675  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:42:43.678  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:42:43.678  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.678  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.678  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.678  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
,09-27 08:42:43.680  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:42:43.680  5593  5639 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 08:42:43.680  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-27 08:42:43.686  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-27 08:42:43.687  5593  5639 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 08:42:43.687  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 08:42:43.689  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 08:42:43.689  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-27 08:42:43.689  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-27 08:42:43.689  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 08:42:43.689  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 08:42:43.690  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 08:42:43.691  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 08:42:43.691  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 08:42:43.691  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-27 08:42:43.691  5593  5639 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 08:42:43.691  5593  5639 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-27 08:42:43.691  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:42:43.692  5593  5639 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 08:42:43.692  5593  5639 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-27 08:42:43.692  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-27 08:42:43.692  5593  5639 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 08:42:43.692  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-27 08:42:43.696  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-27 08:42:43.698  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-27 08:42:43.698  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-27 08:42:43.699  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-27 08:42:43.699  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-27 08:42:43.699  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-27 08:42:43.701  4797  4797 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33519]" dev="sockfs" ino=33519 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:42:43.701  4797  4797 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33519]" dev="sockfs" ino=33519 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:42:43.699  5593  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:42:43.699  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-27 08:42:43.699  5593  5639 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-27 08:42:43.701  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.701  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:42:43.701  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.701  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.701  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.701  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.701  5593  5640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:42:43.701  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-27 08:42:43.702  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.703  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.703  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.703  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.703  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.703  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.703  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.703  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.703  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-27 08:42:43.703  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-27 08:42:43.703  5593  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-27 08:42:43.704  5593  5640 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-27 08:42:43.704  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.704  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.704  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:43.706  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.706  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.706  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.706  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.706  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.707  5593  5639 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-27 08:42:43.707  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.707  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:42:43.707  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.707  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.708  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.708  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.708  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.708  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.708  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.708  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.708  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.708  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.708  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.708  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.709  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.710  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.710  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:43.710  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.710  5593  5639 D BluetoothLeScanner: could not find callback wrapper
,09-27 08:42:43.710  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.710  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.710  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.711  5593  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-27 08:42:43.711  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.711  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.711  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.712  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.712  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.712  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.712  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.712  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.712  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.712  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.712  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.712  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.712  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.712  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.713  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.713  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.713  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:43.713  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.714  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.714  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.714  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.714  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.714  5593  5639 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-27 08:42:43.714  5593  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-27 08:42:43.715  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-27 08:42:43.715  5593  5639 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-27 08:42:43.715  5593  5639 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 08:42:43.715  5593  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-27 08:42:43.715  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 08:42:43.715  5593  5639 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-27 08:42:43.715  5593  5639 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 08:42:43.715  5593  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 08:42:43.715  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 08:42:43.715  5593  5639 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-27 08:42:43.715  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:43.715  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:43.715  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:43.715  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.716  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.716  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:43.716  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.716  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.716  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.716  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.716  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.716  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.716  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.716  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.717  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:43.717  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:43.717  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:43.718  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:43.718  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:43.718  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:43.718  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:43.718  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.719  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:43.719  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.719  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:43.719  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:43.719  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:43.719  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:43.719  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:43.720  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:43.720  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:46.070   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:47.071   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:48.072   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:48.720  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:48.721  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.721  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 08:42:48.721  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:42:48.721  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.721  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:48.722  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:42:48.722  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:48.722  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:48.722  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 08:42:48.723  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:42:48.723  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.723  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
,09-27 08:42:48.723  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.723  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
,09-27 08:42:48.723  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:48.723  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.724  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:48.724  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.724  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:48.727  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:48.727  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:48.727  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:48.729  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:48.729  5593  5639 D BluetoothLeScanner: could not find callback wrapper
,09-27 08:42:48.729  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:48.729  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.731  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.735  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:42:48.736  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:48.737  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 08:42:48.740  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:42:48.740  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 08:42:48.741  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:42:48.741  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 08:42:48.741  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 08:42:48.741  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:48.741  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 08:42:48.741  5593  5642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:42:48.741  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-27 08:42:48.741  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:42:48.742  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.742  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-27 08:42:48.741  4777  4777 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31310]" dev="sockfs" ino=31310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:42:48.742  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:48.741  4777  4777 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31310]" dev="sockfs" ino=31310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:42:48.742  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 08:42:48.742  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.742  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:42:48.743  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:42:48.743  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:42:48.743  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:42:48.743  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:48.744  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:48.744  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:48.744  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:48.744  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:42:48.744  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.744  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.744  5593  5642 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:42:48.744  5593  5642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:42:48.744  5593  5642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:42:48.745  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:42:48.745  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.745  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:48.746  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:48.746  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:48.746  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:48.746  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:48.746  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:48.746  5593  5639 I org.thaliproject.p2p.btconnectorlib.Conn,ectionManager: dispose
09-27 08:42:48.746  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.746  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:48.746  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:48.746  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.746  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.746  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:48.746  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.746  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:48.749  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:48.749  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:42:48.754  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:42:48.754  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:42:48.755  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:42:48.755  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:48.755  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.757  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.758  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.759  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:48.759  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:48.759  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:48.760  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:48.760  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:48.760  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:48.760  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.760  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:42:48.760  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.760  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:48.760  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:42:48.761  5593  5639 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-27 08:42:48.762  5593  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 08:42:48.762  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 08:42:48.763  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:48.763  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:42:48.763  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:48.763  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:48.763  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:48.763  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:48.763  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.763  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:48.763  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:48.763  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.763  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.763  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:48.763  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.763  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:42:48.763  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:42:48.763  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:42:48.764  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.767  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.767  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 08:42:48.767  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.767  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:42:48.768  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:48.768  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:48.768  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:48.768  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:48.768  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:48.769  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:48.769  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.769  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.772  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:48.772  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:48.772  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:48.773  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:48.773  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.773  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.773  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:48.773  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.773  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.773  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:48.773  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.773  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.773  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.773  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.774  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:48.774  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:48.774  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:48.775  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:48.775  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:48.775  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:48.775  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.775  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.776  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:42:48.776  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:42:48.776  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:42:48.776  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:42:48.776  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.776  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.776  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93e6d0c not in the list
09-27 08:42:48.776  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.776  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.776  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:48.777  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.777  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.777  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:48.777  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:42:48.778  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:42:48.778  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:42:48.778  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:42:48.779  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:42:48.779  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:42:48.779  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:42:48.779  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:48.779  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8164655 not in the list
09-27 08:42:48.780  5593  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-27 08:42:48.780  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 08:42:48.780  5593  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-27 08:42:48.780  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 08:42:48.780  5593  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-27 08:42:48.780  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 08:42:48.783  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 08:42:48.783  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-27 08:42:48.783  5593  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-27 08:42:48.783  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 08:42:48.783  5593  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-27 08:42:48.783  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 08:42:48.784  5593  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-27 08:42:48.784  5593  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-27 08:42:48.784  5593  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-27 08:42:48.784  5593  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-27 08:42:48.785  5593  5639 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-27 08:42:48.785  5593  5639 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-27 08:42:48.785  5593  5639 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-27 08:42:48.785  5593  5639 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-27 08:42:48.787  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:42:48.787  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf414c3 added. We now have 3 listener(s)
09-27 08:42:48.787  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:42:48.788  5593  5639 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 08:42:48.788   927  3804 D WifiService: setWifiEnabled: true pid=5593, uid=10077
09-27 08:42:48.788   927  3804 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:42:48.832  4553  4767 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-27 08:42:48.833  4553  4775 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-27 08:42:49.073   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:49.267  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:42:50.074   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:42:51.074   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 08:42:53.792  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 08:42:53.793  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4127140 added. We now have 4 listener(s)
09-27 08:42:53.793  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:42:53.801  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:42:53.801  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4127140 removed from the list
09-27 08:42:53.801  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:53.801  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:53.801  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:53.803  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 08:42:53.803  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dbe879 added. We now have 4 listener(s)
09-27 08:42:53.803  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:42:53.806  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:42:53.806  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dbe879 removed from the list
,09-27 08:42:53.806  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:42:53.806  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:42:53.806  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:42:53.807  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:42:53.808  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20d09be added. We now have 4 listener(s)
09-27 08:42:53.808  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:42:53.812   927  3835 D WifiService: setWifiEnabled: false pid=5593, uid=10077
,09-27 08:42:53.812   927  3835 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:42:53.819   927  2932 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-27 08:42:53.819   927  2932 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 08:42:53.819   927  2932 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:42:53.820   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:42:53.829  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:42:53.831  4553  4623 D BluetoothAdapterState: Current state: ON, message: 23
09-27 08:42:53.831  4553  4623 D BluetoothAdapterProperties: Setting state to 13
09-27 08:42:53.831  4553  4623 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 08:42:53.832  4553  4623 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 08:42:53.833  4553  4623 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:42:53.834  4553  4553 D BluetoothMapService: onReceive
09-27 08:42:53.834  4553  4553 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 08:42:53.835  4553  4553 D BluetoothMapService: STATE_TURNING_OFF
09-27 08:42:53.835  4553  4553 D BluetoothMapService: MAP Service closeService in
,09-27 08:42:53.835  4553  4553 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 08:42:53.835  4553  4553 D ObexServerSockets0: shutdown(block = true)
09-27 08:42:53.836  4553  4553 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:42:53.836   506   923 D CommandListener: Clearing all IP addresses on wlan0
09-27 08:42:53.836  4553  4799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-27 08:42:53.836  4553  4553 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:42:53.837   927  5338 D DhcpClient: Clearing IP address
09-27 08:42:53.837  4553  4775 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-27 08:42:53.839  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:53.840  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:53.840  4553  4800 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 08:42:53.841  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.841  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:42:53.842  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:42:53.844   506   923 D CommandListener: Setting iface cfg
09-27 08:42:53.845  4553  4553 I BtOppRfcommListener: stopping Accept Thread
09-27 08:42:53.845  4553  5280 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 08:42:53.846  4553  5280 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 08:42:53.847   927  5339 D DhcpClient: Receive thread stopped
09-27 08:42:53.848  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.851  3537  5394 V NativeCrypto: Read error: ssl=0x7f71c52880: I/O error during system call, Connection timed out
09-27 08:42:53.852  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.853  3537  5394 V NativeCrypto: SSL shutdown failed: ssl=0x7f71c52880: I/O error during system call, Broken pipe
09-27 08:42:53.855   927  3113 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-27 08:42:53.855   927  5336 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-27 08:42:53.856  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:53.856  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:53.857  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.857  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:53.857   927  5336 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-27 08:42:53.858   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-27 08:42:53.858   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-27 08:42:53.859   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-27 08:42:53.861  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:53.861  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:53.862  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.862  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:42:53.865  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:53.865  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:53.866  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.866  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:53.871   927   940 I ActivityManager: Start proc 5646:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-27 08:42:53.872  4553  4627 D BluetoothAdapterProperties: Scan Mode:20
,09-27 08:42:53.872  4553  4623 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-27 08:42:53.876   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-27 08:42:53.876   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-27 08:42:53.876  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:42:53.877  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:53.877  4553  4553 D HeadsetService: Received stop request...Stopping profile...
09-27 08:42:53.877  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.877  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:53.881  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.881  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:42:53.882  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.882  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:42:53.884   532   532 E Parcel  : Reading a NULL string not supported here.
,09-27 08:42:53.885   927   927 D RttService: SCAN_AVAILABLE : 1
09-27 08:42:53.885   927  3042 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 08:42:53.886   927  2934 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-27 08:42:53.887  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.887  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:42:53.887   927   927 D BluetoothHeadset: Proxy object disconnected
,09-27 08:42:53.887  3076  3092 D BluetoothHeadset: Proxy object disconnected
09-27 08:42:53.888  3076  3076 D HeadsetProfile: Bluetooth service disconnected
09-27 08:42:53.888   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 08:42:53.888   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 08:42:53.888  3730  3868 W QCNEJ   : |CORE| network lost: 100
,09-27 08:42:53.889  3788  3996 D BluetoothHeadset: Proxy object disconnected
,09-27 08:42:53.889  3730  3868 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 08:42:53.889  4553  4553 D A2dpService: Received stop request...Stopping profile...
09-27 08:42:53.890  4553  4780 D A2dpStateMachine: Exit Disconnected: -1
09-27 08:42:53.893   927   927 D BluetoothA2dp: Proxy object disconnected
09-27 08:42:53.894  4553  4553 D HidService: Received stop request...Stopping profile...
,09-27 08:42:53.894  4553  4553 D HidService: Stopping Bluetooth HidService
09-27 08:42:53.895  3076  3076 D BluetoothA2dp: Proxy object disconnected
,09-27 08:42:53.896  4553  4553 D HealthService: Received stop request...Stopping profile...
09-27 08:42:53.897  4553  4553 V BluetoothAdapterState: isTurningOff()=true
,09-27 08:42:53.897  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.897  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.897  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.898  4553  4553 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 08:42:53.898  4553  4553 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 08:42:53.898  4553  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:42:53.899  4553  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:42:53.899  4553  4553 V BluetoothAdapterState: isTurningOff()=true
09-27 08:42:53.899  4553  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:42:53.899  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.899  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.899  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.899  4553  4627 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 08:42:53.899  4553  4627 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 08:42:53.899  4553  4553 D PanService: Received stop request...Stopping profile...
09-27 08:42:53.900   927  2932 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-27 08:42:53.902  4553  4553 D BluetoothMapService: Received stop request...Stopping profile...
09-27 08:42:53.902  4553  4627 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 08:42:53.902  4553  4553 D BluetoothMapService: stop()
09-27 08:42:53.902  4553  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:42:53.902  4553  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:42:53.902  4553  4767 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:42:53.902  4553  4767 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 08:42:53.902  4553  4767 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:42:53.902  4553  4767 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 08:42:53.903  4553  4553 D BluetoothMapAppObserver: deinitObservers()
09-27 08:42:53.903  4553  4553 D BluetoothMapAppObserver: removeReceiver()
09-27 08:42:53.904  4553  4553 V BluetoothAdapterState: isTurningOff()=true
,09-27 08:42:53.904  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.904  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.904  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.904  4553  4553 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 08:42:53.904  4553  4553 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 08:42:53.904  4553  4627 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 08:42:53.904  4553  4553 V BluetoothAdapterState: isTurningOff()=true
09-27 08:42:53.905  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.905  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.905  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.906  4553  4553 D SapService: Received stop request...Stopping profile...
09-27 08:42:53.906  4553  4553 V SapService: stop()
09-27 08:42:53.908  4553  4553 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 08:42:53.909  4553  4627 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 08:42:53.909  4553  4553 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 08:42:53.909  4553  4553 V BluetoothAdapterState: isTurningOff()=true
09-27 08:42:53.909  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.909  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.909  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.909  4553  4553 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 08:42:53.909  4553  4553 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 08:42:53.910   927  2932 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:42:53.910  4553  4553 D BluetoothMapService: MAP Service closeService in
09-27 08:42:53.910  4553  4553 V BluetoothAdapterState: isTurningOff()=true
09-27 08:42:53.910  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.910  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.910  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.911  4553  4553 D BluetoothMapService: cleanup()
09-27 08:42:53.911  4553  4553 D BluetoothMapService: MAP Service closeService in
09-27 08:42:53.911  4553  4553 V BluetoothAdapterState: isTurningOff()=true
09-27 08:42:53.911  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:53.911  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:53.911  4553  4553 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:42:53.912  4553  4623 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 08:42:53.912  4553  4623 D BluetoothAdapterProperties: Setting state to 15
09-27 08:42:53.912  4553  4623 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 08:42:53.913  4553  4623 I BluetoothAdapterState: Entering BleOnState
09-27 08:42:53.913  3076  3088 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:42:53.913   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:42:53.914  3076  3329 D BluetoothPan: onBluetoothStateChange on: false
09-27 08:42:53.914  3076  3076 D BluetoothInputDevice: Proxy object disconnected
09-27 08:42:53.914  3076  3076 D HidProfile: Bluetooth service disconnected
09-27 08:42:53.914  3076  3076 D BluetoothMap: Proxy object disconnected
09-27 08:42:53.914  3076  3076 D MapProfile: Bluetooth service disconnected
,09-27 08:42:53.914  3076  3092 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 08:42:53.915   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:42:53.915  3076  3088 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 08:42:53.916  3788  3822 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:42:53.916   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:42:53.916  3076  3329 D BluetoothMap: onBluetoothStateChange: up=false
09-27 08:42:53.917  3076  3092 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:42:53.917   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:42:53.918  4553  4623 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 08:42:53.918  4553  4623 D BluetoothAdapterProperties: Setting state to 16
09-27 08:42:53.918  4553  4623 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 08:42:53.918   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-27 08:42:53.919  4553  4623 D BluetoothAdapterProperties: onBleDisable
09-27 08:42:53.919  4553  4623 I BluetoothAdapterState: Entering PendingCommandState
09-27 08:42:53.919  4553  4624 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 08:42:53.921  4553  4627 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:42:53.922  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.922  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:53.923  4553  4767 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 08:42:53.923  4553  4767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:42:53.925  5646  5646 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-27 08:42:53.926  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.926  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:42:53.931  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:42:53.932  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.934  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.935  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:53.941  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:42:53.946   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-27 08:42:53.946   506   923 D CommandListener: Clearing all IP addresses on wlan0
09-27 08:42:53.947   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cd0a176:true
,09-27 08:42:53.947   927  2934 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-27 08:42:53.947   506   923 D TetherController: Setting IP forward enable = 0
09-27 08:42:53.947   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 08:42:53.948   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-27 08:42:53.950  5238  5238 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@71d21ed and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-27 08:42:53.952  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:42:53.952   927  2932 D DhcpClient: doQuit
09-27 08:42:53.952   927  2932 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 08:42:53.954  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.956   927  5338 D DhcpClient: onQuitting
09-27 08:42:53.956  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.957  3411  3411 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 08:42:53.957  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 08:42:53.957  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 08:42:53.957  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 08:42:53.957  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:53.958  5010  5033 E SarControlService: no key has been found,reset the power
,09-27 08:42:53.958  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-27 08:42:53.958  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 08:42:53.958  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 08:42:53.959  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:42:53.959  5035  5035 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 08:42:53.961  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 08:42:53.961  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 08:42:53.961  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 08:42:53.961  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:42:53.962  5035  5035 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 08:42:53.962  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000ea03000000000000ffffffff]
09-27 08:42:53.963  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:42:53.963  5035  5049 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-27 08:42:53.963  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 08:42:53.963  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-27 08:42:53.970  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000eb03000000000000ffffffff]
,09-27 08:42:53.971  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 08:42:53.971  5035  5049 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-27 08:42:53.972  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 08:42:53.972  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 08:42:53.972   927  3835 I ActivityManager: Start proc 5671:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-27 08:42:53.976  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.976  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:53.976  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:53.976  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:53.981  5646  5646 D LocalBluetoothProfileManager: Adding local MAP profile
,09-27 08:42:53.979  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.981  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:53.982  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.982  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:53.983  5646  5646 D BluetoothMap: Create BluetoothMap proxy object
,09-27 08:42:53.985  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:53.985  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:53.986  3411  3411 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 08:42:53.986  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:53.986  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:53.992  3411  3411 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-27 08:42:53.993   506   916 W SocketClient: write error (Broken pipe)
09-27 08:42:53.993   506   916 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
,09-27 08:42:53.993   506   916 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 08:42:54.001   506   923 E Netd    : netlink response contains error (No such file or directory)
,09-27 08:42:54.002   927  2934 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-27 08:42:54.005  5646  5646 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-27 08:42:54.022  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,09-27 08:42:54.027  5671  5671 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-27 08:42:54.029   927  3111 I ActivityManager: Killing 4943:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-27 08:42:54.031  3411  3411 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 08:42:54.046  3411  3411 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 08:42:54.060   927  2932 D wifi    : In wifi stop Hal
,09-27 08:42:54.060   927  2932 D wifi    : halHandle = 0x7f707dee00, mVM = 0x7f8ce0d140, mCls = 0x100a02
,09-27 08:42:54.060   927  3410 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 08:42:54.060   927  3410 D WifiHAL : Got a signal to exit!!!
,09-27 08:42:54.060  4984  4984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:42:54.060   927  3410 I WifiHAL : Exit wifi_event_loop
09-27 08:42:54.061   927  2932 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-27 08:42:54.061   927  2932 E WifiHAL : Event processing terminated
09-27 08:42:54.061   927  2932 D wifi    : In wifi cleaned up handler
09-27 08:42:54.061   927  2932 I WifiHAL : Internal cleanup completed
,09-27 08:42:54.062  4038  4177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 08:42:54.063  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:54.064  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:42:54.065  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:54.084   927  3410 D wifi    : set interface wlan0 flags (DOWN)
,09-27 08:42:54.084   927  2932 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 08:42:54.130  4553  4627 I bt_hci  : shut_down
,09-27 08:42:54.134  4553  4632 D bt_hwcfg: hw_epilog_process
,09-27 08:42:54.135  4553  4632 I bt_vendor: low_power_mode_cb
,09-27 08:42:54.137  4553  4632 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-27 08:42:54.137  4553  4632 I bt_vendor: epilog_cb
09-27 08:42:54.137  4553  4632 I bt_hci  : epilog_finished_callback
,09-27 08:42:54.140  4553  4627 I bt_hci_h4: hal_close
,09-27 08:42:54.140  4553  4627 I bt_userial_vendor: device fd = 54 close
,09-27 08:42:54.217  5671  5671 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-27 08:42:54.217  5671  5671 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.217  5671  5671 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.217  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.218  5671  5671 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.218  5671  5671 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.k.d(PG:583)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.218  5671  5671 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.218  5671  5671 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.218  5671  5671 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:42:54.218  5671  5671 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:42:54.248  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 08:42:54.253  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:42:54.255  4553  4624 D bt_stack_manager: event_shut_down_stack finished.
09-27 08:42:54.255  4553  4623 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 08:42:54.258  4553  4553 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:42:54.258  4553  4553 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 08:42:54.258  4553  4553 D BtGatt.GattService: stop()
09-27 08:42:54.258  4553  4553 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 08:42:54.259  4553  4623 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 08:42:54.262  5646  5646 D DockEventReceiver: finishStartingService: stopping service
09-27 08:42:54.263  3689  3689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 08:42:54.263  4553  4553 V BluetoothAdapterState: isTurningOff()=false
09-27 08:42:54.263  4553  4553 V BluetoothAdapterState: isTurningOn()=false
09-27 08:42:54.263  4553  4553 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:42:54.263  4553  4553 V BluetoothAdapterState: isBleTurningOff()=true
09-27 08:42:54.263  4553  4623 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 08:42:54.264  4553  4623 D BluetoothAdapterProperties: Setting state to 10
09-27 08:42:54.264  4553  4623 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 08:42:54.265   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-27 08:42:54.265  4553  4623 I BluetoothAdapterState: Entering OffState
09-27 08:42:54.272  3689  3689 D SystemUpdateService: onCreate
09-27 08:42:54.273  4553  4553 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-27 08:42:54.274  4553  4553 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 08:42:54.274  4553  4553 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 08:42:54.275  4553  4624 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-27 08:42:54.280  3689  3689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-27 08:42:54.287   927   944 D Tethering: InitialState.processMessage what=4
09-27 08:42:54.287  4553  4624 D bt_stack_manager: event_clean_up_stack finished.
09-27 08:42:54.290   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-27 08:42:54.291  3689  3689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 08:42:54.297  3689  5362 I iu.UploadsManager: num queued entries: 0
09-27 08:42:54.297  3689  5362 I iu.UploadsManager: num updated entries: 0
09-27 08:42:54.298  3689  5362 I iu.SyncManager: NEXT; no task
,09-27 08:42:54.310  4553  4553 I art     : System.exit called, status: 0
,09-27 08:42:54.310  4553  4553 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 08:42:54.317  3689  3689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 08:42:54.318  3689  3689 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 08:42:54.320  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-27 08:42:54.324  5365  5365 D SprintDMHelper: simOperator: 
09-27 08:42:54.324  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 08:42:54.336  3689  5705 I SystemUpdateService: active receiver: enabled
,09-27 08:42:54.342  4984  5707 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 08:42:54.348   927  3804 I ActivityManager: Start proc 5708:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-27 08:42:54.348  3689  5705 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 08:42:54.352   927   937 I ActivityManager: Process com.android.bluetooth (pid 4553) has died
,09-27 08:42:54.379  5708  5708 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-27 08:42:54.387   927   937 I ActivityManager: Killing 5238:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-27 08:42:54.400  3689  5705 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 08:42:54.400  3689  5705 I SystemUpdateService: now status is 0 (complete)
,09-27 08:42:54.400  3689  5705 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 08:42:54.400  3689  5705 I SystemUpdateService: file has been verified
09-27 08:42:54.400  3689  5705 I SystemUpdateService: OTA package size = 21989297
,09-27 08:42:54.425  3689  5705 I SystemUpdateService: showing system update notification
,09-27 08:42:54.460  3689  3689 D SystemUpdateService: onDestroy
,09-27 08:42:54.462   927  3847 I ActivityManager: Killing 4637:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-27 08:42:54.575  5671  5699 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-27 08:42:54.591   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b57407b:true
,09-27 08:42:55.023   506   923 D TetherController: Setting IP forward enable = 0
,09-27 08:42:58.844   927  3835 D WifiService: setWifiEnabled: true pid=5593, uid=10077
,09-27 08:42:58.844   927  3835 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:42:58.853   506   923 D SoftapController: Softap fwReload - Ok
,09-27 08:42:58.858   506   923 D CommandListener: Setting iface cfg
,09-27 08:42:58.859   506   923 D CommandListener: Trying to bring down wlan0
09-27 08:42:58.860   506   923 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:42:58.865   927  2932 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 08:42:59.434   927  2932 D wifi    : set interface wlan0 flags (UP)
,09-27 08:42:59.434   927  2932 I WifiHAL : Initializing wifi
09-27 08:42:59.434   927  2932 I WifiHAL : Creating socket
,09-27 08:42:59.438   927  2932 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-27 08:42:59.439   927  2932 D wifi    : Did set static halHandle = 0x7f707dee00
,09-27 08:42:59.439   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-27 08:42:59.439   927  2932 D wifi    : halHandle = 0x7f707dee00, mVM = 0x7f8ce0d140, mCls = 0x198a
09-27 08:42:59.439   927  2932 D wifi    : array field set
09-27 08:42:59.439   927  2932 I WifiNative-HAL: interface[0] = wlan0
,09-27 08:42:59.442   927  5733 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547348147712
,09-27 08:42:59.442   927  5733 D wifi    : waitForHalEvents called, vm = 0x7f8ce0d140, obj = 0x198a, env = 0x7f6e1b38c0
,09-27 08:42:59.508  5734  5734 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 08:42:59.531  5734  5734 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:42:59.541  5734  5734 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:42:59.541  5734  5734 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 08:42:59.544   927  2932 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 08:42:59.550  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:59.551  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:59.554  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:59.554  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:59.554  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:59.554  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:59.560   927  2932 D WifiConfigStore: Loading config and enabling all networks 
,09-27 08:42:59.562  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:59.563  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:59.563  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:59.563  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:42:59.565  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:42:59.565  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:42:59.565  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:42:59.565  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:42:59.567  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:42:59.570   927  2932 D WifiConfigStore: loaded 0 passpoint configs
09-27 08:42:59.570   927  2932 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-27 08:42:59.571   927  2932 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 08:42:59.571   927  2932 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-27 08:42:59.572   927  2932 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 08:42:59.572   927  2932 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 08:42:59.572   927  2932 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-27 08:42:59.572   927  2932 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 08:42:59.575   927  2932 D WifiNative-HAL: Setting external_sim to 1
,09-27 08:42:59.575  4984  4984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 08:42:59.575   927  2932 D wifi    : setting dfs flag to true, 0x7f74368ba0
09-27 08:42:59.575   927  2932 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 08:42:59.575   927  2932 D wifi    : setting scan oui 0x7f74368ba0
09-27 08:42:59.575   927  2932 D WifiHAL : Sending mac address OUI
,09-27 08:42:59.578   927  2932 E native  : do suspend false
,09-27 08:42:59.585   927  2932 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-27 08:42:59.585   927   927 D RttService: SCAN_AVAILABLE : 3
09-27 08:42:59.585   506   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 08:42:59.585   927  3042 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 08:42:59.586   506   923 D CommandListener: Setting iface cfg
,09-27 08:42:59.590   927  2925 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-27 08:42:59.590   927  2925 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 08:42:59.598   927  2925 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 08:42:59.599   927  2925 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 08:42:59.603   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267991 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-27 08:43:02.785  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:02.789  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:02.794  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:02.799  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:02.871   927  2932 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 08:43:02.872   927  2932 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-27 08:43:02.873   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:43:02.883   927  2932 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 08:43:02.918   927  2932 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 08:43:02.920  5734  5734 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 08:43:03.348  5734  5734 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 08:43:03.384  5734  5734 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 08:43:03.384  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 08:43:03.395   927  2932 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 08:43:03.395   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 08:43:03.395   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 08:43:03.411   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:43:03.423   506   923 D CommandListener: Setting iface cfg
,09-27 08:43:03.429   927  2932 D WifiStateMachine: Start Dhcp Watchdog 2
,09-27 08:43:03.438   927  5740 D DhcpClient: Receive thread started
,09-27 08:43:03.438   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:43:03.438   927  2932 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-27 08:43:03.438   927  2934 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-27 08:43:03.519   927  2932 E native  : do suspend false
,09-27 08:43:03.530   927  5739 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 08:43:03.542   927  5740 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172571, domain null
,09-27 08:43:03.543   927  5739 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172571 seconds
,09-27 08:43:03.545   927  5739 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 08:43:03.568   927  5740 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 08:43:03.568   927  5739 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 08:43:03.571   506   923 D CommandListener: Setting iface cfg
,09-27 08:43:03.576   927  2932 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 08:43:03.583   927  5739 D DhcpClient: Scheduling renewal in 86399s
,09-27 08:43:03.592   927  2932 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 08:43:03.593   927  2932 D WifiConfigStore: No blacklist allowed without epno enabled
09-27 08:43:03.594   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-27 08:43:03.596   927  2934 D ConnectivityService: Adding iface wlan0 to network 101
,09-27 08:43:03.604   927  2932 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 08:43:03.653   927  2934 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 08:43:03.653   927  2934 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-27 08:43:03.656   927  2934 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-27 08:43:03.662   927  2934 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-27 08:43:03.664   927  2934 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-27 08:43:03.672   927  2934 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:43:03.677   927  2934 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-27 08:43:03.677   927  2934 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-27 08:43:03.677   927  2934 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-27 08:43:03.677   927  2932 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 08:43:03.678   927  2934 D ConnectivityService:    accepting network in place of null
09-27 08:43:03.678   927  2932 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:43:03.678   927  2934 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 08:43:03.698   927  5738 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272085, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 08:43:03.704   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:43:03.725   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:43:03.729   927  2934 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-27 08:43:03.729  3730  3868 W QCNEJ   : |CORE| network available: 101
,09-27 08:43:03.729   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 08:43:03.730   927  2934 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-27 08:43:03.734  3730  3868 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 08:43:03.734  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.735   927   944 D Tethering: MasterInitialState.processMessage what=3
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:03.735  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:43:03.735  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.735  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:43:03.736  3730  3868 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 08:43:03.736  3730  3868 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-27 08:43:03.738  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:03.738  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:43:03.739  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.739  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:03.741  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:03.742  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:43:03.742  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:43:03.742  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:43:03.750  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 08:43:03.750  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 08:43:03.750  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 08:43:03.750  5010  5033 E SarControlService: no key has been found,reset the power
09-27 08:43:03.750  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 08:43:03.750  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 08:43:03.750  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 08:43:03.751  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:43:03.751  5035  5035 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 08:43:03.752  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 08:43:03.752  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 08:43:03.752  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-27 08:43:03.752  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:43:03.752  5035  5035 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 08:43:03.754  3689  3689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 08:43:03.757  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000ec03000000000000ffffffff]
09-27 08:43:03.757  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:43:03.757  5035  5049 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-27 08:43:03.757  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:43:03.758  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 08:43:03.759  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000ed03000000000000ffffffff]
,09-27 08:43:03.759  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:43:03.759  5035  5049 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-27 08:43:03.760  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:43:03.760  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 08:43:03.760  3689  3689 D SystemUpdateService: onCreate
09-27 08:43:03.763  3689  3689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 08:43:03.766   927  5737 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 08:43:03.772  3689  3689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 08:43:03.776  3689  5362 I iu.UploadsManager: num queued entries: 0
,09-27 08:43:03.777  3689  5362 I iu.UploadsManager: num updated entries: 0
09-27 08:43:03.777  3689  5362 I iu.SyncManager: NEXT; no task
09-27 08:43:03.780  3689  3689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 08:43:03.781  3689  3689 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 08:43:03.783  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:43:03.786  5365  5365 D SprintDMHelper: simOperator: 
09-27 08:43:03.786  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 08:43:03.804  3689  5750 I SystemUpdateService: active receiver: enabled
,09-27 08:43:03.821   927  5737 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 12:43:03 GMT], X-Android-Received-Millis=[1474980183820], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474980183791]}
,09-27 08:43:03.821   927  2934 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-27 08:43:03.822   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-27 08:43:03.822   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-27 08:43:03.823   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-27 08:43:03.824  3689  5750 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 08:43:03.826  3689  5750 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-27 08:43:03.826  3689  5750 I SystemUpdateService: now status is 0 (complete)
09-27 08:43:03.826  3689  5750 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 08:43:03.826  3689  5750 I SystemUpdateService: file has been verified
09-27 08:43:03.826  3689  5750 I SystemUpdateService: OTA package size = 21989297
,09-27 08:43:03.831  3689  5750 I SystemUpdateService: showing system update notification
,09-27 08:43:03.840  3689  3689 D SystemUpdateService: onDestroy
,09-27 08:43:03.853   927  3755 D WifiService: setWifiEnabled: false pid=5593, uid=10077
,09-27 08:43:03.853   927  3755 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:43:03.854   927  2932 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-27 08:43:03.854   927  2932 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 08:43:03.854   927  2932 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:43:03.854   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:43:03.862   927  5739 D DhcpClient: Clearing IP address
09-27 08:43:03.862   506   923 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:43:03.864   506   923 D CommandListener: Setting iface cfg
,09-27 08:43:03.865   927  5740 D DhcpClient: Receive thread stopped
,09-27 08:43:03.869  3537  5751 V NativeCrypto: SSL handshake aborted: ssl=0x7f86d48100: I/O error during system call, Connection timed out
,09-27 08:43:03.874   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-27 08:43:03.874   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-27 08:43:03.880   532   532 E Parcel  : Reading a NULL string not supported here.
,09-27 08:43:03.883  4984  5754 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-27 08:43:03.884   927   927 D RttService: SCAN_AVAILABLE : 1
09-27 08:43:03.884   927  3042 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 08:43:03.887   927  2934 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-27 08:43:03.887   927  2932 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-27 08:43:03.890  3730  3868 W QCNEJ   : |CORE| network lost: 101
,09-27 08:43:03.890  3730  3868 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 08:43:03.890   927  2932 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
09-27 08:43:03.894  4984  5754 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-27 08:43:03.894  4984  5754 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-27 08:43:03.912   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:43:03.931   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:43:03.931   506   923 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:43:03.932   927  2934 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-27 08:43:03.933   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:43:03.934   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-27 08:43:03.937   927  2932 D DhcpClient: doQuit
09-27 08:43:03.937   927  2932 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 08:43:03.937   927  5739 D DhcpClient: onQuitting
09-27 08:43:03.938  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:03.938  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:03.938  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:43:03.938  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:03.939  5734  5734 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 08:43:03.942  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:03.942  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:03.942  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.942  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:03.944  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:03.944  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:03.944  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.944  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:03.945  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:03.946  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:43:03.946  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:03.946  3689  3689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 08:43:03.946  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:03.947  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:03.948  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 08:43:03.948  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 08:43:03.948  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 08:43:03.948  5010  5033 E SarControlService: no key has been found,reset the power
09-27 08:43:03.948  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 08:43:03.948  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 08:43:03.948  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 08:43:03.949  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:43:03.949  5035  5035 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 08:43:03.950  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 08:43:03.950  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 08:43:03.950  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 08:43:03.951  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:43:03.951  5035  5035 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 08:43:03.953  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 08:43:03.954  3689  3689 D SystemUpdateService: onCreate
09-27 08:43:03.956  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000ee03000000000000ffffffff]
09-27 08:43:03.956  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:43:03.956  5035  5049 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-27 08:43:03.956  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 08:43:03.956  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 08:43:03.958  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 08:43:03.959  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000ef03000000000000ffffffff]
09-27 08:43:03.959  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:43:03.959  5035  5049 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-27 08:43:03.960  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 08:43:03.960  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-27 08:43:03.960  3689  3689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 08:43:03.968  3689  5768 I SystemUpdateService: active receiver: enabled
,09-27 08:43:03.970  3689  3689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 08:43:03.977  3689  5362 I iu.UploadsManager: num queued entries: 0
,09-27 08:43:03.977  3689  5362 I iu.UploadsManager: num updated entries: 0
09-27 08:43:03.978  3689  5362 I iu.SyncManager: NEXT; no task
,09-27 08:43:03.980  3689  3689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 08:43:03.982  3689  3689 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 08:43:03.983  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:43:03.987  5365  5365 D SprintDMHelper: simOperator: 
,09-27 08:43:03.987  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 08:43:03.991  5734  5734 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 08:43:03.992  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 08:43:03.994   506   923 E Netd    : netlink response contains error (No such file or directory)
09-27 08:43:03.995   927  2934 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-27 08:43:03.999  4984  5772 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 08:43:03.999  3689  5768 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 08:43:04.004  3689  5768 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 08:43:04.004  3689  5768 I SystemUpdateService: now status is 0 (complete)
09-27 08:43:04.004  3689  5768 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-27 08:43:04.004  3689  5768 I SystemUpdateService: file has been verified
,09-27 08:43:04.006  3689  5768 I SystemUpdateService: OTA package size = 21989297
,09-27 08:43:04.017  3689  5768 I SystemUpdateService: showing system update notification
,09-27 08:43:04.026  3689  3689 D SystemUpdateService: onDestroy
,09-27 08:43:04.097   927  2932 D wifi    : In wifi stop Hal
,09-27 08:43:04.097   927  2932 D wifi    : halHandle = 0x7f707dee00, mVM = 0x7f8ce0d140, mCls = 0x198a
09-27 08:43:04.098   927  5733 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 08:43:04.098   927  5733 D WifiHAL : Got a signal to exit!!!
09-27 08:43:04.098   927  5733 I WifiHAL : Exit wifi_event_loop
09-27 08:43:04.099   927  2932 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 08:43:04.099   927  2932 E WifiHAL : Event processing terminated
,09-27 08:43:04.100  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:04.100  4038  4177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:43:04.100  4984  4984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:43:04.101   927  2932 D wifi    : In wifi cleaned up handler
09-27 08:43:04.101  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:04.101   927  2932 I WifiHAL : Internal cleanup completed
09-27 08:43:04.101  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:04.123   927  5733 D wifi    : set interface wlan0 flags (DOWN)
,09-27 08:43:04.123   927  2932 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 08:43:04.329   927   944 D Tethering: InitialState.processMessage what=4
,09-27 08:43:04.336   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 08:43:04.730   927  2934 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-27 08:43:06.076   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:07.077   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:08.078   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:08.888   927   944 I ActivityManager: Start proc 5774:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 08:43:08.984  5774  5774 D AdapterServiceConfig: Adding HeadsetService
,09-27 08:43:08.984  5774  5774 D AdapterServiceConfig: Adding A2dpService
09-27 08:43:08.984  5774  5774 D AdapterServiceConfig: Adding HidService
09-27 08:43:08.984  5774  5774 D AdapterServiceConfig: Adding HealthService
09-27 08:43:08.984  5774  5774 D AdapterServiceConfig: Adding PanService
09-27 08:43:08.985  5774  5774 D AdapterServiceConfig: Adding GattService
09-27 08:43:08.985  5774  5774 D AdapterServiceConfig: Adding BluetoothMapService
09-27 08:43:08.985  5774  5774 D AdapterServiceConfig: Adding SapService
,09-27 08:43:08.999   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7b16e:true
,09-27 08:43:08.999  5774  5774 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 08:43:09.003  5774  5774 I bt_bluedroid: init
,09-27 08:43:09.003  5774  5786 I BluetoothAdapterState: Entering OffState
,09-27 08:43:09.005  5774  5787 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 08:43:09.006  5774  5787 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 08:43:09.006  5774  5787 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 08:43:09.006  5774  5787 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 08:43:09.007  5774  5774 I bt_bluedroid: get_profile_interface socket
,09-27 08:43:09.008  5774  5790 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 08:43:09.008  5774  5774 I bt_bluedroid: get_profile_interface sdp
09-27 08:43:09.010  5774  5790 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 08:43:09.013  5774  5785 I bt_bluedroid: config_hci_snoop_log
,09-27 08:43:09.014   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-27 08:43:09.018  5774  5786 D BluetoothAdapterState: Current state: OFF, message: 0
09-27 08:43:09.018  5774  5786 D BluetoothAdapterProperties: Setting state to 14
09-27 08:43:09.019  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 08:43:09.020  5774  5786 D BluetoothBondStateMachine: make
,09-27 08:43:09.022  5774  5791 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 08:43:09.024  5774  5786 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:43:09.025  5774  5774 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 08:43:09.028  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:09.028  5774  5774 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:43:09.029  5774  5774 D BtGatt.GattService: Received start request. Starting profile...
09-27 08:43:09.029  5774  5774 D BtGatt.GattService: start()
09-27 08:43:09.029  5774  5774 I bt_bluedroid: get_profile_interface gatt
09-27 08:43:09.030  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:09.030  5774  5774 D BtGatt.AdvertiseManager: advertise manager created
,09-27 08:43:09.036  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.036  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:09.036  5774  5774 V BluetoothAdapterState: isBleTurningOn()=true
09-27 08:43:09.036  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:43:09.036  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 08:43:09.037  5774  5786 I bt_bluedroid: bt_bluedroid
09-27 08:43:09.038  5774  5787 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-27 08:43:09.038  5774  5787 I bt_hci  : start_up
,09-27 08:43:09.043  5774  5787 I bt_vendor: alloc value 0xf4215871
09-27 08:43:09.043  5774  5787 I bt_vendor: init
09-27 08:43:09.043  5774  5787 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 08:43:09.043  5774  5787 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 08:43:09.078   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:09.152  5774  5787 D bt_hci  : start_up starting async portion
,09-27 08:43:09.152  5774  5794 I bt_hci  : event_finish_startup
,09-27 08:43:09.152  5774  5794 I bt_hci_h4: hal_open
,09-27 08:43:09.153  5774  5794 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-27 08:43:09.156  5774  5794 I bt_userial_vendor: device fd = 54 open
09-27 08:43:09.151  5795  5795 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 08:43:09.171  5774  5794 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:43:09.174  5774  5794 D bt_hwcfg: Chipset BCM4358A3
,09-27 08:43:09.174  5774  5794 D bt_hwcfg: Target name = [BCM4358A3]
09-27 08:43:09.174  5774  5794 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 08:43:09.571  5774  5794 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 08:43:09.572  5774  5794 D bt_hwcfg: Settlement delay -- 100 ms
09-27 08:43:09.572  5774  5794 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 08:43:09.705  5774  5794 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:43:09.706  5774  5794 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 08:43:09.707  5774  5794 I bt_hwcfg: vendor lib fwcfg completed
,09-27 08:43:09.707  5774  5794 I bt_vendor: firmware callback
09-27 08:43:09.707  5774  5794 I bt_hci  : firmware_config_callback
,09-27 08:43:09.716  5774  5797 I bt_btu  : btu_task pending for preload complete event
09-27 08:43:09.717  5774  5797 I bt_btu_task: Bluetooth chip preload is complete
,09-27 08:43:09.717  5774  5797 I bt_btu  : btu_task received preload complete event
,09-27 08:43:09.726  5774  5797 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 08:43:09.726  5774  5797 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_A2D
,09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_BNEP
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 08:43:09.727  5774  5797 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 08:43:09.728  5774  5797 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 08:43:09.728  5774  5797 I         : BTE_InitTraceLevels -- TRC_GATT
,09-27 08:43:09.728  5774  5797 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 08:43:09.728  5774  5797 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 08:43:09.728  5774  5797 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 08:43:09.811  5774  5797 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4193549
09-27 08:43:09.811  5774  5797 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4193549 
,09-27 08:43:09.827  5774  5790 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 08:43:09.829  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 08:43:09.830  5774  5790 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 08:43:09.832  5774  5790 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 08:43:09.834  5774  5790 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:43:09.835  5774  5790 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-27 08:43:09.835  5774  5790 D bt_hci  : do_postload posting postload work item
09-27 08:43:09.835  5774  5794 I bt_hci  : event_postload
09-27 08:43:09.835  5774  5794 I bt_vendor: sco_config_cb
09-27 08:43:09.835  5774  5794 I bt_hci  : sco_config_callback postload finished.
,09-27 08:43:09.838  5774  5790 D bt_bte_conf: Device ID record 1 : primary
09-27 08:43:09.839  5774  5790 D bt_bte_conf:   vendorId            = 000f
09-27 08:43:09.839  5774  5790 D bt_bte_conf:   vendorIdSource      = 0001
09-27 08:43:09.839  5774  5790 D bt_bte_conf:   product             = 1200
,09-27 08:43:09.839  5774  5790 D bt_bte_conf:   version             = 1436
09-27 08:43:09.839  5774  5790 D bt_bte_conf:   clientExecutableURL = 
09-27 08:43:09.839  5774  5790 D bt_bte_conf:   serviceDescription  = 
09-27 08:43:09.839  5774  5790 D bt_bte_conf:   documentationURL    = 
09-27 08:43:09.839  5774  5790 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 08:43:09.839  5774  5787 D bt_stack_manager: event_start_up_stack finished
09-27 08:43:09.840  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:09.841  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 08:43:09.841  5774  5786 D BluetoothAdapterProperties: Setting state to 15
09-27 08:43:09.841  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 08:43:09.844  5774  5794 I bt_vendor: low_power_mode_cb
09-27 08:43:09.844  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:09.846  5774  5786 I BluetoothAdapterState: Entering BleOnState
09-27 08:43:09.846  5774  5786 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-27 08:43:09.846  5774  5786 D BluetoothAdapterProperties: Setting state to 11
09-27 08:43:09.846  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-27 08:43:09.848  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.854  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.856  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.860  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.862  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:09.863  5774  5774 D HeadsetService: Received start request. Starting profile...
09-27 08:43:09.867  5774  5774 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 08:43:09.867  5774  5774 D HeadsetStateMachine: make
09-27 08:43:09.873  5774  5786 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:43:09.875  5774  5774 D HeadsetStateMachine: max_hf_connections = 1
09-27 08:43:09.876  5774  5774 I bt_bluedroid: get_profile_interface handsfree
09-27 08:43:09.876  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 08:43:09.876  5774  5790 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-27 08:43:09.880  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:09.881  5774  5774 D A2dpService: Received start request. Starting profile...
,09-27 08:43:09.881  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:43:09.881  5774  5774 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 08:43:09.882  5774  5774 I bt_bluedroid: get_profile_interface avrcp
,09-27 08:43:09.887  5774  5774 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 08:43:09.887  5774  5774 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 08:43:09.887  5774  5774 D A2dpStateMachine: make
09-27 08:43:09.888  5774  5774 I bt_bluedroid: get_profile_interface a2dp
,09-27 08:43:09.889  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 08:43:09.890  5774  5805 D A2dpStateMachine: Enter Disconnected: -2
,09-27 08:43:09.891  5774  5774 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 08:43:09.892  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:09.893  5646  5646 D BluetoothInputDevice: Proxy object connected
09-27 08:43:09.893  5774  5774 D HidService: Received start request. Starting profile...
09-27 08:43:09.894  5774  5774 I bt_bluedroid: get_profile_interface hidhost
09-27 08:43:09.894  5646  5646 D HidProfile: Bluetooth service connected
09-27 08:43:09.894  5774  5774 D HidService: setHidService(): set to: null
09-27 08:43:09.894  5774  5790 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf417456d
09-27 08:43:09.894  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 08:43:09.894  5774  5774 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 08:43:09.895  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:09.896  5774  5774 D HealthService: Received start request. Starting profile...
,09-27 08:43:09.897  5774  5774 I bt_bluedroid: get_profile_interface health
,09-27 08:43:09.898  5774  5774 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 08:43:09.899  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:09.900  5774  5774 D PanService: Received start request. Starting profile...
,09-27 08:43:09.900  5646  5646 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 08:43:09.900  5774  5774 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 08:43:09.900  5774  5774 I bt_bluedroid: get_profile_interface pan
09-27 08:43:09.901  5774  5790 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-27 08:43:09.901  5646  5646 D PanProfile: Bluetooth service connected
09-27 08:43:09.903  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:09.904  5774  5774 D BluetoothMapService: Received start request. Starting profile...
,09-27 08:43:09.904  5774  5774 D BluetoothMapService: start()
09-27 08:43:09.907  5774  5774 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-27 08:43:09.907  5774  5774 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 08:43:09.907  5774  5774 D BluetoothMapAppObserver: createReceiver()
09-27 08:43:09.909  5774  5774 D BluetoothMapAppObserver: initObservers()
09-27 08:43:09.909  5774  5774 D BluetoothMapAppObserver: getEnabledAccountItems()
09-27 08:43:09.912  5646  5646 D BluetoothMap: Proxy object connected
09-27 08:43:09.913  5646  5646 D MapProfile: Bluetooth service connected
09-27 08:43:09.913  5646  5646 D BluetoothMap: getConnectedDevices()
09-27 08:43:09.913  5646  5646 D BluetoothMap: Bluetooth is Not enabled
,09-27 08:43:09.916  5774  5774 V SapService: SapBinder()
,09-27 08:43:09.917  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:09.917  5774  5774 D SapService: Received start request. Starting profile...
09-27 08:43:09.917  5774  5774 V SapService: start()
,09-27 08:43:09.919  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.919  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.919  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.919  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:43:09.919  5774  5803 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.920  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.921  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:09.922  5774  5774 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:09.922  5774  5774 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:09.922  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:09.922  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:09.922  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-27 08:43:09.922  5774  5786 D BluetoothAdapterProperties: ScanMode =  20
09-27 08:43:09.923  5774  5786 D BluetoothAdapterProperties: State =  11
09-27 08:43:09.925  5774  5790 D BluetoothAdapterProperties: Scan Mode:21
09-27 08:43:09.927  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.928  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.925  5774  5786 D BluetoothAdapterProperties: Setting state to 12
09-27 08:43:09.929  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 08:43:09.929  5774  5790 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 08:43:09.929  5774  5786 I BluetoothAdapterState: Entering OnState
09-27 08:43:09.929  5646  5656 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 08:43:09.930  3076  3329 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:09.931  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:43:09.931   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:43:09.931  3076  3088 D BluetoothPan: onBluetoothStateChange on: true
09-27 08:43:09.932   927   927 D BluetoothA2dp: Proxy object connected
09-27 08:43:09.933  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:09.933  5646  5658 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:43:09.933  3076  3076 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 08:43:09.933  3076  3076 D PanProfile: Bluetooth service connected
09-27 08:43:09.934  3076  3088 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 08:43:09.935  5774  5774 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 08:43:09.935   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:09.935  3076  3092 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 08:43:09.935  5774  5774 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 08:43:09.937  5774  5774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:43:09.937  3076  3076 D BluetoothInputDevice: Proxy object connected
,09-27 08:43:09.937  3076  3076 D HidProfile: Bluetooth service connected
09-27 08:43:09.937  3788  3822 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:09.937   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:09.937  3076  3088 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:43:09.939  5774  5774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:43:09.939  3076  3076 D BluetoothMap: Proxy object connected
09-27 08:43:09.939  3076  3076 D MapProfile: Bluetooth service connected
,09-27 08:43:09.939  3076  3329 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:43:09.939  3076  3076 D BluetoothMap: getConnectedDevices()
09-27 08:43:09.940  5774  5774 D ObexServerSockets: Succeed to create listening sockets 
09-27 08:43:09.940  5774  5774 D ObexServerSockets0: startAccept()
09-27 08:43:09.940  5774  5774 D ObexServerSockets0: prepareForNewConnect()
09-27 08:43:09.941   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:09.941  3076  3076 D BluetoothA2dp: Proxy object connected
09-27 08:43:09.941  5646  5656 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 08:43:09.942  5646  5658 D BluetoothPan: onBluetoothStateChange on: true
09-27 08:43:09.943   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 08:43:09.946  5774  5774 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 08:43:09.946  5774  5774 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 08:43:09.946  5774  5812 D ObexServerSockets0: Accepting socket connection...
,09-27 08:43:09.947  5774  5774 D BluetoothMapService: onReceive
,09-27 08:43:09.947  5774  5774 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 08:43:09.947  5774  5774 D BluetoothMapService: STATE_ON
09-27 08:43:09.948  5774  5813 D ObexServerSockets0: Accepting socket connection...
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:09.949  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:09.949  5646  5646 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-27 08:43:09.951  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:09.951  5774  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:43:09.954  5774  5815 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 08:43:09.954  5774  5815 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 08:43:09.955  5646  5646 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:09.955  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:09.958  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:09.959  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:09.964  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:43:09.966  5646  5646 D BluetoothA2dp: Proxy object connected
,09-27 08:43:09.968  5774  5774 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 08:43:09.968  5774  5774 D ObexServerSockets0: prepareForNewConnect()
,09-27 08:43:09.971  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:43:09.979  3076  3076 D BluetoothPbap: Proxy object connected
,09-27 08:43:09.979  3076  3076 D PbapServerProfile: Bluetooth service connected
,09-27 08:43:09.982  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,09-27 08:43:09.982  5646  5646 D BluetoothPbap: Proxy object connected
09-27 08:43:09.983  5646  5646 D PbapServerProfile: Bluetooth service connected
,09-27 08:43:09.988  5774  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:43:10.001  5774  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:43:10.003  5774  5823 I BtOppRfcommListener: Accept thread started.
,09-27 08:43:10.031   927   927 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.032  3076  3329 D BluetoothHeadset: Proxy object connected
09-27 08:43:10.032  3076  3076 D HeadsetProfile: Bluetooth service connected
09-27 08:43:10.032   927   927 D BluetoothHeadset: Proxy object connected
09-27 08:43:10.032   927   927 D BluetoothHeadset: Proxy object connected
09-27 08:43:10.032  3788  3996 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.036   927   944 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.038  3788  3808 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.038   927   944 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.041   927   944 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.061  5646  5658 D BluetoothHeadset: Proxy object connected
,09-27 08:43:10.062  5646  5646 D HeadsetProfile: Bluetooth service connected
,09-27 08:43:10.078   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:11.080   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 08:43:11.685   927  2934 D ConnectivityService: handlePromptUnvalidated 101
,09-27 08:43:13.869  5774  5786 D BluetoothAdapterState: Current state: ON, message: 23
,09-27 08:43:13.869  5774  5786 D BluetoothAdapterProperties: Setting state to 13
,09-27 08:43:13.869  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 08:43:13.870  5774  5786 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 08:43:13.872  5774  5786 I BluetoothAdapterState: Entering PendingCommandState
09-27 08:43:13.874  5774  5774 D BluetoothMapService: onReceive
09-27 08:43:13.875  5774  5774 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-27 08:43:13.875  5774  5774 D BluetoothMapService: STATE_TURNING_OFF
09-27 08:43:13.876  5774  5774 D BluetoothMapService: MAP Service closeService in
09-27 08:43:13.876  5774  5774 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 08:43:13.876  5774  5774 D ObexServerSockets0: shutdown(block = true)
,09-27 08:43:13.878  5774  5774 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:43:13.878  5774  5812 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-27 08:43:13.878  5774  5813 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 08:43:13.880  5774  5774 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:43:13.879  5774  5799 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 08:43:13.884  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:13.885  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:13.885  5774  5790 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:43:13.886  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 08:43:13.886  5774  5774 I BtOppRfcommListener: stopping Accept Thread
09-27 08:43:13.886  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 08:43:13.887  5774  5823 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 08:43:13.888  5774  5823 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 08:43:13.889  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:13.889  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:13.892  5774  5774 D HeadsetService: Received stop request...Stopping profile...
,09-27 08:43:13.894  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:13.894  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:13.897  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:13.897  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:13.903  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:13.903  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:43:13.904  5593  5593 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:43:13.904  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:13.906   927   927 D BluetoothHeadset: Proxy object disconnected
,09-27 08:43:13.907  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:13.908  3076  3092 D BluetoothHeadset: Proxy object disconnected
09-27 08:43:13.908   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 08:43:13.908   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 08:43:13.908  3788  3822 D BluetoothHeadset: Proxy object disconnected
09-27 08:43:13.909  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:13.909  5646  5646 D DockEventReceiver: finishStartingService: stopping service
09-27 08:43:13.910  5646  5658 D BluetoothHeadset: Proxy object disconnected
09-27 08:43:13.910  5774  5774 D A2dpService: Received stop request...Stopping profile...
09-27 08:43:13.910  5774  5805 D A2dpStateMachine: Exit Disconnected: -1
09-27 08:43:13.911  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:13.912   927   927 D BluetoothA2dp: Proxy object disconnected
09-27 08:43:13.912  5646  5646 D HeadsetProfile: Bluetooth service disconnected
09-27 08:43:13.912  5774  5774 V BluetoothAdapterState: isTurningOff()=true
09-27 08:43:13.913  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.913  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.913  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:13.913  5774  5774 D HidService: Received stop request...Stopping profile...
09-27 08:43:13.913  5774  5774 D HidService: Stopping Bluetooth HidService
09-27 08:43:13.914  3076  3076 D HeadsetProfile: Bluetooth service disconnected
09-27 08:43:13.914  3076  3076 D BluetoothA2dp: Proxy object disconnected
09-27 08:43:13.915  5646  5646 D BluetoothA2dp: Proxy object disconnected
09-27 08:43:13.915  3076  3076 D BluetoothInputDevice: Proxy object disconnected
09-27 08:43:13.916  3076  3076 D HidProfile: Bluetooth service disconnected
09-27 08:43:13.916  5646  5646 D BluetoothInputDevice: Proxy object disconnected
09-27 08:43:13.916  5646  5646 D HidProfile: Bluetooth service disconnected
09-27 08:43:13.916  5774  5774 D HealthService: Received stop request...Stopping profile...
09-27 08:43:13.918  5774  5774 D PanService: Received stop request...Stopping profile...
09-27 08:43:13.919  3076  3076 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 08:43:13.919  3076  3076 D PanProfile: Bluetooth service disconnected
,09-27 08:43:13.923  5646  5646 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-27 08:43:13.923  5646  5646 D PanProfile: Bluetooth service disconnected
09-27 08:43:13.923  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:43:13.924  5774  5774 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 08:43:13.924  5774  5774 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 08:43:13.924  5774  5797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:43:13.924  5774  5797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:43:13.924  5774  5797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:43:13.924  5774  5774 D BluetoothMapService: Received stop request...Stopping profile...
09-27 08:43:13.925  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-27 08:43:13.925  5774  5774 D BluetoothMapService: stop()
,09-27 08:43:13.925  5774  5790 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 08:43:13.928  5774  5774 D BluetoothMapAppObserver: deinitObservers()
09-27 08:43:13.928  5774  5774 D BluetoothMapAppObserver: removeReceiver()
09-27 08:43:13.929  3076  3076 D BluetoothMap: Proxy object disconnected
09-27 08:43:13.929  3076  3076 D MapProfile: Bluetooth service disconnected
,09-27 08:43:13.932  5646  5646 D BluetoothMap: Proxy object disconnected
,09-27 08:43:13.932  5774  5774 D SapService: Received stop request...Stopping profile...
09-27 08:43:13.933  5774  5774 V SapService: stop()
09-27 08:43:13.933  5646  5646 D MapProfile: Bluetooth service disconnected
,09-27 08:43:13.934  5774  5774 V BluetoothAdapterState: isTurningOff()=true
,09-27 08:43:13.934  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.934  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.934  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:43:13.935  5774  5797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:43:13.936  5774  5797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isTurningOff()=true
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:13.936  5774  5774 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 08:43:13.936  5774  5774 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isTurningOff()=true
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.936  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:13.936  5774  5774 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 08:43:13.936  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 08:43:13.936  5774  5797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:43:13.937  5774  5797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 08:43:13.937  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 08:43:13.937  5774  5797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:43:13.937  5774  5797 W bt_l2cap: btif_in_execute_service_request: Unknown service
09-27 08:43:13.937  5774  5790 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-27 08:43:13.939  5774  5774 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 08:43:13.939  5774  5774 V BluetoothAdapterState: isTurningOff()=true
09-27 08:43:13.939  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.939  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.939  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:13.939  5774  5774 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 08:43:13.940  5774  5774 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-27 08:43:13.941  3076  3076 D BluetoothPbap: Proxy object disconnected
09-27 08:43:13.942  3076  3076 D PbapServerProfile: Bluetooth service disconnected
09-27 08:43:13.942  5774  5774 D BluetoothMapService: MAP Service closeService in
09-27 08:43:13.942  5774  5774 V BluetoothAdapterState: isTurningOff()=true
09-27 08:43:13.942  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.942  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.942  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:13.942  5774  5774 D BluetoothMapService: cleanup()
09-27 08:43:13.942  5774  5774 D BluetoothMapService: MAP Service closeService in
,09-27 08:43:13.943  5774  5774 V BluetoothAdapterState: isTurningOff()=true
09-27 08:43:13.943  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:13.943  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:13.943  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:13.943  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 08:43:13.943  5774  5786 D BluetoothAdapterProperties: Setting state to 15
09-27 08:43:13.943  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 08:43:13.943  5774  5786 I BluetoothAdapterState: Entering BleOnState
09-27 08:43:13.944  5646  5656 D BluetoothPbap: onBluetoothStateChange: up=false
,09-27 08:43:13.944  3076  3329 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 08:43:13.944   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:43:13.945  3076  3092 D BluetoothPan: onBluetoothStateChange on: false
09-27 08:43:13.945  5646  5658 D BluetoothMap: onBluetoothStateChange: up=false
09-27 08:43:13.946  5646  5656 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-27 08:43:13.946  3076  3088 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 08:43:13.947   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:43:13.947  3076  3329 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 08:43:13.947  3788  3996 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:43:13.947   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:43:13.948  3076  3092 D BluetoothMap: onBluetoothStateChange: up=false
09-27 08:43:13.948  3076  3088 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-27 08:43:13.949   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:43:13.949  5646  5658 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:43:13.949  5646  5656 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 08:43:13.950  5646  5658 D BluetoothPan: onBluetoothStateChange on: false
09-27 08:43:13.950  5774  5786 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 08:43:13.950  5774  5786 D BluetoothAdapterProperties: Setting state to 16
09-27 08:43:13.950  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 08:43:13.951  5774  5786 D BluetoothAdapterProperties: onBleDisable
09-27 08:43:13.951  5774  5786 I BluetoothAdapterState: Entering PendingCommandState
09-27 08:43:13.951  5774  5787 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 08:43:13.952  5774  5797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 08:43:13.953  5774  5797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:43:13.953  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:13.954  5774  5790 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:43:13.954  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 08:43:13.956  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:13.960  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:13.962  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:43:13.962  5646  5646 D DockEventReceiver: finishStartingService: stopping service
09-27 08:43:13.963  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:13.965  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:13.966  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:14.165  5774  5790 I bt_hci  : shut_down
,09-27 08:43:14.174  5774  5794 D bt_hwcfg: hw_epilog_process
,09-27 08:43:14.175  5774  5794 I bt_vendor: low_power_mode_cb
,09-27 08:43:14.178  5774  5794 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-27 08:43:14.178  5774  5794 I bt_vendor: epilog_cb
09-27 08:43:14.178  5774  5794 I bt_hci  : epilog_finished_callback
,09-27 08:43:14.184  5774  5790 I bt_hci_h4: hal_close
,09-27 08:43:14.185  5774  5790 I bt_userial_vendor: device fd = 54 close
,09-27 08:43:14.305  5774  5787 D bt_stack_manager: event_shut_down_stack finished.
,09-27 08:43:14.305  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 08:43:14.309  5774  5786 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-27 08:43:14.310  5774  5774 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:43:14.310  5774  5774 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 08:43:14.311  5774  5774 D BtGatt.GattService: stop()
,09-27 08:43:14.311  5774  5774 D BtGatt.AdvertiseManager: advertise clients cleared
,09-27 08:43:14.314  5774  5774 V BluetoothAdapterState: isTurningOff()=false
,09-27 08:43:14.314  5774  5774 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:14.314  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:14.314  5774  5774 V BluetoothAdapterState: isBleTurningOff()=true
,09-27 08:43:14.315  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-27 08:43:14.315  5774  5786 D BluetoothAdapterProperties: Setting state to 10
09-27 08:43:14.316  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 08:43:14.317  5774  5786 I BluetoothAdapterState: Entering OffState
09-27 08:43:14.318   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-27 08:43:14.332  5774  5774 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 08:43:14.333  5774  5774 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 08:43:14.333  5774  5787 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-27 08:43:14.337  5774  5774 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-27 08:43:14.342  5774  5774 I art     : System.exit called, status: 0
,09-27 08:43:14.344  5774  5774 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 08:43:14.372   927  3773 I ActivityManager: Process com.android.bluetooth (pid 5774) has died
,09-27 08:43:18.866  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:43:18.867  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:18.871  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:43:18.871  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20d09be removed from the list
09-27 08:43:18.871  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:43:18.871  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:18.871  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:18.874  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 08:43:18.874  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@94d616c added. We now have 4 listener(s)
09-27 08:43:18.874  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:43:18.876  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:18.876  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@94d616c removed from the list
09-27 08:43:18.876  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:43:18.876  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:18.876  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:18.878  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:43:18.878  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f299335 added. We now have 4 listener(s)
,09-27 08:43:18.878  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:43:23.887  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:23.908   927   944 I ActivityManager: Start proc 5831:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 08:43:23.979  5831  5831 D AdapterServiceConfig: Adding HeadsetService
,09-27 08:43:23.979  5831  5831 D AdapterServiceConfig: Adding A2dpService
09-27 08:43:23.980  5831  5831 D AdapterServiceConfig: Adding HidService
09-27 08:43:23.980  5831  5831 D AdapterServiceConfig: Adding HealthService
09-27 08:43:23.980  5831  5831 D AdapterServiceConfig: Adding PanService
09-27 08:43:23.980  5831  5831 D AdapterServiceConfig: Adding GattService
09-27 08:43:23.980  5831  5831 D AdapterServiceConfig: Adding BluetoothMapService
09-27 08:43:23.981  5831  5831 D AdapterServiceConfig: Adding SapService
,09-27 08:43:23.993   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d613cf:true
,09-27 08:43:23.993  5831  5831 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 08:43:23.996  5831  5831 I bt_bluedroid: init
,09-27 08:43:23.997  5831  5843 I BluetoothAdapterState: Entering OffState
,09-27 08:43:24.000  5831  5844 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-27 08:43:24.000  5831  5844 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 08:43:24.000  5831  5844 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 08:43:24.000  5831  5844 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-27 08:43:24.001  5831  5831 I bt_bluedroid: get_profile_interface socket
,09-27 08:43:24.002  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 08:43:24.003  5831  5831 I bt_bluedroid: get_profile_interface sdp
09-27 08:43:24.004  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 08:43:24.008  5831  5842 I bt_bluedroid: config_hci_snoop_log
,09-27 08:43:24.009   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 08:43:24.014  5831  5843 D BluetoothAdapterState: Current state: OFF, message: 0
09-27 08:43:24.014  5831  5843 D BluetoothAdapterProperties: Setting state to 14
09-27 08:43:24.014  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 08:43:24.015  5831  5843 D BluetoothBondStateMachine: make
,09-27 08:43:24.018  5831  5848 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 08:43:24.021  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:43:24.022  5831  5831 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 08:43:24.024  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:24.025  5831  5831 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:43:24.026  5831  5831 D BtGatt.GattService: Received start request. Starting profile...
,09-27 08:43:24.026  5831  5831 D BtGatt.GattService: start()
09-27 08:43:24.026  5831  5831 I bt_bluedroid: get_profile_interface gatt
09-27 08:43:24.027  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:24.027  5831  5831 D BtGatt.AdvertiseManager: advertise manager created
,09-27 08:43:24.033  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:24.033  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-27 08:43:24.033  5831  5831 V BluetoothAdapterState: isBleTurningOn()=true
,09-27 08:43:24.034  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:24.034  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 08:43:24.036  5831  5843 I bt_bluedroid: bt_bluedroid
,09-27 08:43:24.036  5831  5844 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-27 08:43:24.036  5831  5844 I bt_hci  : start_up
,09-27 08:43:24.041  5831  5844 I bt_vendor: alloc value 0xf4215871
09-27 08:43:24.042  5831  5844 I bt_vendor: init
09-27 08:43:24.042  5831  5844 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 08:43:24.042  5831  5844 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 08:43:24.150  5831  5844 D bt_hci  : start_up starting async portion
,09-27 08:43:24.150  5831  5851 I bt_hci  : event_finish_startup
,09-27 08:43:24.151  5831  5851 I bt_hci_h4: hal_open
09-27 08:43:24.151  5831  5851 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-27 08:43:24.151  5852  5852 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-27 08:43:24.153  5831  5851 I bt_userial_vendor: device fd = 54 open
,09-27 08:43:24.170  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:43:24.173  5831  5851 D bt_hwcfg: Chipset BCM4358A3
,09-27 08:43:24.173  5831  5851 D bt_hwcfg: Target name = [BCM4358A3]
09-27 08:43:24.173  5831  5851 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 08:43:24.678  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 08:43:24.679  5831  5851 D bt_hwcfg: Settlement delay -- 100 ms
09-27 08:43:24.679  5831  5851 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 08:43:24.813  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:43:24.814  5831  5851 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-27 08:43:24.816  5831  5851 I bt_hwcfg: vendor lib fwcfg completed
09-27 08:43:24.816  5831  5851 I bt_vendor: firmware callback
09-27 08:43:24.816  5831  5851 I bt_hci  : firmware_config_callback
,09-27 08:43:24.824  5831  5854 I bt_btu  : btu_task pending for preload complete event
09-27 08:43:24.824  5831  5854 I bt_btu_task: Bluetooth chip preload is complete
09-27 08:43:24.824  5831  5854 I bt_btu  : btu_task received preload complete event
,09-27 08:43:24.830  5831  5854 I         : BTE_InitTraceLevels -- TRC_HCI
09-27 08:43:24.830  5831  5854 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-27 08:43:24.830  5831  5854 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 08:43:24.830  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 08:43:24.830  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-27 08:43:24.830  5831  5854 I         : BTE_InitTraceLevels -- TRC_A2D
09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTM
,09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_GAP
,09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_GATT
,09-27 08:43:24.831  5831  5854 I         : BTE_InitTraceLevels -- TRC_SMP
,09-27 08:43:24.853  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 08:43:24.853  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 08:43:24.960  5831  5854 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4193549
,09-27 08:43:24.961  5831  5854 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4193549 
,09-27 08:43:24.980  5831  5847 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 08:43:24.985  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 08:43:24.985  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 08:43:24.988  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 08:43:24.991  5831  5847 D BluetoothAdapterProperties: Scan Mode:20
,09-27 08:43:24.991  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-27 08:43:24.991  5831  5847 D bt_hci  : do_postload posting postload work item
09-27 08:43:24.992  5831  5851 I bt_hci  : event_postload
09-27 08:43:24.992  5831  5851 I bt_vendor: sco_config_cb
,09-27 08:43:24.992  5831  5851 I bt_hci  : sco_config_callback postload finished.
09-27 08:43:24.996  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:24.996  5831  5847 D bt_bte_conf: Device ID record 1 : primary
09-27 08:43:24.997  5831  5847 D bt_bte_conf:   vendorId            = 000f
,09-27 08:43:24.997  5831  5847 D bt_bte_conf:   vendorIdSource      = 0001
09-27 08:43:24.997  5831  5847 D bt_bte_conf:   product             = 1200
09-27 08:43:24.997  5831  5847 D bt_bte_conf:   version             = 1436
09-27 08:43:24.997  5831  5847 D bt_bte_conf:   clientExecutableURL = 
09-27 08:43:24.997  5831  5847 D bt_bte_conf:   serviceDescription  = 
09-27 08:43:24.997  5831  5847 D bt_bte_conf:   documentationURL    = 
09-27 08:43:24.998  5831  5847 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 08:43:24.998  5831  5844 D bt_stack_manager: event_start_up_stack finished
09-27 08:43:25.000  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 08:43:25.000  5831  5843 D BluetoothAdapterProperties: Setting state to 15
09-27 08:43:25.000  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:25.000  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 08:43:25.003  5831  5843 I BluetoothAdapterState: Entering BleOnState
,09-27 08:43:25.009  5831  5851 I bt_vendor: low_power_mode_cb
09-27 08:43:25.010  5831  5843 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 08:43:25.010  5831  5843 D BluetoothAdapterProperties: Setting state to 11
09-27 08:43:25.010  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 08:43:25.017  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:25.024  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:25.024  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:25.024  5831  5831 D HeadsetService: Received start request. Starting profile...
09-27 08:43:25.027  5831  5831 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 08:43:25.028  5831  5831 D HeadsetStateMachine: make
09-27 08:43:25.031  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:43:25.048  5831  5831 D HeadsetStateMachine: max_hf_connections = 1
,09-27 08:43:25.049  5831  5831 I bt_bluedroid: get_profile_interface handsfree
09-27 08:43:25.049  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 08:43:25.049  5831  5847 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-27 08:43:25.054  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:25.055  5831  5831 D A2dpService: Received start request. Starting profile...
09-27 08:43:25.055  5831  5831 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 08:43:25.056  5831  5831 I bt_bluedroid: get_profile_interface avrcp
,09-27 08:43:25.063  5831  5831 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 08:43:25.064  5831  5831 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 08:43:25.064  5831  5831 D A2dpStateMachine: make
,09-27 08:43:25.066  5831  5831 I bt_bluedroid: get_profile_interface a2dp
,09-27 08:43:25.067  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 08:43:25.069  5831  5863 D A2dpStateMachine: Enter Disconnected: -2
,09-27 08:43:25.070  5831  5831 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 08:43:25.071  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:25.072  5831  5831 D HidService: Received start request. Starting profile...
09-27 08:43:25.073  5831  5831 I bt_bluedroid: get_profile_interface hidhost
,09-27 08:43:25.073  5831  5831 D HidService: setHidService(): set to: null
09-27 08:43:25.074  5831  5831 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 08:43:25.074  5831  5847 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf417456d
09-27 08:43:25.074  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 08:43:25.074  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:43:25.075  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:25.075  5831  5831 D HealthService: Received start request. Starting profile...
,09-27 08:43:25.078  5831  5831 I bt_bluedroid: get_profile_interface health
,09-27 08:43:25.080  5831  5831 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 08:43:25.080  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:25.081  5831  5831 D PanService: Received start request. Starting profile...
09-27 08:43:25.082  5831  5831 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 08:43:25.082  5831  5831 I bt_bluedroid: get_profile_interface pan
,09-27 08:43:25.083  5831  5847 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 08:43:25.084  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:25.086  5831  5831 D BluetoothMapService: Received start request. Starting profile...
09-27 08:43:25.086  5831  5831 D BluetoothMapService: start()
09-27 08:43:25.088  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 08:43:25.089  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 08:43:25.089  5831  5831 D BluetoothMapAppObserver: createReceiver()
09-27 08:43:25.091  5831  5831 D BluetoothMapAppObserver: initObservers()
09-27 08:43:25.091  5831  5831 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 08:43:25.101  5831  5831 V SapService: SapBinder()
09-27 08:43:25.101  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
,09-27 08:43:25.102  5831  5831 D SapService: Received start request. Starting profile...
,09-27 08:43:25.102  5831  5831 V SapService: start()
,09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOff()=false
,09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOn()=true
,09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:25.107  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:25.108  5831  5861 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 08:43:25.108  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:43:25.109  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 08:43:25.109  5831  5843 D BluetoothAdapterProperties: ScanMode =  20
09-27 08:43:25.109  5831  5843 D BluetoothAdapterProperties: State =  11
09-27 08:43:25.111  5831  5847 D BluetoothAdapterProperties: Scan Mode:21
09-27 08:43:25.111  5831  5843 D BluetoothAdapterProperties: Setting state to 12
09-27 08:43:25.111  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 08:43:25.111  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 08:43:25.111  5831  5843 I BluetoothAdapterState: Entering OnState
09-27 08:43:25.111  5646  5658 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 08:43:25.113  3076  3088 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 08:43:25.114   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:43:25.114  3076  3092 D BluetoothPan: onBluetoothStateChange on: true
09-27 08:43:25.115   927   927 D BluetoothA2dp: Proxy object connected
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:25.116  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:25.116  5646  5656 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:43:25.117  3076  3076 D BluetoothPan: BluetoothPAN Proxy object connected
,09-27 08:43:25.117  3076  3076 D PanProfile: Bluetooth service connected
09-27 08:43:25.118  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 08:43:25.118  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:25.118  5646  5658 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:43:25.118  5831  5831 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 08:43:25.119  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:43:25.120  3076  3088 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 08:43:25.121  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:25.121  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:43:25.121   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:25.122  3076  3092 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 08:43:25.122  5831  5831 D ObexServerSockets: Succeed to create listening sockets 
,09-27 08:43:25.122  5831  5831 D ObexServerSockets0: startAccept()
09-27 08:43:25.122  5831  5831 D ObexServerSockets0: prepareForNewConnect()
09-27 08:43:25.122  5646  5646 D BluetoothA2dp: Proxy object connected
09-27 08:43:25.123  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:43:25.124  3788  3808 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:25.124  5831  5831 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 08:43:25.124  5831  5831 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 08:43:25.124   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:25.125  3076  3329 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:43:25.125  5831  5870 D ObexServerSockets0: Accepting socket connection...
09-27 08:43:25.125  5831  5871 D ObexServerSockets0: Accepting socket connection...
09-27 08:43:25.125  3076  3076 D BluetoothInputDevice: Proxy object connected
09-27 08:43:25.126  3076  3076 D HidProfile: Bluetooth service connected
09-27 08:43:25.126  3076  3329 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:43:25.127  3076  3076 D BluetoothMap: Proxy object connected
,09-27 08:43:25.127  5646  5646 D BluetoothMap: Proxy object connected
09-27 08:43:25.127  3076  3076 D MapProfile: Bluetooth service connected
09-27 08:43:25.127  5646  5646 D MapProfile: Bluetooth service connected
09-27 08:43:25.127  3076  3076 D BluetoothMap: getConnectedDevices()
09-27 08:43:25.127  5646  5646 D BluetoothMap: getConnectedDevices()
09-27 08:43:25.128   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:25.128  5646  5658 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:43:25.129  5646  5656 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 08:43:25.129  3076  3076 D BluetoothA2dp: Proxy object connected
09-27 08:43:25.131  5646  5658 D BluetoothPan: onBluetoothStateChange on: true
,09-27 08:43:25.132  5646  5646 D BluetoothInputDevice: Proxy object connected
,09-27 08:43:25.132  5646  5646 D HidProfile: Bluetooth service connected
09-27 08:43:25.134   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 08:43:25.134  5831  5831 D BluetoothMapService: onReceive
09-27 08:43:25.134  5831  5831 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 08:43:25.135  5831  5831 D BluetoothMapService: STATE_ON
,09-27 08:43:25.136  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:25.136  5646  5646 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 08:43:25.136  5646  5646 D PanProfile: Bluetooth service connected
09-27 08:43:25.137  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:25.137  5831  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:43:25.138  5831  5872 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 08:43:25.138  5831  5872 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 08:43:25.140  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:43:25.145  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:43:25.146  5646  5646 D DockEventReceiver: finishStartingService: stopping service
,09-27 08:43:25.149  5646  5646 D BluetoothPbap: Proxy object connected
09-27 08:43:25.150  5646  5646 D PbapServerProfile: Bluetooth service connected
09-27 08:43:25.151  5831  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:43:25.152  3076  3076 D BluetoothPbap: Proxy object connected
09-27 08:43:25.152  3076  3076 D PbapServerProfile: Bluetooth service connected
,09-27 08:43:25.164  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-27 08:43:25.164  5831  5831 D ObexServerSockets0: prepareForNewConnect()
,09-27 08:43:25.168  5831  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:43:25.170  5831  5880 I BtOppRfcommListener: Accept thread started.
,09-27 08:43:25.215   927   927 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.215  3076  3329 D BluetoothHeadset: Proxy object connected
09-27 08:43:25.216  3076  3076 D HeadsetProfile: Bluetooth service connected
09-27 08:43:25.216   927   927 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.216   927   927 D BluetoothHeadset: Proxy object connected
09-27 08:43:25.216  3788  3822 D BluetoothHeadset: Proxy object connected
09-27 08:43:25.217  5646  5869 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.220  5646  5646 D HeadsetProfile: Bluetooth service connected
,09-27 08:43:25.221   927   944 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.225  3788  3996 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.225   927   944 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.227   927   944 D BluetoothHeadset: Proxy object connected
,09-27 08:43:25.229  5646  5658 D BluetoothHeadset: Proxy object connected
09-27 08:43:25.230  5646  5646 D HeadsetProfile: Bluetooth service connected
,09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:28.904  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:43:28.909  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:28.910  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:28.910  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f299335 removed from the list
09-27 08:43:28.910  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:43:28.910  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:43:28.911  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:28.913  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:43:28.913  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8c03ca added. We now have 4 listener(s)
09-27 08:43:28.913  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:43:28.916   927   937 D WifiService: setWifiEnabled: false pid=5593, uid=10077
09-27 08:43:28.917   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:43:31.081   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:32.082   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:33.084   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:33.927  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:33.927   927  3760 D WifiService: setWifiEnabled: true pid=5593, uid=10077
,09-27 08:43:33.928   927  3760 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 08:43:33.935   506   923 D SoftapController: Softap fwReload - Ok
,09-27 08:43:33.942   506   923 D CommandListener: Setting iface cfg
09-27 08:43:33.943   506   923 D CommandListener: Trying to bring down wlan0
,09-27 08:43:33.945   506   923 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:43:33.950   927  2932 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 08:43:34.086   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:34.618   927  2932 D wifi    : set interface wlan0 flags (UP)
09-27 08:43:34.619   927  2932 I WifiHAL : Initializing wifi
,09-27 08:43:34.619   927  2932 I WifiHAL : Creating socket
,09-27 08:43:34.625   927  2932 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 08:43:34.626   927  2932 D wifi    : Did set static halHandle = 0x7f707dee00
09-27 08:43:34.626   927  2932 D wifi    : halHandle = 0x7f707dee00, mVM = 0x7f8ce0d140, mCls = 0x178a
,09-27 08:43:34.627   927  2932 D wifi    : array field set
,09-27 08:43:34.627   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-27 08:43:34.628   927  2932 I WifiNative-HAL: interface[0] = wlan0
09-27 08:43:34.634   927  5885 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547348147712
,09-27 08:43:34.634   927  5885 D wifi    : waitForHalEvents called, vm = 0x7f8ce0d140, obj = 0x178a, env = 0x7f6e1b4b80
09-27 08:43:34.637   927  2932 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-27 08:43:34.640   927  2932 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-27 08:43:34.645  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:34.650  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:34.691  5886  5886 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 08:43:34.711  5886  5886 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:43:34.744  5886  5886 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:43:34.744  5886  5886 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 08:43:35.087   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:43:35.656   927  2932 D WifiConfigStore: Loading config and enabling all networks 
,09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:35.663  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:43:35.666  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:35.672  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:43:35.674   927  2932 D WifiConfigStore: loaded 0 passpoint configs
09-27 08:43:35.675   927  2932 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 08:43:35.675   927  2932 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 08:43:35.676  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:35.676   927  2932 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-27 08:43:35.678   927  2932 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-27 08:43:35.678   927  2932 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 08:43:35.678   927  2932 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 08:43:35.678   927  2932 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 08:43:35.683   927  2932 D WifiNative-HAL: Setting external_sim to 1
,09-27 08:43:35.683   927  2932 D wifi    : setting dfs flag to true, 0x7f74368420
09-27 08:43:35.683  4984  4984 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:43:35.684   927  2932 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 08:43:35.684   927  2932 D wifi    : setting scan oui 0x7f74368420
09-27 08:43:35.684   927  2932 D WifiHAL : Sending mac address OUI
,09-27 08:43:35.689   927  2932 E native  : do suspend false
,09-27 08:43:35.700   927  2932 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-27 08:43:35.700   506   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 08:43:35.701   927   927 D RttService: SCAN_AVAILABLE : 3
09-27 08:43:35.701   927  3042 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 08:43:35.702   506   923 D CommandListener: Setting iface cfg
,09-27 08:43:35.707   927  2925 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-27 08:43:35.707   927  2925 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 08:43:35.712   927  2925 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 08:43:35.712   927  2925 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 08:43:35.752   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304140 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=44 mControllerEnergyUsed=167 }
,09-27 08:43:36.088   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 08:43:38.893  5886  5886 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-27 08:43:38.897  5886  5886 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:38.902  5886  5886 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:38.907  5886  5886 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:38.911  5886  5886 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:43:38.942  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:43:38.945  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:43:38.945  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:38.945  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8c03ca removed from the list
09-27 08:43:38.945  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:43:38.945  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:38.946  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:38.950  5593  5888 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-27 08:43:38.951  5593  5888 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 08:43:38.965   927  2932 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 08:43:38.966   927  2932 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-27 08:43:38.966   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:43:38.976   927  2932 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 08:43:39.016   927  2932 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 08:43:39.018  5886  5886 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 08:43:39.768  5886  5886 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 08:43:39.802  5886  5886 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 08:43:39.803  5886  5886 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 08:43:39.811   927  2932 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-27 08:43:39.811   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 08:43:39.811   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 08:43:39.831   927  2932 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:43:39.847   506   923 D CommandListener: Setting iface cfg
,09-27 08:43:39.855   927  2932 D WifiStateMachine: Start Dhcp Watchdog 3
,09-27 08:43:39.863   927  5892 D DhcpClient: Receive thread started
,09-27 08:43:39.869   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:43:39.869   927  2932 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 08:43:39.869   927  2934 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-27 08:43:39.959   927  2932 E native  : do suspend false
,09-27 08:43:39.982   927  5891 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 08:43:39.995   927  5892 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,09-27 08:43:39.997   927  5891 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,09-27 08:43:39.999   927  5891 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 08:43:40.024   927  5892 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 08:43:40.026   927  5891 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 08:43:40.029   506   923 D CommandListener: Setting iface cfg
,09-27 08:43:40.033   927  2932 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 08:43:40.040   927  5891 D DhcpClient: Scheduling renewal in 86399s
,09-27 08:43:40.052   927  2932 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-27 08:43:40.054   927  2932 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 08:43:40.055   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-27 08:43:40.057   927  2934 D ConnectivityService: Adding iface wlan0 to network 102
,09-27 08:43:40.068   927  2932 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 08:43:40.113   927  2934 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 08:43:40.115   927  2934 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-27 08:43:40.118   927  2934 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-27 08:43:40.121   927  2934 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-27 08:43:40.124   927  2934 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-27 08:43:40.131   927  2934 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:43:40.135   927  2934 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-27 08:43:40.135   927  2934 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-27 08:43:40.135   927  2934 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-27 08:43:40.136   927  2934 D ConnectivityService:    accepting network in place of null
09-27 08:43:40.136   927  2932 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 08:43:40.136   927  2932 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:43:40.136   927  2934 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 08:43:40.160   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:43:40.182   506   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:43:40.186   927  2934 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-27 08:43:40.187   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:43:40.187  3730  3868 W QCNEJ   : |CORE| network available: 102
,09-27 08:43:40.188   927  2934 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-27 08:43:40.190   927   944 D Tethering: MasterInitialState.processMessage what=3
09-27 08:43:40.190  3730  3868 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 08:43:40.191  3730  3868 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-27 08:43:40.192  3730  3868 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:40.197  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:43:40.200  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:43:40.202  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 08:43:40.202  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 08:43:40.202  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 08:43:40.202  5010  5033 E SarControlService: no key has been found,reset the power
09-27 08:43:40.202  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 08:43:40.202  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-27 08:43:40.203  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-27 08:43:40.203  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:43:40.203  5035  5035 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 08:43:40.205  5010  5047 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 08:43:40.205  5010  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:40.206  5593  5593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:43:40.210  5593  5593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:40.211  3689  3689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 08:43:40.212  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000f003000000000000ffffffff]
09-27 08:43:40.212  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 08:43:40.212  5035  5049 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-27 08:43:40.213  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:43:40.213  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 08:43:40.215  3689  3689 D SystemUpdateService: onCreate
09-27 08:43:40.216  5010  5047 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 08:43:40.217  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:43:40.217  5035  5035 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-27 08:43:40.220  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@402577b HexData = [00000000f103000000000000ffffffff]
09-27 08:43:40.220  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:43:40.220  5035  5049 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-27 08:43:40.221  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:43:40.221  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 08:43:40.222  3689  3689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 08:43:40.231  3689  3689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 08:43:40.235   927  5890 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 08:43:40.238  3689  5362 I iu.UploadsManager: num queued entries: 0
09-27 08:43:40.238  3689  5362 I iu.UploadsManager: num updated entries: 0
,09-27 08:43:40.238  3689  5362 I iu.SyncManager: NEXT; no task
09-27 08:43:40.239  3689  5902 I SystemUpdateService: active receiver: enabled
,09-27 08:43:40.240  3689  3689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 08:43:40.247  3689  3689 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-27 08:43:40.249  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:43:40.253  5365  5365 D SprintDMHelper: simOperator: 
,09-27 08:43:40.254  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 08:43:40.262  3689  5902 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 08:43:40.273  3689  5902 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-27 08:43:40.273  3689  5902 I SystemUpdateService: now status is 0 (complete)
09-27 08:43:40.273  3689  5902 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 08:43:40.273  3689  5902 I SystemUpdateService: file has been verified
09-27 08:43:40.274  3689  5902 I SystemUpdateService: OTA package size = 21989297
,09-27 08:43:40.291  3689  5902 I SystemUpdateService: showing system update notification
,09-27 08:43:40.299  3689  3689 D SystemUpdateService: onDestroy
,09-27 08:43:40.524   927  5889 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 08:43:40.610  4984  5907 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-27 08:43:40.611   927  5889 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 12:43:40 GMT], X-Android-Received-Millis=[1474980220608], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474980220573]}
,09-27 08:43:40.613   927  2934 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 08:43:40.614   927  2934 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-27 08:43:40.614   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-27 08:43:40.617   927  2934 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-27 08:43:41.963  5593  5914 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-27 08:43:41.963  5593  5888 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-27 08:43:41.964  5593  5888 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-27 08:43:41.964  5593  5914 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:43:41.965  5593  5888 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:43:41.965  5593  5914 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:43:41.966  5593  5914 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:43:41.966  5593  5888 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:43:41.971  5593  5888 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 08:43:41.971  5593  5914 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 08:43:41.971  5593  5916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender)
09-27 08:43:41.971  5593  5917 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender)
,09-27 08:43:41.974  5593  5918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver)
09-27 08:43:41.976  5593  5919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver)
09-27 08:43:41.976  5593  5918 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver)
09-27 08:43:41.976  5593  5918 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-27 08:43:41.976  5593  5918 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 08:43:41.977  5593  5919 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver)
09-27 08:43:41.978  5593  5919 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-27 08:43:41.978  5593  5919 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 08:43:42.890   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:43:44.957  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-27 08:43:44.958  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-27 08:43:44.965  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@407934f Bundle[{}]
,09-27 08:43:44.967  5593  5639 I io.jxcore.node.LifeCycleMonitor: start: OK
09-27 08:43:44.967  5593  5639 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-27 08:43:44.968  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-27 08:43:44.971  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-27 08:43:44.972  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-27 08:43:44.973  5593  5639 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-27 08:43:44.979  5593  5639 I System.out: Running OutgoingSocketThread
,09-27 08:43:44.981  5593  5920 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-27 08:43:44.981  5593  5920 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 08:43:47.992  5593  5920 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-27 08:43:47.993  5593  5920 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:43:47.993  5593  5921 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-27 08:43:47.993  5593  5921 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:43:47.993  5593  5920 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:43:47.993  5593  5921 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:43:47.995  5593  5921 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:43:47.995  5593  5920 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:43:48.001  5593  5921 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 08:43:48.001  5593  5920 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-27 08:43:48.004  5593  5924 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender)
,09-27 08:43:48.006  5593  5923 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender)
09-27 08:43:48.007  5593  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver)
09-27 08:43:48.008  5593  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver)
,09-27 08:43:48.009  5593  5926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver)
,09-27 08:43:48.009  5593  5926 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 08:43:48.009  5593  5925 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver)
09-27 08:43:48.010  5593  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 08:43:48.010  5593  5925 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 08:43:48.010  5593  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 08:43:48.141   927  2934 D ConnectivityService: handlePromptUnvalidated 102
,09-27 08:43:50.757   927  2932 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,09-27 08:43:50.991  5593  5639 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
09-27 08:43:50.992  5593  5639 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-27 08:43:50.992  5593  5639 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-27 08:43:50.998  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:43:50.998  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1593b added. We now have 3 listener(s)
,09-27 08:43:51.003  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:43:51.003  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 08:43:51.004  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:43:51.004  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:43:51.004  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8652858 added. We now have 4 listener(s)
09-27 08:43:51.004  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:43:51.006  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:43:51.010  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:51.017  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:43:51.019  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:43:51.019  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:43:51.020  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:43:51.020  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:43:51.021  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:43:51.021  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:43:51.021  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:51.021  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:51.021  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:43:51.021  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1593b removed from the list
09-27 08:43:51.021  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:51.021  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8652858 removed from the list
,09-27 08:43:51.024  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:51.024  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:43:51.025  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:51.026  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:51.026  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:51.027  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 08:43:51.027  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:43:51.027  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:51.028  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8652858 not in the list
09-27 08:43:51.028  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:51.029  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:51.030  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:51.031  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:43:51.031  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:43:51.031  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 08:43:51.032  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8652858 not in the list
09-27 08:43:51.032  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:43:51.032  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:51.032  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:51.032  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1593b not in the list
09-27 08:43:51.032  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:43:51.033  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e9296 added. We now have 3 listener(s)
09-27 08:43:51.034  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:43:51.034  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:43:51.034  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:43:51.034  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:43:51.034  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3224e17 added. We now have 4 listener(s)
09-27 08:43:51.034  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:43:51.035  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:43:51.038  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:51.042  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:43:51.044  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:51.044  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:43:51.044  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:43:51.044  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 08:43:51.044  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 08:43:51.045  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:43:51.045  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 08:43:51.047  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:51.049  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:43:51.049  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:43:51.050  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:51.052  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:43:51.053  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:43:51.053  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 08:43:51.057  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 08:43:51.057  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-27 08:43:51.057  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 08:43:51.057  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:43:51.060  5831  5842 D BtGatt.GattService: registerClient() - UUID=84b46fee-733c-42b3-8c32-e1c7f024f962
09-27 08:43:51.061  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=84b46fee-733c-42b3-8c32-e1c7f024f962, clientIf=5
,09-27 08:43:51.061  5593  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 08:43:51.062  5831  5841 D BtGatt.GattService: start scan with filters
,09-27 08:43:51.066  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-27 08:43:51.066  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 08:43:51.066  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 08:43:51.066  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 08:43:51.066  5831  5850 D BtGatt.ScanManager: handling starting scan
09-27 08:43:51.069  5831  5850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9b753b0
09-27 08:43:51.069  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 08:43:51.069  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 08:43:51.070  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 08:43:51.071  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 08:43:51.073  5593  5639 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-27 08:43:51.074  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 08:43:51.074  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 08:43:51.074  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:51.074  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:43:51.074  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:43:51.074  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:43:51.074  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:43:51.074  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:43:51.074  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:43:51.074  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 08:43:51.075  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:43:51.076  5831  5842 D BtGatt.GattService: stopScan() - queue size =1
09-27 08:43:51.077  5831  5841 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:43:51.077  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:43:51.077  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 08:43:51.077  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 08:43:51.077  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 08:43:51.077  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 08:43:51.077  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:43:51.077  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 08:43:51.078  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 08:43:51.078  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:43:51.079  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:43:51.079  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:43:51.079  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:43:51.079  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:43:51.081  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:43:51.081  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:43:51.081  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:43:51.083  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:43:51.084  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:43:51.085  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 08:43:51.085  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:51.085  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:43:51.085  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 08:43:51.088  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:43:51.088  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:43:51.089  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:43:51.089  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:43:51.089  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:51.091  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:43:51.091  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:43:51.091  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:43:51.096  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:43:51.096  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:43:51.096  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:51.096  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 08:43:51.096  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:51.102  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:43:51.102  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 08:43:51.102  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:51.110  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 08:43:51.110  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:43:51.110  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:43:51.117  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 08:43:51.117  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:51.117  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 08:43:51.123  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-27 08:43:51.123  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:51.603  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:43:51.604  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:43:51.604  5593  5593 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:43:54.081  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:43:54.081  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:43:54.081  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 08:43:54.082  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:43:54.082  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:54.082  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:54.082  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-27 08:43:54.082  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e9296 removed from the list
09-27 08:43:54.083  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:54.083  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3224e17 removed from the list
09-27 08:43:54.083  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:43:54.083  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:54.085  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:54.085  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:54.089  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:43:54.089  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:43:54.089  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:43:54.090  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:43:54.091  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:43:54.091  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:43:54.091  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:54.091  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3224e17 not in the list
,09-27 08:43:54.091  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:54.091  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:54.094  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:43:54.096  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:43:54.096  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:43:54.096  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:43:54.096  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 08:43:54.096  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:43:54.097  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:54.097  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3224e17 not in the list
09-27 08:43:54.097  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:43:54.097  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:43:54.097  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:54.097  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74e9296 not in the list
09-27 08:43:54.099  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:43:54.099  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@621fd9c added. We now have 3 listener(s)
,09-27 08:43:54.104  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:43:54.104  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:43:54.104  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:43:54.105  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:43:54.105  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a66b3a5 added. We now have 4 listener(s)
,09-27 08:43:54.105  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:43:54.106  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:43:54.111  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:54.119  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:43:54.124  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:43:54.124  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:43:54.124  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:43:54.126  5593  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-27 08:43:54.126  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-27 08:43:54.126  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:43:54.126  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 08:43:54.126  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:43:54.127  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:43:54.129  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 08:43:54.131  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:54.131  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:43:54.132  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 08:43:54.133  5593  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:43:54.133  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:43:54.134  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-27 08:43:54.134  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:43:54.134  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:43:54.139  5593  5927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 08:43:54.140  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:43:54.140  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-27 08:43:54.135  5868  5868 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32435]" dev="sockfs" ino=32435 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:43:54.135  5868  5868 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32435]" dev="sockfs" ino=32435 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:43:54.142  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:43:54.142  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:43:54.148  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:43:54.149  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 08:43:54.149  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:43:54.152  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 08:43:54.153  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:43:54.154  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-27 08:43:54.155  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:43:54.155  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-27 08:43:54.155  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 08:43:54.156  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:43:54.163  5831  5841 D BtGatt.GattService: registerClient() - UUID=0608cffd-5876-41b1-8bbc-fa266cd42716
,09-27 08:43:54.164  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=0608cffd-5876-41b1-8bbc-fa266cd42716, clientIf=5
,09-27 08:43:54.164  5593  5687 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 08:43:54.167  5831  5849 D BtGatt.AdvertiseManager: message : 0
,09-27 08:43:54.170  5831  5849 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 08:43:54.187  5831  5847 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 08:43:54.196  5831  5847 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 08:43:54.197  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 08:43:54.197  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 08:43:54.200  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:43:54.201  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:43:54.202  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-27 08:43:54.202  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:43:54.202  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 08:43:54.202  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 08:43:54.202  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 08:43:54.205  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:43:54.206  5593  5593 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 08:43:54.207  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 08:43:54.707  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 08:43:54.707  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:43:54.707  5593  5593 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:43:57.206  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:43:57.207  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 08:43:57.207  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 08:43:57.207  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 08:43:57.207  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 08:43:57.207  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:43:57.208  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:43:57.208  5593  5927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:43:57.208  5593  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-27 08:43:57.208  5593  5927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:43:57.208  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:43:57.208  5593  5927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:43:57.208  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:43:57.209  5593  5593 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-27 08:43:57.209  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:43:57.209  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:43:57.209  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:43:57.211  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:43:57.211  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:43:57.211  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:43:57.212  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 08:43:57.215  5831  5849 D BtGatt.AdvertiseManager: message : 1
09-27 08:43:57.216  5831  5849 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 08:43:57.229  5831  5847 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 08:43:57.230  5831  5847 D BtGatt.GattService: Client app is not null!
,09-27 08:43:57.232  5831  5859 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 08:43:57.233  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:43:57.233  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 08:43:57.233  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-27 08:43:57.234  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 08:43:57.234  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 08:43:57.236  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:43:57.236  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-27 08:43:57.236  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:43:57.237  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:57.239  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:43:57.239  5593  5593 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 08:43:57.239  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:57.239  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:57.239  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:43:57.239  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:43:57.239  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@621fd9c removed from the list
09-27 08:43:57.239  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:43:57.239  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:57.239  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:43:57.239  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a66b3a5 removed from the list
09-27 08:43:57.240  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:43:57.240  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:43:57.244  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:43:57.244  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:43:57.250  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:43:57.251  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:43:57.251  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:43:57.251  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:43:57.252  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:57.255  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:57.255  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:57.257  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:43:57.257  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:43:57.257  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:43:57.258  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:43:57.258  5593  5639 D BluetoothLeScanner: could not find callback wrapper
,09-27 08:43:57.258  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:43:57.258  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:57.258  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:43:57.259  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a66b3a5 not in the list
09-27 08:43:57.259  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:43:57.259  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 08:43:57.262  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:43:57.263  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:43:57.263  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:57.266  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:43:57.267  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:43:57.267  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:43:57.268  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:43:57.269  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:43:57.269  5593  5639 D BluetoothLeScanner: could not find callback wrapper
,09-27 08:43:57.269  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:43:57.269  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:43:57.269  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 08:43:57.269  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:43:57.270  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a66b3a5 not in the list
,09-27 08:43:57.270  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:43:57.270  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:43:57.270  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:43:57.270  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@621fd9c not in the list
09-27 08:43:57.271  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:43:57.271  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a77d2 added. We now have 3 listener(s)
09-27 08:43:57.273  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 08:43:57.274  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:43:57.274  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:43:57.274  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:43:57.274  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d330a3 added. We now have 4 listener(s)
,09-27 08:43:57.274  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:43:57.275  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:43:57.279  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:43:57.285  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:43:57.289  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:43:57.289  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:43:57.289  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:43:57.289  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 08:43:57.289  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 08:43:57.289  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:43:57.290  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:43:57.293  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:57.297  5593  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:43:57.297  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:43:57.298  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:43:57.303  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:43:57.304  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:43:57.305  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 08:43:57.310  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 08:43:57.310  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 08:43:57.310  5593  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 08:43:57.311  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:43:57.314  5831  5868 D BtGatt.GattService: registerClient() - UUID=4b418b52-5f5c-410a-b7b7-5baffccfdbc7
09-27 08:43:57.314  5831  5847 D BtGatt.GattService: onClientRegistered() - UUID=4b418b52-5f5c-410a-b7b7-5baffccfdbc7, clientIf=5
,09-27 08:43:57.315  5593  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 08:43:57.315  5831  5841 D BtGatt.GattService: start scan with filters
09-27 08:43:57.318  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 08:43:57.318  5831  5850 D BtGatt.ScanManager: handling starting scan
09-27 08:43:57.318  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 08:43:57.318  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 08:43:57.318  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 08:43:57.322  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 08:43:57.322  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:43:57.322  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 08:43:57.324  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:43:57.327  5831  5847 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 08:43:57.327  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:43:57.327  5831  5850 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 08:43:57.333  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 08:43:57.333  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:57.334  5831  5850 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:43:57.334  5831  5850 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 08:43:57.346  5831  5847 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 08:43:57.346  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:57.353  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-27 08:43:57.353  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:43:57.767  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:43:57.823  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 08:43:57.823  5593  5593 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 08:43:57.823  5593  5593 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:44:00.334  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:44:00.335  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:44:00.335  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 08:44:00.335  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:44:00.335  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:44:00.336  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 08:44:00.336  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-27 08:44:00.336  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:44:00.336  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 08:44:00.336  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:44:00.336  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 08:44:00.338  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:44:00.340  5831  5842 D BtGatt.GattService: stopScan() - queue size =1
09-27 08:44:00.342  5831  5868 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:44:00.343  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:44:00.344  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 08:44:00.344  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 08:44:00.344  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 08:44:00.344  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 08:44:00.347  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:44:00.348  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:44:00.348  5593  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:44:00.348  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:44:00.350  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:44:00.353  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:44:00.353  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:44:00.353  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:44:00.353  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:44:00.354  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.354  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:44:00.354  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:44:00.354  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a77d2 removed from the list
09-27 08:44:00.354  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:44:00.355  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d330a3 removed from the list
09-27 08:44:00.355  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:44:00.355  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:44:00.355  5831  5831 D BtGatt.ScanManager: awakened up at time 328743
,09-27 08:44:00.360  5831  5847 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 08:44:00.360  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:44:00.360  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:44:00.360  5593  5593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:44:00.360  5831  5850 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:44:00.365  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:44:00.367  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 08:44:00.367  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:44:00.367  5831  5847 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 08:44:00.367  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:44:00.367  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:44:00.367  5831  5850 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 08:44:00.367  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:44:00.369  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.369  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:44:00.372  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:44:00.372  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:44:00.372  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:44:00.373  5593  5639 D BluetoothAdapter: STATE_ON
09-27 08:44:00.373  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:44:00.373  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:44:00.373  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:44:00.373  5593  5593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:44:00.373  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d330a3 not in the list
09-27 08:44:00.373  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:44:00.373  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 08:44:00.376  5593  5593 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:44:00.376  5593  5593 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:44:00.377  5593  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:44:00.379  5593  5593 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:44:00.379  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.379  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:44:00.381  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:44:00.382  5593  5639 D BluetoothAdapter: STATE_ON
,09-27 08:44:00.382  5593  5639 D BluetoothLeScanner: could not find callback wrapper
09-27 08:44:00.382  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:44:00.382  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:44:00.382  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:44:00.382  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:44:00.383  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d330a3 not in the list
09-27 08:44:00.383  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:44:00.383  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:44:00.383  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:44:00.383  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a77d2 not in the list
09-27 08:44:00.383  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:44:00.384  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bb2b8 added. We now have 3 listener(s)
09-27 08:44:00.385  5831  5847 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-27 08:44:00.385  5831  5847 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:44:00.385  5831  5847 D BtGatt.GattService: current time is 328773535920
,09-27 08:44:00.386  5831  5847 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -81, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -72, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -77, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -73, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 08:44:00.386  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:44:00.386  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:44:00.386  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:44:00.386  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 08:44:00.386  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48f5891 added. We now have 4 listener(s)
09-27 08:44:00.386  5593  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:44:00.387  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 08:44:00.387  5831  5847 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 08:44:00.388  5831  5847 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 08:44:00.388  5831  5847 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 08:44:00.388  5831  5847 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-27 08:44:00.389  5831  5847 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 08:44:00.389  5831  5847 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-27 08:44:00.390  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:44:00.393  5593  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:44:00.395  5593  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:44:00.395  5593  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 08:44:00.396  5593  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:44:00.396  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:44:00.396  5593  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:44:00.396  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:44:00.396  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.396  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:44:00.396  5593  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:44:00.396  5593  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bb2b8 removed from the list
,09-27 08:44:00.396  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:44:00.396  5593  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48f5891 removed from the list
,09-27 08:44:00.398  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:44:00.398  5593  5639 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:44:00.399  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:44:00.399  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.399  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:44:00.400  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:44:00.400  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 08:44:00.400  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:44:00.400  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48f5891 not in the list
09-27 08:44:00.400  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.400  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:44:00.401  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:44:00.401  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 08:44:00.402  5593  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:44:00.402  5593  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48f5891 not in the list
,09-27 08:44:00.402  5593  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:44:00.402  5593  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:44:00.402  5593  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:44:00.402  5593  5593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:44:00.402  5593  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1bb2b8 not in the list
,09-27 08:44:00.403  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-27 08:44:00.403  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:44:00.403  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 08:44:00.403  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:44:00.404  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-27 08:44:00.404  5593  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:44:00.880  5593  5593 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:44:01.089   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 08:44:01.089   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 08:44:02.415  5593  5930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-27 08:44:04.414  5593  5639 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 191
,09-27 08:44:04.414  5593  5639 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 191, name: My test thread name)
,09-27 08:44:04.419  5593  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,09-27 08:44:04.419  5593  5931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name)
09-27 08:44:04.420  5593  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-27 08:44:04.426  5593  5639 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:44:04.431  5593  5932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name)
,09-27 08:44:04.432  5593  5932 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
,09-27 08:44:04.433  5593  5932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-27 08:44:04.438  5593  5930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-27 08:44:04.441  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-27 08:44:04.441  5593  5639 I jxcore-log: 
,09-27 08:44:04.442  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-27 08:44:04.442  5593  5639 I jxcore-log: 
,09-27 08:44:04.443  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-27 08:44:04.443  5593  5639 I jxcore-log: 
09-27 08:44:04.445  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-27 08:44:04.445  5593  5639 I jxcore-log: 
,09-27 08:44:04.447  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Total duration:  101046'
09-27 08:44:04.447  5593  5639 I jxcore-log: 
,09-27 08:44:04.455  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-27 08:44:04.455  5593  5639 I jxcore-log: 
,09-27 08:44:04.465  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.465  5593  5639 I jxcore-log: 
,09-27 08:44:04.468  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.468  5593  5639 I jxcore-log: 
09-27 08:44:04.470  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.470  5593  5639 I jxcore-log: 
,09-27 08:44:04.471  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.471  5593  5639 I jxcore-log: 
,09-27 08:44:04.473  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 08:44:04.473  5593  5639 I jxcore-log: 
09-27 08:44:04.473  5593  5593 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-27 08:44:04.475  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 08:44:04.475  5593  5639 I jxcore-log: 
,09-27 08:44:04.476  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.476  5593  5639 I jxcore-log: 
,09-27 08:44:04.477  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.477  5593  5639 I jxcore-log: 
,09-27 08:44:04.479  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 08:44:04.479  5593  5639 I jxcore-log: 
,09-27 08:44:04.480  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 08:44:04.480  5593  5639 I jxcore-log: 
,09-27 08:44:04.480  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 08:44:04.480  5593  5639 I jxcore-log: 
09-27 08:44:04.481  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.481  5593  5639 I jxcore-log: 
09-27 08:44:04.482  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.482  5593  5639 I jxcore-log: 
,09-27 08:44:04.483  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.483  5593  5639 I jxcore-log: 
,09-27 08:44:04.484  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.484  5593  5639 I jxcore-log: 
,09-27 08:44:04.486  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.486  5593  5639 I jxcore-log: 
,09-27 08:44:04.487  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.487  5593  5639 I jxcore-log: 
09-27 08:44:04.488  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.488  5593  5639 I jxcore-log: 
09-27 08:44:04.489  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.489  5593  5639 I jxcore-log: 
,09-27 08:44:04.490  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.490  5593  5639 I jxcore-log: 
,09-27 08:44:04.491  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.491  5593  5639 I jxcore-log: 
,09-27 08:44:04.492  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.492  5593  5639 I jxcore-log: 
,09-27 08:44:04.493  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.493  5593  5639 I jxcore-log: 
,09-27 08:44:04.497  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.497  5593  5639 I jxcore-log: 
09-27 08:44:04.497  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.497  5593  5639 I jxcore-log: 
,09-27 08:44:04.499  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.499  5593  5639 I jxcore-log: 
09-27 08:44:04.500  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.500  5593  5639 I jxcore-log: 
,09-27 08:44:04.501  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.501  5593  5639 I jxcore-log: 
,09-27 08:44:04.502  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.502  5593  5639 I jxcore-log: 
,09-27 08:44:04.503  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.503  5593  5639 I jxcore-log: 
,09-27 08:44:04.504  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.504  5593  5639 I jxcore-log: 
09-27 08:44:04.505  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.505  5593  5639 I jxcore-log: 
,09-27 08:44:04.506  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.506  5593  5639 I jxcore-log: 
,09-27 08:44:04.506  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.506  5593  5639 I jxcore-log: 
09-27 08:44:04.507  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.507  5593  5639 I jxcore-log: 
09-27 08:44:04.507  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.507  5593  5639 I jxcore-log: 
09-27 08:44:04.508  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.508  5593  5639 I jxcore-log: 
,09-27 08:44:04.508  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.508  5593  5639 I jxcore-log: 
,09-27 08:44:04.510  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 08:44:04.510  5593  5639 I jxcore-log: 
09-27 08:44:04.510  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.510  5593  5639 I jxcore-log: 
09-27 08:44:04.511  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.511  5593  5639 I jxcore-log: 
09-27 08:44:04.512  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 08:44:04.512  5593  5639 I jxcore-log: 
09-27 08:44:04.513  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.513  5593  5639 I jxcore-log: 
,09-27 08:44:04.513  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.513  5593  5639 I jxcore-log: 
09-27 08:44:04.514  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.514  5593  5639 I jxcore-log: 
,09-27 08:44:04.515  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.515  5593  5639 I jxcore-log: 
,09-27 08:44:04.516  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 08:44:04.516  5593  5639 I jxcore-log: 
09-27 08:44:04.516  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.516  5593  5639 I jxcore-log: 
,09-27 08:44:04.517  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-27 08:44:04.517  5593  5639 I jxcore-log: 
09-27 08:44:04.518  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.518  5593  5639 I jxcore-log: 
,09-27 08:44:04.518  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 08:44:04.518  5593  5639 I jxcore-log: 
,09-27 08:44:04.519  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 08:44:04.519  5593  5639 I jxcore-log: 
09-27 08:44:04.520  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 08:44:04.520  5593  5639 I jxcore-log: 
,09-27 08:44:04.520  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 08:44:04.520  5593  5639 I jxcore-log: 
,09-27 08:44:04.524  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-27 08:44:04.524  5593  5639 I jxcore-log: 
,09-27 08:44:04.524  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - WARN testUtils: 'myNameCallback not set!'
09-27 08:44:04.524  5593  5639 I jxcore-log: 
,09-27 08:44:04.525  5593  5639 I jxcore-log: 2016-09-27 12:44:04 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-27 08:44:04.525  5593  5639 I jxcore-log: 
,09-27 08:44:06.566  5593  5639 I jxcore-log: 2016-09-27 12:44:06 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-27 08:44:06.566  5593  5639 I jxcore-log: 
,09-27 08:44:06.890  5593  5639 I jxcore-log: 2016-09-27 12:44:06 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-27 08:44:06.890  5593  5639 I jxcore-log: 
,09-27 08:44:06.905  5593  5639 I jxcore-log: 2016-09-27 12:44:06 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-27 08:44:06.905  5593  5639 I jxcore-log: 
,09-27 08:44:08.022  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-27 08:44:08.022  5593  5639 I jxcore-log: 
,09-27 08:44:08.173  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-27 08:44:08.173  5593  5639 I jxcore-log: 
,09-27 08:44:08.178  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-27 08:44:08.178  5593  5639 I jxcore-log: 
,09-27 08:44:08.182  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-27 08:44:08.182  5593  5639 I jxcore-log: 
,09-27 08:44:08.708  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-27 08:44:08.708  5593  5639 I jxcore-log: 
,09-27 08:44:08.759  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-27 08:44:08.759  5593  5639 I jxcore-log: 
,09-27 08:44:08.771  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-27 08:44:08.771  5593  5639 I jxcore-log: 
,09-27 08:44:08.783  5593  5639 I jxcore-log: 2016-09-27 12:44:08 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-27 08:44:08.783  5593  5639 I jxcore-log: 
,09-27 08:44:09.043  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-27 08:44:09.043  5593  5639 I jxcore-log: 
,09-27 08:44:09.165  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-27 08:44:09.165  5593  5639 I jxcore-log: 
,09-27 08:44:09.396  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-27 08:44:09.396  5593  5639 I jxcore-log: 
,09-27 08:44:09.406  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-27 08:44:09.406  5593  5639 I jxcore-log: 
,09-27 08:44:09.412  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-27 08:44:09.412  5593  5639 I jxcore-log: 
,09-27 08:44:09.418  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-27 08:44:09.418  5593  5639 I jxcore-log: 
,09-27 08:44:09.448  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-27 08:44:09.448  5593  5639 I jxcore-log: 
,09-27 08:44:09.485  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-27 08:44:09.485  5593  5639 I jxcore-log: 
,09-27 08:44:09.492  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-27 08:44:09.492  5593  5639 I jxcore-log: 
,09-27 08:44:09.499  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-27 08:44:09.499  5593  5639 I jxcore-log: 
,09-27 08:44:09.514  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-27 08:44:09.514  5593  5639 I jxcore-log: 
,09-27 08:44:09.519  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-27 08:44:09.519  5593  5639 I jxcore-log: 
,09-27 08:44:09.525  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-27 08:44:09.525  5593  5639 I jxcore-log: 
,09-27 08:44:09.538  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-27 08:44:09.538  5593  5639 I jxcore-log: 
,09-27 08:44:09.560  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-27 08:44:09.560  5593  5639 I jxcore-log: 
,09-27 08:44:09.569  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-27 08:44:09.569  5593  5639 I jxcore-log: 
,09-27 08:44:09.580  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-27 08:44:09.580  5593  5639 I jxcore-log: 
,09-27 08:44:09.589  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-27 08:44:09.589  5593  5639 I jxcore-log: 
,09-27 08:44:09.602  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-27 08:44:09.602  5593  5639 I jxcore-log: 
,09-27 08:44:09.611  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-27 08:44:09.611  5593  5639 I jxcore-log: 
,09-27 08:44:09.617  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-27 08:44:09.617  5593  5639 I jxcore-log: 
,09-27 08:44:09.636  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-27 08:44:09.636  5593  5639 I jxcore-log: 
,09-27 08:44:09.643  5593  5639 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-27 08:44:09.644  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - INFO testUtils: 'BLE multiple advertisement supported'
09-27 08:44:09.644  5593  5639 I jxcore-log: 
,09-27 08:44:09.911  5593  5639 I jxcore-log: 2016-09-27 12:44:09 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:44:09.911  5593  5639 I jxcore-log: 
,09-27 08:44:16.090   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:17.092   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:18.093   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:19.094   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:20.096   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:20.110   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:44:21.097   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 08:44:22.178   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:44:25.208   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:44:26.098   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:27.099   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:28.101   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:29.102   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:30.103   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:31.104   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 08:44:41.105   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:42.107   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:43.108   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:44.109   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:45.110   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:44:46.111   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 08:44:52.444   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:44:55.473   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:45:00.114   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:45:01.113   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:02.114   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:03.116   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:04.117   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:05.118   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:06.119   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 08:45:20.116   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:45:26.120   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:27.122   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:28.124   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:29.125   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:30.126   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:45:31.127   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 08:45:56.128   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 08:45:56.129   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 08:46:00.121   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:46:16.130   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:17.131   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:18.133   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:19.134   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:20.124   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:46:20.135   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:21.136   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 08:46:26.137   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:27.139   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:28.140   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:29.142   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:30.143   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:31.143   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 08:46:40.126   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:46:41.145   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:42.146   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:43.148   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:44.149   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:44.465   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:46:45.151   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:46:46.152   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 08:46:47.498   927  2934 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 08:47:01.153   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:02.154   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:03.155   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:04.157   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:05.158   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:06.159   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 08:47:09.716  5593  5639 I jxcore-log: 2016-09-27 12:47:09 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-27 08:47:09.716  5593  5639 I jxcore-log: 
,09-27 08:47:09.873  5593  5639 I jxcore-log: 2016-09-27 12:47:09 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:09.873  5593  5639 I jxcore-log: 
,09-27 08:47:09.880  5593  5639 I jxcore-log: 2016-09-27 12:47:09 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:09.880  5593  5639 I jxcore-log: 
,09-27 08:47:10.390  5593  5639 I jxcore-log: 2016-09-27 12:47:10 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:10.390  5593  5639 I jxcore-log: 
,09-27 08:47:10.400  5593  5639 I jxcore-log: 2016-09-27 12:47:10 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:10.400  5593  5639 I jxcore-log: 
,09-27 08:47:11.041  5593  5639 I jxcore-log: 2016-09-27 12:47:11 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:11.041  5593  5639 I jxcore-log: 
,09-27 08:47:11.050  5593  5639 I jxcore-log: 2016-09-27 12:47:11 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:11.050  5593  5639 I jxcore-log: 
,09-27 08:47:12.090  5593  5639 I jxcore-log: 2016-09-27 12:47:12 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:12.090  5593  5639 I jxcore-log: 
,09-27 08:47:12.099  5593  5639 I jxcore-log: 2016-09-27 12:47:12 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:12.099  5593  5639 I jxcore-log: 
,09-27 08:47:13.138  5593  5639 I jxcore-log: 2016-09-27 12:47:13 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:13.138  5593  5639 I jxcore-log: 
09-27 08:47:13.144  5593  5639 I jxcore-log: 2016-09-27 12:47:13 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:13.144  5593  5639 I jxcore-log: 
,09-27 08:47:14.185  5593  5639 I jxcore-log: 2016-09-27 12:47:14 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:14.185  5593  5639 I jxcore-log: 
,09-27 08:47:14.192  5593  5639 I jxcore-log: 2016-09-27 12:47:14 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:14.192  5593  5639 I jxcore-log: 
,09-27 08:47:15.232  5593  5639 I jxcore-log: 2016-09-27 12:47:15 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:15.232  5593  5639 I jxcore-log: 
,09-27 08:47:15.240  5593  5639 I jxcore-log: 2016-09-27 12:47:15 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:15.240  5593  5639 I jxcore-log: 
,09-27 08:47:16.285  5593  5639 I jxcore-log: 2016-09-27 12:47:16 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:16.285  5593  5639 I jxcore-log: 
,09-27 08:47:16.293  5593  5639 I jxcore-log: 2016-09-27 12:47:16 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:16.293  5593  5639 I jxcore-log: 
,09-27 08:47:17.331  5593  5639 I jxcore-log: 2016-09-27 12:47:17 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:17.331  5593  5639 I jxcore-log: 
,09-27 08:47:17.337  5593  5639 I jxcore-log: 2016-09-27 12:47:17 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:17.337  5593  5639 I jxcore-log: 
,09-27 08:47:18.401  5593  5639 I jxcore-log: 2016-09-27 12:47:18 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:18.401  5593  5639 I jxcore-log: 
,09-27 08:47:18.409  5593  5639 I jxcore-log: 2016-09-27 12:47:18 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:18.409  5593  5639 I jxcore-log: 
,09-27 08:47:19.445  5593  5639 I jxcore-log: 2016-09-27 12:47:19 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:19.445  5593  5639 I jxcore-log: 
,09-27 08:47:19.454  5593  5639 I jxcore-log: 2016-09-27 12:47:19 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:19.454  5593  5639 I jxcore-log: 
,09-27 08:47:20.130   927  2932 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:47:20.488  5593  5639 I jxcore-log: 2016-09-27 12:47:20 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:20.488  5593  5639 I jxcore-log: 
09-27 08:47:20.494  5593  5639 I jxcore-log: 2016-09-27 12:47:20 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:20.494  5593  5639 I jxcore-log: 
,09-27 08:47:21.531  5593  5639 I jxcore-log: 2016-09-27 12:47:21 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:21.531  5593  5639 I jxcore-log: 
,09-27 08:47:21.540  5593  5639 I jxcore-log: 2016-09-27 12:47:21 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:21.540  5593  5639 I jxcore-log: 
,09-27 08:47:22.573  5593  5639 I jxcore-log: 2016-09-27 12:47:22 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:22.573  5593  5639 I jxcore-log: 
,09-27 08:47:22.581  5593  5639 I jxcore-log: 2016-09-27 12:47:22 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:22.581  5593  5639 I jxcore-log: 
,09-27 08:47:23.613  5593  5639 I jxcore-log: 2016-09-27 12:47:23 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 08:47:23.613  5593  5639 I jxcore-log: 
,09-27 08:47:23.623  5593  5639 I jxcore-log: 2016-09-27 12:47:23 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 08:47:23.623  5593  5639 I jxcore-log: 
,09-27 08:47:26.160   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:27.161   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:47:28.162   534   534 I ServiceManager: Waiting for service AtCmdFwd...

```
