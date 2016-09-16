#### Test 85594025c926e20_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-16 12:19:37.695   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 12:19:39.431  5396  5396 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 12:19:39.437  5396  5396 D AndroidRuntime: CheckJNI is OFF
09-16 12:19:39.463  5396  5396 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 12:19:39.496  5396  5396 I Radio-JNI: register_android_hardware_Radio DONE
09-16 12:19:39.511  5396  5396 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-16 12:19:39.514   927  3380 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 12:19:39.567   927  3380 I ActivityManager: Start proc 5405:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 12:19:39.584  5396  5396 D AndroidRuntime: Shutting down VM
,09-16 12:19:39.919   927  3921 I WindowManager: Screenshot max retries 4 of Token{6c41538 ActivityRecord{cc66d9b u0 com.test.thalitest/.MainActivity t4}} appWin=Window{ffaf513 u0 Starting com.test.thalitest} drawState=4
,09-16 12:19:39.983  5405  5405 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-16 12:19:40.016  5405  5405 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-16 12:19:40.049  5405  5405 I LibraryLoader: Time to load native libraries: 28 ms (timestamps 5632-5660)
,09-16 12:19:40.049  5405  5405 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 12:19:40.071  5405  5405 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a9a259}
09-16 12:19:40.071  5405  5405 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 12:19:40.072  5405  5405 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-16 12:19:40.075  5405  5405 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-16 12:19:40.076  5405  5405 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-16 12:19:40.113  5405  5405 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-16 12:19:40.121  5405  5405 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 12:19:40.121  5405  5405 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-16 12:19:40.121  5405  5405 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 12:19:40.121  5405  5405 I Adreno  : Build Date                       : 12/06/15
09-16 12:19:40.121  5405  5405 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 12:19:40.121  5405  5405 I Adreno  : Local Branch                     : mybranch17112971
09-16 12:19:40.121  5405  5405 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 12:19:40.121  5405  5405 I Adreno  : Remote Branch                    : NONE
09-16 12:19:40.121  5405  5405 I Adreno  : Reconstruct Branch               : NOTHING
,09-16 12:19:40.159   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@659f38b:true
,09-16 12:19:40.187   401   401 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13929]" dev="sockfs" ino=13929 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 12:19:40.187   401   401 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[13929]" dev="sockfs" ino=13929 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 12:19:40.197  5405  5405 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-16 12:19:40.207  5405  5405 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-16 12:19:40.231   401   401 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33001]" dev="sockfs" ino=33001 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 12:19:40.233  5405  5442 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 12:19:40.231   401   401 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33001]" dev="sockfs" ino=33001 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 12:19:40.234  3922  3922 W Binder_C: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30551]" dev="sockfs" ino=30551 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 12:19:40.234  3922  3922 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30551]" dev="sockfs" ino=30551 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 12:19:40.242  5405  5429 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-16 12:19:40.267  5405  5442 I OpenGLRenderer: Initialized EGL, version 1.4
,09-16 12:19:40.335   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +413ms (total +797ms)
,09-16 12:19:40.367  5405  5405 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5405
,09-16 12:19:40.492  5405  5405 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 12:19:40.586  5405  5445 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -563082960
,09-16 12:19:40.590  5405  5445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 12:19:40.590  5405  5445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 12:19:40.590  5405  5445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 12:19:40.590  5405  5445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 12:19:40.590  5405  5445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-16 12:19:40.590  5405  5445 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c02b7 added. We now have 1 listener(s)
,09-16 12:19:40.593  5405  5445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-16 12:19:40.593  5405  5445 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 12:19:40.593  5405  5445 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 12:19:40.594  5405  5445 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 12:19:40.595  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 12:19:40.596  5405  5445 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7db7742 added. We now have 1 listener(s)
09-16 12:19:40.596  5405  5445 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:19:40.599   927  2914 D WifiService: New client listening to asynchronous messages
,09-16 12:19:40.600  5405  5445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 12:19:40.600  5405  5445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 12:19:40.600  5405  5445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 12:19:40.600  5405  5445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 12:19:40.600  5405  5445 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-16 12:19:40.602  5405  5445 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:19:40.602  5405  5445 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-16 12:19:40.606  5405  5445 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:19:40.606  5405  5445 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:19:40.606  5405  5445 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 12:19:40.606  5405  5445 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:19:40.606  5405  5445 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 12:19:40.684  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:19:40.687  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:19:40.690  5405  5405 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 12:19:40.889  5405  5451 W jxcore-log: Initializing JXcore engine
,09-16 12:19:40.889  5405  5451 W jxcore-log: JXcore engine is ready
,09-16 12:19:40.914  5451  5451 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12599 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-16 12:19:40.914  5451  5451 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13432]" dev="sockfs" ino=13432 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-16 12:19:40.914  5451  5451 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 12:19:40.914  5451  5451 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30525]" dev="sockfs" ino=30525 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 12:19:40.922  5405  5451 W jxcore-log: Starting JXcore engine
,09-16 12:19:40.977  5405  5451 W jxcore-log: Platform android
09-16 12:19:40.977  5405  5451 W jxcore-log: 
,09-16 12:19:40.977  5405  5451 W jxcore-log: Process ARCH arm
09-16 12:19:40.977  5405  5451 W jxcore-log: 
,09-16 12:19:41.074  5405  5451 I jxcore-log: JXcore Cordova bridge is ready!
09-16 12:19:41.074  5405  5451 I jxcore-log: 
,09-16 12:19:41.074  5405  5451 W jxcore-log: JXcore engine is started
,09-16 12:19:41.079  5405  5445 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 12:19:41.081  5405  5405 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 12:19:42.697   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:19:43.697   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:19:44.698   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:19:45.699   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:19:46.700   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:19:47.700   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 12:19:50.730  5405  5451 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 12:19:50.730  5405  5451 I jxcore-log: 
,09-16 12:19:50.732  5405  5451 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 12:19:50.732  5405  5451 I jxcore-log: 
,09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:19:50.740  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 12:19:50.745  5405  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 12:19:50.747  5405  5451 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 12:19:50.747  5405  5451 I jxcore-log: 
,09-16 12:19:50.748  5405  5451 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 12:19:50.748  5405  5451 I jxcore-log: 
,09-16 12:19:50.998  5405  5451 I jxcore-log: Running unit tests
09-16 12:19:50.998  5405  5451 I jxcore-log: 
,09-16 12:19:50.999  5405  5451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 12:19:50.999  5405  5451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c905d3 added. We now have 2 listener(s)
09-16 12:19:51.000  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 12:19:51.000  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 12:19:51.000  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 12:19:51.000  5405  5451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 12:19:51.000  5405  5451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68ff510 added. We now have 2 listener(s)
09-16 12:19:51.000  5405  5451 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 12:19:51.001  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 12:19:51.003  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:19:51.006  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:19:51.007  5405  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 12:19:51.007  5405  5451 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:19:51.007  5405  5451 D executeNativeTests: Running unit tests
,09-16 12:19:51.015  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:19:51.020  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:19:51.044  5405  5451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 12:19:51.044  5405  5451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82842be added. We now have 3 listener(s)
,09-16 12:19:51.045  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 12:19:51.045  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 12:19:51.045  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 12:19:51.045  5405  5451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 12:19:51.045  5405  5451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f added. We now have 3 listener(s)
09-16 12:19:51.045  5405  5451 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:19:51.046  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 12:19:51.047  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:19:51.050  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 12:19:51.050  5405  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:51.050  5405  5451 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:19:51.052  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 12:19:51.052  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 12:19:51.052  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 12:19:51.052  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 12:19:51.053  5405  5451 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 12:19:51.053  5405  5451 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 12:19:51.053  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 12:19:51.053  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 12:19:51.053  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 12:19:51.053  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 12:19:51.053  5405  5451 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:19:51.053  5405  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:19:51.053  5405  5451 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 12:19:51.053  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:19:51.053  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.054  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 12:19:51.054  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 12:19:51.054  5405  5451 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82842be removed from the list
09-16 12:19:51.054  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:19:51.054  5405  5451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f removed from the list
09-16 12:19:51.056  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:19:51.062  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:19:51.062  5405  5451 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 12:19:51.062  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:51.063  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 12:19:51.063  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 12:19:51.063  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:19:51.063  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:19:51.063  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:19:51.063  5405  5451 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f not in the list
09-16 12:19:51.064  5405  5451 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 12:19:51.064  5405  5451 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:19:51.065  5405  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:19:51.065  5405  5451 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 12:19:51.065  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:19:51.065  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.065  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:51.065  5405  5451 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82842be not in the list
09-16 12:19:51.065  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:19:51.065  5405  5451 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f not in the list
,09-16 12:19:51.065  5405  5451 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:19:51.065  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.065  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:51.065  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.065  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 12:19:51.066  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:19:51.066  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:19:51.066  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:19:51.066  5405  5451 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f not in the list
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 12:19:51.068  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 12:19:51.069  5405  5451 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:19:51.069  5405  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:19:51.069  5405  5451 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:19:51.069  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:19:51.069  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.069  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:51.069  5405  5451 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82842be not in the list
09-16 12:19:51.069  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:19:51.069  5405  5451 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f not in the list
09-16 12:19:51.069  5405  5451 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:19:51.069  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.069  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:51.069  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:51.069  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:51.070  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:19:51.070  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:19:51.070  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:19:51.070  5405  5451 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f not in the list
09-16 12:19:51.070  5405  5451 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 12:19:51.071  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:19:51.084  5405  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:19:51.086  5405  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 12:19:51.086  5405  5451 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:19:51.086  5405  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 12:19:51.087  5405  5451 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 12:19:51.087  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 12:19:51.087  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:19:51.087  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 12:19:51.089  5405  5451 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:19:51.089  5405  5451 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 12:19:51.091  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:19:51.092  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 12:19:51.093  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 12:19:51.093  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 12:19:51.094  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-16 12:19:51.096  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:19:51.097  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-16 12:19:51.097  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 12:19:51.097  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 12:19:51.097  5405  5451 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 12:19:51.098  5405  5451 D BluetoothAdapter: STATE_ON
09-16 12:19:51.100  4395  4646 D BtGatt.GattService: registerClient() - UUID=50778e9c-6e8b-4878-9c4b-66570f0d2e95
09-16 12:19:51.100  4395  4483 D BtGatt.GattService: onClientRegistered() - UUID=50778e9c-6e8b-4878-9c4b-66570f0d2e95, clientIf=5
09-16 12:19:51.103  5405  5415 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 12:19:51.104  4395  4653 D BtGatt.GattService: start scan with filters
09-16 12:19:51.111  4395  4488 D BtGatt.ScanManager: handling starting scan
09-16 12:19:51.111  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 12:19:51.111  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 12:19:51.111  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 12:19:51.111  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 12:19:51.112  5405  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 12:19:51.113  5405  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 12:19:51.113  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 12:19:51.113  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 12:19:51.114  5405  5451 I io.jxcore.node.ConnectionHelper: start: OK
09-16 12:19:51.115  4395  4488 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10d69b8
,09-16 12:19:51.123  4395  4483 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 12:19:51.123  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:19:51.123  4395  4488 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 12:19:51.130  4395  4483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 12:19:51.130  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:19:51.131  4395  4488 D BtGatt.ScanManager: Starting BLE batch scan
09-16 12:19:51.131  4395  4488 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 12:19:51.143  4395  4483 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 12:19:51.143  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:19:51.150  4395  4483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 12:19:51.150  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 12:19:51.615  5405  5405 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 12:19:51.615  5405  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 12:19:51.615  5405  5405 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 12:19:56.119  5405  5451 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 12:19:56.119  5405  5451 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 12:19:56.119  5405  5451 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 12:19:56.119  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:56.119  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 12:19:56.119  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 12:19:56.120  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 12:19:56.120  5405  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 12:19:56.120  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 12:19:56.120  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 12:19:56.121  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 12:19:56.122  5405  5451 D BluetoothAdapter: STATE_ON
,09-16 12:19:56.123  4395  4645 D BtGatt.GattService: stopScan() - queue size =1
09-16 12:19:56.124  4395  4410 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 12:19:56.126  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:19:56.126  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 12:19:56.126  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 12:19:56.127  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 12:19:56.127  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 12:19:56.130  5405  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 12:19:56.131  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 12:19:56.131  5405  5451 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 12:19:56.132  5405  5451 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:19:56.132  4395  4395 D BtGatt.ScanManager: awakened up at time 251744
09-16 12:19:56.134  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 12:19:56.138  5405  5451 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:19:56.138  5405  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:19:56.139  5405  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:19:56.139  5405  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 12:19:56.139  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 12:19:56.138  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 12:19:56.140  5405  5451 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82842be not in the list
09-16 12:19:56.140  5405  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:19:56.140  5405  5451 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e7f1f not in the list
09-16 12:19:56.140  5405  5451 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:19:56.140  5405  5451 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:19:56.144  4395  4483 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 12:19:56.144  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:19:56.144  4395  4488 D BtGatt.ScanManager: stopping BLe Batch
,09-16 12:19:56.153  4395  4483 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 12:19:56.153  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:19:56.153  4395  4488 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 12:19:56.178  4395  4483 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-16 12:19:56.178  4395  4483 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 12:19:56.178  4395  4483 D BtGatt.GattService: current time is 251790216781
,09-16 12:19:56.179  4395  4483 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -83, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -82, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 85, -113, -37, 31, -33, 8, 0, 4, -82, 70, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, -46, -4, -117, 6, 105, -37, 1, -128, -85, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -89, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 12:19:56.181  4395  4483 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-16 12:19:56.183  4395  4483 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 12:19:56.183  4395  4483 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 12:19:56.183  4395  4483 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-16 12:19:56.184  4395  4483 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 12:19:56.184  4395  4483 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 12:19:56.640  5405  5405 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 12:19:56.890   927  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 12:19:57.701   536   536 I ServiceManager: Waiting for service AtCmdFwd...

```
