#### Test 871194040e26dea_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-12 07:04:25.037   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-12 07:04:25.037   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-12 07:04:25.565  5473  5473 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-12 07:04:25.571  5473  5473 D AndroidRuntime: CheckJNI is OFF
10-12 07:04:25.596   928  2819 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
10-12 07:04:25.603  5473  5473 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-12 07:04:25.643  5473  5473 I Radio-JNI: register_android_hardware_Radio DONE
10-12 07:04:25.658  5473  5473 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-12 07:04:25.667   928  3243 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-12 07:04:25.716   928  3243 I ActivityManager: Start proc 5482:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-12 07:04:25.738  5473  5473 D AndroidRuntime: Shutting down VM
,10-12 07:04:26.062   928   939 I WindowManager: Screenshot max retries 4 of Token{234cfb4 ActivityRecord{70bd487 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{550cd7f u0 Starting com.test.thalitest} drawState=2
,10-12 07:04:26.138  5482  5482 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 07:04:26.173  5482  5482 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 07:04:26.198  5482  5482 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 626-646)
,10-12 07:04:26.198  5482  5482 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 07:04:26.219  5482  5482 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10c0f48}
,10-12 07:04:26.219  5482  5482 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 07:04:26.219  5482  5482 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 07:04:26.224  5482  5482 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-12 07:04:26.226  5482  5482 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 07:04:26.261  5482  5482 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 07:04:26.275  5482  5482 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-12 07:04:26.275  5482  5482 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 07:04:26.275  5482  5482 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 07:04:26.275  5482  5482 I Adreno  : Build Date                       : 12/06/15
10-12 07:04:26.275  5482  5482 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 07:04:26.275  5482  5482 I Adreno  : Local Branch                     : mybranch17112971
10-12 07:04:26.275  5482  5482 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 07:04:26.275  5482  5482 I Adreno  : Remote Branch                    : NONE
10-12 07:04:26.275  5482  5482 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 07:04:26.330   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b467102:true
,10-12 07:04:26.367   400   400 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33065]" dev="sockfs" ino=33065 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:26.367   400   400 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33065]" dev="sockfs" ino=33065 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:26.381  5482  5482 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 07:04:26.391  5482  5482 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 07:04:26.421  5482  5519 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-12 07:04:26.417   402   402 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30597]" dev="sockfs" ino=30597 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:26.417   402   402 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30597]" dev="sockfs" ino=30597 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:26.424  3655  3655 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[19933]" dev="sockfs" ino=19933 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:26.424  3655  3655 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[19933]" dev="sockfs" ino=19933 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:26.430  5482  5506 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-12 07:04:26.457  5482  5519 I OpenGLRenderer: Initialized EGL, version 1.4
,10-12 07:04:26.544   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +476ms (total +856ms)
,10-12 07:04:26.566  5482  5482 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5482
,10-12 07:04:26.643  5482  5482 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-12 07:04:26.780  5482  5522 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -605288144
,10-12 07:04:26.785  5482  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-12 07:04:26.785  5482  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-12 07:04:26.785  5482  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-12 07:04:26.785  5482  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-12 07:04:26.785  5482  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-12 07:04:26.785  5482  5522 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f899d9 added. We now have 1 listener(s)
,10-12 07:04:26.788  5482  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-12 07:04:26.788  5482  5522 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6",
10-12 07:04:26.789  5482  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:04:26.789  5482  5522 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-12 07:04:26.792  5482  5522 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b94a4c added. We now have 1 listener(s)
10-12 07:04:26.792  5482  5522 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:04:26.796   928  2820 D WifiService: New client listening to asynchronous messages
,10-12 07:04:26.797  5482  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 07:04:26.797  5482  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-12 07:04:26.797  5482  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,10-12 07:04:26.797  5482  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,10-12 07:04:26.797  5482  5522 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-12 07:04:26.799  5482  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:04:26.799  5482  5522 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-12 07:04:26.802  5482  5522 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:26.803  5482  5522 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:04:26.803  5482  5522 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-12 07:04:26.803  5482  5522 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 07:04:26.803  5482  5522 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 07:04:26.808  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:26.811  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:26.819  5482  5482 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-12 07:04:27.233  5482  5528 W jxcore-log: Initializing JXcore engine
,10-12 07:04:27.234  5482  5528 W jxcore-log: JXcore engine is ready
,10-12 07:04:27.264  5528  5528 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12543 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-12 07:04:27.264  5528  5528 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13352]" dev="sockfs" ino=13352 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-12 07:04:27.264  5528  5528 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-12 07:04:27.264  5528  5528 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30570]" dev="sockfs" ino=30570 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-12 07:04:27.274  5482  5528 W jxcore-log: Starting JXcore engine
,10-12 07:04:27.332  5482  5528 W jxcore-log: Platform android
10-12 07:04:27.332  5482  5528 W jxcore-log: 
,10-12 07:04:27.332  5482  5528 W jxcore-log: Process ARCH arm
10-12 07:04:27.332  5482  5528 W jxcore-log: 
,10-12 07:04:27.476  5482  5528 I jxcore-log: JXcore Cordova bridge is ready!
10-12 07:04:27.476  5482  5528 I jxcore-log: 
,10-12 07:04:27.477  5482  5528 W jxcore-log: JXcore engine is started
,10-12 07:04:27.482  5482  5522 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-12 07:04:27.486  5482  5482 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-12 07:04:35.039   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:36.040   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:37.041   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:37.289  5482  5528 I jxcore-log: 2016-10-12 11:04:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-12 07:04:37.289  5482  5528 I jxcore-log: 
,10-12 07:04:37.291  5482  5528 I jxcore-log: 2016-10-12 11:04:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-12 07:04:37.291  5482  5528 I jxcore-log: 
,10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:37.295  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:04:37.296  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:04:37.298  5482  5528 I jxcore-log: 2016-10-12 11:04:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-12 07:04:37.298  5482  5528 I jxcore-log: 
,10-12 07:04:37.299  5482  5528 I jxcore-log: 2016-10-12 11:04:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-12 07:04:37.299  5482  5528 I jxcore-log: 
,10-12 07:04:37.546  5482  5528 I jxcore-log: 2016-10-12 11:04:37 - DEBUG UnitTest_app: 'Running unit tests'
10-12 07:04:37.546  5482  5528 I jxcore-log: 
,10-12 07:04:37.547  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 07:04:37.547  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12a0007 added. We now have 2 listener(s)
,10-12 07:04:37.548  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 07:04:37.548  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:04:37.548  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:04:37.548  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 07:04:37.548  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74e5534 added. We now have 2 listener(s)
10-12 07:04:37.548  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:04:37.549  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 07:04:37.550  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:37.553  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:04:37.554  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:37.554  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:04:37.555  5482  5528 D executeNativeTests: Running unit tests
,10-12 07:04:37.561  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:37.566  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:37.592  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:04:37.592  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 added. We now have 3 listener(s)
,10-12 07:04:37.592  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:04:37.592  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-12 07:04:37.592  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:04:37.592  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:04:37.592  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 added. We now have 3 listener(s)
10-12 07:04:37.593  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:04:37.593  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 07:04:37.594  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:37.596  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:04:37.597  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:04:37.597  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:04:37.599  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 07:04:37.599  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 07:04:37.599  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 07:04:37.599  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 07:04:37.600  5482  5528 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-12 07:04:37.600  5482  5528 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 07:04:37.600  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 07:04:37.600  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:04:37.600  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:04:37.600  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:04:37.600  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:37.600  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:37.600  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:37.600  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:37.600  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.601  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:37.601  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:37.601  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-12 07:04:37.601  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 removed from the list
10-12 07:04:37.601  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:37.601  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 removed from the list
10-12 07:04:37.602  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:37.606  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:04:37.607  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:04:37.607  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:37.607  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.607  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.608  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:37.608  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 07:04:37.608  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:37.608  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:37.609  5482  5528 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-12 07:04:37.609  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:37.609  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:37.609  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 07:04:37.609  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:37.609  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.609  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.609  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:37.609  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
,10-12 07:04:37.609  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:37.609  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:37.609  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:37.609  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.609  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.609  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.609  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.610  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:37.610  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:37.610  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:37.610  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
,10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-12 07:04:37.612  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 07:04:37.613  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-12 07:04:37.613  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:37.613  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:37.613  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:37.613  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:37.613  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.614  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.614  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:37.614  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:37.614  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:37.614  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:37.614  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:37.614  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.614  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.614  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:37.614  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:37.614  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:37.614  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:37.614  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:37.614  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:37.615  5482  5528 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-12 07:04:37.616  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:37.618  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:04:37.618  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:37.619  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:04:37.619  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:04:37.619  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 07:04:37.619  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 07:04:37.619  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:04:37.619  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 07:04:37.622  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:04:37.625  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:04:37.627  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 07:04:37.627  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 07:04:37.631  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 07:04:37.632  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 07:04:37.632  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 07:04:37.633  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-12 07:04:37.634  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-12 07:04:37.634  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 07:04:37.634  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 07:04:37.634  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 07:04:37.634  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 07:04:37.634  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 07:04:37.635  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:04:37.636  4450  4709 D BtGatt.GattService: registerClient() - UUID=0f0eec03-4edc-4165-b16a-2efb697c21ed
10-12 07:04:37.637  4450  4537 D BtGatt.GattService: onClientRegistered() - UUID=0f0eec03-4edc-4165-b16a-2efb697c21ed, clientIf=5
10-12 07:04:37.638  5482  5493 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 07:04:37.639  4450  4464 D BtGatt.GattService: start scan with filters
10-12 07:04:37.642  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 07:04:37.643  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 07:04:37.643  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:04:37.643  4450  4542 D BtGatt.ScanManager: handling starting scan
10-12 07:04:37.643  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 07:04:37.643  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 07:04:37.643  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 07:04:37.643  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 07:04:37.644  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:04:37.644  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 07:04:37.645  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 07:04:37.645  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:04:37.646  5482  5528 I io.jxcore.node.ConnectionHelper: start: OK
10-12 07:04:37.646  4450  4542 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:04:37.654  4450  4537 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 07:04:37.654  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:37.654  4450  4542 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 07:04:37.660  4450  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 07:04:37.660  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:37.661  4450  4542 D BtGatt.ScanManager: Starting BLE batch scan
10-12 07:04:37.661  4450  4542 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 07:04:37.671  4450  4537 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 07:04:37.672  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:37.679  4450  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 07:04:37.679  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:04:38.043   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:38.147  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 07:04:38.147  5482  5482 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:04:38.148  5482  5482 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 07:04:38.563   928  5223 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-12 07:04:39.044   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:39.446   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 07:04:39.449   928  2821 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-12 07:04:40.045   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 07:04:42.465   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 07:04:42.468   928  2821 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-12 07:04:42.650  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:04:42.650  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:42.650  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 07:04:42.650  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:42.650  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 07:04:42.651  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:42.651  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-12 07:04:42.651  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:04:42.651  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-12 07:04:42.651  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-12 07:04:42.652  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 07:04:42.652  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 07:04:42.653  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:04:42.653  4450  4709 D BtGatt.GattService: stopScan() - queue size =1
10-12 07:04:42.655  4450  4464 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 07:04:42.657  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 07:04:42.657  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 07:04:42.658  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 07:04:42.658  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:04:42.658  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 07:04:42.658  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 07:04:42.658  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 07:04:42.659  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 07:04:42.660  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:04:42.661  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 07:04:42.661  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-12 07:04:42.661  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 07:04:42.661  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 07:04:42.662  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:42.663  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:42.663  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:42.663  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:42.664  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:42.663  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:04:42.664  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:42.664  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:42.664  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:42.664  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:04:42.664  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:42.664  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:42.664  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:04:42.665  4450  4450 D BtGatt.ScanManager: awakened up at time 237113
10-12 07:04:42.670  4450  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 07:04:42.670  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:42.671  4450  4542 D BtGatt.ScanManager: stopping BLe Batch
,10-12 07:04:42.680  4450  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-12 07:04:42.680  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:42.680  4450  4542 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 07:04:42.701  4450  4537 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-12 07:04:42.702  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:42.702  4450  4537 D BtGatt.GattService: current time is 237150088720
10-12 07:04:42.703  4450  4537 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -87, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-12 07:04:42.705  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-12 07:04:42.707  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-12 07:04:42.708  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-12 07:04:42.708  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-12 07:04:42.708  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-12 07:04:42.708  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-12 07:04:43.165  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 07:04:45.046   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:46.048   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:47.048   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:47.667  5482  5528 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-12 07:04:47.673  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:47.683  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:04:47.688  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:47.688  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 07:04:47.688  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:04:47.689  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 07:04:47.689  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 07:04:47.689  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:04:47.689  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 07:04:47.693  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:47.696  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 07:04:47.696  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 07:04:47.698  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:04:47.702  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 07:04:47.703  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 07:04:47.704  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 07:04:47.710  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 07:04:47.710  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 07:04:47.710  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 07:04:47.710  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-12 07:04:47.710  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 07:04:47.711  5482  5528 D BluetoothAdapter: STATE_ON
,10-12 07:04:47.715  4450  4709 D BtGatt.GattService: registerClient() - UUID=de193c5a-1952-4631-8f40-2dfb95b2db00
,10-12 07:04:47.716  4450  4537 D BtGatt.GattService: onClientRegistered() - UUID=de193c5a-1952-4631-8f40-2dfb95b2db00, clientIf=5
,10-12 07:04:47.717  5482  5493 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 07:04:47.717  4450  4464 D BtGatt.GattService: start scan with filters
,10-12 07:04:47.724  4450  4542 D BtGatt.ScanManager: handling starting scan
,10-12 07:04:47.724  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 07:04:47.724  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 07:04:47.724  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:04:47.724  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 07:04:47.724  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 07:04:47.724  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 07:04:47.725  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 07:04:47.730  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 07:04:47.730  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 07:04:47.730  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 07:04:47.733  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 07:04:47.734  4450  4537 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-12 07:04:47.734  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.734  4450  4542 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 07:04:47.737  5482  5528 I io.jxcore.node.ConnectionHelper: start: OK
10-12 07:04:47.740  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:04:47.740  5482  5528 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 07:04:47.741  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:47.741  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 07:04:47.741  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:47.741  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 07:04:47.741  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:47.741  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 07:04:47.741  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:04:47.741  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 07:04:47.741  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-12 07:04:47.741  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 07:04:47.741  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 07:04:47.742  4450  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 07:04:47.742  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.742  4450  4542 D BtGatt.ScanManager: Starting BLE batch scan
10-12 07:04:47.743  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:04:47.743  4450  4542 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 07:04:47.743  4450  4709 D BtGatt.GattService: stopScan() - queue size =1
10-12 07:04:47.744  4450  4464 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 07:04:47.745  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 07:04:47.745  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 07:04:47.745  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-12 07:04:47.745  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:04:47.745  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 07:04:47.746  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 07:04:47.746  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 07:04:47.746  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 07:04:47.748  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:04:47.748  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 07:04:47.748  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-12 07:04:47.748  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 07:04:47.748  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 07:04:47.749  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:47.751  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:47.751  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:04:47.751  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:47.751  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 07:04:47.751  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:47.751  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:47.751  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:04:47.751  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:47.751  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:47.752  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:47.752  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:47.752  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:47.753  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:04:47.753  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:47.755  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:47.755  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:47.755  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:47.755  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:47.756  4450  4537 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 07:04:47.756  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.756  5482  5528 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-12 07:04:47.759  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:04:47.764  4450  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-12 07:04:47.764  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:04:47.766  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:04:47.768  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:04:47.768  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:04:47.769  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:04:47.769  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-12 07:04:47.769  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 07:04:47.769  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:04:47.769  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 07:04:47.771  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:04:47.772  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 07:04:47.772  4450  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 07:04:47.772  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 07:04:47.772  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.773  4450  4542 D BtGatt.ScanManager: stopping BLe Batch
,10-12 07:04:47.774  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:04:47.776  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 07:04:47.778  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 07:04:47.778  4450  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 07:04:47.778  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.778  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 07:04:47.778  4450  4542 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 07:04:47.781  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 07:04:47.781  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 07:04:47.781  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 07:04:47.781  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 07:04:47.781  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 07:04:47.782  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:04:47.783  4450  4537 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 07:04:47.783  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.784  4450  4463 D BtGatt.GattService: registerClient() - UUID=3b83a8e3-24e2-4a19-a6fa-0aee923826fc
10-12 07:04:47.785  4450  4537 D BtGatt.GattService: onClientRegistered() - UUID=3b83a8e3-24e2-4a19-a6fa-0aee923826fc, clientIf=5
10-12 07:04:47.785  5482  5492 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 07:04:47.785  4450  4464 D BtGatt.GattService: start scan with filters
,10-12 07:04:47.788  4450  4542 D BtGatt.ScanManager: handling starting scan
,10-12 07:04:47.788  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 07:04:47.788  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 07:04:47.788  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:04:47.788  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 07:04:47.788  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 07:04:47.788  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 07:04:47.788  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 07:04:47.790  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:04:47.791  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 07:04:47.791  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 07:04:47.793  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 07:04:47.795  4450  4537 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 07:04:47.795  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.795  4450  4542 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 07:04:47.795  5482  5528 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 07:04:47.800  4450  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 07:04:47.800  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:47.800  4450  4542 D BtGatt.ScanManager: Starting BLE batch scan
10-12 07:04:47.800  4450  4542 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 07:04:47.809  4450  4537 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-12 07:04:47.809  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:04:47.814  4450  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 07:04:47.814  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:04:48.050   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:48.292  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 07:04:48.292  5482  5482 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:04:48.293  5482  5482 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 07:04:49.051   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:04:50.051   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 07:04:51.547   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 07:04:52.796  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:04:52.796  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 07:04:52.796  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-12 07:04:52.796  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:52.796  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 07:04:52.797  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 07:04:52.797  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 07:04:52.797  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:04:52.797  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 07:04:52.797  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 07:04:52.797  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 07:04:52.798  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 07:04:52.800  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:04:52.801  4450  4709 D BtGatt.GattService: stopScan() - queue size =1
10-12 07:04:52.803  4450  4463 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 07:04:52.803  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 07:04:52.804  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-12 07:04:52.804  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 07:04:52.804  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:04:52.804  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 07:04:52.804  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 07:04:52.804  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 07:04:52.805  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 07:04:52.808  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:04:52.808  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 07:04:52.808  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 07:04:52.809  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 07:04:52.809  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-12 07:04:52.811  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:52.812  4450  4450 D BtGatt.ScanManager: awakened up at time 247259
10-12 07:04:52.816  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:04:52.817  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:04:52.817  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:04:52.818  4450  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 07:04:52.818  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:52.818  4450  4542 D BtGatt.ScanManager: stopping BLe Batch
,10-12 07:04:52.826  4450  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-12 07:04:52.826  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:52.826  4450  4542 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 07:04:52.844  4450  4537 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-12 07:04:52.844  4450  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:04:52.844  4450  4537 D BtGatt.GattService: current time is 247292636948
10-12 07:04:52.845  4450  4537 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-12 07:04:52.845  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-12 07:04:52.845  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
10-12 07:04:52.846  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-12 07:04:52.846  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-12 07:04:52.846  4450  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-12 07:04:53.318  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 07:04:53.318  5482  5482 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:53.318  5482  5482 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 07:04:57.817  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:04:57.817  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 07:04:57.817  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 07:04:57.818  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.818  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.818  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:04:57.818  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 07:04:57.818  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.818  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.819  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.819  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.819  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.820  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.821  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:57.824  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.825  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.825  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:04:57.825  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.826  5482  5528 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-12 07:04:57.828  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.828  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 07:04:57.828  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 07:04:57.829  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.829  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.829  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.829  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 07:04:57.830  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.830  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.830  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.830  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:04:57.830  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:04:57.830  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.830  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.830  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:57.833  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.833  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.833  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.833  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.836  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-12 07:04:57.836  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.836  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.836  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.837  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.837  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:04:57.837  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.837  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.837  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.837  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.837  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
,10-12 07:04:57.837  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.838  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.838  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.838  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.838  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.840  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.840  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.840  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.841  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.842  5482  5528 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-12 07:04:57.842  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.843  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.843  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.843  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.843  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.843  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.843  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.844  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.844  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.844  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.844  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.844  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:04:57.844  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.844  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.844  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:57.847  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.847  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 07:04:57.847  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.847  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.849  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-12 07:04:57.849  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.850  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.850  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 07:04:57.850  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.850  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.850  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.850  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 07:04:57.850  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.851  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.851  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.851  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.851  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.851  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:57.851  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.851  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.854  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.854  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.854  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.855  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
,10-12 07:04:57.856  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-12 07:04:57.857  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 07:04:57.857  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 07:04:57.857  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 07:04:57.857  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:04:57.857  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:04:57.857  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 07:04:57.858  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 07:04:57.858  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 07:04:57.858  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:04:57.858  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.858  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.858  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.859  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.859  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.859  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.859  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
,10-12 07:04:57.859  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.859  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.859  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.859  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:04:57.859  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.860  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
10-12 07:04:57.860  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.861  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.861  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.861  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.862  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.863  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 07:04:57.863  5482  5528 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 07:04:57.863  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-12 07:04:57.868  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 07:04:57.868  5482  5528 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-12 07:04:57.869  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-12 07:04:57.870  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 07:04:57.871  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-12 07:04:57.872  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 07:04:57.872  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 07:04:57.872  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-12 07:04:57.872  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-12 07:04:57.872  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 07:04:57.872  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,10-12 07:04:57.872  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-12 07:04:57.873  5482  5528 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 07:04:57.873  5482  5528 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-12 07:04:57.873  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 07:04:57.873  5482  5528 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 07:04:57.874  5482  5528 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-12 07:04:57.874  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 07:04:57.874  5482  5528 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 07:04:57.874  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-12 07:04:57.879  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-12 07:04:57.880  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-12 07:04:57.880  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-12 07:04:57.881  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-12 07:04:57.881  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-12 07:04:57.881  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-12 07:04:57.882  5482  5528 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-12 07:04:57.882  5482  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-12 07:04:57.882  5482  5528 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-12 07:04:57.882  5482  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-12 07:04:57.882  5482  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-12 07:04:57.882  5482  5529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-12 07:04:57.883  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.883  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.883  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.883  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.883  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.883  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.883  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.884  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-12 07:04:57.885  5482  5529 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-12 07:04:57.885  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.885  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.885  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.885  5482  5529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:04:57.885  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.885  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.885  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.885  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.885  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.884  4463  4463 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33798]" dev="sockfs" ino=33798 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-12 07:04:57.884  4463  4463 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33798]" dev="sockfs" ino=33798 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 07:04:57.886  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.886  5482  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-12 07:04:57.886  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.886  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.886  5482  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-12 07:04:57.887  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.887  5482  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-12 07:04:57.887  5482  5528 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-12 07:04:57.888  5482  5529 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-12 07:04:57.888  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.888  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.888  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.888  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.889  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.889  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.889  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.889  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.889  5482  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-12 07:04:57.889  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.889  5482  5529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-12 07:04:57.889  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.889  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.889  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.889  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.889  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.889  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blue,toothManager: release: 2 listener(s) left
10-12 07:04:57.891  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.891  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.891  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.891  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.892  5482  5528 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-12 07:04:57.893  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.893  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:04:57.893  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.893  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.893  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.893  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.893  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.893  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.893  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.893  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.893  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.893  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.894  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.894  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.894  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:04:57.895  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.896  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.896  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:04:57.896  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.897  5482  5528 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-12 07:04:57.897  5482  5528 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-12 07:04:57.897  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 07:04:57.897  5482  5528 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-12 07:04:57.897  5482  5528 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 07:04:57.897  5482  5528 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-12 07:04:57.897  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 07:04:57.897  5482  5528 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-12 07:04:57.897  5482  5528 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 07:04:57.897  5482  5528 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 07:04:57.898  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 07:04:57.898  5482  5528 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-12 07:04:57.898  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:04:57.898  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 07:04:57.898  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:04:57.898  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.898  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.898  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.898  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.898  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.898  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.898  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.898  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.898  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.898  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.898  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:04:57.899  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.900  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:04:57.900  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:04:57.900  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:04:57.900  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.901  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:04:57.901  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.901  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:04:57.902  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:04:57.902  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:04:57.902  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:04:57.902  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:04:57.902  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:04:57.902  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:04:57.902  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:00.052   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:00.626   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 07:05:01.053   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:02.054   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:02.903  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:05:02.903  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.903  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 07:05:02.903  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.904  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:02.904  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:02.904  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.904  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:02.904  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 07:05:02.905  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:02.905  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 07:05:02.905  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.905  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:02.905  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 07:05:02.906  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.906  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.906  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.906  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:02.906  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.906  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.906  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.907  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.910  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:02.911  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:02.911  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.911  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
,10-12 07:05:02.918  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-12 07:05:02.919  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:05:02.922  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-12 07:05:02.924  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 07:05:02.924  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 07:05:02.924  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 07:05:02.925  5482  5531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 07:05:02.925  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-12 07:05:02.925  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 07:05:02.925  5482  5482 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 07:05:02.925  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:02.926  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-12 07:05:02.926  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 07:05:02.926  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 07:05:02.926  5482  5531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:02.926  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.926  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 07:05:02.926  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 07:05:02.926  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.926  5482  5482 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 07:05:02.926  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:05:02.926  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:05:02.926  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 07:05:02.926  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 07:05:02.927  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.927  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.924  4464  4464 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 07:05:02.927  4464  4464 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 07:05:02.929  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 07:05:02.929  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.929  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:05:02.930  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:05:02.930  5482  5531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 07:05:02.930  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:05:02.930  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:02.930  5482  5531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-12 07:05:02.930  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:02.930  5482  5531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 07:05:02.930  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:02.930  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:02.930  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.930  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:02.930  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 07:05:02.930  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.931  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.931  5482  5482 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 07:05:02.931  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.931  5482  5482 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 07:05:02.931  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:02.931  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.931  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.931  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.931  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:02.934  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:02.934  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:02.934  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.934  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.936  5482  5528 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-12 07:05:02.937  5482  5528 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 07:05:02.937  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 07:05:02.937  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:05:02.937  5482  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 07:05:02.938  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:02.938  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:02.938  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:02.938  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:02.938  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.938  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.938  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:02.938  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.938  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.939  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.939  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:02.939  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.939  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.939  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.939  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.940  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:02.941  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:02.941  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.941  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Disco,veryManager@d6e2d93 not in the list
10-12 07:05:02.945  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:02.945  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:02.945  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:02.945  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:02.945  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.945  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.945  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:02.945  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.945  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.945  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.946  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:02.946  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.946  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.946  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.946  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.947  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:02.947  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:02.947  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.947  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.948  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:02.948  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:02.948  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:02.948  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:02.948  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.948  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.948  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:02.948  5482  5528 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org,.thaliproject.p2p.btconnectorlib.ConnectionManager@6009282 not in the list
10-12 07:05:02.948  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.948  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.948  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:02.948  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.949  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.949  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:02.949  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:02.950  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:02.950  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:02.950  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:02.950  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6e2d93 not in the list
10-12 07:05:02.951  5482  5528 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-12 07:05:02.951  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 07:05:02.951  5482  5528 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-12 07:05:02.951  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 07:05:02.951  5482  5528 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-12 07:05:02.952  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 07:05:02.954  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-12 07:05:02.954  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-12 07:05:02.955  5482  5528 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-12 07:05:02.956  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 07:05:02.956  5482  5528 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-12 07:05:02.956  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 07:05:02.956  5482  5528 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-12 07:05:02.956  5482  5528 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-12 07:05:02.956  5482  5528 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-12 07:05:02.956  5482  5528 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-12 07:05:02.957  5482  5528 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-12 07:05:02.957  5482  5528 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-12 07:05:02.957  5482  5528 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-12 07:05:02.957  5482  5528 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-12 07:05:02.958  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:02.958  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c4c03d added. We now have 3 listener(s)
10-12 07:05:02.958  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:02.960  5482  5528 D BluetoothAdapter: enable(): BT is already enabled..!
10-12 07:05:02.960   928  3639 D WifiService: setWifiEnabled: true pid=5482, uid=10077
10-12 07:05:02.960   928  3639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 07:05:03.015  4450  4669 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
10-12 07:05:03.015  4450  4674 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-12 07:05:03.055   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:03.430  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 07:05:03.658   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 07:05:04.056   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:05.056   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 07:05:05.600   928  2819 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 07:05:07.966  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 07:05:07.966  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@686a032 added. We now have 4 listener(s)
10-12 07:05:07.966  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:07.978  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:05:07.979  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@686a032 removed from the list
10-12 07:05:07.979  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:05:07.979  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:05:07.979  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:07.981  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:07.981  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cda183 added. We now have 4 listener(s)
,10-12 07:05:07.981  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:07.984  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:07.985  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cda183 removed from the list
10-12 07:05:07.985  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:05:07.985  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:07.985  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:07.986  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:07.986  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@115df00 added. We now have 4 listener(s)
,10-12 07:05:07.987  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:07.990   928  2983 D WifiService: setWifiEnabled: false pid=5482, uid=10077
10-12 07:05:07.990   928  2983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 07:05:07.997   928  2819 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-12 07:05:07.997   928  2819 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-12 07:05:07.999   928  2819 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 07:05:07.999   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:08.001  4450  4532 D BluetoothAdapterState: Current state: ON, message: 23
10-12 07:05:08.001  4450  4532 D BluetoothAdapterProperties: Setting state to 13
,10-12 07:05:08.001  4450  4532 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-12 07:05:08.001  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:05:08.002  4450  4532 D BluetoothAdapterProperties: onBluetoothDisable()
10-12 07:05:08.007  4450  4532 I BluetoothAdapterState: Entering PendingCommandState
10-12 07:05:08.009  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:08.009  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:08.010  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.010  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:05:08.010  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 07:05:08.013  4450  4450 D BluetoothMapService: onReceive
10-12 07:05:08.013  4450  4450 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 07:05:08.013  4450  4450 D BluetoothMapService: STATE_TURNING_OFF
10-12 07:05:08.014  4450  4450 D BluetoothMapService: MAP Service closeService in
10-12 07:05:08.014  4450  4450 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 07:05:08.014  4450  4450 D ObexServerSockets0: shutdown(block = true)
10-12 07:05:08.014  4450  4450 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 07:05:08.015  4450  4674 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 07:05:08.015  4450  4450 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 07:05:08.015  4450  4715 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-12 07:05:08.016  4450  4714 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-12 07:05:08.017  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.017  4450  4450 I BtOppRfcommListener: stopping Accept Thread
,10-12 07:05:08.017   928  5224 D DhcpClient: Clearing IP address
,10-12 07:05:08.017   506   924 D CommandListener: Clearing all IP addresses on wlan0
10-12 07:05:08.018  4450  5191 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 07:05:08.019  4450  5191 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-12 07:05:08.021  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:08.025   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:08.028  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:08.028  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:08.029  3410  5279 V NativeCrypto: Read error: ssl=0x7f8155fc80: I/O error during system call, Connection timed out
10-12 07:05:08.031  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.031  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:08.032  3410  5279 V NativeCrypto: SSL shutdown failed: ssl=0x7f8155fc80: I/O error during system call, Broken pipe
10-12 07:05:08.034   928  5225 D DhcpClient: Receive thread stopped
10-12 07:05:08.035   928   941 I ActivityManager: Start proc 5535:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-12 07:05:08.036  4450  4537 D BluetoothAdapterProperties: Scan Mode:20
,10-12 07:05:08.036  4450  4532 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-12 07:05:08.036  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:08.036  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:08.037  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:08.037  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:08.039   928  3243 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,10-12 07:05:08.039   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 07:05:08.039   928  5221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-12 07:05:08.039   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-12 07:05:08.042   928  5221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-12 07:05:08.044   928   928 D RttService: SCAN_AVAILABLE : 1
10-12 07:05:08.044   928  2878 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-12 07:05:08.044   538   538 E Parcel  : Reading a NULL string not supported here.
,10-12 07:05:08.045   928  2821 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-12 07:05:08.046  4450  4450 D HeadsetService: Received stop request...Stopping profile...
10-12 07:05:08.046  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:08.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:08.047  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.047  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 07:05:08.047  3583  3719 W QCNEJ   : |CORE| network lost: 100
10-12 07:05:08.048  3583  3719 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-12 07:05:08.049   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:08.049   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:08.050  3621  3635 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:08.050  4450  4450 D A2dpService: Received stop request...Stopping profile...
10-12 07:05:08.050  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:08.050  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:08.050  4450  4679 D A2dpStateMachine: Exit Disconnected: -1
10-12 07:05:08.050   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:08.050  2951  3162 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:08.051  2951  2951 D HeadsetProfile: Bluetooth service disconnected
10-12 07:05:08.051  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.051  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:08.052  2951  2951 D BluetoothA2dp: Proxy object disconnected
10-12 07:05:08.053   928   928 D BluetoothA2dp: Proxy object disconnected
,10-12 07:05:08.053  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:08.053  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:08.054  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.054  4450  4450 D HidService: Received stop request...Stopping profile...
10-12 07:05:08.054  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:08.054  4450  4450 D HidService: Stopping Bluetooth HidService
10-12 07:05:08.056  4450  4450 D HealthService: Received stop request...Stopping profile...
10-12 07:05:08.057  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.057  4450  4450 D PanService: Received stop request...Stopping profile...
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:08.057  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:08.062  4450  4450 D BluetoothMapService: Received stop request...Stopping profile...
10-12 07:05:08.062  4450  4450 D BluetoothMapService: stop()
,10-12 07:05:08.063  4450  4450 D BluetoothMapAppObserver: deinitObservers()
10-12 07:05:08.063  4450  4450 D BluetoothMapAppObserver: removeReceiver()
10-12 07:05:08.059   928  2819 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-12 07:05:08.065  4450  4450 D SapService: Received stop request...Stopping profile...
10-12 07:05:08.065  4450  4450 V SapService: stop()
10-12 07:05:08.067  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.067  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.067  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.067  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.067  2951  2951 D BluetoothInputDevice: Proxy object disconnected
10-12 07:05:08.068  2951  2951 D HidProfile: Bluetooth service disconnected
10-12 07:05:08.068  2951  2951 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 07:05:08.068  2951  2951 D PanProfile: Bluetooth service disconnected
10-12 07:05:08.068  2951  2951 D BluetoothMap: Proxy object disconnected
10-12 07:05:08.068  2951  2951 D MapProfile: Bluetooth service disconnected
,10-12 07:05:08.069  4450  4450 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-12 07:05:08.069  4450  4450 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-12 07:05:08.069  4450  4537 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 07:05:08.069  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.069  4450  4669 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:08.069  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.069  4450  4669 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:08.069  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.070  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.070  4450  4669 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 07:05:08.070  4450  4537 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-12 07:05:08.071  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.071  4450  4669 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:08.071  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.071  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.071  4450  4669 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:08.071  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.071  4450  4537 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 07:05:08.072  4450  4669 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 07:05:08.072  4450  4669 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 07:05:08.072  4450  4669 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 07:05:08.072  4450  4450 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 07:05:08.072  4450  4669 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 07:05:08.072  4450  4450 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 07:05:08.072  4450  4537 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 07:05:08.072  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.072  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.072  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.072  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.072  4450  4450 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 07:05:08.073  4450  4450 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 07:05:08.073  4450  4537 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 07:05:08.073  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.073  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.073  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.073  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.073  4450  4450 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 07:05:08.073  4450  4450 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 07:05:08.074   928  2819 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 07:05:08.074  4450  4450 D BluetoothMapService: MAP Service closeService in
10-12 07:05:08.074  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.074  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.074  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.074  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.075  4450  4450 D BluetoothMapService: cleanup()
10-12 07:05:08.075  4450  4450 D BluetoothMapService: MAP Service closeService in
10-12 07:05:08.075  4450  4450 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:08.075  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.075  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.075  4450  4450 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:08.075  4450  4532 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-12 07:05:08.075  4450  4532 D BluetoothAdapterProperties: Setting state to 15
10-12 07:05:08.075  4450  4532 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 07:05:08.076  4450  4532 I BluetoothAdapterState: Entering BleOnState
10-12 07:05:08.077   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 07:05:08.085  2951  3162 D BluetoothPan: onBluetoothStateChange on: false
,10-12 07:05:08.086  3621  4653 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:08.087   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 07:05:08.087  2951  3800 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 07:05:08.087  2951  2962 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 07:05:08.088   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:08.088   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:08.088  2951  2964 D BluetoothMap: onBluetoothStateChange: up=false
,10-12 07:05:08.089  2951  3162 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 07:05:08.089   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:08.090  2951  3800 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-12 07:05:08.090  4450  4532 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 07:05:08.090  4450  4532 D BluetoothAdapterProperties: Setting state to 16
10-12 07:05:08.090  4450  4532 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 07:05:08.091  4450  4532 D BluetoothAdapterProperties: onBleDisable
10-12 07:05:08.091  4450  4532 I BluetoothAdapterState: Entering PendingCommandState
10-12 07:05:08.091  4450  4533 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 07:05:08.092  4450  4669 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 07:05:08.092  4450  4669 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:08.093  4450  4537 D BluetoothAdapterProperties: Scan Mode:20
10-12 07:05:08.095  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:08.096  5535  5535 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-12 07:05:08.097  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:08.099  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:08.100  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.102  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.102   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 07:05:08.102   506   924 D CommandListener: Clearing all IP addresses on wlan0
10-12 07:05:08.102   506   924 D TetherController: Setting IP forward enable = 0
10-12 07:05:08.103  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.104   928  2821 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-12 07:05:08.104   928  2821 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 07:05:08.104   928  2819 D DhcpClient: doQuit
,10-12 07:05:08.105   928  2819 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 07:05:08.105  3286  3286 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-12 07:05:08.106   928  5224 D DhcpClient: onQuitting
10-12 07:05:08.106   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-12 07:05:08.111  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:08.111  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:08.112  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:08.112  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:08.115  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:08.115  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:08.116  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.116  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:08.120  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:08.120  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:08.120  5114  5114 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@eeb4063 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-12 07:05:08.121  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:08.121  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:08.122  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.124  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.124  4899  4919 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 07:05:08.124  4899  4919 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 07:05:08.124  4899  4919 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 07:05:08.124  4899  4919 E SarControlService: no key has been found,reset the power
10-12 07:05:08.124  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-12 07:05:08.124  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 07:05:08.124  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 07:05:08.125  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.125  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:08.125  4924  4924 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 07:05:08.128  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-12 07:05:08.128  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 07:05:08.128  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 07:05:08.128  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:08.128  4924  4924 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 07:05:08.131  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000ea03000000000000ffffffff]
10-12 07:05:08.131  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:08.131  4924  4938 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,10-12 07:05:08.132  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:08.132  4899  4909 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-12 07:05:08.137  5535  5535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 07:05:08.139  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000eb03000000000000ffffffff]
10-12 07:05:08.139  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:08.139  4924  4938 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-12 07:05:08.140  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:08.140  4899  4910 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-12 07:05:08.141  3286  3286 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-12 07:05:08.144   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@331d6a:true
,10-12 07:05:08.146  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 07:05:08.146  3286  3286 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-12 07:05:08.149   506   917 W SocketClient: write error (Broken pipe)
,10-12 07:05:08.149   506   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-12 07:05:08.149   506   917 W SocketListener: Error sending broadcast (Broken pipe)
,10-12 07:05:08.157   506   924 E Netd    : netlink response contains error (No such file or directory)
10-12 07:05:08.158   928  2821 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 07:05:08.159   506   924 D TetherController: Setting IP forward enable = 0
,10-12 07:05:08.163   928  3424 I ActivityManager: Start proc 5566:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-12 07:05:08.171  5535  5535 D LocalBluetoothProfileManager: Adding local MAP profile
,10-12 07:05:08.174  3286  3286 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 07:05:08.173  5535  5535 D BluetoothMap: Create BluetoothMap proxy object
,10-12 07:05:08.182  5535  5535 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-12 07:05:08.186  3286  3286 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-12 07:05:08.188  5535  5535 D DockEventReceiver: finishStartingService: stopping service
,10-12 07:05:08.191   928   939 I ActivityManager: Killing 4839:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-12 07:05:08.218  5566  5566 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-12 07:05:08.291  4874  4874 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 07:05:08.291   928  2819 D wifi    : In wifi stop Hal
10-12 07:05:08.291   928  2819 D wifi    : halHandle = 0x7f6fa03680, mVM = 0x7f8c08d140, mCls = 0x100a06
10-12 07:05:08.291   928  3285 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-12 07:05:08.291   928  3285 D WifiHAL : Got a signal to exit!!!
10-12 07:05:08.291   928  3285 I WifiHAL : Exit wifi_event_loop
10-12 07:05:08.292   928  2819 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-12 07:05:08.292   928  2819 E WifiHAL : Event processing terminated
,10-12 07:05:08.292   928  2819 D wifi    : In wifi cleaned up handler
10-12 07:05:08.292   928  2819 I WifiHAL : Internal cleanup completed
,10-12 07:05:08.293  3892  4058 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 07:05:08.294  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:08.296  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:08.297  4450  4537 I bt_hci  : shut_down
,10-12 07:05:08.298  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:08.299  4450  4543 D bt_hwcfg: hw_epilog_process
10-12 07:05:08.302  4450  4543 I bt_vendor: low_power_mode_cb
10-12 07:05:08.305  4450  4543 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-12 07:05:08.305  4450  4543 I bt_vendor: epilog_cb
10-12 07:05:08.305  4450  4543 I bt_hci  : epilog_finished_callback
,10-12 07:05:08.306  4450  4537 I bt_hci_h4: hal_close
,10-12 07:05:08.307  4450  4537 I bt_userial_vendor: device fd = 54 close
,10-12 07:05:08.311   928  3285 D wifi    : set interface wlan0 flags (DOWN)
,10-12 07:05:08.311   928  2819 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.k.d(PG:583)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.392  5566  5566 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.392  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.393  5566  5566 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 07:05:08.393  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 07:05:08.406  5535  5535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 07:05:08.411  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 07:05:08.418  4450  4533 D bt_stack_manager: event_shut_down_stack finished.
10-12 07:05:08.418  4450  4532 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-12 07:05:08.419  3693  3693 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 07:05:08.419  4450  4450 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 07:05:08.420  4450  4450 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 07:05:08.420  4450  4450 D BtGatt.GattService: stop()
10-12 07:05:08.420  4450  4450 D BtGatt.AdvertiseManager: advertise clients cleared
10-12 07:05:08.420  4450  4532 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-12 07:05:08.421  3693  3693 D SystemUpdateService: onCreate
10-12 07:05:08.422  4450  4450 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:08.422  4450  4450 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:08.422  4450  4450 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:08.422  4450  4450 V BluetoothAdapterState: isBleTurningOff()=true
10-12 07:05:08.423  4450  4532 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-12 07:05:08.423  4450  4532 D BluetoothAdapterProperties: Setting state to 10
10-12 07:05:08.423  4450  4532 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 07:05:08.423  4450  4532 I BluetoothAdapterState: Entering OffState
10-12 07:05:08.424   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-12 07:05:08.425  3693  3693 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 07:05:08.429  4450  4450 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-12 07:05:08.429  4450  4450 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 07:05:08.430  4450  4450 I BluetoothServiceJni: cleanupNative: return from cleanup
10-12 07:05:08.431  4450  4533 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-12 07:05:08.441  4450  4533 D bt_stack_manager: event_clean_up_stack finished.
10-12 07:05:08.442  4450  4450 I art     : System.exit called, status: 0
10-12 07:05:08.442  4450  4450 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-12 07:05:08.443  3693  3693 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-12 07:05:08.450  3693  3693 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-12 07:05:08.451  3693  3693 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-12 07:05:08.454  5253  5253 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-12 07:05:08.457  5253  5253 D SprintDMHelper: simOperator: 
10-12 07:05:08.457  5253  5253 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-12 07:05:08.467  4874  5603 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 07:05:08.473  3693  5250 I iu.UploadsManager: num queued entries: 0
,10-12 07:05:08.473  3693  5250 I iu.UploadsManager: num updated entries: 0
10-12 07:05:08.474  3693  5250 I iu.SyncManager: NEXT; no task
,10-12 07:05:08.481   928  3655 I ActivityManager: Start proc 5604:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-12 07:05:08.482  5535  5535 D DockEventReceiver: finishStartingService: stopping service
,10-12 07:05:08.496  3693  5600 I SystemUpdateService: active receiver: enabled
,10-12 07:05:08.508  5604  5604 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-12 07:05:08.513   928   945 D Tethering: InitialState.processMessage what=4
,10-12 07:05:08.515   928  3496 I ActivityManager: Killing 5114:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-12 07:05:08.536  3693  5600 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 07:05:08.538  3693  5600 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-12 07:05:08.538  3693  5600 I SystemUpdateService: now status is 0 (complete)
10-12 07:05:08.538  3693  5600 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 07:05:08.538  3693  5600 I SystemUpdateService: file has been verified
10-12 07:05:08.538  3693  5600 I SystemUpdateService: OTA package size = 21989297
,10-12 07:05:08.548   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 07:05:08.548   928  3667 I ActivityManager: Process com.android.bluetooth (pid 4450) has died
,10-12 07:05:08.571  3693  5600 I SystemUpdateService: showing system update notification
,10-12 07:05:08.611  3693  3693 D SystemUpdateService: onDestroy
,10-12 07:05:08.612   928  3667 I ActivityManager: Killing 4547:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-12 07:05:08.719  5566  5591 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-12 07:05:08.727   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6e9b1f:true
,10-12 07:05:13.013   928  3684 D WifiService: setWifiEnabled: true pid=5482, uid=10077
10-12 07:05:13.013   928  3684 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 07:05:13.021   506   924 D SoftapController: Softap fwReload - Ok
10-12 07:05:13.026   506   924 D CommandListener: Setting iface cfg
10-12 07:05:13.026   506   924 D CommandListener: Trying to bring down wlan0
,10-12 07:05:13.029   506   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 07:05:13.035   928  2819 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 07:05:13.605   928  2819 D wifi    : set interface wlan0 flags (UP)
,10-12 07:05:13.609   928  2819 I WifiHAL : Initializing wifi
10-12 07:05:13.610   928  2819 I WifiHAL : Creating socket
10-12 07:05:13.611   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 07:05:13.619   928  2819 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-12 07:05:13.619   928  2819 D wifi    : Did set static halHandle = 0x7f6fa03680
10-12 07:05:13.619   928  2819 D wifi    : halHandle = 0x7f6fa03680, mVM = 0x7f8c08d140, mCls = 0x194a
10-12 07:05:13.619   928  2819 D wifi    : array field set
10-12 07:05:13.619   928  2819 I WifiNative-HAL: interface[0] = wlan0
10-12 07:05:13.621   928  5621 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547333617280
10-12 07:05:13.621   928  5621 D wifi    : waitForHalEvents called, vm = 0x7f8c08d140, obj = 0x194a, env = 0x7f6d3f6080
,10-12 07:05:13.697  5622  5622 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 07:05:13.717  5622  5622 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 07:05:13.722   928  2819 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 07:05:13.731  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:13.734  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:13.735  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:13.741  5622  5622 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 07:05:13.741  5622  5622 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 07:05:13.756   928  2819 D WifiConfigStore: Loading config and enabling all networks 
,10-12 07:05:13.757  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:13.757  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:13.757  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:13.757  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:13.758  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:13.758  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:13.759  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:13.759  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:13.760  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:13.760  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:13.760  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:13.760  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:13.765   928  2819 D WifiConfigStore: loaded 0 passpoint configs
,10-12 07:05:13.766   928  2819 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 07:05:13.766   928  2819 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-12 07:05:13.767   928  2819 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-12 07:05:13.768   928  2819 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-12 07:05:13.768   928  2819 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 07:05:13.768   928  2819 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 07:05:13.768   928  2819 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 07:05:13.773  4874  4874 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 07:05:13.773   928  2819 D WifiNative-HAL: Setting external_sim to 1
10-12 07:05:13.773   928  2819 D wifi    : setting dfs flag to true, 0x7f70efeba0
10-12 07:05:13.774   928  2819 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 07:05:13.774   928  2819 D wifi    : setting scan oui 0x7f70efeba0
10-12 07:05:13.774   928  2819 D WifiHAL : Sending mac address OUI
,10-12 07:05:13.777   928  2819 E native  : do suspend false
,10-12 07:05:13.785   928  2819 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 07:05:13.785   928   928 D RttService: SCAN_AVAILABLE : 3
10-12 07:05:13.785   506   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 07:05:13.785   928  2878 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 07:05:13.786   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:13.790   928  2807 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-12 07:05:13.790   928  2807 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 07:05:13.798   928  2807 D WifiNative-HAL: p2pGetDeviceAddress
10-12 07:05:13.799   928  2807 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 07:05:13.816   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268263 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=26 mControllerEnergyUsed=98 }
,10-12 07:05:16.945  5622  5622 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:16.950  5622  5622 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:16.955  5622  5622 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:17.010   928  2819 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-12 07:05:17.012   928  2819 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-12 07:05:17.012   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:17.027   928  2819 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 07:05:17.066   928  2819 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 07:05:17.068  5622  5622 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 07:05:17.500  5622  5622 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 07:05:17.532  5622  5622 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 07:05:17.534  5622  5622 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 07:05:17.541   928  2819 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 07:05:17.541   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 07:05:17.541   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 07:05:17.555   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:17.565   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:17.569   928  2819 D WifiStateMachine: Start Dhcp Watchdog 2
,10-12 07:05:17.575   928  5628 D DhcpClient: Receive thread started
,10-12 07:05:17.580   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 07:05:17.580   928  2819 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-12 07:05:17.580   928  2821 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-12 07:05:17.667   928  2819 E native  : do suspend false
,10-12 07:05:17.687   928  5627 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 07:05:17.706   928  5628 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,10-12 07:05:17.707   928  5627 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,10-12 07:05:17.710   928  5627 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 07:05:17.732   928  5628 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-12 07:05:17.734   928  5627 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-12 07:05:17.738   506   924 D CommandListener: Setting iface cfg
10-12 07:05:17.742   928  2819 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 07:05:17.750   928  5627 D DhcpClient: Scheduling renewal in 86399s
,10-12 07:05:17.759   928  2819 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 07:05:17.760   928  2819 D WifiConfigStore: No blacklist allowed without epno enabled
,10-12 07:05:17.761   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-12 07:05:17.767   928  2821 D ConnectivityService: Adding iface wlan0 to network 101
10-12 07:05:17.769   928  2819 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 07:05:17.816   928  2821 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-12 07:05:17.817   928  2821 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
10-12 07:05:17.820   928  2821 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-12 07:05:17.823   928  2821 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-12 07:05:17.828   928  2821 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-12 07:05:17.837   928  2821 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 07:05:17.842   928  2821 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-12 07:05:17.842   928  2821 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-12 07:05:17.842   928  2821 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-12 07:05:17.842   928  2819 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-12 07:05:17.842   928  2821 D ConnectivityService:    accepting network in place of null
10-12 07:05:17.842   928  2819 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 07:05:17.843   928  2821 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 07:05:17.862   928  5626 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272310, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 07:05:17.867   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 07:05:17.889   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 07:05:17.893   928  2821 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-12 07:05:17.894   928  2821 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 07:05:17.894  3583  3719 W QCNEJ   : |CORE| network available: 101
10-12 07:05:17.895   928  2821 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-12 07:05:17.896   928   945 D Tethering: MasterInitialState.processMessage what=3
10-12 07:05:17.898  3583  3719 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-12 07:05:17.899  3583  3719 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 07:05:17.899  3583  3719 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-12 07:05:17.902  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:17.902  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:17.902  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:17.902  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:17.905  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:17.905  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:17.905  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:17.905  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:17.907  4899  4919 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 07:05:17.907  4899  4919 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 07:05:17.907  4899  4919 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 07:05:17.907  4899  4919 E SarControlService: no key has been found,reset the power
10-12 07:05:17.907  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:17.907  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:17.907  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 07:05:17.907  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:17.907  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:17.907  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 07:05:17.907  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 07:05:17.908  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:17.908  4924  4924 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 07:05:17.911  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 07:05:17.911  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 07:05:17.911  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 07:05:17.911  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:17.911  4924  4924 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 07:05:17.913  3693  3693 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 07:05:17.916  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000ec03000000000000ffffffff]
,10-12 07:05:17.916  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:17.916  4924  4938 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-12 07:05:17.917  3693  3693 D SystemUpdateService: onCreate
10-12 07:05:17.918  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000ed03000000000000ffffffff]
10-12 07:05:17.918  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:17.918  4924  4938 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-12 07:05:17.918  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:17.918  4899  4909 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 07:05:17.919  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-12 07:05:17.919  4899  4910 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 07:05:17.922  3693  3693 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 07:05:17.932   928  5625 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-12 07:05:17.933  3693  3693 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 07:05:17.938  3693  5250 I iu.UploadsManager: num queued entries: 0
10-12 07:05:17.938  3693  5250 I iu.UploadsManager: num updated entries: 0
,10-12 07:05:17.945  3693  3693 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 07:05:17.947  3693  3693 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 07:05:17.949  5253  5253 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 07:05:17.953  5253  5253 D SprintDMHelper: simOperator: 
10-12 07:05:17.953  5253  5253 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 07:05:17.955  3693  5638 I SystemUpdateService: active receiver: enabled
,10-12 07:05:17.961  3693  5250 I iu.SyncManager: NEXT; no task
,10-12 07:05:17.974  3693  5638 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 07:05:17.985  3693  5638 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-12 07:05:17.985  3693  5638 I SystemUpdateService: now status is 0 (complete)
10-12 07:05:17.985  3693  5638 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 07:05:17.985  3693  5638 I SystemUpdateService: file has been verified
10-12 07:05:17.985  3693  5638 I SystemUpdateService: OTA package size = 21989297
,10-12 07:05:17.988   928  5625 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 11:05:17 GMT], X-Android-Received-Millis=[1476270317987], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476270317962]}
,10-12 07:05:17.989   928  2821 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 07:05:17.989   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-12 07:05:17.989   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-12 07:05:17.990   928  2821 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 07:05:17.991  3693  5638 I SystemUpdateService: showing system update notification
,10-12 07:05:18.002  3693  3693 D SystemUpdateService: onDestroy
,10-12 07:05:18.017   928   938 D WifiService: setWifiEnabled: false pid=5482, uid=10077
,10-12 07:05:18.017   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 07:05:18.019   928  2819 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-12 07:05:18.019   928  2819 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-12 07:05:18.019   928  2819 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 07:05:18.019   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:18.030   928  5627 D DhcpClient: Clearing IP address
10-12 07:05:18.030   506   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 07:05:18.033   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:18.035  3410  5639 V NativeCrypto: SSL handshake aborted: ssl=0x7f70b83e00: I/O error during system call, Connection timed out
,10-12 07:05:18.040   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-12 07:05:18.040   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-12 07:05:18.042   928  5628 D DhcpClient: Receive thread stopped
10-12 07:05:18.043   928   928 D RttService: SCAN_AVAILABLE : 1
10-12 07:05:18.045   928  2878 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 07:05:18.045   538   538 E Parcel  : Reading a NULL string not supported here.
10-12 07:05:18.047   928  2821 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-12 07:05:18.048  4874  5643 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
10-12 07:05:18.049  3583  3719 W QCNEJ   : |CORE| network lost: 101
10-12 07:05:18.050  3583  3719 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-12 07:05:18.054   928  2819 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-12 07:05:18.057   928  2819 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.206 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
10-12 07:05:18.061  4874  5643 W Babel_NetworkConnectionCheckingService: 	... 23 more
10-12 07:05:18.061  4874  5643 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-12 07:05:18.072   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 07:05:18.090   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 07:05:18.090   506   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 07:05:18.091   928  2821 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-12 07:05:18.091   928  2821 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-12 07:05:18.092   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-12 07:05:18.094   928  2819 D DhcpClient: doQuit
10-12 07:05:18.094   928  2819 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 07:05:18.095   928  5627 D DhcpClient: onQuitting
10-12 07:05:18.095  5622  5622 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 07:05:18.097  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:18.097  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:18.098  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:18.098  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:18.099  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:18.100  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:18.100  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:18.100  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:18.102  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:18.102  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:18.102  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:18.102  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 07:05:18.104  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:18.105  3693  3693 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 07:05:18.105  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:18.106  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:18.107  4899  4919 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 07:05:18.107  4899  4919 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 07:05:18.107  4899  4919 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 07:05:18.107  4899  4919 E SarControlService: no key has been found,reset the power
10-12 07:05:18.107  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 07:05:18.107  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 07:05:18.107  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 07:05:18.108  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:18.108  4924  4924 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-12 07:05:18.109  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 07:05:18.110  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 07:05:18.110  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 07:05:18.110  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:18.110  4924  4924 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 07:05:18.110  5622  5622 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-12 07:05:18.113  3693  3693 D SystemUpdateService: onCreate
10-12 07:05:18.114  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000ee03000000000000ffffffff]
10-12 07:05:18.114  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:18.115  4924  4938 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,10-12 07:05:18.115  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:18.115  5622  5622 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-12 07:05:18.115  4899  4910 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 07:05:18.118  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000ef03000000000000ffffffff]
10-12 07:05:18.118  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:18.118  4924  4938 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-12 07:05:18.119  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:18.119  4899  4909 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 07:05:18.119  3693  3693 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-12 07:05:18.122  3693  5656 I SystemUpdateService: active receiver: enabled
,10-12 07:05:18.127  3693  3693 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 07:05:18.131  3693  5250 I iu.UploadsManager: num queued entries: 0
10-12 07:05:18.131  3693  5250 I iu.UploadsManager: num updated entries: 0
,10-12 07:05:18.133  3693  5656 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 07:05:18.135  3693  5656 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-12 07:05:18.135  3693  5656 I SystemUpdateService: now status is 0 (complete)
,10-12 07:05:18.136  3693  3693 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 07:05:18.137  3693  3693 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 07:05:18.139  5253  5253 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 07:05:18.144  5253  5253 D SprintDMHelper: simOperator: 
10-12 07:05:18.144  5253  5253 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 07:05:18.148   506   924 E Netd    : netlink response contains error (No such file or directory)
,10-12 07:05:18.149   928  2821 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-12 07:05:18.150  3693  5656 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 07:05:18.150  3693  5656 I SystemUpdateService: file has been verified
10-12 07:05:18.151  5622  5622 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 07:05:18.153  3693  5656 I SystemUpdateService: OTA package size = 21989297
,10-12 07:05:18.160  3693  5250 I iu.SyncManager: NEXT; no task
,10-12 07:05:18.160  5622  5622 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-12 07:05:18.161  4874  5660 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 07:05:18.165   928  2819 D wifi    : In wifi stop Hal
,10-12 07:05:18.165   928  2819 D wifi    : halHandle = 0x7f6fa03680, mVM = 0x7f8c08d140, mCls = 0x194a
10-12 07:05:18.165   928  5621 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 07:05:18.165   928  5621 D WifiHAL : Got a signal to exit!!!
10-12 07:05:18.165   928  5621 I WifiHAL : Exit wifi_event_loop
10-12 07:05:18.165  4874  4874 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 07:05:18.165   928  2819 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 07:05:18.165   928  2819 E WifiHAL : Event processing terminated
,10-12 07:05:18.166   928  2819 D wifi    : In wifi cleaned up handler
10-12 07:05:18.166   928  2819 I WifiHAL : Internal cleanup completed
10-12 07:05:18.167  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:18.167  3892  4058 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 07:05:18.167  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:18.168  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:18.179  3693  5656 I SystemUpdateService: showing system update notification
,10-12 07:05:18.186  3693  3693 D SystemUpdateService: onDestroy
,10-12 07:05:18.189   928  5621 D wifi    : set interface wlan0 flags (DOWN)
10-12 07:05:18.189   928  2819 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 07:05:18.396   928   945 D Tethering: InitialState.processMessage what=4
,10-12 07:05:18.404   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 07:05:18.895   928  2821 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-12 07:05:20.058   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:21.059   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:22.060   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:23.057   928   945 I ActivityManager: Start proc 5662:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 07:05:23.061   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:23.153  5662  5662 D AdapterServiceConfig: Adding HeadsetService
,10-12 07:05:23.154  5662  5662 D AdapterServiceConfig: Adding A2dpService
,10-12 07:05:23.154  5662  5662 D AdapterServiceConfig: Adding HidService
10-12 07:05:23.154  5662  5662 D AdapterServiceConfig: Adding HealthService
10-12 07:05:23.154  5662  5662 D AdapterServiceConfig: Adding PanService
,10-12 07:05:23.154  5662  5662 D AdapterServiceConfig: Adding GattService
,10-12 07:05:23.155  5662  5662 D AdapterServiceConfig: Adding BluetoothMapService
10-12 07:05:23.155  5662  5662 D AdapterServiceConfig: Adding SapService
,10-12 07:05:23.168   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e75d73:true
,10-12 07:05:23.169  5662  5662 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 07:05:23.172  5662  5662 I bt_bluedroid: init
,10-12 07:05:23.172  5662  5674 I BluetoothAdapterState: Entering OffState
,10-12 07:05:23.174  5662  5675 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-12 07:05:23.174  5662  5675 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 07:05:23.174  5662  5675 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 07:05:23.174  5662  5675 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-12 07:05:23.174  5662  5662 I bt_bluedroid: get_profile_interface socket
,10-12 07:05:23.176  5662  5678 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 07:05:23.176  5662  5662 I bt_bluedroid: get_profile_interface sdp
10-12 07:05:23.177  5662  5678 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 07:05:23.181  5662  5673 I bt_bluedroid: config_hci_snoop_log
,10-12 07:05:23.182   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 07:05:23.186  5662  5674 D BluetoothAdapterState: Current state: OFF, message: 0
10-12 07:05:23.186  5662  5674 D BluetoothAdapterProperties: Setting state to 14
10-12 07:05:23.186  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-12 07:05:23.187  5662  5674 D BluetoothBondStateMachine: make
,10-12 07:05:23.189  5662  5679 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 07:05:23.192  5662  5674 I BluetoothAdapterState: Entering PendingCommandState
,10-12 07:05:23.193  5662  5662 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 07:05:23.195  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:23.195  5662  5662 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 07:05:23.196  5662  5662 D BtGatt.GattService: Received start request. Starting profile...
10-12 07:05:23.196  5662  5662 D BtGatt.GattService: start()
10-12 07:05:23.196  5662  5662 I bt_bluedroid: get_profile_interface gatt
,10-12 07:05:23.197  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:23.197  5662  5662 D BtGatt.AdvertiseManager: advertise manager created
,10-12 07:05:23.201  5662  5662 V BluetoothAdapterState: isTurningOff()=false
,10-12 07:05:23.201  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:23.201  5662  5662 V BluetoothAdapterState: isBleTurningOn()=true
10-12 07:05:23.201  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:23.202  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 07:05:23.203  5662  5674 I bt_bluedroid: bt_bluedroid
10-12 07:05:23.203  5662  5675 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-12 07:05:23.203  5662  5675 I bt_hci  : start_up
,10-12 07:05:23.208  5662  5675 I bt_vendor: alloc value 0xf3cd3871
,10-12 07:05:23.208  5662  5675 I bt_vendor: init
10-12 07:05:23.208  5662  5675 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 07:05:23.208  5662  5675 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 07:05:23.319  5662  5675 D bt_hci  : start_up starting async portion
10-12 07:05:23.319  5662  5682 I bt_hci  : event_finish_startup
,10-12 07:05:23.319  5662  5682 I bt_hci_h4: hal_open
,10-12 07:05:23.320  5662  5682 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-12 07:05:23.317  5683  5683 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-12 07:05:23.323  5662  5682 I bt_userial_vendor: device fd = 54 open
,10-12 07:05:23.337  5662  5682 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 07:05:23.339  5662  5682 D bt_hwcfg: Chipset BCM4358A3
,10-12 07:05:23.339  5662  5682 D bt_hwcfg: Target name = [BCM4358A3]
10-12 07:05:23.340  5662  5682 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 07:05:23.744  5662  5682 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 07:05:23.744  5662  5682 D bt_hwcfg: Settlement delay -- 100 ms
,10-12 07:05:23.745  5662  5682 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 07:05:23.880  5662  5682 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 07:05:23.880  5662  5682 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-12 07:05:23.882  5662  5682 I bt_hwcfg: vendor lib fwcfg completed
10-12 07:05:23.882  5662  5682 I bt_vendor: firmware callback
10-12 07:05:23.882  5662  5682 I bt_hci  : firmware_config_callback
,10-12 07:05:23.890  5662  5685 I bt_btu  : btu_task pending for preload complete event
,10-12 07:05:23.890  5662  5685 I bt_btu_task: Bluetooth chip preload is complete
,10-12 07:05:23.891  5662  5685 I bt_btu  : btu_task received preload complete event
,10-12 07:05:23.898  5662  5685 I         : BTE_InitTraceLevels -- TRC_HCI
,10-12 07:05:23.898  5662  5685 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-12 07:05:23.898  5662  5685 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 07:05:23.898  5662  5685 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-12 07:05:23.898  5662  5685 I         : BTE_InitTraceLevels -- TRC_AVRC
10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_A2D
,10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_BTM
,10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_GAP
,10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_GATT
,10-12 07:05:23.899  5662  5685 I         : BTE_InitTraceLevels -- TRC_SMP
10-12 07:05:23.900  5662  5685 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-12 07:05:23.900  5662  5685 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 07:05:23.980  5662  5685 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c51549
10-12 07:05:23.980  5662  5685 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c51549 
,10-12 07:05:23.990  5662  5678 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 07:05:23.991  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 07:05:23.992  5662  5678 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 07:05:23.994  5662  5678 D BluetoothAdapterProperties: Name is: Nexus 6P
10-12 07:05:23.996  5662  5678 D BluetoothAdapterProperties: Scan Mode:20
10-12 07:05:23.996  5662  5678 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 07:05:23.997  5662  5678 D bt_hci  : do_postload posting postload work item
10-12 07:05:23.997  5662  5682 I bt_hci  : event_postload
10-12 07:05:23.997  5662  5682 I bt_vendor: sco_config_cb
,10-12 07:05:23.997  5662  5682 I bt_hci  : sco_config_callback postload finished.
10-12 07:05:24.000  5662  5678 D bt_bte_conf: Device ID record 1 : primary
10-12 07:05:24.000  5662  5678 D bt_bte_conf:   vendorId            = 000f
,10-12 07:05:24.000  5662  5678 D bt_bte_conf:   vendorIdSource      = 0001
10-12 07:05:24.000  5662  5678 D bt_bte_conf:   product             = 1200
10-12 07:05:24.000  5662  5678 D bt_bte_conf:   version             = 1436
,10-12 07:05:24.000  5662  5678 D bt_bte_conf:   clientExecutableURL = 
10-12 07:05:24.000  5662  5678 D bt_bte_conf:   serviceDescription  = 
10-12 07:05:24.001  5662  5678 D bt_bte_conf:   documentationURL    = 
10-12 07:05:24.001  5662  5678 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-12 07:05:24.001  5662  5675 D bt_stack_manager: event_start_up_stack finished
10-12 07:05:24.003  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:24.003  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-12 07:05:24.004  5662  5674 D BluetoothAdapterProperties: Setting state to 15
,10-12 07:05:24.004  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-12 07:05:24.005  5662  5674 I BluetoothAdapterState: Entering BleOnState
10-12 07:05:24.010  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:24.011  5662  5674 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-12 07:05:24.011  5662  5674 D BluetoothAdapterProperties: Setting state to 11
10-12 07:05:24.011  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-12 07:05:24.012  5662  5682 I bt_vendor: low_power_mode_cb
10-12 07:05:24.012  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:24.017  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:24.018  5662  5662 D HeadsetService: Received start request. Starting profile...
10-12 07:05:24.018  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:24.021  5662  5662 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 07:05:24.021  5662  5662 D HeadsetStateMachine: make
,10-12 07:05:24.021  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:24.024  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:24.034  5662  5662 D HeadsetStateMachine: max_hf_connections = 1
,10-12 07:05:24.034  5662  5662 I bt_bluedroid: get_profile_interface handsfree
10-12 07:05:24.035  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 07:05:24.035  5662  5678 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-12 07:05:24.036  5662  5674 I BluetoothAdapterState: Entering PendingCommandState
,10-12 07:05:24.038  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:24.040  5662  5662 D A2dpService: Received start request. Starting profile...
10-12 07:05:24.040  5662  5662 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-12 07:05:24.041  5662  5662 I bt_bluedroid: get_profile_interface avrcp
,10-12 07:05:24.046  5662  5662 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 07:05:24.046  5662  5662 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 07:05:24.046  5662  5662 D A2dpStateMachine: make
10-12 07:05:24.047  5662  5662 I bt_bluedroid: get_profile_interface a2dp
,10-12 07:05:24.048  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 07:05:24.049  5662  5694 D A2dpStateMachine: Enter Disconnected: -2
,10-12 07:05:24.051  5662  5662 I BluetoothHidServiceJni: classInitNative: succeeds
10-12 07:05:24.052  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 07:05:24.052  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:24.053  5535  5535 D BluetoothInputDevice: Proxy object connected
,10-12 07:05:24.054  5535  5535 D HidProfile: Bluetooth service connected
10-12 07:05:24.054  5662  5662 D HidService: Received start request. Starting profile...
10-12 07:05:24.054  5662  5662 I bt_bluedroid: get_profile_interface hidhost
10-12 07:05:24.055  5662  5662 D HidService: setHidService(): set to: null
10-12 07:05:24.055  5662  5678 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c3256d
10-12 07:05:24.055  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-12 07:05:24.055  5662  5662 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-12 07:05:24.056  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:24.057  5662  5662 D HealthService: Received start request. Starting profile...
,10-12 07:05:24.058  5662  5662 I bt_bluedroid: get_profile_interface health
,10-12 07:05:24.061  5662  5662 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-12 07:05:24.061  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:24.061   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:24.063  5662  5662 D PanService: Received start request. Starting profile...
,10-12 07:05:24.063  5535  5535 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 07:05:24.063  5662  5662 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 07:05:24.063  5662  5662 I bt_bluedroid: get_profile_interface pan
10-12 07:05:24.063  5535  5535 D PanProfile: Bluetooth service connected
10-12 07:05:24.064  5662  5678 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-12 07:05:24.065  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:24.067  5662  5662 D BluetoothMapService: Received start request. Starting profile...
10-12 07:05:24.067  5662  5662 D BluetoothMapService: start()
,10-12 07:05:24.067  5535  5535 D BluetoothMap: Proxy object connected
,10-12 07:05:24.068  5535  5535 D MapProfile: Bluetooth service connected
10-12 07:05:24.068  5535  5535 D BluetoothMap: getConnectedDevices()
10-12 07:05:24.068  5535  5535 D BluetoothMap: Bluetooth is Not enabled
,10-12 07:05:24.070  5662  5662 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-12 07:05:24.071  5662  5662 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-12 07:05:24.071  5662  5662 D BluetoothMapAppObserver: createReceiver()
,10-12 07:05:24.072  5662  5662 D BluetoothMapAppObserver: initObservers()
,10-12 07:05:24.073  5662  5662 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 07:05:24.079  5662  5662 V SapService: SapBinder()
,10-12 07:05:24.080  5662  5662 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:24.080  5662  5662 D SapService: Received start request. Starting profile...
,10-12 07:05:24.080  5662  5662 V SapService: start()
10-12 07:05:24.082  5662  5662 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:24.082  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.082  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.082  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:24.083  5662  5692 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.083  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.084  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:24.085  5662  5662 V BluetoothAdapterState: isTurningOff()=false
,10-12 07:05:24.085  5662  5662 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:24.085  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:24.085  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:24.085  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-12 07:05:24.085  5662  5674 D BluetoothAdapterProperties: ScanMode =  20
10-12 07:05:24.085  5662  5674 D BluetoothAdapterProperties: State =  11
10-12 07:05:24.086  5662  5674 D BluetoothAdapterProperties: Setting state to 12
10-12 07:05:24.086  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-12 07:05:24.086  5662  5674 I BluetoothAdapterState: Entering OnState
10-12 07:05:24.086  5535  5553 D BluetoothMap: onBluetoothStateChange: up=true
,10-12 07:05:24.087  2951  3162 D BluetoothPan: onBluetoothStateChange on: true
10-12 07:05:24.089  5662  5678 D BluetoothAdapterProperties: Scan Mode:21
10-12 07:05:24.089  5535  5547 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 07:05:24.089  2951  2951 D BluetoothPan: BluetoothPAN Proxy object connected
,10-12 07:05:24.089  5662  5678 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 07:05:24.089  2951  2951 D PanProfile: Bluetooth service connected
10-12 07:05:24.090  3621  3842 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:24.090  5482  5482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-12 07:05:24.090  5535  5553 D BluetoothPan: onBluetoothStateChange on: true
10-12 07:05:24.090   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 07:05:24.091  2951  3800 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 07:05:24.092   928   928 D BluetoothA2dp: Proxy object connected
10-12 07:05:24.093  2951  2951 D BluetoothInputDevice: Proxy object connected
10-12 07:05:24.093  2951  2964 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 07:05:24.093  2951  2951 D HidProfile: Bluetooth service connected
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:24.094  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:24.095   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:24.095  5535  5547 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 07:05:24.096   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:24.096  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:24.096  2951  2962 D BluetoothMap: onBluetoothStateChange: up=true
10-12 07:05:24.097  2951  3800 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-12 07:05:24.098  5662  5662 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 07:05:24.098  2951  2951 D BluetoothMap: Proxy object connected
10-12 07:05:24.098  2951  2951 D MapProfile: Bluetooth service connected
10-12 07:05:24.098  2951  2951 D BluetoothMap: getConnectedDevices()
10-12 07:05:24.098  5662  5662 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:24.099  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:24.100  5662  5662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:24.101  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 07:05:24.102   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:24.102  2951  2951 D BluetoothA2dp: Proxy object connected
10-12 07:05:24.102  2951  2962 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 07:05:24.103   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:24.106  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:24.106  5662  5662 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 07:05:24.108  5535  5535 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-12 07:05:24.108  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:24.108  5482  5482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-12 07:05:24.109  5662  5662 D ObexServerSockets: Succeed to create listening sockets 
,10-12 07:05:24.109  5662  5662 D ObexServerSockets0: startAccept()
10-12 07:05:24.109  5662  5662 D ObexServerSockets0: prepareForNewConnect()
10-12 07:05:24.110  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:24.111  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:24.111  5535  5535 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-12 07:05:24.112  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:24.112  5662  5662 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 07:05:24.112  5662  5662 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 07:05:24.113  5662  5662 D BluetoothMapService: onReceive
10-12 07:05:24.113  5662  5662 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 07:05:24.113  5662  5662 D BluetoothMapService: STATE_ON
10-12 07:05:24.115  5662  5702 D ObexServerSockets0: Accepting socket connection...
10-12 07:05:24.116  5662  5701 D ObexServerSockets0: Accepting socket connection...
10-12 07:05:24.117  5662  5703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:24.118  5662  5703 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 07:05:24.119  5662  5703 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-12 07:05:24.120  5535  5535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 07:05:24.122  5535  5535 D BluetoothA2dp: Proxy object connected
,10-12 07:05:24.126  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 07:05:24.129  5535  5535 D DockEventReceiver: finishStartingService: stopping service
,10-12 07:05:24.133  2951  2951 D BluetoothPbap: Proxy object connected
,10-12 07:05:24.133  2951  2951 D PbapServerProfile: Bluetooth service connected
10-12 07:05:24.133  5535  5535 D BluetoothPbap: Proxy object connected
,10-12 07:05:24.133  5535  5535 D PbapServerProfile: Bluetooth service connected
,10-12 07:05:24.142  5662  5662 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 07:05:24.142  5662  5662 D ObexServerSockets0: prepareForNewConnect()
10-12 07:05:24.142  5662  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 07:05:24.157  5662  5711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 07:05:24.158  5662  5711 I BtOppRfcommListener: Accept thread started.
,10-12 07:05:24.192   928   928 D BluetoothHeadset: Proxy object connected
,10-12 07:05:24.192   928   928 D BluetoothHeadset: Proxy object connected
10-12 07:05:24.192  3621  3638 D BluetoothHeadset: Proxy object connected
10-12 07:05:24.192   928   928 D BluetoothHeadset: Proxy object connected
10-12 07:05:24.192  2951  3162 D BluetoothHeadset: Proxy object connected
10-12 07:05:24.193  2951  2951 D HeadsetProfile: Bluetooth service connected
,10-12 07:05:24.195   928   945 D BluetoothHeadset: Proxy object connected
,10-12 07:05:24.196   928   945 D BluetoothHeadset: Proxy object connected
,10-12 07:05:24.202   928   945 D BluetoothHeadset: Proxy object connected
,10-12 07:05:24.203  2951  3800 D BluetoothHeadset: Proxy object connected
10-12 07:05:24.203  2951  2951 D HeadsetProfile: Bluetooth service connected
,10-12 07:05:24.216  5535  5547 D BluetoothHeadset: Proxy object connected
,10-12 07:05:24.218  5535  5535 D HeadsetProfile: Bluetooth service connected
,10-12 07:05:25.062   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-12 07:05:25.848   928  2821 D ConnectivityService: handlePromptUnvalidated 101
,10-12 07:05:28.030  5662  5674 D BluetoothAdapterState: Current state: ON, message: 23
,10-12 07:05:28.031  5662  5674 D BluetoothAdapterProperties: Setting state to 13
,10-12 07:05:28.031  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-12 07:05:28.033  5662  5674 D BluetoothAdapterProperties: onBluetoothDisable()
,10-12 07:05:28.035  5662  5674 I BluetoothAdapterState: Entering PendingCommandState
10-12 07:05:28.042  5662  5678 D BluetoothAdapterProperties: Scan Mode:20
10-12 07:05:28.043  5662  5662 D BluetoothMapService: onReceive
10-12 07:05:28.043  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-12 07:05:28.043  5662  5662 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 07:05:28.043  5662  5662 D BluetoothMapService: STATE_TURNING_OFF
,10-12 07:05:28.044  5662  5662 D BluetoothMapService: MAP Service closeService in
10-12 07:05:28.044  5662  5662 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 07:05:28.044  5662  5662 D ObexServerSockets0: shutdown(block = true)
10-12 07:05:28.045  5662  5662 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 07:05:28.045  5662  5701 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-12 07:05:28.045  5662  5702 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-12 07:05:28.046  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:28.046  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:28.047  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:28.047  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 07:05:28.048  5662  5662 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-12 07:05:28.050  5662  5687 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 07:05:28.050  5535  5535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 07:05:28.054  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:28.054  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:28.056  5662  5662 I BtOppRfcommListener: stopping Accept Thread
10-12 07:05:28.056  5662  5711 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 07:05:28.056  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:28.056  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:28.056  5662  5711 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-12 07:05:28.061  5662  5662 D HeadsetService: Received stop request...Stopping profile...
10-12 07:05:28.062  5535  5535 D DockEventReceiver: finishStartingService: stopping service
10-12 07:05:28.065   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:28.065   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:28.066  3621  4653 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:28.067  5535  5547 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:28.067   928   928 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:28.067  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:28.067  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:28.067  2951  3162 D BluetoothHeadset: Proxy object disconnected
10-12 07:05:,28.067  5662  5662 D A2dpService: Received stop request...Stopping profile...
10-12 07:05:28.068  5662  5694 D A2dpStateMachine: Exit Disconnected: -1
10-12 07:05:28.068  5482  5482 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 07:05:28.068  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:28.068  5535  5535 D HeadsetProfile: Bluetooth service disconnected
10-12 07:05:28.070  2951  2951 D HeadsetProfile: Bluetooth service disconnected
10-12 07:05:28.070   928   928 D BluetoothA2dp: Proxy object disconnected
10-12 07:05:28.071  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:28.072  2951  2951 D BluetoothA2dp: Proxy object disconnected
10-12 07:05:28.073  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:28.074  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:28.075  5662  5662 D HidService: Received stop request...Stopping profile...
10-12 07:05:28.075  5662  5662 D HidService: Stopping Bluetooth HidService
10-12 07:05:28.076  2951  2951 D BluetoothInputDevice: Proxy object disconnected
10-12 07:05:28.076  2951  2951 D HidProfile: Bluetooth service disconnected
,10-12 07:05:28.077  5662  5662 D HealthService: Received stop request...Stopping profile...
10-12 07:05:28.079  5662  5662 D PanService: Received stop request...Stopping profile...
10-12 07:05:28.080  2951  2951 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 07:05:28.080  2951  2951 D PanProfile: Bluetooth service disconnected
10-12 07:05:28.082  5535  5535 D BluetoothA2dp: Proxy object disconnected
10-12 07:05:28.083  5535  5535 D BluetoothInputDevice: Proxy object disconnected
10-12 07:05:28.083  5535  5535 D HidProfile: Bluetooth service disconnected
10-12 07:05:28.083  5535  5535 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 07:05:28.083  5535  5535 D PanProfile: Bluetooth service disconnected
10-12 07:05:28.083  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 07:05:28.084  5662  5662 D BluetoothMapService: Received stop request...Stopping profile...
10-12 07:05:28.084  5662  5662 D BluetoothMapService: stop()
,10-12 07:05:28.086  5662  5662 D BluetoothMapAppObserver: deinitObservers()
10-12 07:05:28.086  5662  5662 D BluetoothMapAppObserver: removeReceiver()
10-12 07:05:28.087  2951  2951 D BluetoothMap: Proxy object disconnected
,10-12 07:05:28.088  2951  2951 D MapProfile: Bluetooth service disconnected
10-12 07:05:28.088  5535  5535 D BluetoothMap: Proxy object disconnected
10-12 07:05:28.088  5535  5535 D MapProfile: Bluetooth service disconnected
10-12 07:05:28.088  5662  5662 D SapService: Received stop request...Stopping profile...
10-12 07:05:28.088  5662  5662 V SapService: stop()
,10-12 07:05:28.090  5662  5662 V BluetoothAdapterState: isTurningOff()=true
,10-12 07:05:28.090  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:28.090  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.090  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.092  5662  5662 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-12 07:05:28.092  5662  5662 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-12 07:05:28.092  5662  5685 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:28.092  5662  5685 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:28.092  5662  5662 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:28.092  5662  5685 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:28.092  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:28.093  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.093  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.093  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-12 07:05:28.099  5662  5678 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-12 07:05:28.099  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 07:05:28.099  5662  5662 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:28.099  5662  5685 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 07:05:28.099  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:28.099  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.100  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.100  5662  5685 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 07:05:28.100  5662  5662 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 07:05:28.100  5662  5662 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 07:05:28.100  5662  5685 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 07:05:28.100  5662  5685 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 07:05:28.100  5662  5678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 07:05:28.100  5662  5662 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:28.100  5662  5685 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 07:05:28.100  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:28.100  5662  5685 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 07:05:28.100  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.100  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.101  5662  5662 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 07:05:28.101  5662  5678 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 07:05:28.101  5662  5662 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 07:05:28.102  5662  5662 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:28.102  5662  5662 V BluetoothAdapterState: isTurningOn()=false
,10-12 07:05:28.102  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.102  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.102  5662  5662 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 07:05:28.103  5662  5662 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-12 07:05:28.106  2951  2951 D BluetoothPbap: Proxy object disconnected
10-12 07:05:28.106  2951  2951 D PbapServerProfile: Bluetooth service disconnected
10-12 07:05:28.106  5535  5535 D BluetoothPbap: Proxy object disconnected
10-12 07:05:28.106  5535  5535 D PbapServerProfile: Bluetooth service disconnected
10-12 07:05:28.106  5662  5662 D BluetoothMapService: MAP Service closeService in
10-12 07:05:28.106  5662  5662 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:28.106  5662  5662 V BluetoothAdapterState: isTurningOn()=false
,10-12 07:05:28.106  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.106  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.107  5662  5662 D BluetoothMapService: cleanup()
10-12 07:05:28.107  5662  5662 D BluetoothMapService: MAP Service closeService in
10-12 07:05:28.107  5662  5662 V BluetoothAdapterState: isTurningOff()=true
10-12 07:05:28.107  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:28.107  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.107  5662  5662 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:28.108  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-12 07:05:28.108  5662  5674 D BluetoothAdapterProperties: Setting state to 15
,10-12 07:05:28.108  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 07:05:28.108  5662  5674 I BluetoothAdapterState: Entering BleOnState
,10-12 07:05:28.108  5535  5553 D BluetoothMap: onBluetoothStateChange: up=false
10-12 07:05:28.110  2951  3162 D BluetoothPan: onBluetoothStateChange on: false
,10-12 07:05:28.111  5535  5547 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 07:05:28.111  5535  5553 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:28.112  3621  3635 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:28.112  5535  5547 D BluetoothPan: onBluetoothStateChange on: false
10-12 07:05:28.113   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 07:05:28.113  2951  3800 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 07:05:28.113  2951  2964 D BluetoothPbap: onBluetoothStateChange: up=false
,10-12 07:05:28.114   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:28.114  5535  5553 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 07:05:28.115   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:28.115  2951  2962 D BluetoothMap: onBluetoothStateChange: up=false
10-12 07:05:28.115  5535  5547 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 07:05:28.116  2951  3162 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 07:05:28.116   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:28.117  2951  3800 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 07:05:28.117  5662  5674 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 07:05:28.117  5662  5674 D BluetoothAdapterProperties: Setting state to 16
10-12 07:05:28.117  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 07:05:28.118  5662  5674 D BluetoothAdapterProperties: onBleDisable
,10-12 07:05:28.118  5662  5674 I BluetoothAdapterState: Entering PendingCommandState
10-12 07:05:28.118  5662  5675 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 07:05:28.121  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:28.121  5662  5685 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 07:05:28.121  5662  5685 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 07:05:28.122  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:28.123  5662  5678 D BluetoothAdapterProperties: Scan Mode:20
10-12 07:05:28.124  5535  5535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 07:05:28.125  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:28.127  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:28.128  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:28.129  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:28.132  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 07:05:28.133  5535  5535 D DockEventReceiver: finishStartingService: stopping service
,10-12 07:05:28.333  5662  5678 I bt_hci  : shut_down
,10-12 07:05:28.337  5662  5682 D bt_hwcfg: hw_epilog_process
,10-12 07:05:28.338  5662  5682 I bt_vendor: low_power_mode_cb
,10-12 07:05:28.341  5662  5682 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-12 07:05:28.342  5662  5682 I bt_vendor: epilog_cb
10-12 07:05:28.342  5662  5682 I bt_hci  : epilog_finished_callback
,10-12 07:05:28.347  5662  5678 I bt_hci_h4: hal_close
,10-12 07:05:28.348  5662  5678 I bt_userial_vendor: device fd = 54 close
,10-12 07:05:28.471  5662  5675 D bt_stack_manager: event_shut_down_stack finished.
,10-12 07:05:28.471  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-12 07:05:28.475  5662  5674 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-12 07:05:28.475  5662  5662 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 07:05:28.476  5662  5662 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 07:05:28.477  5662  5662 D BtGatt.GattService: stop()
,10-12 07:05:28.477  5662  5662 D BtGatt.AdvertiseManager: advertise clients cleared
,10-12 07:05:28.481  5662  5662 V BluetoothAdapterState: isTurningOff()=false
,10-12 07:05:28.481  5662  5662 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:28.481  5662  5662 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:28.481  5662  5662 V BluetoothAdapterState: isBleTurningOff()=true
,10-12 07:05:28.482  5662  5674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-12 07:05:28.482  5662  5674 D BluetoothAdapterProperties: Setting state to 10
10-12 07:05:28.482  5662  5674 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 07:05:28.483  5662  5674 I BluetoothAdapterState: Entering OffState
10-12 07:05:28.484   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-12 07:05:28.497  5662  5662 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-12 07:05:28.497  5662  5662 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 07:05:28.497  5662  5662 I BluetoothServiceJni: cleanupNative: return from cleanup
10-12 07:05:28.500  5662  5675 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-12 07:05:28.507  5662  5662 I art     : System.exit called, status: 0
,10-12 07:05:28.508  5662  5662 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 07:05:28.539   928  3243 I ActivityManager: Process com.android.bluetooth (pid 5662) has died
,10-12 07:05:33.031  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:05:33.031  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:33.036  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:05:33.036  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@115df00 removed from the list
10-12 07:05:33.036  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:05:33.036  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:33.036  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:33.040  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 07:05:33.040  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfa8d7e added. We now have 4 listener(s)
,10-12 07:05:33.040  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:33.041  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:33.042  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfa8d7e removed from the list
,10-12 07:05:33.042  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:33.042  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:33.042  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:33.044  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 07:05:33.044  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3ed2df added. We now have 4 listener(s)
10-12 07:05:33.044  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:38.055  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:38.085   928   945 I ActivityManager: Start proc 5719:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 07:05:38.169  5719  5719 D AdapterServiceConfig: Adding HeadsetService
,10-12 07:05:38.169  5719  5719 D AdapterServiceConfig: Adding A2dpService
10-12 07:05:38.170  5719  5719 D AdapterServiceConfig: Adding HidService
10-12 07:05:38.170  5719  5719 D AdapterServiceConfig: Adding HealthService
10-12 07:05:38.170  5719  5719 D AdapterServiceConfig: Adding PanService
10-12 07:05:38.170  5719  5719 D AdapterServiceConfig: Adding GattService
10-12 07:05:38.170  5719  5719 D AdapterServiceConfig: Adding BluetoothMapService
,10-12 07:05:38.170  5719  5719 D AdapterServiceConfig: Adding SapService
,10-12 07:05:38.181   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@adb60f0:true
10-12 07:05:38.182  5719  5719 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 07:05:38.184  5719  5719 I bt_bluedroid: init
10-12 07:05:38.185  5719  5731 I BluetoothAdapterState: Entering OffState
,10-12 07:05:38.187  5719  5732 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-12 07:05:38.187  5719  5732 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 07:05:38.188  5719  5732 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 07:05:38.188  5719  5732 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-12 07:05:38.189  5719  5719 I bt_bluedroid: get_profile_interface socket
,10-12 07:05:38.191  5719  5735 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 07:05:38.191  5719  5719 I bt_bluedroid: get_profile_interface sdp
10-12 07:05:38.192  5719  5735 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 07:05:38.196  5719  5730 I bt_bluedroid: config_hci_snoop_log
,10-12 07:05:38.197   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 07:05:38.202  5719  5731 D BluetoothAdapterState: Current state: OFF, message: 0
,10-12 07:05:38.202  5719  5731 D BluetoothAdapterProperties: Setting state to 14
10-12 07:05:38.202  5719  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-12 07:05:38.204  5719  5731 D BluetoothBondStateMachine: make
,10-12 07:05:38.206  5719  5736 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 07:05:38.209  5719  5731 I BluetoothAdapterState: Entering PendingCommandState
,10-12 07:05:38.210  5719  5719 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 07:05:38.213  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:38.214  5719  5719 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 07:05:38.214  5719  5719 D BtGatt.GattService: Received start request. Starting profile...
10-12 07:05:38.214  5719  5719 D BtGatt.GattService: start()
10-12 07:05:38.214  5719  5719 I bt_bluedroid: get_profile_interface gatt
10-12 07:05:38.216  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:38.216  5719  5719 D BtGatt.AdvertiseManager: advertise manager created
,10-12 07:05:38.221  5719  5719 V BluetoothAdapterState: isTurningOff()=false
,10-12 07:05:38.221  5719  5719 V BluetoothAdapterState: isTurningOn()=false
10-12 07:05:38.222  5719  5719 V BluetoothAdapterState: isBleTurningOn()=true
10-12 07:05:38.222  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 07:05:38.222  5719  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 07:05:38.224  5719  5731 I bt_bluedroid: bt_bluedroid
10-12 07:05:38.224  5719  5732 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-12 07:05:38.224  5719  5732 I bt_hci  : start_up
,10-12 07:05:38.230  5719  5732 I bt_vendor: alloc value 0xf3cd3871
,10-12 07:05:38.230  5719  5732 I bt_vendor: init
10-12 07:05:38.230  5719  5732 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 07:05:38.230  5719  5732 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 07:05:38.340  5719  5732 D bt_hci  : start_up starting async portion
10-12 07:05:38.340  5719  5739 I bt_hci  : event_finish_startup
,10-12 07:05:38.340  5719  5739 I bt_hci_h4: hal_open
10-12 07:05:38.340  5719  5739 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-12 07:05:38.340  5740  5740 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 07:05:38.346  5719  5739 I bt_userial_vendor: device fd = 54 open
,10-12 07:05:38.362  5719  5739 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 07:05:38.366  5719  5739 D bt_hwcfg: Chipset BCM4358A3
,10-12 07:05:38.366  5719  5739 D bt_hwcfg: Target name = [BCM4358A3]
10-12 07:05:38.366  5719  5739 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 07:05:38.820  5719  5739 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 07:05:38.820  5719  5739 D bt_hwcfg: Settlement delay -- 100 ms
,10-12 07:05:38.821  5719  5739 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 07:05:38.955  5719  5739 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 07:05:38.956  5719  5739 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-12 07:05:38.957  5719  5739 I bt_hwcfg: vendor lib fwcfg completed
,10-12 07:05:38.958  5719  5739 I bt_vendor: firmware callback
,10-12 07:05:38.958  5719  5739 I bt_hci  : firmware_config_callback
,10-12 07:05:38.967  5719  5742 I bt_btu  : btu_task pending for preload complete event
10-12 07:05:38.967  5719  5742 I bt_btu_task: Bluetooth chip preload is complete
10-12 07:05:38.967  5719  5742 I bt_btu  : btu_task received preload complete event
,10-12 07:05:38.974  5719  5742 I         : BTE_InitTraceLevels -- TRC_HCI
,10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_AVRC
10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_A2D
,10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 07:05:38.975  5719  5742 I         : BTE_InitTraceLevels -- TRC_BTM
10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_GAP
10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_SDP
,10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_GATT
10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_SMP
10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-12 07:05:38.976  5719  5742 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 07:05:39.056  5719  5742 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c51549
10-12 07:05:39.056  5719  5742 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c51549 
,10-12 07:05:39.071  5719  5735 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 07:05:39.072  5719  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 07:05:39.073  5719  5735 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 07:05:39.076  5719  5735 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 07:05:39.080  5719  5735 D BluetoothAdapterProperties: Scan Mode:20
10-12 07:05:39.080  5719  5735 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 07:05:39.081  5719  5735 D bt_hci  : do_postload posting postload work item
10-12 07:05:39.081  5719  5739 I bt_hci  : event_postload
10-12 07:05:39.081  5719  5739 I bt_vendor: sco_config_cb
10-12 07:05:39.081  5719  5739 I bt_hci  : sco_config_callback postload finished.
,10-12 07:05:39.086  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:39.088  5719  5739 I bt_vendor: low_power_mode_cb
10-12 07:05:39.089  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:39.091  5719  5735 D bt_bte_conf: Device ID record 1 : primary
,10-12 07:05:39.091  5719  5735 D bt_bte_conf:   vendorId            = 000f
,10-12 07:05:39.091  5719  5735 D bt_bte_conf:   vendorIdSource      = 0001
10-12 07:05:39.091  5719  5735 D bt_bte_conf:   product             = 1200
10-12 07:05:39.092  5719  5735 D bt_bte_conf:   version             = 1436
10-12 07:05:39.092  5719  5735 D bt_bte_conf:   clientExecutableURL = 
10-12 07:05:39.092  5719  5735 D bt_bte_conf:   serviceDescription  = 
,10-12 07:05:39.092  5719  5735 D bt_bte_conf:   documentationURL    = 
10-12 07:05:39.092  5719  5735 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-12 07:05:39.092  5719  5732 D bt_stack_manager: event_start_up_stack finished
10-12 07:05:39.093  5719  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-12 07:05:39.094  5719  5731 D BluetoothAdapterProperties: Setting state to 15
,10-12 07:05:39.094  5719  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-12 07:05:39.096  5719  5731 I BluetoothAdapterState: Entering BleOnState
,10-12 07:05:39.101  5719  5731 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-12 07:05:39.101  5719  5731 D BluetoothAdapterProperties: Setting state to 11
10-12 07:05:39.101  5719  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-12 07:05:39.107  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:39.108  5719  5719 D HeadsetService: Received start request. Starting profile...
10-12 07:05:39.111  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:39.113  5719  5719 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 07:05:39.113  5719  5719 D HeadsetStateMachine: make
10-12 07:05:39.115  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:39.125  5719  5731 I BluetoothAdapterState: Entering PendingCommandState
,10-12 07:05:39.126  5719  5719 D HeadsetStateMachine: max_hf_connections = 1
,10-12 07:05:39.126  5719  5719 I bt_bluedroid: get_profile_interface handsfree
10-12 07:05:39.127  5719  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 07:05:39.127  5719  5735 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-12 07:05:39.130  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:39.131  5719  5719 D A2dpService: Received start request. Starting profile...
,10-12 07:05:39.135  5719  5719 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-12 07:05:39.136  5719  5719 I bt_bluedroid: get_profile_interface avrcp
,10-12 07:05:39.145  5719  5719 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 07:05:39.145  5719  5719 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 07:05:39.146  5719  5719 D A2dpStateMachine: make
,10-12 07:05:39.147  5719  5719 I bt_bluedroid: get_profile_interface a2dp
,10-12 07:05:39.147  5719  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-12 07:05:39.150  5719  5719 I BluetoothHidServiceJni: classInitNative: succeeds
10-12 07:05:39.149  5719  5750 D A2dpStateMachine: Enter Disconnected: -2
10-12 07:05:39.151  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:39.152  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 07:05:39.160  5719  5719 D HidService: Received start request. Starting profile...
,10-12 07:05:39.160  5719  5719 I bt_bluedroid: get_profile_interface hidhost
10-12 07:05:39.160  5719  5719 D HidService: setHidService(): set to: null
10-12 07:05:39.160  5719  5735 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c3256d
10-12 07:05:39.160  5719  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-12 07:05:39.161  5719  5719 I BluetoothHealthServiceJni: classInitNative: succeeds
10-12 07:05:39.162  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:39.163  5719  5719 D HealthService: Received start request. Starting profile...
,10-12 07:05:39.164  5719  5719 I bt_bluedroid: get_profile_interface health
,10-12 07:05:39.165  5719  5719 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-12 07:05:39.166  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:39.167  5719  5719 D PanService: Received start request. Starting profile...
,10-12 07:05:39.167  5719  5719 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 07:05:39.167  5719  5719 I bt_bluedroid: get_profile_interface pan
10-12 07:05:39.171  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:39.171  5719  5719 D BluetoothMapService: Received start request. Starting profile...
10-12 07:05:39.172  5719  5719 D BluetoothMapService: start()
10-12 07:05:39.174  5719  5735 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-12 07:05:39.175  5719  5719 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-12 07:05:39.176  5719  5719 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-12 07:05:39.176  5719  5719 D BluetoothMapAppObserver: createReceiver()
10-12 07:05:39.178  5719  5719 D BluetoothMapAppObserver: initObservers()
10-12 07:05:39.178  5719  5719 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 07:05:39.183  5719  5719 V SapService: SapBinder()
,10-12 07:05:39.183  5719  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
10-12 07:05:39.184  5719  5719 D SapService: Received start request. Starting profile...
10-12 07:05:39.184  5719  5719 V SapService: start()
,10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isTurningOff()=false
,10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.185  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:39.186  5719  5747 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:39.186  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isTurningOff()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isTurningOn()=true
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isBleTurningOn()=false
10-12 07:05:39.187  5719  5719 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 07:05:39.188  5719  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-12 07:05:39.188  5719  5731 D BluetoothAdapterProperties: ScanMode =  20
10-12 07:05:39.188  5719  5731 D BluetoothAdapterProperties: State =  11
10-12 07:05:39.188  5719  5731 D BluetoothAdapterProperties: Setting state to 12
10-12 07:05:39.188  5719  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 07:05:39.188  5719  5731 I BluetoothAdapterState: Entering OnState
10-12 07:05:39.189  5535  5553 D BluetoothMap: onBluetoothStateChange: up=true
,10-12 07:05:39.189  5719  5735 D BluetoothAdapterProperties: Scan Mode:21
10-12 07:05:39.189  5719  5735 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 07:05:39.189  5482  5482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-12 07:05:39.192  2951  2964 D BluetoothPan: onBluetoothStateChange on: true
10-12 07:05:39.194  5535  5553 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:39.194  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:39.194  2951  2951 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 07:05:39.194  2951  2951 D PanProfile: Bluetooth service connected
,10-12 07:05:39.195  5535  5547 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:39.196  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:39.196  3621  3635 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:39.197  5535  5553 D BluetoothPan: onBluetoothStateChange on: true
,10-12 07:05:39.198   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 07:05:39.200  2951  3162 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 07:05:39.200  5535  5535 D BluetoothMap: Proxy object connected
,10-12 07:05:39.200  5535  5535 D MapProfile: Bluetooth service connected
,10-12 07:05:39.200  5535  5535 D BluetoothMap: getConnectedDevices()
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:39.202  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:39.203   928   928 D BluetoothA2dp: Proxy object connected
,10-12 07:05:39.204  5719  5719 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 07:05:39.205  5719  5719 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 07:05:39.206  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:39.207  2951  3162 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 07:05:39.207  5535  5535 D BluetoothInputDevice: Proxy object connected
10-12 07:05:39.207  5535  5535 D HidProfile: Bluetooth service connected
10-12 07:05:39.207  5719  5719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:39.209  2951  2951 D BluetoothInputDevice: Proxy object connected
10-12 07:05:39.209  2951  2951 D HidProfile: Bluetooth service connected
10-12 07:05:39.209   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:39.209  5535  5547 D BluetoothPbap: onBluetoothStateChange: up=true
,10-12 07:05:39.210  5535  5535 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 07:05:39.210  5535  5535 D PanProfile: Bluetooth service connected
,10-12 07:05:39.211   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 07:05:39.211  2951  2964 D BluetoothMap: onBluetoothStateChange: up=true
10-12 07:05:39.212  5719  5719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:39.213  5535  5553 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 07:05:39.213  5719  5719 D ObexServerSockets: Succeed to create listening sockets 
10-12 07:05:39.213  5719  5719 D ObexServerSockets0: startAccept()
10-12 07:05:39.213  5719  5719 D ObexServerSockets0: prepareForNewConnect()
10-12 07:05:39.215  2951  3800 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 07:05:39.215  5535  5535 D BluetoothA2dp: Proxy object connected
,10-12 07:05:39.216  5719  5719 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 07:05:39.216  5719  5719 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 07:05:39.216  5719  5758 D ObexServerSockets0: Accepting socket connection...
10-12 07:05:39.216   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:39.216  2951  3162 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 07:05:39.217  5719  5759 D ObexServerSockets0: Accepting socket connection...
10-12 07:05:39.217   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-12 07:05:39.218  5482  5482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 07:05:39.219  5719  5719 D BluetoothMapService: onReceive
,10-12 07:05:39.219  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:39.219  5719  5719 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 07:05:39.219  5719  5719 D BluetoothMapService: STATE_ON
10-12 07:05:39.220  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:39.222  5719  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:39.223  5719  5760 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 07:05:39.223  5719  5760 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-12 07:05:39.224  5535  5535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 07:05:39.228  3410  3410 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 07:05:39.229  5535  5535 D DockEventReceiver: finishStartingService: stopping service
10-12 07:05:39.230  2951  2951 D BluetoothMap: Proxy object connected
10-12 07:05:39.230  2951  2951 D MapProfile: Bluetooth service connected
10-12 07:05:39.230  2951  2951 D BluetoothMap: getConnectedDevices()
10-12 07:05:39.232  5535  5535 D BluetoothPbap: Proxy object connected
10-12 07:05:39.232  5535  5535 D PbapServerProfile: Bluetooth service connected
,10-12 07:05:39.232  2951  2951 D BluetoothA2dp: Proxy object connected
,10-12 07:05:39.236  5719  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 07:05:39.243  5719  5719 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 07:05:39.243  5719  5719 D ObexServerSockets0: prepareForNewConnect()
,10-12 07:05:39.245  2951  2951 D BluetoothPbap: Proxy object connected
,10-12 07:05:39.245  2951  2951 D PbapServerProfile: Bluetooth service connected
,10-12 07:05:39.246  5719  5768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 07:05:39.248  5719  5768 I BtOppRfcommListener: Accept thread started.
,10-12 07:05:39.297   928   928 D BluetoothHeadset: Proxy object connected
,10-12 07:05:39.297   928   928 D BluetoothHeadset: Proxy object connected
10-12 07:05:39.298  3621  3638 D BluetoothHeadset: Proxy object connected
,10-12 07:05:39.298  5535  5756 D BluetoothHeadset: Proxy object connected
,10-12 07:05:39.298   928   928 D BluetoothHeadset: Proxy object connected
10-12 07:05:39.299  2951  3162 D BluetoothHeadset: Proxy object connected
10-12 07:05:39.299  2951  2951 D HeadsetProfile: Bluetooth service connected
10-12 07:05:39.300  5535  5535 D HeadsetProfile: Bluetooth service connected
,10-12 07:05:39.309   928   945 D BluetoothHeadset: Proxy object connected
,10-12 07:05:39.312   928   945 D BluetoothHeadset: Proxy object connected
,10-12 07:05:39.316   928   945 D BluetoothHeadset: Proxy object connected
,10-12 07:05:39.316  2951  2964 D BluetoothHeadset: Proxy object connected
10-12 07:05:39.316  2951  2951 D HeadsetProfile: Bluetooth service connected
,10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:43.071  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:43.077  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:43.078  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:05:43.078  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3ed2df removed from the list
10-12 07:05:43.078  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:43.078  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:43.079  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:43.081  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 07:05:43.082  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c79eb2c added. We now have 4 listener(s)
10-12 07:05:43.082  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:43.087   928  3667 D WifiService: setWifiEnabled: false pid=5482, uid=10077
,10-12 07:05:43.087   928  3667 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 07:05:45.063   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:46.064   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:47.065   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:48.066   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:48.097  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:48.098   928  3639 D WifiService: setWifiEnabled: true pid=5482, uid=10077
,10-12 07:05:48.098   928  3639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 07:05:48.106   506   924 D SoftapController: Softap fwReload - Ok
,10-12 07:05:48.111   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:48.112   506   924 D CommandListener: Trying to bring down wlan0
10-12 07:05:48.113   506   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 07:05:48.119   928  2819 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 07:05:48.743   928  2819 D wifi    : set interface wlan0 flags (UP)
,10-12 07:05:48.744   928  2819 I WifiHAL : Initializing wifi
,10-12 07:05:48.744   928  2819 I WifiHAL : Creating socket
,10-12 07:05:48.751   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 07:05:48.754   928  2819 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-12 07:05:48.754   928  2819 D wifi    : Did set static halHandle = 0x7f6fa03680
10-12 07:05:48.754   928  2819 D wifi    : halHandle = 0x7f6fa03680, mVM = 0x7f8c08d140, mCls = 0x16ee
,10-12 07:05:48.756   928  2819 D wifi    : array field set
10-12 07:05:48.757   928  2819 I WifiNative-HAL: interface[0] = wlan0
,10-12 07:05:48.760   928  5773 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547333617280
10-12 07:05:48.760   928  5773 D wifi    : waitForHalEvents called, vm = 0x7f8c08d140, obj = 0x16ee, env = 0x7f6d3f7700
,10-12 07:05:48.821  5774  5774 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 07:05:48.845  5774  5774 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 07:05:48.855  5774  5774 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 07:05:48.855  5774  5774 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 07:05:48.861   928  2819 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 07:05:48.868  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:48.873  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:48.878   928  2819 D WifiConfigStore: Loading config and enabling all networks 
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:48.880  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 07:05:48.882  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 07:05:48.885  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 07:05:48.887  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 07:05:48.890   928  2819 D WifiConfigStore: loaded 0 passpoint configs
10-12 07:05:48.891   928  2819 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 07:05:48.891   928  2819 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 07:05:48.892   928  2819 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-12 07:05:48.893   928  2819 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-12 07:05:48.893   928  2819 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 07:05:48.893   928  2819 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 07:05:48.893   928  2819 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 07:05:48.896   928  2819 D WifiNative-HAL: Setting external_sim to 1
10-12 07:05:48.897   928  2819 D wifi    : setting dfs flag to true, 0x7f70efe420
10-12 07:05:48.897   928  2819 D WifiStateMachine: Setting OUI to DA-A1-19
,10-12 07:05:48.897   928  2819 D wifi    : setting scan oui 0x7f70efe420
10-12 07:05:48.897   928  2819 D WifiHAL : Sending mac address OUI
10-12 07:05:48.898  4874  4874 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 07:05:48.903   928  2819 E native  : do suspend false
,10-12 07:05:48.911   928  2819 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 07:05:48.911   506   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 07:05:48.911   928   928 D RttService: SCAN_AVAILABLE : 3
,10-12 07:05:48.911   928  2878 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-12 07:05:48.912   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:48.916   928  2807 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-12 07:05:48.916   928  2807 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 07:05:48.927   928  2807 D WifiNative-HAL: p2pGetDeviceAddress
10-12 07:05:48.927   928  2807 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 07:05:48.950   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303397 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=33 mControllerEnergyUsed=125 }
,10-12 07:05:49.067   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:05:50.068   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 07:05:52.096  5774  5774 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:52.102  5774  5774 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:52.108  5774  5774 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:52.113  5774  5774 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 07:05:52.170   928  2819 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-12 07:05:52.171   928  2819 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-12 07:05:52.172   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:52.184   928  2819 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 07:05:52.217   928  2819 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 07:05:52.219  5774  5774 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 07:05:52.668  5774  5774 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 07:05:52.706  5774  5774 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 07:05:52.708  5774  5774 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 07:05:52.719   928  2819 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-12 07:05:52.719   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:52.719   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 07:05:52.735   928  2819 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 07:05:52.746   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:52.752   928  2819 D WifiStateMachine: Start Dhcp Watchdog 3
,10-12 07:05:52.759   928  5779 D DhcpClient: Receive thread started
,10-12 07:05:52.764   928  2819 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-12 07:05:52.764   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-12 07:05:52.764   928  2821 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-12 07:05:52.845   928  2819 E native  : do suspend false
,10-12 07:05:52.856   928  5778 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 07:05:52.868   928  5779 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-12 07:05:52.869   928  5778 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-12 07:05:52.871   928  5778 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 07:05:52.883   928  5779 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-12 07:05:52.883   928  5778 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-12 07:05:52.886   506   924 D CommandListener: Setting iface cfg
,10-12 07:05:52.890   928  2819 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 07:05:52.893   928  5778 D DhcpClient: Scheduling renewal in 86399s
,10-12 07:05:52.901   928  2819 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 07:05:52.901   928  2819 D WifiConfigStore: No blacklist allowed without epno enabled
,10-12 07:05:52.902   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-12 07:05:52.904   928  2821 D ConnectivityService: Adding iface wlan0 to network 102
10-12 07:05:52.913   928  2819 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 07:05:52.956   928  2821 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-12 07:05:52.957   928  2821 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-12 07:05:52.958   928  2821 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-12 07:05:52.962   928  2821 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-12 07:05:52.964   928  2821 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-12 07:05:52.971   928  2821 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 07:05:52.975   928  2821 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-12 07:05:52.975   928  2821 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-12 07:05:52.975   928  2821 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,10-12 07:05:52.975   928  2819 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-12 07:05:52.975   928  2821 D ConnectivityService:    accepting network in place of null
10-12 07:05:52.976   928  2819 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 07:05:52.977   928  2821 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 07:05:52.991   928  5777 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 07:05:53.000   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 07:05:53.020   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 07:05:53.024   928  2821 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-12 07:05:53.024  3583  3719 W QCNEJ   : |CORE| network available: 102
10-12 07:05:53.024   928  2821 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 07:05:53.025   928  2821 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-12 07:05:53.026  3583  3719 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-12 07:05:53.027  3583  3719 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 07:05:53.027  3583  3719 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-12 07:05:53.028   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.034  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.037  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:05:53.040  4899  4919 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 07:05:53.040  4899  4919 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 07:05:53.040  4899  4919 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 07:05:53.040  4899  4919 E SarControlService: no key has been found,reset the power
10-12 07:05:53.040  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 07:05:53.040  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 07:05:53.040  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-12 07:05:53.041  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.041  5482  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 07:05:53.041  4924  4924 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 07:05:53.043  5482  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.044  4899  4934 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 07:05:53.044  4899  4934 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 07:05:53.044  4899  4934 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 07:05:53.045  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 07:05:53.045  4924  4924 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 07:05:53.047  3693  3693 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 07:05:53.051  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000f003000000000000ffffffff]
,10-12 07:05:53.051  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:53.051  4924  4938 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-12 07:05:53.052  4924  4938 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@749ad21 HexData = [00000000f103000000000000ffffffff]
10-12 07:05:53.052  4924  4938 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 07:05:53.052  4924  4938 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-12 07:05:53.053  3693  3693 D SystemUpdateService: onCreate
10-12 07:05:53.053  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:53.054  4899  4910 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 07:05:53.054  4924  4924 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 07:05:53.054  4899  4909 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-12 07:05:53.057  3693  3693 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 07:05:53.067  3693  3693 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 07:05:53.067   928  5776 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-12 07:05:53.074  3693  5250 I iu.UploadsManager: num queued entries: 0
,10-12 07:05:53.074  3693  5250 I iu.UploadsManager: num updated entries: 0
10-12 07:05:53.075  3693  5789 I SystemUpdateService: active receiver: enabled
,10-12 07:05:53.078  3693  3693 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 07:05:53.079  3693  3693 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-12 07:05:53.080  5253  5253 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 07:05:53.084  5253  5253 D SprintDMHelper: simOperator: 
,10-12 07:05:53.084  5253  5253 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 07:05:53.094  3693  5250 I iu.SyncManager: NEXT; no task
,10-12 07:05:53.105  3693  5789 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.113  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.114  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.114  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.114  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c79eb2c removed from the list
10-12 07:05:53.114  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:53.115  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.115  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:53.117  3693  5789 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-12 07:05:53.117  3693  5789 I SystemUpdateService: now status is 0 (complete)
10-12 07:05:53.117  3693  5789 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 07:05:53.117  3693  5789 I SystemUpdateService: file has been verified
10-12 07:05:53.117  3693  5789 I SystemUpdateService: OTA package size = 21989297
10-12 07:05:53.118  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-12 07:05:53.118  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-12 07:05:53.120  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1cb14de Bundle[{}]
10-12 07:05:53.120  5482  5528 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 07:05:53.120  5482  5528 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-12 07:05:53.121  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-12 07:05:53.121  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-12 07:05:53.122  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-12 07:05:53.122  3693  5789 I SystemUpdateService: showing system update notification
10-12 07:05:53.123  5482  5528 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-12 07:05:53.123   928  5776 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 11:05:53 GMT], X-Android-Received-Millis=[1476270353122], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476270353097]}
10-12 07:05:53.123   928  2821 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 07:05:53.124   928  2821 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-12 07:05:53.124   928  2821 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-12 07:05:53.125   928  2821 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 07:05:53.129  5482  5528 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-12 07:05:53.130  5482  5528 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-12 07:05:53.130  5482  5528 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-12 07:05:53.132  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 07:05:53.132  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@598b9f5 added. We now have 3 listener(s)
,10-12 07:05:53.133  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.134  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.134  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.134  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 07:05:53.134  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e038a added. We now have 4 listener(s)
10-12 07:05:53.134  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:53.134  3693  3693 D SystemUpdateService: onDestroy
10-12 07:05:53.135  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 07:05:53.137  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.143  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.145  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:05:53.146  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:05:53.146  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.146  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1308e18 added. We now have 4 listener(s)
10-12 07:05:53.147  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.147  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.147  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.147  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.147  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b880071 added. We now have 5 listener(s)
10-12 07:05:53.147  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.147  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:05:53.147  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:53.148  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:53.148  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:53.148  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.148  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.148  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:05:53.148  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.148  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.148  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@598b9f5 removed from the list
10-12 07:05:53.148  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.148  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e038a removed from the list
,10-12 07:05:53.151  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:53.151  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:53.151  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:53.152  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:05:53.152  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.153  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.153  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.153  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.153  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32e038a not in the list
10-12 07:05:53.153  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.154  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.154  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.154  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.154  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.154  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b880071 removed from the list
10-12 07:05:53.154  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 07:05:53.154  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.154  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.154  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.154  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.155  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1308e18 removed from the list
10-12 07:05:53.155  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.155  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@170ce56 added. We now have 3 listener(s)
,10-12 07:05:53.156  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.157  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.157  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.157  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.157  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86a3ed7 added. We now have 4 listener(s)
10-12 07:05:53.157  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 07:05:53.158  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 07:05:53.160  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.165  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.166  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:05:53.166  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:05:53.167  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.167  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b32ad added. We now have 4 listener(s)
10-12 07:05:53.168  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.168  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.168  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.169  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:53.169  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.169  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4379e2 added. We now have 5 listener(s)
10-12 07:05:53.169  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.170  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:05:53.170  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-12 07:05:53.170  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 07:05:53.170  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:05:53.170  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 07:05:53.171  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:53.172  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 07:05:53.172  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 07:05:53.176  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 07:05:53.176  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 07:05:53.177  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 07:05:53.179  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 07:05:53.180  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 07:05:53.180  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 07:05:53.180  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 07:05:53.180  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 07:05:53.180  5482  5528 D BluetoothAdapter: STATE_ON
,10-12 07:05:53.183  5719  5748 D BtGatt.GattService: registerClient() - UUID=630809f1-ac27-453d-8629-d9ca965d3a88
,10-12 07:05:53.183  5719  5735 D BtGatt.GattService: onClientRegistered() - UUID=630809f1-ac27-453d-8629-d9ca965d3a88, clientIf=5
,10-12 07:05:53.184  5482  5492 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 07:05:53.184  5719  5757 D BtGatt.GattService: start scan with filters
10-12 07:05:53.187  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 07:05:53.187  5719  5738 D BtGatt.ScanManager: handling starting scan
10-12 07:05:53.187  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 07:05:53.187  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:05:53.187  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 07:05:53.187  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 07:05:53.187  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 07:05:53.187  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 07:05:53.188  5719  5738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ec60763
,10-12 07:05:53.190  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:05:53.190  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 07:05:53.191  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 07:05:53.191  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 07:05:53.194  5482  5528 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 07:05:53.194  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:53.194  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 07:05:53.194  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.194  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-12 07:05:53.194  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.194  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 07:05:53.194  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:05:53.194  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 07:05:53.194  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 07:05:53.194  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 07:05:53.194  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 07:05:53.195  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:05:53.196  5719  5735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 07:05:53.196  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.196  5719  5748 D BtGatt.GattService: stopScan() - queue size =1
,10-12 07:05:53.196  5719  5738 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 07:05:53.197  5719  5757 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 07:05:53.197  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 07:05:53.197  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 07:05:53.197  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 07:05:53.197  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:05:53.197  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 07:05:53.197  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 07:05:53.197  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-12 07:05:53.197  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 07:05:53.198  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:05:53.199  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 07:05:53.199  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 07:05:53.199  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 07:05:53.199  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 07:05:53.199  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:05:53.200  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:05:53.200  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 07:05:53.201  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:05:53.201  5719  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 07:05:53.201  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:05:53.202  5719  5738 D BtGatt.ScanManager: Starting BLE batch scan
10-12 07:05:53.202  5719  5738 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 07:05:53.204  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:05:53.204  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:53.204  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:53.204  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.204  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.204  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:05:53.204  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.204  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.204  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@170ce56 removed from the list
10-12 07:05:53.204  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.204  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86a3ed7 removed from the list
10-12 07:05:53.204  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 07:05:53.204  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.205  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.205  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:53.209  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-12 07:05:53.209  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.209  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.209  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86a3ed7 not in the list
10-12 07:05:53.209  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.209  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.210  5719  5735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 07:05:53.210  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.211  4874  5794 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-12 07:05:53.213  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 07:05:53.214  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.214  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.214  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4379e2 removed from the list
10-12 07:05:53.214  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.214  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.214  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.214  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.214  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-12 07:05:53.214  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b32ad removed from the list
10-12 07:05:53.215  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.215  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa3522e added. We now have 3 listener(s)
10-12 07:05:53.216  5719  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 07:05:53.216  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.217  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.217  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.217  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.217  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.217  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82831cf added. We now have 4 listener(s)
,10-12 07:05:53.217  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.218  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 07:05:53.220  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:05:53.222  5719  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 07:05:53.222  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.222  5719  5738 D BtGatt.ScanManager: stopping BLe Batch
,10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.225  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.228  5719  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 07:05:53.228  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.228  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:05:53.228  5719  5738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 07:05:53.228  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 07:05:53.228  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.228  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4d0a65 added. We now have 4 listener(s)
10-12 07:05:53.229  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.229  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.229  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.229  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.229  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216633a added. We now have 5 listener(s)
10-12 07:05:53.230  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.230  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:05:53.230  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:05:53.230  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-12 07:05:53.230  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 07:05:53.230  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:05:53.230  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 07:05:53.233  5719  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 07:05:53.233  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.233  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 07:05:53.233  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 07:05:53.234  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:53.237  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:53.237  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 07:05:53.238  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 07:05:53.238  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 07:05:53.242  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 07:05:53.242  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 07:05:53.242  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 07:05:53.242  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 07:05:53.242  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-12 07:05:53.243  5482  5528 D BluetoothAdapter: STATE_ON
,10-12 07:05:53.245  5719  5757 D BtGatt.GattService: registerClient() - UUID=eb068ecb-8b5a-45ac-b45a-0e79e569ac9b
,10-12 07:05:53.246  5719  5735 D BtGatt.GattService: onClientRegistered() - UUID=eb068ecb-8b5a-45ac-b45a-0e79e569ac9b, clientIf=5
,10-12 07:05:53.246  5482  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 07:05:53.246  5719  5755 D BtGatt.GattService: start scan with filters
,10-12 07:05:53.248  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 07:05:53.248  5719  5738 D BtGatt.ScanManager: handling starting scan
10-12 07:05:53.248  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-12 07:05:53.249  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:05:53.249  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 07:05:53.249  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 07:05:53.249  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 07:05:53.249  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 07:05:53.251  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:05:53.252  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 07:05:53.252  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 07:05:53.253  5719  5735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 07:05:53.253  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 07:05:53.253  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:05:53.253  5719  5738 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 07:05:53.256  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-12 07:05:53.256  5482  5528 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 07:05:53.256  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:53.256  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:53.256  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:53.256  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.256  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.256  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 07:05:53.256  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.257  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.257  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa3522e removed from the list
10-12 07:05:53.257  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 07:05:53.257  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82831cf removed from the list
10-12 07:05:53.257  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:53.257  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:05:53.258  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.258  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-12 07:05:53.258  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.258  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 07:05:53.258  5719  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 07:05:53.258  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.258  5719  5738 D BtGatt.ScanManager: Starting BLE batch scan
10-12 07:05:53.258  5719  5738 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 07:05:53.259  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.259  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.259  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.259  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82831cf not in the list
10-12 07:05:53.259  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:05:53.259  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 07:05:53.260  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 07:05:53.260  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 07:05:53.260  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 07:05:53.262  5482  5528 D BluetoothAdapter: STATE_ON
,10-12 07:05:53.263  5719  5748 D BtGatt.GattService: stopScan() - queue size =1
,10-12 07:05:53.263  5719  5730 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 07:05:53.264  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 07:05:53.264  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 07:05:53.264  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 07:05:53.264  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:05:53.264  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-12 07:05:53.264  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-12 07:05:53.264  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 07:05:53.264  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 07:05:53.265  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:05:53.265  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 07:05:53.265  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 07:05:53.265  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 07:05:53.265  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-12 07:05:53.266  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:53.267  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.267  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.267  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.267  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:05:53.267  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@216633a removed from the list
,10-12 07:05:53.267  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.267  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:05:53.267  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.267  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:05:53.267  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.267  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.267  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.267  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4d0a65 removed from the list
10-12 07:05:53.268  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.268  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4777906 added. We now have 3 listener(s)
10-12 07:05:53.268  5719  5735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 07:05:53.268  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.269  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.269  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.269  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 07:05:53.270  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.270  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e628bc7 added. We now have 4 listener(s)
10-12 07:05:53.270  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.270  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 07:05:53.272  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:05:53.273  5719  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 07:05:53.273  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.276  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.278  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 07:05:53.278  5719  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 07:05:53.278  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.278  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:05:53.278  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.278  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44b211d added. We now have 4 listener(s)
10-12 07:05:53.278  5719  5738 D BtGatt.ScanManager: stopping BLe Batch
10-12 07:05:53.279  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.279  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.279  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.279  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.279  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1821f92 added. We now have 5 listener(s)
10-12 07:05:53.279  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.279  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:05:53.280  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 07:05:53.280  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 07:05:53.280  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 07:05:53.280  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 07:05:53.280  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:53.282  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:53.283  5719  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 07:05:53.283  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.283  5719  5738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 07:05:53.283  5482  5528 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 07:05:53.283  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 07:05:53.286  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 07:05:53.286  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 07:05:53.286  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 07:05:53.287  5719  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 07:05:53.287  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:05:53.289  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 07:05:53.289  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 07:05:53.289  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 07:05:53.289  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 07:05:53.289  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 07:05:53.290  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:05:53.291  5719  5748 D BtGatt.GattService: registerClient() - UUID=8166388f-73da-4829-9cf6-6d052dcade86
10-12 07:05:53.292  5719  5735 D BtGatt.GattService: onClientRegistered() - UUID=8166388f-73da-4829-9cf6-6d052dcade86, clientIf=5
,10-12 07:05:53.292  5482  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 07:05:53.292  5719  5729 D BtGatt.GattService: start scan with filters
10-12 07:05:53.294  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 07:05:53.294  5719  5738 D BtGatt.ScanManager: handling starting scan
10-12 07:05:53.294  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 07:05:53.294  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 07:05:53.294  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 07:05:53.294  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 07:05:53.294  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 07:05:53.294  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 07:05:53.296  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:05:53.296  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 07:05:53.296  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 07:05:53.297  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 07:05:53.298  5719  5735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 07:05:53.299  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.299  5719  5738 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 07:05:53.301  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 07:05:53.301  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:53.301  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:53.301  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.301  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.301  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 07:05:53.301  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.301  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.301  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4777906 removed from the list
,10-12 07:05:53.301  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.301  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e628bc7 removed from the list
10-12 07:05:53.301  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:53.301  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:05:53.302  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.302  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-12 07:05:53.302  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.302  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 07:05:53.303  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.303  5719  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 07:05:53.303  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.303  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.303  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.303  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e628bc7 not in the list
10-12 07:05:53.303  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 07:05:53.303  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 07:05:53.303  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 07:05:53.303  5719  5738 D BtGatt.ScanManager: Starting BLE batch scan
,10-12 07:05:53.303  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 07:05:53.303  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 07:05:53.303  5719  5738 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 07:05:53.304  5482  5528 D BluetoothAdapter: STATE_ON
10-12 07:05:53.304  5719  5729 D BtGatt.GattService: stopScan() - queue size =1
10-12 07:05:53.305  5719  5757 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 07:05:53.305  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 07:05:53.305  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 07:05:53.305  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 07:05:53.305  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-12 07:05:53.305  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 07:05:53.305  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 07:05:53.305  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 07:05:53.305  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 07:05:53.307  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 07:05:53.307  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 07:05:53.307  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 07:05:53.307  5482  5528 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 07:05:53.307  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 07:05:53.308  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.309  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.309  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.309  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.309  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 07:05:53.309  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1821f92 removed from the list
10-12 07:05:53.309  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.309  5482  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 07:05:53.309  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.309  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.309  5482  5482 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 07:05:53.309  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.309  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.309  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44b211d removed from the list
10-12 07:05:53.310  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.310  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71ea2de added. We now have 3 listener(s)
10-12 07:05:53.311  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 07:05:53.311  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.311  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 07:05:53.311  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.311  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2cbf added. We now have 4 listener(s)
10-12 07:05:53.311  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.311  5719  5735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 07:05:53.311  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:05:53.312  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 07:05:53.314  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 07:05:53.315  5719  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 07:05:53.315  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 07:05:53.319  5482  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 07:05:53.320  5482  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 07:05:53.320  5719  5735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 07:05:53.320  5482  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 07:05:53.320  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.320  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 07:05:53.320  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae56d5 added. We now have 4 listener(s)
10-12 07:05:53.320  5719  5738 D BtGatt.ScanManager: stopping BLe Batch
10-12 07:05:53.321  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 07:05:53.321  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 07:05:53.322  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 07:05:53.322  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 07:05:53.322  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76e0eea added. We now have 5 listener(s)
10-12 07:05:53.322  5482  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 07:05:53.322  5482  5528 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 07:05:53.322  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:05:53.322  5482  5528 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 07:05:53.323  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.323  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.323  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 07:05:53.323  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 07:05:53.323  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.323  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.323  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71ea2de removed from the list
10-12 07:05:53.323  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.323  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2cbf removed from the list
,10-12 07:05:53.325  5482  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 07:05:53.325  5719  5735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 07:05:53.325  5482  5528 D io.jxcore.node.ConnectivityMonitor: stop
10-12 07:05:53.325  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.325  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.325  5719  5738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 07:05:53.326  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 07:05:53.326  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 07:05:53.327  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.327  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.327  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.327  5482  5528 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2cbf not in the list
10-12 07:05:53.327  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:05:53.327  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:53.330  5719  5735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-12 07:05:53.330  5719  5735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 07:05:53.330  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 07:05:53.330  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 07:05:53.330  5482  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 07:05:53.330  5482  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76e0eea removed from the list
10-12 07:05:53.330  5482  5528 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 07:05:53.330  5482  5528 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 07:05:53.330  5482  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 07:05:53.330  5482  5528 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 07:05:53.330  5482  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 07:05:53.330  5482  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae56d5 removed from the list
10-12 07:05:53.331  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 07:05:53.331  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 07:05:53.331  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 07:05:53.331  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:05:53.331  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-12 07:05:53.331  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 07:05:53.701  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 07:05:53.768  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 07:05:53.810  5482  5482 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 07:05:55.473  5482  5801 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 07:05:55.473  5482  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:05:56.251  5482  5801 W !!      : call onHalfStreamCopied
,10-12 07:05:56.251  5482  5801 I testCopyDataAndClose: closing input stream
,10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 07:05:57.027  5482  5801 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-12 07:05:57.028  5482  5801 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 07:05:57.028  5482  5801 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 07:06:00.790  5482  5802 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:00.790  5482  5802 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:06:00.981   928  2821 D ConnectivityService: handlePromptUnvalidated 102
,10-12 07:06:02.790  5482  5528 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-12 07:06:02.790  5482  5528 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:06:02.791  5482  5528 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-12 07:06:02.821  5482  5802 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-12 07:06:02.822  5482  5802 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:02.822  5482  5802 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,10-12 07:06:02.933  5482  5803 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 07:06:02.933  5482  5803 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:06:03.928   928  2819 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 07:06:04.548  5482  5803 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 07:06:08.286  5482  5804 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:08.286  5482  5804 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 07:06:08.287  5482  5804 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-12 07:06:08.288  5482  5804 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 07:06:08.288  5482  5804 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:08.288  5482  5804 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-12 07:06:08.289  5482  5528 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-12 07:06:08.293  5482  5805 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:08.293  5482  5805 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 07:06:08.294  5482  5805 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,10-12 07:06:08.294  5482  5805 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:08.294  5482  5805 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-12 07:06:08.295  5482  5805 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-12 07:06:08.295  5482  5805 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 07:06:08.295  5482  5805 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-12 07:06:08.301  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-12 07:06:08.301  5482  5528 I jxcore-log: 
10-12 07:06:08.302  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-12 07:06:08.302  5482  5528 I jxcore-log: 
10-12 07:06:08.302  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-12 07:06:08.302  5482  5528 I jxcore-log: 
10-12 07:06:08.302  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-12 07:06:08.302  5482  5528 I jxcore-log: 
,10-12 07:06:08.303  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Total duration:  90707'
10-12 07:06:08.303  5482  5528 I jxcore-log: 
,10-12 07:06:08.305  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-12 07:06:08.305  5482  5528 I jxcore-log: 
,10-12 07:06:08.310  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.310  5482  5528 I jxcore-log: 
,10-12 07:06:08.312  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.312  5482  5528 I jxcore-log: 
10-12 07:06:08.313  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.313  5482  5528 I jxcore-log: 
10-12 07:06:08.313  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.313  5482  5528 I jxcore-log: 
,10-12 07:06:08.313  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 07:06:08.313  5482  5528 I jxcore-log: 
,10-12 07:06:08.314  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 07:06:08.314  5482  5528 I jxcore-log: 
10-12 07:06:08.314  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.314  5482  5528 I jxcore-log: 
10-12 07:06:08.314  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.314  5482  5528 I jxcore-log: 
10-12 07:06:08.315  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 07:06:08.315  5482  5528 I jxcore-log: 
10-12 07:06:08.315  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 07:06:08.315  5482  5528 I jxcore-log: 
10-12 07:06:08.315  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 07:06:08.315  5482  5528 I jxcore-log: 
10-12 07:06:08.315  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.315  5482  5528 I jxcore-log: 
,10-12 07:06:08.316  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.316  5482  5528 I jxcore-log: 
10-12 07:06:08.316  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.316  5482  5528 I jxcore-log: 
10-12 07:06:08.316  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.316  5482  5528 I jxcore-log: 
10-12 07:06:08.316  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.316  5482  5528 I jxcore-log: 
10-12 07:06:08.317  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.317  5482  5528 I jxcore-log: 
10-12 07:06:08.317  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.317  5482  5528 I jxcore-log: 
10-12 07:06:08.317  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.317  5482  5528 I jxcore-log: 
10-12 07:06:08.317  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.317  5482  5528 I jxcore-log: 
10-12 07:06:08.318  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.318  5482  5528 I jxcore-log: 
,10-12 07:06:08.318  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.318  5482  5528 I jxcore-log: 
10-12 07:06:08.318  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.318  5482  5528 I jxcore-log: 
10-12 07:06:08.319  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.319  5482  5528 I jxcore-log: 
10-12 07:06:08.320  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.320  5482  5528 I jxcore-log: 
10-12 07:06:08.320  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.320  5482  5528 I jxcore-log: 
10-12 07:06:08.320  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.320  5482  5528 I jxcore-log: 
10-12 07:06:08.320  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.320  5482  5528 I jxcore-log: 
10-12 07:06:08.321  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.321  5482  5528 I jxcore-log: 
10-12 07:06:08.321  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.321  5482  5528 I jxcore-log: 
10-12 07:06:08.321  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.321  5482  5528 I jxcore-log: 
10-12 07:06:08.321  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.321  5482  5528 I jxcore-log: 
10-12 07:06:08.322  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.322  5482  5528 I jxcore-log: 
,10-12 07:06:08.322  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.322  5482  5528 I jxcore-log: 
10-12 07:06:08.322  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.322  5482  5528 I jxcore-log: 
10-12 07:06:08.322  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.322  5482  5528 I jxcore-log: 
10-12 07:06:08.322  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.322  5482  5528 I jxcore-log: 
10-12 07:06:08.323  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 07:06:08.323  5482  5528 I jxcore-log: 
10-12 07:06:08.323  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.323  5482  5528 I jxcore-log: 
10-12 07:06:08.323  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 07:06:08.323  5482  5528 I jxcore-log: 
10-12 07:06:08.323  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.323  5482  5528 I jxcore-log: 
10-12 07:06:08.323  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.323  5482  5528 I jxcore-log: 
10-12 07:06:08.324  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.324  5482  5528 I jxcore-log: 
10-12 07:06:08.324  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.324  5482  5528 I jxcore-log: 
10-12 07:06:08.324  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.324  5482  5528 I jxcore-log: 
,10-12 07:06:08.324  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 07:06:08.324  5482  5528 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-12 07:06:08.325  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.325  5482  5528 I jxcore-log: 
10-12 07:06:08.325  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.325  5482  5528 I jxcore-log: 
10-12 07:06:08.325  5482  5528 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 07:06:08.325  5482  5528 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-12 07:06:08.325  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 07:06:08.325  5482  5528 I jxcore-log: 
10-12 07:06:08.325  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 07:06:08.325  5482  5528 I jxcore-log: 
10-12 07:06:08.326  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 07:06:08.326  5482  5528 I jxcore-log: 
10-12 07:06:08.326  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 07:06:08.326  5482  5528 I jxcore-log: 
10-12 07:06:08.328  5482  5482 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-12 07:06:08.331  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-12 07:06:08.331  5482  5528 I jxcore-log: 
10-12 07:06:08.331  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - WARN testUtils: 'myNameCallback not set!'
10-12 07:06:08.331  5482  5528 I jxcore-log: 
10-12 07:06:08.332  5482  5528 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-12 07:06:08.333  5482  5528 I jxcore-log: 2016-10-12 11:06:08 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-12 07:06:08.333  5482  5528 I jxcore-log: 
,10-12 07:06:10.304  5482  5528 I jxcore-log: 2016-10-12 11:06:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-12 07:06:10.304  5482  5528 I jxcore-log: 
,10-12 07:06:10.625  5482  5528 I jxcore-log: 2016-10-12 11:06:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-12 07:06:10.625  5482  5528 I jxcore-log: 
,10-12 07:06:10.644  5482  5528 I jxcore-log: 2016-10-12 11:06:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-12 07:06:10.644  5482  5528 I jxcore-log: 
,10-12 07:06:11.713  5482  5528 I jxcore-log: 2016-10-12 11:06:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-12 07:06:11.713  5482  5528 I jxcore-log: 
,10-12 07:06:11.874  5482  5528 I jxcore-log: 2016-10-12 11:06:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-12 07:06:11.874  5482  5528 I jxcore-log: 
,10-12 07:06:11.880  5482  5528 I jxcore-log: 2016-10-12 11:06:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-12 07:06:11.880  5482  5528 I jxcore-log: 
,10-12 07:06:11.885  5482  5528 I jxcore-log: 2016-10-12 11:06:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-12 07:06:11.885  5482  5528 I jxcore-log: 
,10-12 07:06:12.363  5482  5528 I jxcore-log: 2016-10-12 11:06:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-12 07:06:12.363  5482  5528 I jxcore-log: 
,10-12 07:06:12.406  5482  5528 I jxcore-log: 2016-10-12 11:06:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-12 07:06:12.406  5482  5528 I jxcore-log: 
,10-12 07:06:12.418  5482  5528 I jxcore-log: 2016-10-12 11:06:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-12 07:06:12.418  5482  5528 I jxcore-log: 
,10-12 07:06:12.423  5482  5528 I jxcore-log: 2016-10-12 11:06:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-12 07:06:12.423  5482  5528 I jxcore-log: 
,10-12 07:06:12.713  5482  5528 I jxcore-log: 2016-10-12 11:06:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-12 07:06:12.713  5482  5528 I jxcore-log: 
,10-12 07:06:12.836  5482  5528 I jxcore-log: 2016-10-12 11:06:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-12 07:06:12.836  5482  5528 I jxcore-log: 
,10-12 07:06:13.067  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-12 07:06:13.067  5482  5528 I jxcore-log: 
,10-12 07:06:13.213  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-12 07:06:13.213  5482  5528 I jxcore-log: 
,10-12 07:06:13.219  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-12 07:06:13.219  5482  5528 I jxcore-log: 
,10-12 07:06:13.223  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-12 07:06:13.223  5482  5528 I jxcore-log: 
,10-12 07:06:13.228  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-12 07:06:13.228  5482  5528 I jxcore-log: 
,10-12 07:06:13.255  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-12 07:06:13.255  5482  5528 I jxcore-log: 
,10-12 07:06:13.288  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-12 07:06:13.288  5482  5528 I jxcore-log: 
,10-12 07:06:13.295  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-12 07:06:13.295  5482  5528 I jxcore-log: 
,10-12 07:06:13.302  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-12 07:06:13.302  5482  5528 I jxcore-log: 
,10-12 07:06:13.316  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-12 07:06:13.316  5482  5528 I jxcore-log: 
,10-12 07:06:13.321  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-12 07:06:13.321  5482  5528 I jxcore-log: 
,10-12 07:06:13.327  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-12 07:06:13.327  5482  5528 I jxcore-log: 
,10-12 07:06:13.332  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-12 07:06:13.332  5482  5528 I jxcore-log: 
,10-12 07:06:13.344  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-12 07:06:13.344  5482  5528 I jxcore-log: 
,10-12 07:06:13.364  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-12 07:06:13.364  5482  5528 I jxcore-log: 
,10-12 07:06:13.374  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-12 07:06:13.374  5482  5528 I jxcore-log: 
,10-12 07:06:13.385  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-12 07:06:13.385  5482  5528 I jxcore-log: 
,10-12 07:06:13.394  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-12 07:06:13.394  5482  5528 I jxcore-log: 
,10-12 07:06:13.407  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-12 07:06:13.407  5482  5528 I jxcore-log: 
,10-12 07:06:13.417  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-12 07:06:13.417  5482  5528 I jxcore-log: 
,10-12 07:06:13.422  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-12 07:06:13.422  5482  5528 I jxcore-log: 
,10-12 07:06:13.443  5482  5528 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-12 07:06:13.444  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - INFO testUtils: 'BLE multiple advertisement supported'
10-12 07:06:13.444  5482  5528 I jxcore-log: 
,10-12 07:06:13.620  5482  5528 I jxcore-log: 2016-10-12 11:06:13 - DEBUG CoordinatedClient: 'connected to the test server'
10-12 07:06:13.620  5482  5528 I jxcore-log: 
,10-12 07:06:14.288  5482  5528 I jxcore-log: TAP version 13
10-12 07:06:14.288  5482  5528 I jxcore-log: 
,10-12 07:06:14.329  5482  5528 I jxcore-log: # setup
10-12 07:06:14.329  5482  5528 I jxcore-log: 
,10-12 07:06:14.962  5482  5528 I jxcore-log: # calling createNativeListener directly rejects
10-12 07:06:14.962  5482  5528 I jxcore-log: 
,10-12 07:06:15.068   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-12 07:06:15.069   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-12 07:06:15.423  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:15.423  5482  5528 I jxcore-log: 
,10-12 07:06:15.431  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'listening 47610'
10-12 07:06:15.431  5482  5528 I jxcore-log: 
,10-12 07:06:15.439  5482  5528 I jxcore-log: ok 1 Should throw
10-12 07:06:15.439  5482  5528 I jxcore-log: 
,10-12 07:06:15.451  5482  5528 I jxcore-log: # teardown
10-12 07:06:15.451  5482  5528 I jxcore-log: 
,10-12 07:06:15.608  5482  5528 I jxcore-log: # setup
10-12 07:06:15.608  5482  5528 I jxcore-log: 
,10-12 07:06:15.762  5482  5528 I jxcore-log: # emits incomingConnectionState
10-12 07:06:15.762  5482  5528 I jxcore-log: 
,10-12 07:06:15.934  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:15.934  5482  5528 I jxcore-log: 
,10-12 07:06:15.940  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'listening 44613'
10-12 07:06:15.940  5482  5528 I jxcore-log: 
,10-12 07:06:15.949  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:15.949  5482  5528 I jxcore-log: 
,10-12 07:06:15.952  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:15.952  5482  5528 I jxcore-log: 
,10-12 07:06:15.963  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'new mux'
10-12 07:06:15.963  5482  5528 I jxcore-log: 
,10-12 07:06:15.969  5482  5528 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-12 07:06:15.969  5482  5528 I jxcore-log: 
,10-12 07:06:15.990  5482  5528 I jxcore-log: 2016-10-12 11:06:15 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:15.990  5482  5528 I jxcore-log: 
,10-12 07:06:15.992  5482  5528 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-12 07:06:15.992  5482  5528 I jxcore-log: 
,10-12 07:06:16.002  5482  5528 I jxcore-log: # teardown
10-12 07:06:16.002  5482  5528 I jxcore-log: 
,10-12 07:06:16.070  5482  5528 I jxcore-log: # setup
10-12 07:06:16.070  5482  5528 I jxcore-log: 
,10-12 07:06:16.230  5482  5528 I jxcore-log: # emits routerPortConnectionFailed
10-12 07:06:16.230  5482  5528 I jxcore-log: 
,10-12 07:06:16.416  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:16.416  5482  5528 I jxcore-log: 
,10-12 07:06:16.420  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'listening 38067'
10-12 07:06:16.420  5482  5528 I jxcore-log: 
,10-12 07:06:16.428  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:16.428  5482  5528 I jxcore-log: 
,10-12 07:06:16.431  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:16.431  5482  5528 I jxcore-log: 
,10-12 07:06:16.432  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'new mux'
10-12 07:06:16.432  5482  5528 I jxcore-log: 
,10-12 07:06:16.456  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:16.456  5482  5528 I jxcore-log: 
,10-12 07:06:16.458  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:16.458  5482  5528 I jxcore-log: 
,10-12 07:06:16.463  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: ' $c@net.js:837:7
10-12 07:06:16.463  5482  5528 I jxcore-log: $09@net.js:829:13
10-12 07:06:16.463  5482  5528 I jxcore-log: '
10-12 07:06:16.463  5482  5528 I jxcore-log: 
,10-12 07:06:16.464  5482  5528 I jxcore-log: ok 4 tried to connect to right port
10-12 07:06:16.464  5482  5528 I jxcore-log: 
10-12 07:06:16.464  5482  5528 I jxcore-log: ok 5 failed due to refused connection
10-12 07:06:16.464  5482  5528 I jxcore-log: 
10-12 07:06:16.465  5482  5528 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-12 07:06:16.465  5482  5528 I jxcore-log: 
10-12 07:06:16.469  5482  5528 I jxcore-log: # teardown
10-12 07:06:16.469  5482  5528 I jxcore-log: 
,10-12 07:06:16.471  5482  5528 I jxcore-log: 2016-10-12 11:06:16 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:16.471  5482  5528 I jxcore-log: 
,10-12 07:06:17.406  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'mux close'
10-12 07:06:17.406  5482  5528 I jxcore-log: 
,10-12 07:06:17.413  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:17.413  5482  5528 I jxcore-log: 
,10-12 07:06:17.427  5482  5528 I jxcore-log: # setup
10-12 07:06:17.427  5482  5528 I jxcore-log: 
,10-12 07:06:17.469  5482  5528 I jxcore-log: # native server connections all up
10-12 07:06:17.469  5482  5528 I jxcore-log: 
,10-12 07:06:17.545  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:17.545  5482  5528 I jxcore-log: 
,10-12 07:06:17.549  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'listening 45704'
10-12 07:06:17.549  5482  5528 I jxcore-log: 
,10-12 07:06:17.559  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:17.559  5482  5528 I jxcore-log: 
,10-12 07:06:17.561  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:17.561  5482  5528 I jxcore-log: 
,10-12 07:06:17.563  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new mux'
10-12 07:06:17.563  5482  5528 I jxcore-log: 
,10-12 07:06:17.589  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:17.589  5482  5528 I jxcore-log: 
,10-12 07:06:17.593  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:17.593  5482  5528 I jxcore-log: 
,10-12 07:06:17.595  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:17.595  5482  5528 I jxcore-log: 
,10-12 07:06:17.598  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:17.598  5482  5528 I jxcore-log: 
,10-12 07:06:17.618  5482  5528 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-12 07:06:17.618  5482  5528 I jxcore-log: 
10-12 07:06:17.618  5482  5528 I jxcore-log: ok 8 Send/recvd #1 should be same
10-12 07:06:17.618  5482  5528 I jxcore-log: 
10-12 07:06:17.621  5482  5528 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-12 07:06:17.621  5482  5528 I jxcore-log: 
10-12 07:06:17.621  5482  5528 I jxcore-log: ok 10 Send/recvd #2 should be same
10-12 07:06:17.621  5482  5528 I jxcore-log: 
,10-12 07:06:17.624  5482  5528 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-12 07:06:17.624  5482  5528 I jxcore-log: 
,10-12 07:06:17.630  5482  5528 I jxcore-log: # teardown
10-12 07:06:17.630  5482  5528 I jxcore-log: 
,10-12 07:06:17.650  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:17.650  5482  5528 I jxcore-log: 
,10-12 07:06:17.652  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:17.652  5482  5528 I jxcore-log: 
,10-12 07:06:17.653  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'mux close'
10-12 07:06:17.653  5482  5528 I jxcore-log: 
,10-12 07:06:17.657  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:17.657  5482  5528 I jxcore-log: 
,10-12 07:06:17.666  5482  5528 I jxcore-log: # setup
10-12 07:06:17.666  5482  5528 I jxcore-log: 
,10-12 07:06:17.706  5482  5528 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-12 07:06:17.706  5482  5528 I jxcore-log: 
,10-12 07:06:17.752  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:17.752  5482  5528 I jxcore-log: 
,10-12 07:06:17.756  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'listening 47711'
10-12 07:06:17.756  5482  5528 I jxcore-log: 
,10-12 07:06:17.762  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:17.762  5482  5528 I jxcore-log: 
,10-12 07:06:17.764  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:17.764  5482  5528 I jxcore-log: 
,10-12 07:06:17.768  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new mux'
10-12 07:06:17.768  5482  5528 I jxcore-log: 
,10-12 07:06:17.781  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:17.781  5482  5528 I jxcore-log: 
,10-12 07:06:17.784  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:17.784  5482  5528 I jxcore-log: 
,10-12 07:06:17.796  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:17.796  5482  5528 I jxcore-log: 
,10-12 07:06:17.809  5482  5528 I jxcore-log: ok 12 socket shouldn't close until after stream
10-12 07:06:17.809  5482  5528 I jxcore-log: 
,10-12 07:06:17.809  5482  5528 I jxcore-log: ok 13 incoming remains open
10-12 07:06:17.809  5482  5528 I jxcore-log: 
,10-12 07:06:17.817  5482  5528 I jxcore-log: # teardown
10-12 07:06:17.817  5482  5528 I jxcore-log: 
,10-12 07:06:17.867  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'mux close'
10-12 07:06:17.867  5482  5528 I jxcore-log: 
,10-12 07:06:17.873  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:17.873  5482  5528 I jxcore-log: 
,10-12 07:06:17.881  5482  5528 I jxcore-log: # setup
10-12 07:06:17.881  5482  5528 I jxcore-log: 
,10-12 07:06:17.960  5482  5528 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-12 07:06:17.960  5482  5528 I jxcore-log: 
,10-12 07:06:17.991  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:17.991  5482  5528 I jxcore-log: 
,10-12 07:06:17.994  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'listening 42042'
10-12 07:06:17.994  5482  5528 I jxcore-log: 
,10-12 07:06:17.999  5482  5528 I jxcore-log: 2016-10-12 11:06:17 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:17.999  5482  5528 I jxcore-log: 
,10-12 07:06:18.000  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.000  5482  5528 I jxcore-log: 
,10-12 07:06:18.001  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.001  5482  5528 I jxcore-log: 
,10-12 07:06:18.011  5482  5528 I jxcore-log: ok 14 we should not have gotten an error
10-12 07:06:18.011  5482  5528 I jxcore-log: 
,10-12 07:06:18.016  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.016  5482  5528 I jxcore-log: 
,10-12 07:06:18.020  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.020  5482  5528 I jxcore-log: 
,10-12 07:06:18.030  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.030  5482  5528 I jxcore-log: 
,10-12 07:06:18.032  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.032  5482  5528 I jxcore-log: 
,10-12 07:06:18.040  5482  5528 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-12 07:06:18.040  5482  5528 I jxcore-log: 
,10-12 07:06:18.040  5482  5528 I jxcore-log: ok 16 incoming is cleaned up
10-12 07:06:18.040  5482  5528 I jxcore-log: 
,10-12 07:06:18.048  5482  5528 I jxcore-log: # teardown
10-12 07:06:18.048  5482  5528 I jxcore-log: 
,10-12 07:06:18.121  5482  5528 I jxcore-log: # setup
10-12 07:06:18.121  5482  5528 I jxcore-log: 
,10-12 07:06:18.177  5482  5528 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-12 07:06:18.177  5482  5528 I jxcore-log: 
,10-12 07:06:18.227  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:18.227  5482  5528 I jxcore-log: 
,10-12 07:06:18.233  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'listening 42306'
10-12 07:06:18.233  5482  5528 I jxcore-log: 
,10-12 07:06:18.241  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.241  5482  5528 I jxcore-log: 
,10-12 07:06:18.242  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.242  5482  5528 I jxcore-log: 
,10-12 07:06:18.246  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.246  5482  5528 I jxcore-log: 
,10-12 07:06:18.259  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.259  5482  5528 I jxcore-log: 
,10-12 07:06:18.262  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.262  5482  5528 I jxcore-log: 
,10-12 07:06:18.277  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.277  5482  5528 I jxcore-log: 
,10-12 07:06:18.286  5482  5528 I jxcore-log: ok 17 stream was closed
10-12 07:06:18.286  5482  5528 I jxcore-log: 
,10-12 07:06:18.286  5482  5528 I jxcore-log: ok 18 incoming should survive
10-12 07:06:18.286  5482  5528 I jxcore-log: 
10-12 07:06:18.286  5482  5528 I jxcore-log: ok 19 mux should have no streams
10-12 07:06:18.286  5482  5528 I jxcore-log: 
,10-12 07:06:18.293  5482  5528 I jxcore-log: # teardown
10-12 07:06:18.293  5482  5528 I jxcore-log: 
,10-12 07:06:18.314  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.314  5482  5528 I jxcore-log: 
,10-12 07:06:18.324  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.324  5482  5528 I jxcore-log: 
,10-12 07:06:18.335  5482  5528 I jxcore-log: # setup
10-12 07:06:18.335  5482  5528 I jxcore-log: 
,10-12 07:06:18.407  5482  5528 I jxcore-log: # native server - closing the whole server cleans everything up
10-12 07:06:18.407  5482  5528 I jxcore-log: 
,10-12 07:06:18.450  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:18.450  5482  5528 I jxcore-log: 
,10-12 07:06:18.453  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'listening 46833'
10-12 07:06:18.453  5482  5528 I jxcore-log: 
,10-12 07:06:18.459  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.459  5482  5528 I jxcore-log: 
,10-12 07:06:18.460  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.460  5482  5528 I jxcore-log: 
,10-12 07:06:18.463  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.463  5482  5528 I jxcore-log: 
,10-12 07:06:18.472  5482  5528 I jxcore-log: ok 20 we should not have gotten an error
10-12 07:06:18.472  5482  5528 I jxcore-log: 
,10-12 07:06:18.477  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.477  5482  5528 I jxcore-log: 
,10-12 07:06:18.480  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.480  5482  5528 I jxcore-log: 
,10-12 07:06:18.487  5482  5528 I jxcore-log: ok 21 Buffers are identical
10-12 07:06:18.487  5482  5528 I jxcore-log: 
,10-12 07:06:18.489  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.489  5482  5528 I jxcore-log: 
,10-12 07:06:18.492  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.492  5482  5528 I jxcore-log: 
,10-12 07:06:18.494  5482  5528 I jxcore-log: ok 22 native server is nulled out
10-12 07:06:18.494  5482  5528 I jxcore-log: 
10-12 07:06:18.494  5482  5528 I jxcore-log: ok 23 native server should be closed
10-12 07:06:18.494  5482  5528 I jxcore-log: 
10-12 07:06:18.494  5482  5528 I jxcore-log: ok 24 incoming has been removed
10-12 07:06:18.494  5482  5528 I jxcore-log: 
10-12 07:06:18.495  5482  5528 I jxcore-log: ok 25 Incoming should be done
10-12 07:06:18.495  5482  5528 I jxcore-log: 
10-12 07:06:18.495  5482  5528 I jxcore-log: ok 26 The mux object should be closed
10-12 07:06:18.495  5482  5528 I jxcore-log: 
10-12 07:06:18.495  5482  5528 I jxcore-log: ok 27 The mux stream should be closed
10-12 07:06:18.495  5482  5528 I jxcore-log: 
10-12 07:06:18.496  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.496  5482  5528 I jxcore-log: 
,10-12 07:06:18.508  5482  5528 I jxcore-log: # teardown
10-12 07:06:18.508  5482  5528 I jxcore-log: 
,10-12 07:06:18.547  5482  5528 I jxcore-log: # setup
10-12 07:06:18.547  5482  5528 I jxcore-log: 
,10-12 07:06:18.581  5482  5528 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-12 07:06:18.581  5482  5528 I jxcore-log: 
,10-12 07:06:18.616  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:18.616  5482  5528 I jxcore-log: 
,10-12 07:06:18.620  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'listening 42475'
10-12 07:06:18.620  5482  5528 I jxcore-log: 
,10-12 07:06:18.651  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.651  5482  5528 I jxcore-log: 
,10-12 07:06:18.652  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.652  5482  5528 I jxcore-log: 
,10-12 07:06:18.653  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.653  5482  5528 I jxcore-log: 
,10-12 07:06:18.658  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.658  5482  5528 I jxcore-log: 
,10-12 07:06:18.658  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.658  5482  5528 I jxcore-log: 
,10-12 07:06:18.660  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.660  5482  5528 I jxcore-log: 
,10-12 07:06:18.664  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.664  5482  5528 I jxcore-log: 
,10-12 07:06:18.664  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.664  5482  5528 I jxcore-log: 
10-12 07:06:18.666  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.666  5482  5528 I jxcore-log: 
,10-12 07:06:18.670  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.670  5482  5528 I jxcore-log: 
,10-12 07:06:18.670  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.670  5482  5528 I jxcore-log: 
10-12 07:06:18.671  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.671  5482  5528 I jxcore-log: 
10-12 07:06:18.675  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.675  5482  5528 I jxcore-log: 
10-12 07:06:18.675  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.675  5482  5528 I jxcore-log: 
,10-12 07:06:18.678  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.678  5482  5528 I jxcore-log: 
,10-12 07:06:18.680  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.680  5482  5528 I jxcore-log: 
10-12 07:06:18.681  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.681  5482  5528 I jxcore-log: 
10-12 07:06:18.682  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.682  5482  5528 I jxcore-log: 
,10-12 07:06:18.690  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.690  5482  5528 I jxcore-log: 
,10-12 07:06:18.691  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.691  5482  5528 I jxcore-log: 
,10-12 07:06:18.692  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.692  5482  5528 I jxcore-log: 
,10-12 07:06:18.695  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.695  5482  5528 I jxcore-log: 
,10-12 07:06:18.695  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.695  5482  5528 I jxcore-log: 
,10-12 07:06:18.696  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.696  5482  5528 I jxcore-log: 
,10-12 07:06:18.699  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.699  5482  5528 I jxcore-log: 
,10-12 07:06:18.699  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.699  5482  5528 I jxcore-log: 
,10-12 07:06:18.700  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.700  5482  5528 I jxcore-log: 
,10-12 07:06:18.703  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:18.703  5482  5528 I jxcore-log: 
,10-12 07:06:18.703  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:18.703  5482  5528 I jxcore-log: 
,10-12 07:06:18.704  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new mux'
10-12 07:06:18.704  5482  5528 I jxcore-log: 
,10-12 07:06:18.760  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.760  5482  5528 I jxcore-log: 
,10-12 07:06:18.762  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.762  5482  5528 I jxcore-log: 
,10-12 07:06:18.764  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.764  5482  5528 I jxcore-log: 
,10-12 07:06:18.765  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.765  5482  5528 I jxcore-log: 
,10-12 07:06:18.766  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.766  5482  5528 I jxcore-log: 
,10-12 07:06:18.767  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.767  5482  5528 I jxcore-log: 
,10-12 07:06:18.768  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.768  5482  5528 I jxcore-log: 
,10-12 07:06:18.769  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.769  5482  5528 I jxcore-log: 
,10-12 07:06:18.770  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.770  5482  5528 I jxcore-log: 
10-12 07:06:18.772  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.772  5482  5528 I jxcore-log: 
10-12 07:06:18.772  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.772  5482  5528 I jxcore-log: 
10-12 07:06:18.773  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.773  5482  5528 I jxcore-log: 
10-12 07:06:18.774  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.774  5482  5528 I jxcore-log: 
10-12 07:06:18.775  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.775  5482  5528 I jxcore-log: 
10-12 07:06:18.775  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.775  5482  5528 I jxcore-log: 
,10-12 07:06:18.776  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.776  5482  5528 I jxcore-log: 
,10-12 07:06:18.778  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.778  5482  5528 I jxcore-log: 
10-12 07:06:18.779  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.779  5482  5528 I jxcore-log: 
,10-12 07:06:18.779  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.779  5482  5528 I jxcore-log: 
,10-12 07:06:18.780  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.780  5482  5528 I jxcore-log: 
10-12 07:06:18.781  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.781  5482  5528 I jxcore-log: 
,10-12 07:06:18.782  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.782  5482  5528 I jxcore-log: 
,10-12 07:06:18.782  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.782  5482  5528 I jxcore-log: 
10-12 07:06:18.783  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.783  5482  5528 I jxcore-log: 
,10-12 07:06:18.784  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.784  5482  5528 I jxcore-log: 
,10-12 07:06:18.785  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.785  5482  5528 I jxcore-log: 
10-12 07:06:18.786  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.786  5482  5528 I jxcore-log: 
,10-12 07:06:18.787  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.787  5482  5528 I jxcore-log: 
10-12 07:06:18.787  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.787  5482  5528 I jxcore-log: 
,10-12 07:06:18.788  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.788  5482  5528 I jxcore-log: 
10-12 07:06:18.789  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.789  5482  5528 I jxcore-log: 
,10-12 07:06:18.789  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.789  5482  5528 I jxcore-log: 
,10-12 07:06:18.791  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.791  5482  5528 I jxcore-log: 
10-12 07:06:18.792  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.792  5482  5528 I jxcore-log: 
,10-12 07:06:18.792  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.792  5482  5528 I jxcore-log: 
10-12 07:06:18.793  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.793  5482  5528 I jxcore-log: 
,10-12 07:06:18.794  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.794  5482  5528 I jxcore-log: 
10-12 07:06:18.794  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.794  5482  5528 I jxcore-log: 
10-12 07:06:18.795  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.795  5482  5528 I jxcore-log: 
,10-12 07:06:18.796  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.796  5482  5528 I jxcore-log: 
,10-12 07:06:18.797  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.797  5482  5528 I jxcore-log: 
,10-12 07:06:18.798  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.798  5482  5528 I jxcore-log: 
10-12 07:06:18.798  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.798  5482  5528 I jxcore-log: 
10-12 07:06:18.799  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.799  5482  5528 I jxcore-log: 
,10-12 07:06:18.800  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.800  5482  5528 I jxcore-log: 
,10-12 07:06:18.801  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.801  5482  5528 I jxcore-log: 
10-12 07:06:18.801  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.801  5482  5528 I jxcore-log: 
,10-12 07:06:18.802  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.802  5482  5528 I jxcore-log: 
,10-12 07:06:18.809  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.809  5482  5528 I jxcore-log: 
,10-12 07:06:18.810  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.810  5482  5528 I jxcore-log: 
,10-12 07:06:18.811  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.811  5482  5528 I jxcore-log: 
,10-12 07:06:18.812  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.812  5482  5528 I jxcore-log: 
10-12 07:06:18.812  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.812  5482  5528 I jxcore-log: 
,10-12 07:06:18.813  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.813  5482  5528 I jxcore-log: 
10-12 07:06:18.814  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.814  5482  5528 I jxcore-log: 
,10-12 07:06:18.815  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.815  5482  5528 I jxcore-log: 
,10-12 07:06:18.816  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.816  5482  5528 I jxcore-log: 
10-12 07:06:18.817  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.817  5482  5528 I jxcore-log: 
,10-12 07:06:18.817  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.817  5482  5528 I jxcore-log: 
10-12 07:06:18.818  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.818  5482  5528 I jxcore-log: 
,10-12 07:06:18.819  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.819  5482  5528 I jxcore-log: 
10-12 07:06:18.819  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.819  5482  5528 I jxcore-log: 
10-12 07:06:18.820  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.820  5482  5528 I jxcore-log: 
,10-12 07:06:18.821  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.821  5482  5528 I jxcore-log: 
,10-12 07:06:18.821  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.821  5482  5528 I jxcore-log: 
,10-12 07:06:18.822  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.822  5482  5528 I jxcore-log: 
10-12 07:06:18.823  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.823  5482  5528 I jxcore-log: 
,10-12 07:06:18.824  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.824  5482  5528 I jxcore-log: 
,10-12 07:06:18.824  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.824  5482  5528 I jxcore-log: 
10-12 07:06:18.825  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.825  5482  5528 I jxcore-log: 
10-12 07:06:18.825  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.825  5482  5528 I jxcore-log: 
,10-12 07:06:18.826  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.826  5482  5528 I jxcore-log: 
10-12 07:06:18.827  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.827  5482  5528 I jxcore-log: 
,10-12 07:06:18.828  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.828  5482  5528 I jxcore-log: 
10-12 07:06:18.828  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.828  5482  5528 I jxcore-log: 
,10-12 07:06:18.829  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.829  5482  5528 I jxcore-log: 
10-12 07:06:18.829  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.829  5482  5528 I jxcore-log: 
,10-12 07:06:18.832  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.832  5482  5528 I jxcore-log: 
,10-12 07:06:18.833  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:18.833  5482  5528 I jxcore-log: 
,10-12 07:06:18.834  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:18.834  5482  5528 I jxcore-log: 
,10-12 07:06:18.880  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.880  5482  5528 I jxcore-log: 
,10-12 07:06:18.881  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.881  5482  5528 I jxcore-log: 
,10-12 07:06:18.882  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.882  5482  5528 I jxcore-log: 
,10-12 07:06:18.883  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.883  5482  5528 I jxcore-log: 
10-12 07:06:18.883  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.883  5482  5528 I jxcore-log: 
,10-12 07:06:18.884  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.884  5482  5528 I jxcore-log: 
10-12 07:06:18.884  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.884  5482  5528 I jxcore-log: 
10-12 07:06:18.885  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.885  5482  5528 I jxcore-log: 
,10-12 07:06:18.885  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.885  5482  5528 I jxcore-log: 
10-12 07:06:18.886  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.886  5482  5528 I jxcore-log: 
10-12 07:06:18.886  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.886  5482  5528 I jxcore-log: 
10-12 07:06:18.887  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.887  5482  5528 I jxcore-log: 
,10-12 07:06:18.887  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.887  5482  5528 I jxcore-log: 
10-12 07:06:18.887  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.887  5482  5528 I jxcore-log: 
10-12 07:06:18.888  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.888  5482  5528 I jxcore-log: 
,10-12 07:06:18.889  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.889  5482  5528 I jxcore-log: 
10-12 07:06:18.889  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.889  5482  5528 I jxcore-log: 
10-12 07:06:18.890  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.890  5482  5528 I jxcore-log: 
,10-12 07:06:18.890  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.890  5482  5528 I jxcore-log: 
10-12 07:06:18.890  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.890  5482  5528 I jxcore-log: 
10-12 07:06:18.891  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.891  5482  5528 I jxcore-log: 
,10-12 07:06:18.891  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.891  5482  5528 I jxcore-log: 
10-12 07:06:18.892  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.892  5482  5528 I jxcore-log: 
10-12 07:06:18.892  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.892  5482  5528 I jxcore-log: 
,10-12 07:06:18.893  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.893  5482  5528 I jxcore-log: 
10-12 07:06:18.893  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.893  5482  5528 I jxcore-log: 
,10-12 07:06:18.894  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.894  5482  5528 I jxcore-log: 
10-12 07:06:18.894  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.894  5482  5528 I jxcore-log: 
10-12 07:06:18.894  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.894  5482  5528 I jxcore-log: 
10-12 07:06:18.895  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.895  5482  5528 I jxcore-log: 
,10-12 07:06:18.896  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.896  5482  5528 I jxcore-log: 
10-12 07:06:18.896  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.896  5482  5528 I jxcore-log: 
10-12 07:06:18.896  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.896  5482  5528 I jxcore-log: 
,10-12 07:06:18.897  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.897  5482  5528 I jxcore-log: 
10-12 07:06:18.897  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.897  5482  5528 I jxcore-log: 
,10-12 07:06:18.898  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.898  5482  5528 I jxcore-log: 
10-12 07:06:18.898  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.898  5482  5528 I jxcore-log: 
10-12 07:06:18.898  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.898  5482  5528 I jxcore-log: 
10-12 07:06:18.899  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.899  5482  5528 I jxcore-log: 
,10-12 07:06:18.899  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.899  5482  5528 I jxcore-log: 
10-12 07:06:18.900  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.900  5482  5528 I jxcore-log: 
10-12 07:06:18.900  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.900  5482  5528 I jxcore-log: 
10-12 07:06:18.900  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.900  5482  5528 I jxcore-log: 
10-12 07:06:18.901  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.901  5482  5528 I jxcore-log: 
,10-12 07:06:18.902  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.902  5482  5528 I jxcore-log: 
,10-12 07:06:18.903  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.903  5482  5528 I jxcore-log: 
10-12 07:06:18.904  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.904  5482  5528 I jxcore-log: 
10-12 07:06:18.904  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.904  5482  5528 I jxcore-log: 
,10-12 07:06:18.904  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:18.904  5482  5528 I jxcore-log: 
,10-12 07:06:18.907  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'mux close'
10-12 07:06:18.907  5482  5528 I jxcore-log: 
,10-12 07:06:18.909  5482  5528 I jxcore-log: ok 28 native server is nulled out
10-12 07:06:18.909  5482  5528 I jxcore-log: 
,10-12 07:06:18.909  5482  5528 I jxcore-log: ok 29 native server should be closed
10-12 07:06:18.909  5482  5528 I jxcore-log: 
10-12 07:06:18.909  5482  5528 I jxcore-log: ok 30 incoming has been removed
10-12 07:06:18.909  5482  5528 I jxcore-log: 
,10-12 07:06:18.910  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.910  5482  5528 I jxcore-log: 
10-12 07:06:18.911  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.911  5482  5528 I jxcore-log: 
10-12 07:06:18.911  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.911  5482  5528 I jxcore-log: 
,10-12 07:06:18.911  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.911  5482  5528 I jxcore-log: 
10-12 07:06:18.911  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.911  5482  5528 I jxcore-log: 
10-12 07:06:18.912  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.912  5482  5528 I jxcore-log: 
10-12 07:06:18.912  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.912  5482  5528 I jxcore-log: 
,10-12 07:06:18.912  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.912  5482  5528 I jxcore-log: 
10-12 07:06:18.912  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.912  5482  5528 I jxcore-log: 
10-12 07:06:18.913  5482  5528 I jxcore-log: 2016-10-12 11:06:18 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:18.913  5482  5528 I jxcore-log: 
,10-12 07:06:18.986  5482  5528 I jxcore-log: # teardown
10-12 07:06:18.986  5482  5528 I jxcore-log: 
,10-12 07:06:19.064  5482  5528 I jxcore-log: # setup
10-12 07:06:19.064  5482  5528 I jxcore-log: 
,10-12 07:06:20.889  5482  5528 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-12 07:06:20.889  5482  5528 I jxcore-log: 
,10-12 07:06:21.706  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:21.706  5482  5528 I jxcore-log: 
,10-12 07:06:21.711  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'listening 46475'
10-12 07:06:21.711  5482  5528 I jxcore-log: 
,10-12 07:06:21.719  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:21.719  5482  5528 I jxcore-log: 
,10-12 07:06:21.721  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:21.721  5482  5528 I jxcore-log: 
10-12 07:06:21.723  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'new mux'
10-12 07:06:21.723  5482  5528 I jxcore-log: 
,10-12 07:06:21.733  5482  5528 I jxcore-log: ok 31 we should not have gotten an error
10-12 07:06:21.733  5482  5528 I jxcore-log: 
,10-12 07:06:21.737  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:21.737  5482  5528 I jxcore-log: 
,10-12 07:06:21.740  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:21.740  5482  5528 I jxcore-log: 
,10-12 07:06:21.747  5482  5528 I jxcore-log: ok 32 Buffers are identical
10-12 07:06:21.747  5482  5528 I jxcore-log: 
,10-12 07:06:21.747  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:21.747  5482  5528 I jxcore-log: 
10-12 07:06:21.749  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'mux close'
10-12 07:06:21.749  5482  5528 I jxcore-log: 
,10-12 07:06:21.759  5482  5528 I jxcore-log: 2016-10-12 11:06:21 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:21.759  5482  5528 I jxcore-log: 
,10-12 07:06:21.760  5482  5528 I jxcore-log: ok 33 server should be fine
10-12 07:06:21.760  5482  5528 I jxcore-log: 
10-12 07:06:21.760  5482  5528 I jxcore-log: ok 34 server should be open
10-12 07:06:21.760  5482  5528 I jxcore-log: 
10-12 07:06:21.761  5482  5528 I jxcore-log: ok 35 incoming has been removed
10-12 07:06:21.761  5482  5528 I jxcore-log: 
10-12 07:06:21.761  5482  5528 I jxcore-log: ok 36 The mux object should be closed
10-12 07:06:21.761  5482  5528 I jxcore-log: 
10-12 07:06:21.761  5482  5528 I jxcore-log: ok 37 The mux stream should be closed
10-12 07:06:21.761  5482  5528 I jxcore-log: 
,10-12 07:06:21.766  5482  5528 I jxcore-log: # teardown
10-12 07:06:21.766  5482  5528 I jxcore-log: 
,10-12 07:06:22.737  5482  5528 I jxcore-log: # setup
10-12 07:06:22.737  5482  5528 I jxcore-log: 
,10-12 07:06:22.948  5482  5528 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-12 07:06:22.948  5482  5528 I jxcore-log: 
,10-12 07:06:23.852  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'creating native server'
10-12 07:06:23.852  5482  5528 I jxcore-log: 
,10-12 07:06:23.858  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'listening 44568'
10-12 07:06:23.858  5482  5528 I jxcore-log: 
,10-12 07:06:23.866  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'new incoming socket'
10-12 07:06:23.866  5482  5528 I jxcore-log: 
10-12 07:06:23.868  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'creating incoming mux'
10-12 07:06:23.868  5482  5528 I jxcore-log: 
,10-12 07:06:23.870  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'new mux'
10-12 07:06:23.870  5482  5528 I jxcore-log: 
,10-12 07:06:23.877  5482  5528 I jxcore-log: ok 38 we should not have gotten an error
10-12 07:06:23.877  5482  5528 I jxcore-log: 
,10-12 07:06:23.881  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'new stream: '
10-12 07:06:23.881  5482  5528 I jxcore-log: 
,10-12 07:06:23.884  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'new outgoing socket'
10-12 07:06:23.884  5482  5528 I jxcore-log: 
,10-12 07:06:23.891  5482  5528 I jxcore-log: ok 39 Buffers are identical
10-12 07:06:23.891  5482  5528 I jxcore-log: 
,10-12 07:06:23.896  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'incoming socket timeout'
10-12 07:06:23.896  5482  5528 I jxcore-log: 
,10-12 07:06:23.897  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'stream close:'
10-12 07:06:23.897  5482  5528 I jxcore-log: 
,10-12 07:06:23.900  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'mux close'
10-12 07:06:23.900  5482  5528 I jxcore-log: 
,10-12 07:06:23.905  5482  5528 I jxcore-log: 2016-10-12 11:06:23 - DEBUG createNativeListener: 'incoming socket close'
10-12 07:06:23.905  5482  5528 I jxcore-log: 
,10-12 07:06:23.906  5482  5528 I jxcore-log: ok 40 server should be fine
10-12 07:06:23.906  5482  5528 I jxcore-log: 
10-12 07:06:23.906  5482  5528 I jxcore-log: ok 41 server should be open
10-12 07:06:23.906  5482  5528 I jxcore-log: 
10-12 07:06:23.907  5482  5528 I jxcore-log: ok 42 incoming has been removed
10-12 07:06:23.907  5482  5528 I jxcore-log: 
,10-12 07:06:23.907  5482  5528 I jxcore-log: ok 43 The mux object should be closed
10-12 07:06:23.907  5482  5528 I jxcore-log: 
,10-12 07:06:23.908  5482  5528 I jxcore-log: ok 44 The mux stream should be closed
10-12 07:06:23.908  5482  5528 I jxcore-log: 
,10-12 07:06:23.915  5482  5528 I jxcore-log: # teardown
10-12 07:06:23.915  5482  5528 I jxcore-log: 
,10-12 07:06:24.273  5482  5528 I jxcore-log: # setup
10-12 07:06:24.273  5482  5528 I jxcore-log: 
,10-12 07:06:25.189  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-12 07:06:25.189  5482  5528 I jxcore-log: 
,10-12 07:06:25.486  5482  5528 I jxcore-log: 2016-10-12 11:06:25 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-12 07:06:25.486  5482  5528 I jxcore-log: 
,10-12 07:06:25.487  5482  5528 I jxcore-log: ok 45 Got right error
10-12 07:06:25.487  5482  5528 I jxcore-log: 
,10-12 07:06:25.492  5482  5528 I jxcore-log: # teardown
10-12 07:06:25.492  5482  5528 I jxcore-log: 
,10-12 07:06:26.520  5482  5528 I jxcore-log: # setup
10-12 07:06:26.520  5482  5528 I jxcore-log: 
,10-12 07:06:26.690  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-12 07:06:26.690  5482  5528 I jxcore-log: 
,10-12 07:06:27.798  5482  5528 I jxcore-log: 2016-10-12 11:06:27 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-12 07:06:27.798  5482  5528 I jxcore-log: 
,10-12 07:06:27.800  5482  5528 I jxcore-log: ok 46 Got socket hang up
10-12 07:06:27.800  5482  5528 I jxcore-log: 
,10-12 07:06:27.806  5482  5528 I jxcore-log: # teardown
10-12 07:06:27.806  5482  5528 I jxcore-log: 
,10-12 07:06:27.873  5482  5528 I jxcore-log: # setup
10-12 07:06:27.873  5482  5528 I jxcore-log: 
,10-12 07:06:27.957  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-12 07:06:27.957  5482  5528 I jxcore-log: 
,10-12 07:06:28.145  5482  5528 I jxcore-log: 2016-10-12 11:06:28 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-12 07:06:28.145  5482  5528 I jxcore-log: 
,10-12 07:06:28.146  5482  5528 I jxcore-log: ok 47 Got 500 as expected
10-12 07:06:28.146  5482  5528 I jxcore-log: 
,10-12 07:06:28.151  5482  5528 I jxcore-log: # teardown
10-12 07:06:28.151  5482  5528 I jxcore-log: 
,10-12 07:06:28.195  5482  5528 I jxcore-log: # setup
10-12 07:06:28.195  5482  5528 I jxcore-log: 
,10-12 07:06:28.240  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-12 07:06:28.240  5482  5528 I jxcore-log: 
,10-12 07:06:29.761  5482  5528 I jxcore-log: ok 48 should be equal
10-12 07:06:29.761  5482  5528 I jxcore-log: 
10-12 07:06:29.761  5482  5528 I jxcore-log: ok 49 revs are equal
10-12 07:06:29.761  5482  5528 I jxcore-log: 
,10-12 07:06:29.767  5482  5528 I jxcore-log: # teardown
10-12 07:06:29.767  5482  5528 I jxcore-log: 
,10-12 07:06:29.805  5482  5528 I jxcore-log: # setup
10-12 07:06:29.805  5482  5528 I jxcore-log: 
,10-12 07:06:30.070   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:30.727  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-12 07:06:30.727  5482  5528 I jxcore-log: 
,10-12 07:06:31.072   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:32.073   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:32.285  5482  5528 I jxcore-log: ok 50 should be equal
10-12 07:06:32.285  5482  5528 I jxcore-log: 
,10-12 07:06:32.286  5482  5528 I jxcore-log: ok 51 revs are equal
10-12 07:06:32.286  5482  5528 I jxcore-log: 
,10-12 07:06:32.293  5482  5528 I jxcore-log: # teardown
10-12 07:06:32.293  5482  5528 I jxcore-log: 
,10-12 07:06:32.585  5482  5528 I jxcore-log: # setup
10-12 07:06:32.585  5482  5528 I jxcore-log: 
,10-12 07:06:32.959   928  2819 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 07:06:33.074   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:33.229  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-12 07:06:33.229  5482  5528 I jxcore-log: 
,10-12 07:06:34.075   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:34.319  5482  5528 I jxcore-log: ok 52 should be equal
10-12 07:06:34.319  5482  5528 I jxcore-log: 
,10-12 07:06:34.319  5482  5528 I jxcore-log: ok 53 revs are equal
10-12 07:06:34.319  5482  5528 I jxcore-log: 
,10-12 07:06:34.459  5482  5528 I jxcore-log: ok 54 should be equal
10-12 07:06:34.459  5482  5528 I jxcore-log: 
,10-12 07:06:34.460  5482  5528 I jxcore-log: ok 55 revs are equal
10-12 07:06:34.460  5482  5528 I jxcore-log: 
,10-12 07:06:34.595  5482  5528 I jxcore-log: ok 56 should be equal
10-12 07:06:34.595  5482  5528 I jxcore-log: 
,10-12 07:06:34.595  5482  5528 I jxcore-log: ok 57 revs are equal
10-12 07:06:34.595  5482  5528 I jxcore-log: 
,10-12 07:06:34.601  5482  5528 I jxcore-log: # teardown
10-12 07:06:34.601  5482  5528 I jxcore-log: 
,10-12 07:06:35.075   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 07:06:35.272  5482  5528 I jxcore-log: # setup
10-12 07:06:35.272  5482  5528 I jxcore-log: 
,10-12 07:06:35.851  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-12 07:06:35.851  5482  5528 I jxcore-log: 
,10-12 07:06:37.291  5482  5528 I jxcore-log: 2016-10-12 11:06:37 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-12 07:06:37.291  5482  5528 I jxcore-log: 
,10-12 07:06:37.292  5482  5528 I jxcore-log: ok 58 Our rev is old so we should fail
10-12 07:06:37.292  5482  5528 I jxcore-log: 
,10-12 07:06:37.312  5482  5528 I jxcore-log: # teardown
10-12 07:06:37.312  5482  5528 I jxcore-log: 
,10-12 07:06:37.717  5482  5528 I jxcore-log: # setup
10-12 07:06:37.717  5482  5528 I jxcore-log: 
,10-12 07:06:37.854  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-12 07:06:37.854  5482  5528 I jxcore-log: 
,10-12 07:06:38.005  5482  5528 I jxcore-log: ok 59 confirm stop caused failure
10-12 07:06:38.005  5482  5528 I jxcore-log: 
,10-12 07:06:38.017  5482  5528 I jxcore-log: # teardown
10-12 07:06:38.017  5482  5528 I jxcore-log: 
,10-12 07:06:38.085  5482  5528 I jxcore-log: # setup
10-12 07:06:38.085  5482  5528 I jxcore-log: 
,10-12 07:06:38.126  5482  5528 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-12 07:06:38.126  5482  5528 I jxcore-log: 
,10-12 07:06:38.564  5482  5528 I jxcore-log: 2016-10-12 11:06:38 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-12 07:06:38.564  5482  5528 I jxcore-log: 
,10-12 07:06:38.565  5482  5528 I jxcore-log: ok 60 stop caused us to fail
10-12 07:06:38.565  5482  5528 I jxcore-log: 
,10-12 07:06:38.566  5482  5528 I jxcore-log: ok 61 We specifically failed on a stop before put
10-12 07:06:38.566  5482  5528 I jxcore-log: 
,10-12 07:06:38.584  5482  5528 I jxcore-log: # teardown
10-12 07:06:38.584  5482  5528 I jxcore-log: 
,10-12 07:06:38.627  5482  5528 I jxcore-log: # setup
10-12 07:06:38.627  5482  5528 I jxcore-log: 
,10-12 07:06:38.677  5482  5528 I jxcore-log: # #update - fail if stop is called
10-12 07:06:38.677  5482  5528 I jxcore-log: 
,10-12 07:06:38.783  5482  5528 I jxcore-log: ok 62 failed due to stop
10-12 07:06:38.783  5482  5528 I jxcore-log: 
,10-12 07:06:38.784  5482  5528 I jxcore-log: ok 63 failed due to stop
10-12 07:06:38.784  5482  5528 I jxcore-log: 
,10-12 07:06:38.791  5482  5528 I jxcore-log: # teardown
10-12 07:06:38.791  5482  5528 I jxcore-log: 
,10-12 07:06:38.881  5482  5528 I jxcore-log: # setup
10-12 07:06:38.881  5482  5528 I jxcore-log: 
,10-12 07:06:38.914  5482  5528 I jxcore-log: # #update - set seq for first time
10-12 07:06:38.914  5482  5528 I jxcore-log: 
,10-12 07:06:39.544  5482  5528 I jxcore-log: ok 64 should be equal
10-12 07:06:39.544  5482  5528 I jxcore-log: 
,10-12 07:06:39.567  5482  5528 I jxcore-log: # teardown
10-12 07:06:39.567  5482  5528 I jxcore-log: 
,10-12 07:06:39.655  5482  5528 I jxcore-log: # setup
10-12 07:06:39.655  5482  5528 I jxcore-log: 
,10-12 07:06:39.691  5482  5528 I jxcore-log: # #update - Fail on bad seq value
10-12 07:06:39.691  5482  5528 I jxcore-log: 
,10-12 07:06:40.076   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:40.248  5482  5528 I jxcore-log: 2016-10-12 11:06:40 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-12 07:06:40.248  5482  5528 I jxcore-log: 
,10-12 07:06:40.249  5482  5528 I jxcore-log: ok 65 Expected bad seq error
10-12 07:06:40.249  5482  5528 I jxcore-log: 
,10-12 07:06:40.270  5482  5528 I jxcore-log: # teardown
10-12 07:06:40.270  5482  5528 I jxcore-log: 
,10-12 07:06:40.400  5482  5528 I jxcore-log: # setup
10-12 07:06:40.400  5482  5528 I jxcore-log: 
,10-12 07:06:40.439  5482  5528 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-12 07:06:40.439  5482  5528 I jxcore-log: 
,10-12 07:06:40.573  5482  5528 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-12 07:06:40.573  5482  5528 E jxcore-log: 
,10-12 07:06:40.575  5482  5528 E jxcore-log: Trace: 
10-12 07:06:40.575  5482  5528 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-12 07:06:40.575  5482  5528 E jxcore-log:     at addListener@events.js:140:1
10-12 07:06:40.575  5482  5528 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-12 07:06:40.575  5482  5528 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-12 07:06:40.575  5482  5528 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-12 07:06:40.575  5482  5528 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-12 07:06:40.575  5482  5528 E jxcore-log: 
,10-12 07:06:41.077   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:41.415  5482  5528 I jxcore-log: ok 66 Different promises
10-12 07:06:41.415  5482  5528 I jxcore-log: 
,10-12 07:06:41.416  5482  5528 I jxcore-log: ok 67 Timer was cancelled
10-12 07:06:41.416  5482  5528 I jxcore-log: 
,10-12 07:06:41.599  5482  5528 I jxcore-log: ok 68 should be equal
10-12 07:06:41.599  5482  5528 I jxcore-log: 
,10-12 07:06:41.655  5482  5528 I jxcore-log: # teardown
10-12 07:06:41.655  5482  5528 I jxcore-log: 
,10-12 07:06:42.078   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:42.927  5482  5528 I jxcore-log: # setup
10-12 07:06:42.927  5482  5528 I jxcore-log: 
,10-12 07:06:43.079   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:44.080   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:44.234  5482  5528 I jxcore-log: # #update - do we wait for blocked update
10-12 07:06:44.234  5482  5528 I jxcore-log: 
,10-12 07:06:44.321  5482  5528 I jxcore-log: ok 69 One go and one blocked
10-12 07:06:44.321  5482  5528 I jxcore-log: 
,10-12 07:06:44.322  5482  5528 I jxcore-log: ok 70 All blocked
10-12 07:06:44.322  5482  5528 I jxcore-log: 
10-12 07:06:44.323  5482  5528 I jxcore-log: ok 71 Still blocked
10-12 07:06:44.323  5482  5528 I jxcore-log: 
,10-12 07:06:44.339  5482  5528 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-12 07:06:44.339  5482  5528 E jxcore-log: 
,10-12 07:06:44.341  5482  5528 E jxcore-log: Trace: 
10-12 07:06:44.341  5482  5528 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-12 07:06:44.341  5482  5528 E jxcore-log:     at addListener@events.js:140:1
10-12 07:06:44.341  5482  5528 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-12 07:06:44.341  5482  5528 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-12 07:06:44.341  5482  5528 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-12 07:06:44.341  5482  5528 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-12 07:06:44.341  5482  5528 E jxcore-log: 
,10-12 07:06:44.917  5482  5528 I jxcore-log: ok 72 should be equal
10-12 07:06:44.917  5482  5528 I jxcore-log: 
,10-12 07:06:44.939  5482  5528 I jxcore-log: # teardown
10-12 07:06:44.939  5482  5528 I jxcore-log: 
,10-12 07:06:45.080   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 07:06:45.407  5482  5528 I jxcore-log: # setup
10-12 07:06:45.407  5482  5528 I jxcore-log: 
,10-12 07:06:47.106  5482  5528 I jxcore-log: # #update - test that we wait long enough
10-12 07:06:47.106  5482  5528 I jxcore-log: 
,10-12 07:06:48.772  5482  5528 I jxcore-log: ok 73 We waited long enough
10-12 07:06:48.772  5482  5528 I jxcore-log: 
,10-12 07:06:48.966  5482  5528 I jxcore-log: ok 74 should be equal
10-12 07:06:48.966  5482  5528 I jxcore-log: 
,10-12 07:06:48.991  5482  5528 I jxcore-log: # teardown
10-12 07:06:48.991  5482  5528 I jxcore-log: 
,10-12 07:06:49.688  5482  5528 I jxcore-log: # setup
10-12 07:06:49.688  5482  5528 I jxcore-log: 
,10-12 07:06:50.479  5482  5528 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-12 07:06:50.479  5482  5528 I jxcore-log: 
,10-12 07:06:51.780  5482  5528 I jxcore-log: ok 75 Should have gotten same timer promise
10-12 07:06:51.780  5482  5528 I jxcore-log: 
,10-12 07:06:51.780  5482  5528 I jxcore-log: ok 76 Still same timer promise
10-12 07:06:51.780  5482  5528 I jxcore-log: 
,10-12 07:06:52.355  5482  5528 I jxcore-log: ok 77 We waited long enough
10-12 07:06:52.355  5482  5528 I jxcore-log: 
,10-12 07:06:52.478  5482  5528 I jxcore-log: ok 78 should be equal
10-12 07:06:52.478  5482  5528 I jxcore-log: 
,10-12 07:06:52.555  5482  5528 I jxcore-log: # teardown
10-12 07:06:52.555  5482  5528 I jxcore-log: 
,10-12 07:06:53.143  5482  5528 I jxcore-log: # setup
10-12 07:06:53.143  5482  5528 I jxcore-log: 
,10-12 07:06:54.708  5482  5528 I jxcore-log: # Coordinated seq test
10-12 07:06:54.708  5482  5528 I jxcore-log: 
,10-12 07:06:55.082   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:55.449  5482  5528 I jxcore-log: 2016-10-12 11:06:55 - DEBUG thaliWifiInfrastructure: 'listening 44160'
10-12 07:06:55.449  5482  5528 I jxcore-log: 
,10-12 07:06:56.083   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:57.084   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:58.086   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:06:58.750  5482  5528 I jxcore-log: ok 79 should be equal
10-12 07:06:58.750  5482  5528 I jxcore-log: 
,10-12 07:06:59.087   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:00.088   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 07:07:02.382  5482  5528 I jxcore-log: ok 80 should be equal
10-12 07:07:02.382  5482  5528 I jxcore-log: 
,10-12 07:07:02.397  5482  5528 I jxcore-log: # teardown
10-12 07:07:02.397  5482  5528 I jxcore-log: 
,10-12 07:07:12.966   928  2819 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 07:07:15.089   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:16.090   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:17.092   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:18.093   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:19.094   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:20.095   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-12 07:07:32.967   928  2819 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 07:07:40.096   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:41.097   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:42.098   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:43.100   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:44.101   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 07:07:45.101   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 07:08:02.413  5482  5528 I jxcore-log: 2016-10-12 11:08:02 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-12 07:08:02.413  5482  5528 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-12 07:08:02.413  5482  5528 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-12 07:08:02.413  5482  5528 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-12 07:08:02.413  5482  5528 I jxcore-log:     at $9@timers.js:120:1
10-12 07:08:02.413  5482  5528 I jxcore-log: ''
10-12 07:08:02.413  5482  5528 I jxcore-log: 
,10-12 07:08:02.416  5482  5528 I jxcore-log: 2016-10-12 11:08:02 - DEBUG CoordinatedClient: 'test client failed'
10-12 07:08:02.416  5482  5528 I jxcore-log: 
,10-12 07:08:02.428  5482  5528 I jxcore-log: 2016-10-12 11:08:02 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-12 07:08:02.428  5482  5528 I jxcore-log: 
,10-12 07:08:02.433  5482  5528 I jxcore-log: 2016-10-12 11:08:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-12 07:08:02.433  5482  5528 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-12 07:08:02.433  5482  5528 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-12 07:08:02.433  5482  5528 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-12 07:08:02.433  5482  5528 I jxcore-log:     at $9@timers.js:120:1
10-12 07:08:02.433  5482  5528 I jxcore-log: ''
10-12 07:08:02.433  5482  5528 I jxcore-log: 
10-12 07:08:02.434  5482  5528 I jxcore-log: 2016-10-12 11:08:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-12 07:08:02.434  5482  5528 I jxcore-log: 
,10-12 07:08:02.509   928  2796 W InputDispatcher: channel 'a411eb2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-12 07:08:02.510   928  2796 E InputDispatcher: channel 'a411eb2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-12 07:08:02.525   928  3655 I WindowState: WIN DEATH: Window{a411eb2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-12 07:08:02.525   928  3655 W InputDispatcher: Attempted to unregister already unregistered input channel 'a411eb2 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-12 07:08:02.525   928  3684 D GraphicsStats: Buffer count: 2
10-12 07:08:02.530   526   526 I Zygote  : Process 5482 exited cleanly (139)
10-12 07:08:02.526   928  2820 D WifiService: Client connection lost with reason: 4
10-12 07:08:02.531   928  3424 I ActivityManager: Process com.test.thalitest (pid 5482) has died
,10-12 07:08:02.565   928  3424 I ActivityManager: Start proc 5820:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-12 07:08:02.897   928   938 I WindowManager: Screenshot max retries 4 of Token{234cfb4 ActivityRecord{70bd487 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{4015f2a u0 Starting com.test.thalitest} drawState=4
,10-12 07:08:02.968  5820  5820 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 07:08:02.988  5820  5820 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 07:08:02.993  5820  5820 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7438-7440)
,10-12 07:08:02.993  5820  5820 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 07:08:03.002  5820  5820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {348c5eb}
10-12 07:08:03.003  5820  5820 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 07:08:03.003  5820  5820 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 07:08:03.006  5820  5820 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-12 07:08:03.007  5820  5820 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 07:08:03.013  5818  5818 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-12 07:08:03.018  5820  5820 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 07:08:03.025  5820  5820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 07:08:03.025  5820  5820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-12 07:08:03.025  5820  5820 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 07:08:03.025  5820  5820 I Adreno  : Build Date                       : 12/06/15
10-12 07:08:03.025  5820  5820 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 07:08:03.025  5820  5820 I Adreno  : Local Branch                     : mybranch17112971
10-12 07:08:03.025  5820  5820 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 07:08:03.025  5820  5820 I Adreno  : Remote Branch                    : NONE
10-12 07:08:03.025  5820  5820 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 07:08:03.028  5818  5818 D AndroidRuntime: CheckJNI is OFF
,10-12 07:08:03.051  5818  5818 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-12 07:08:03.057   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d03f893:true
,10-12 07:08:03.070   400   400 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[15254]" dev="sockfs" ino=15254 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 07:08:03.070   400   400 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[15254]" dev="sockfs" ino=15254 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 07:08:03.077  5818  5818 I Radio-JNI: register_android_hardware_Radio DONE
,10-12 07:08:03.084  5820  5820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 07:08:03.091  5820  5820 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 07:08:03.093  5818  5818 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-12 07:08:03.099   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-12 07:08:03.099   928   941 I ActivityManager: Killing 5820:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-12 07:08:03.258   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-12 07:08:03.259   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-12 07:08:03.261   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-12 07:08:03.261   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-12 07:08:03.261   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:08:03.261   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:08:03.261   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 07:08:03.261   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-12 07:08:03.262   928   941 I ActivityManager:   Force finishing activity ActivityRecord{70bd487 u0 com.test.thalitest/.MainActivity t2}
,10-12 07:08:03.268   928   951 I art     : Starting a blocking GC Explicit
,10-12 07:08:03.275   928  3639 W ActivityManager: Spurious death for ProcessRecord{6ec2c83 0:com.test.thalitest/u0a77}, curProc for 5820: null
,10-12 07:08:03.282   928   946 W WindowManager: Failed looking up window
10-12 07:08:03.282   928   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@4b7c015 does not exist
10-12 07:08:03.282   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-12 07:08:03.282   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-12 07:08:03.282   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-12 07:08:03.282   928   946 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-12 07:08:03.282   928   946 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-12 07:08:03.282   928   946 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-12 07:08:03.282   928   946 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-12 07:08:03.282   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:08:03.282   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:08:03.282   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 07:08:03.282   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-12 07:08:03.366   928   951 I art     : Explicit concurrent mark sweep GC freed 82869(5MB) AllocSpace objects, 45(1536KB) LOS objects, 33% free, 29MB/43MB, paused 1.762ms total 97.562ms
,10-12 07:08:03.388   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-12 07:08:03.391  5818  5818 I art     : System.exit called, status: 0
,10-12 07:08:03.392  5818  5818 I AndroidRuntime: VM exiting with result code 0.
,10-12 07:08:03.397   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-12 07:08:03.405   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-12 07:08:03.410  5719  5719 D BluetoothMapAppObserver: onReceive
,10-12 07:08:03.411  5719  5719 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-12 07:08:03.413  3495  3495 I Keyboard.Facilitator: resetDictionaries() : en_US
10-12 07:08:03.414  3892  4002 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-12 07:08:03.426   928  2797 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-12 07:08:03.437  3495  5862 I Keyboard.Facilitator.DecoderInitializer: run()
,10-12 07:08:03.448  3495  5862 I Decoder : createOrResetDecoder
,10-12 07:08:03.450  3621  3621 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-12 07:08:03.467  3229  5865 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-12 07:08:03.494  3410  3410 I ConfigService: onCreate
,10-12 07:08:03.503   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-12 07:08:03.504  3410  3410 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-12 07:08:03.504  3410  3410 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-12 07:08:03.500    13    13 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 07:08:03.507    13    13 W kworker/1:0: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 07:08:03.517  3644  3771 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-12 07:08:03.522  3693  5870 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-12 07:08:03.522  3495  5862 I Keyboard.Facilitator.MainLanguageModelLoader: run()
10-12 07:08:03.522  3693  5870 D AccountUtils: Clearing selected account for com.test.thalitest
,10-12 07:08:03.527    13    13 W kworker/1:0: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 07:08:03.534   928  2984 I ActivityManager: Start proc 5872:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-12 07:08:03.535  3644  3771 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-12 07:08:03.535  3644  3771 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3644
10-12 07:08:03.535  3644  3771 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:08:03.535  3644  3771 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 07:08:03.540   928  3639 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-12 07:08:03.544   928  5882 E DropBoxManagerService: Can't write: system_app_crash
10-12 07:08:03.544   928  5882 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
10-12 07:08:03.544   928  5882 E DropBoxManagerService: 	... 8 more
,10-12 07:08:03.548  3644  3771 I Process : Sending signal. PID: 3644 SIG: 9
10-12 07:08:03.555  3693  5870 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-12 07:08:03.582  3693  5870 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:08:03.582  3693  5870 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 07:08:03.582  3693  5870 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:08:03.582  3693  5870 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 07:08:03.583  3693  5870 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
10-12 07:08:03.586  3229  3252 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjEB55539F9) - 
,10-12 07:08:03.634  3229  3252 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-12 07:08:03.634  3229  3252 E AndroidRuntime: Process: android.process.acore, PID: 3229
10-12 07:08:03.634  3229  3252 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 07:08:03.634  3229  3252 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 07:08:03.658   928  3655 D GraphicsStats: Buffer count: 1
,10-12 07:08:03.658   928  2984 I WindowState: WIN DEATH: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
,10-12 07:08:03.663   928  3496 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3644) has died
,10-12 07:08:03.664   928  3496 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-12 07:08:03.669  3229  3252 I Process : Sending signal. PID: 3229 SIG: 9
,10-12 07:08:03.670   928   946 E WindowState: getStack: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{94c8295 token=Token{732f24c ActivityRecord{8e9027f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,10-12 07:08:03.670   928   946 E WindowState: getStack: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{94c8295 token=Token{732f24c ActivityRecord{8e9027f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
,10-12 07:08:03.671   928   946 E WindowState: getStack: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{94c8295 token=Token{732f24c ActivityRecord{8e9027f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
10-12 07:08:03.671   928   946 E WindowState: getStack: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{94c8295 token=Token{732f24c ActivityRecord{8e9027f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
10-12 07:08:03.672   928   946 E WindowState: getStack: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{94c8295 token=Token{732f24c ActivityRecord{8e9027f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
10-12 07:08:03.672   928   946 E WindowState: getStack: Window{9559f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{94c8295 token=Token{732f24c ActivityRecord{8e9027f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,10-12 07:08:03.700  3693  5891 I GMPM-SVC: App measurement is starting up
,10-12 07:08:03.713  3693  5891 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-12 07:08:03.714  3693  5891 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-12 07:08:03.922   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
